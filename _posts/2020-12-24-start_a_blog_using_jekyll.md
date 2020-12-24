---
layout: post
title: "Upload blog to github using Jekyll"
date: 2020-12-24 21:31:34 +0900
categories: tools
---

지킬 이라는 툴을 이용하여 블로그를 시작하였다.

I've decided to organize my development records using a tool called Jekyll.
It generates a static (blog like) website from md files.

[jekyll-docs](https://jekyllrb.com/docs/home)
[jekyll-gh](https://github.com/jekyll/jekyll)
[jekyll-talk](https://talk.jekyllrb.com/)

This is the simple process.

Install Ruby
`sudo apt-get install ruby-full build-essential zlib1g-dev`

Install Jekyll
`sudo gem install jekyll bundler`

Create Jekyll project
`jekyll new PATH` and `cd PATH`

Test on localhost
`jekyll serve` or `jekyll s`

Build
`jekyll build` or `jekyll b`

Jekyll provides automatic regeneration when the source changes.
But that function doesn't work in my case. It seems like there are a lot of people like me.

[1.vscode]
![screenshot]({{site.url}}/img/2020-12-24-194035.png)
