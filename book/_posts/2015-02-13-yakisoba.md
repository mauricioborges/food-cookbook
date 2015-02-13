---
layout: post
title:  "Food Cookbook!"
date:   2015-02-13 10:59:09
categories: jekyll update
---
Here's a list of our outstanding cookbook.


{% for post in site.posts %}
<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
<p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} . <a href="http://erjjones.github.com{{ post.url }}#disqus_thread"></a></small></p>
{% endfor %} 
