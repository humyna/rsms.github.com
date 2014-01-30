---
title: "使用Jekyll与GitHub Pages构建网站"
layout: post
photo_url: "/img/octojekyll-topleft.png"
photo_title: "Jekyll & GitHub"
comments: yes
---
![](/img/octojekyll.png)

本博开篇，按例介绍一下使用 [Jekyll](http://jekyllrb.com/) 与 [GitHub Pages](http://pages.github.com/) 构建网站的流程，一为后来者造福，二为自己留个记录。

## 准备

我搭建的过程大部分也是乘着前人栽树的阴凉，下面是我建议的**阅读清单**：

- [搭建一个免费的，无限流量的Blog----github Pages和Jekyll入门 (阮一峰)](http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html)
  
  看完你应该有整体概念了，但这是 2012年写的，现在GitHub 除了支持 Project site (`gh_pages` branch)，还支持 User or organization site (`username.github.io` repository)。

- [Using Jekyll with Pages (GitHub help)](https://help.github.com/articles/using-jekyll-with-pages)

  本篇重点在搭建与 GitHub Pages 相同的 Jekyll 环境，保证本地调试与最终发布的页面一致。
  
  特别说明一下，我的Gemfile如下
  
  ```ruby
  source 'http://ruby.taobao.org'
  gem 'github-pages'
  gem 'wdm'
  ```
  - 使用了淘宝搭建的 [RubyGems 镜像](http://ruby.taobao.org)
  - `wdm`: Windows Directory Monitor (WDM) is a library which can be used to monitor directories for changes.

## 简略步骤

...待续