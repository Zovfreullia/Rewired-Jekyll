# Rewired-Jekyll
![shields.io](
<a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/mit-license-brightgreen.svg" alt="mit license">
<a href="https://www.ruby-lang.org/en/downloads/"><img src="https://img.shields.io/badge/ruby-2.0.0-red.svg" alt="ruby version">


This is a Jekyll version of the website reWired by CCNMTL: http://ccnmtl.columbia.edu/events/websites/rewired_f14/

You can check the Jekyll build here: http://columbia.edu/~ffv2102/Rewired

Unlike the original theme, users can change the content of the "Post" and "Article" directly under the _post directory. You can add as many posts you want, and you can even change the image by inputting a different file picture. All you have to do is create a new post with the proper file heading: ```YEAR-MM-DD-FILENAME.markdown``` and include this on the header.

```
---
layout: default
title: Post 1
desc: This is a sample post that is added under the "desc" part of the YAML.
img: pic01.jpg
categories: carousel
---
```

#### [Requirements](http://jekyllrb.com/docs/installation/)

* [Ruby](https://www.ruby-lang.org/en/downloads/)
* [Ruby Gems](https://rubygems.org/pages/download) A note on ruby gems and gh-pages. 
  If you also want to push your site to gh-pages, make sure you add the [gh-page gem](http://jekyllrb.com/docs/github-pages/). 
* Linux, Unix, or Mac OS X
* [NodeJS](https://nodejs.org)
