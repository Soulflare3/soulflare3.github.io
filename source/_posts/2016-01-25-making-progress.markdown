---
status: published
layout: post
title: "Making Progress"
date: 2016-01-25 13:01:05 -0500
comments: true
categories:
 - Blog
 - Jekyll
 - Octopress
 - Github
---

So far I've made quite a lot of progress with the Octopress/Jekyll migration from Ghost. I had to swap out some tags from markdown to liquid (such as image tags) but I like the ease of adding media. Video for example is a lot easier to add to my posts, because Ruby handles the insertion of the necessary tags.

The theme I'm using at the moment is called [Slash](https://tommy351.github.io/Octopress-Theme-Slash/). I like it a lot, but it's a bit too bright for me, so I think I'll tinker with it and make it darker.
<!--more-->
I still like Octopress/Jekyll, though I still haven't figured out how to use plugins. Supposedly Jekyll has quite a few, but every time I put a gem in my `_config.yml` `rake` generates errors (from plugin manager). I'm still new to this so it may be a little while before I actually look into the problem, but for now I'm fine with doing stuff manually. It's not too bad, because I never imported my ancient blogs into Ghost, so the posts only go back a few months anyway. I did have to manually add tags/categories to all of the posts, but [this JSON->table parser](http://json2table.com) helped me out a lot.

One thing I would really like to get working is Pingbacks. So far I've found [WebMention.io](http://webmention.io) which I'll probably end up going with anyway, because Jekyll plugins don't work at the moment... I still absolutely love that I can preview my entire site offline before pushing changes. Jekyll++