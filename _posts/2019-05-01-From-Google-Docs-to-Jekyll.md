---
title: From Google Docs to Jekyll
date: 2019-05-01 00:00:00 Z
permalink: "/from-google-docs-to-jekyll/"
layout: post
author: macseek
source-id: 1fRRg5ieg6IuWJ_lZQGBV_r_ICkfeVgvPlpR2D5flnU4
---

I just want to share my current workflow in case this might help some others. 

I have figured out how to publish my site regardless of computer I use allowing me to write my posts in [Google Docs](https://www.google.com/docs/about/) and then publish this site with [Jekyll](https://jekyllrb.com/). 

The first step obviously is to write your post in Google Docs. Heck you might even want to add an image or two like this one:

![image alt text]({{ site.url }}/public/avijk4G0g3cdWOYTgIbeA_img_0.jpg)

When done writing I use the[ Gabriel add-on](https://chrome.google.com/webstore/detail/gabriel/okimajjeocnndpifeelaajdebkkbckff?hl=en-GB) to publish my post to [Github](https://github.com/). If I were hosting my site on [Github Pages](https://pages.github.com/), then I would be done. But because I use [firebase](https://firebase.google.com/) to host my site, I have to open my terminal and do a "git pull" to get my post locally on my computer. 

After the git pull I run a [jekyll build](https://jekyllrb.com/docs/usage/) command  to create my site with the updated post and then deploy my site to firebase hosting and then after a few seconds my site is live. 

  

