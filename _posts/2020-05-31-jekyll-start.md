---
layout: post
title: Jekyll start
date: 2020-05-31 13:41
summary: Jekyll installation with flexible-jekyll theme
category: tech
author: Han, Insung
img: software.jpg
tags: [blog, jekyll, ruby, tech]
---

* Sign up to github.com with fortylove.github.io
* Follow [Jekyll Quickstart][jekyll-quickstart]
* Download the theme https://github.com/artemsheludko/flexible-jekyll and overrwrite to blog folder 
* Run bundle update to fix the error "runtime.rb:312:in `check_for_activated_spec!`: You have already activated mercenary 0.4.0, but your Gemfile requires mercenary 0.3.6. Prepending `bundle exec` to your command may solve this. (Gem::LoadError)
"
* Remove index.markdown and about.markdown to fix the warn message
* Modify index.html and add image files into the /asset/img folder

[jekyll-quickstart]: https://jekyllrb.com/docs/