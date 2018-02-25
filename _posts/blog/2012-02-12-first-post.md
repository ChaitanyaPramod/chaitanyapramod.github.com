---
title:  "First Post"
date:   2012-02-12 12:30:00 +0530
permalink: /blog/first-post
excerpt: My journey setting up a Jekyll blog
---
Phew, just finished the basic setup of my brand-new blog-site. It took almost five hours to get here. Working with [Octopress](http://octopress.org) was fun. Setting up a blog on commandline is way cooler than doing it the wordpress style. Of course, Octopress drew me to itself with its subtitle:

> A blogging framework for hackers.

I noticed [Divya Manian](http://nimbupani.com/) [move her blog to Octopress](http://nimbupani.com/redesign-notes.html). After looking up Octopress and what people feel about it (everyone seems to like it), I decided to try it myself.

After reading almost all of the [Octopress](http://octopress.org) site, I cloned the [Octopress repo](http://github.com/imathis/octopress), setup a [Disqus](https://disqus.com) account for the site and plugged in account into the config files. All commands are run through rake, which makes it as easy as:

{% highlight bash %}
rake new_page[page_title]   # create a new page  
rake new_post[post_title]   # create a new post  
rake preview                # fire up a local server and preview the site at localhost:4000  
rake deploy                 # Make it live! :)
{% endhighlight %}

Just now realized that syntax highlighting breaks on Windows. Gotta find a fix for it soon. The Google Fonts were making the pages render slower, so I am thinking if they should be removed. The styles look good, but will spend some time on the CSS and fiddle around with it. Compass and SASS are new to me, more CSS frameworks to learn :(.

That’s it folks for now, will update with more changes I am planning to the site.

