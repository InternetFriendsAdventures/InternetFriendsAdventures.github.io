---
layout: inner
title: Posts list
permalink: /posts/
---
You are not supposed to be here. This page is unlisted for a reason.

This page contains a list of all of the posts I have made. I will eventually add a search function, but I have not done so yet. There are so few posts that it does not matter at this point. 

<ul class="posts">
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
