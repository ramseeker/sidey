---
title: Hosted by Github Pages for Free
date: 2019-04-12 00:00:00 Z
layout: post
external-url: https://pages.github.com
---

For the past week or so I have been trying to find a solution that would allow me to have a fast website, but still be easy to maintain. You would think that this would be easy, but it seems to be harder than I had thought

![githubpages](/images/githubpages.png)


My requirements for hosting this site are:
1. Cheap
2. Easy

When I first started with websites in the late '90's it was all HTML and static files and then like almost the entire Internet I got hooked on Wordpress. Wordpress has a lot going for it and it's gotten easy and easier to use over the years but it's also gotten more complicated with themes and plugins  and security certificates needed, etc.

I could just use some managed webhost like WP Engine or Kinsta or even use [CloudWays](https://jim.am/2017-07-08-managed-cloud-hosting-platform-cloudways.markdown) like I have in the past but even though Cloudways was cheaper it still left me with [Wordpress](http://wordpresss.com) and then I would still have to worry about caching all over again.

## It's 1999 Again

I have written in the past about using Jekyll to publish this site and after some consideration I've decided to go back. Wordpress has it's advantages but I was never really  been a fan of the fancy and bloated themes and the new 'gutenburg' design.

So, enter [Jekyll](http://jekyllrb.com).  It's not the fastest to build the site but I'm not that busy or important that I can't wait 10 seconds  for the site to build. When it's done building, I just take my local files and 'push them' to host my site at [github pages ](https://pages.github.com/)because: free.

I have search for other solutions and this is not perfect, as github pages has some limitations but none that I have come across that are a big deal for my needs because all I need to do is write in [plain text](https://jim.am/2016-09-28-plain-text.markdown) and then have Jekyll do it's thing.

For now, this works. In this past I had a need for big complicated databases and scripts but i don't anymore and this simple static site generator seems to be working for my just fine.