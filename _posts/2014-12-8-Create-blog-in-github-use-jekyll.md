---
layout: post
title: "Create blog in github use jekyll"
data: 2014-12-08
categories: Tool 
tag: Tool
---
I created blog in github, but it simple, not has `categories` and `tags`.because don't need `categories` now, I think.

To be honest, create blog in github is very easy.just to see.

- `sudo yum install jekyll`. if require pre-conditions, and you will first install them.

- `jekyll new projectName`. if require "javascript runtime", and you can `sudo yum install nodejs`, as other situation, you can see the error message.if successful, the jekyll will generate a folder and some of files under this folder.Do not understand the role of these files first.

- switch to your "projectName", run `jekyll build` and `jekyll server`,then you can open `http://127.0.0.1:4000/`  

- create repo in github, the project name is "yourUserName.github.io" and clone to your computer and rename of "yourUserName.github.io"

- Copy files of under the "projectName" folder to "yourUserName.github.io"

- Finally，push to github and enter the "yourUserName.github.io" in the browser address bar. 

if you add article in blog, then create a file and rename to "xxxx.md" in "_post", and again push to github.

