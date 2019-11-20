---
date: 2019-11-20 08:24:55
layout: post
title: "How to post in jekyll"
subtitle: Github.io 사용하기
description: github.io + jekyll
image: https://camo.githubusercontent.com/c2fc91a17e3fd048fa16d201a23840ced6867071/68747470733a2f2f7265732e636c6f7564696e6172792e636f6d2f646d3768376538786a2f696d6167652f75706c6f61642f76313530353335343138322f6a656b666c69782d6c6f676f5f6d666e6770732e706e67
optimized_image: https://camo.githubusercontent.com/c2fc91a17e3fd048fa16d201a23840ced6867071/68747470733a2f2f7265732e636c6f7564696e6172792e636f6d2f646d3768376538786a2f696d6167652f75706c6f61642f76313530353335343138322f6a656b666c69782d6c6f676f5f6d666e6770732e706e67 
category: tips
tags: 
    - github
    - jekflix
    - jekyll
author: HaningYa
paginate: false
---

## 포스팅 먼저 만들기
터미널에서 해당 github.io 디렉토리에 들어간다.
#Code
```js
./initpost.sh -c "POST_TITLE"
```
하면 끗

## 마크업 변수
* layout : post, page, minimal, main, default, compress, category, author
* title : 자기 맘대로 쓰면됨
* subtitle : 자기 맘대로 쓰면됨
* description : 자기 맘대로 쓰면됨
* image : url
* optimized_image : optional
* category : blog, code, css, diet, life, music, tips, travel, work(by default) 자신이 원하면 category 디렉토리에서 NAME.md 를 만들면 됨(카테고리에 없는 경우 포스팅은 되지만 메인 페이지의 콜렉션뷰에 나타나지 않음)
* tags : - TAGNAME 
* author : 자기 맘대로 쓰면됨
* paginate : true / false 하면됨

참고 : 
https://github.com/thiagorossener/jekflix-template/wiki/post#creating-a-post
