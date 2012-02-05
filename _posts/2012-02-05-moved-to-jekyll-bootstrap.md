---
layout: post
title: "Moved to jekyll Bootstrap"
category: 
tags: []
---
{% include JB/setup %}

For the past few months I have been thinking about making my website much more simpler
in design and removing all the unwanted and complicated things out of it.I started out
with designing my own layout and stuffs and soon realized that it will end up as a crap :-P
While wondering what to do, I was landed in [jekyll bootstrap](http://jekyllbootstrap.com/).
OMG, I immediately fell in love with this project mainly due to this theme and at once decided to 
move my blog. It haven't took me more than an hour or so to entirely transfer my site. I quickly
wrote a script which transferred my blog posts to html files and thats it, the new site was
almost ready. I pushed the project to my github repo and it went live within minutes. The things
which took some time were dns propagation, migration of comments from my old wordpress blog to
disqus (ah! At last I did it. My laziness prevented me from doing it for over an year!) and url
mapping for threads in disqus.

Some of the links which I found useful to do it were,
* [Importing Your Data from your heroku app to local dev env](http://devcenter.heroku.com/articles/taps)
* [rails runner command](http://guides.rubyonrails.org/command_line.html)
* [Jekyll Bootstrap](http://jekyllbootstrap.com/)
* [Github pages](http://pages.github.com/)

If you consider moving to a static blogger, I would suggest you to take a look at this setup.
