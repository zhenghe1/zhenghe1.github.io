---
layout: page
title: Something About Code
tagline: Is this how I code?
---
{% include JB/setup %}

Welcome to Something About Code!
I'm Zheng He and this is my blog.

I will mostly be blogging about my current coursework and interests. Please note that I mostly code in C++ so my pseudocode will be in that style.
<br />
<br />
    
## Previous Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

Leaf tree operations
