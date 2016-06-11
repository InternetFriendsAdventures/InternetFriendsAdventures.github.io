---
layout: inner
title: 'First Game'
date: 2016-06-08 18:24:36
categories: adventure
tags: First Game Adventure
---
# Our first game
We recently started our first game. We chose friends based on [this](https://rpgmaker.net/media/content/users/441/locker/kXpqU.png).

### Rules
It was decided that each of the three players would choose 5 from the list linked previously. These companions would accompany them on a short test journey because role playing 4 years would be too hard for us as new players. Each player starts with three of their "Hella Funtime Friends" and the other two will show up later. 

# Players
This is a list of all the player pages:
{% for page in site.pages %}
{% if page.lead_text == "Player Page" %}
<a href="{{ page.url }}">{{ page.title }}</a>
{% endif %}
{% endfor %}
