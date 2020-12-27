---
layout: post
title: "Start a blog using Jekyll"
date: 2020-12-24 15:31:34 +0900
categories: tools
---

I've decided to write my development records using a tool called Jekyll.
It generates a static (blog like) website from md files.

---

This is the simple process.

Install Ruby (Linux)
`sudo apt-get install ruby-full build-essential zlib1g-dev`

Install Jekyll
`sudo gem install jekyll bundler`

Create Jekyll project
`jekyll new PATH` and `cd PATH`

Test on localhost
`jekyll serve` or `jekyll s`

Build
`jekyll build` or `jekyll b`

Publish
`git push origin master`

Jekyll provides automatic regeneration when a source changes.

Links inside your blog should be this format. `{{site.baseurl}}/img/2020-12-24-194035.png`.
`{{site.baseurl}}` is defined in `_config.yml`

Anyone can use Github as a free hosting server for their static website, called Github page, just with a little setup.
`repository > settings > GitHub Pages`

Once github setup is complete, you can find the public URL nearby.

_**WSL 리눅스에 설치했을때는 auto regenerating이 안되었었는데 윈도용으로 설치하니 잘 된다.**_

_**깃헙 페이지에선 여전히 지킬을 기본으로 지원하지만, 정적 블로그의 최근 대세는 Gatsby로 넘어간 것 같다.**_

---

[1. links]
[jekyll-docs](https://jekyllrb.com/docs/home)
[jekyll-gh](https://github.com/jekyll/jekyll)
[jekyll-talk](https://talk.jekyllrb.com/)

[2. vscode]
![screenshot]({{site.baseurl}}/img/2020-12-24-194035.png)
