---
layout: inner
title: 'Second Game'
date: 2016-06-12 18:24:36
categories: adventure
tags: Second Game Adventure
---
# Our second game
This is our second game with We chose friends based on [this](http://127.0.0.1:4000/games/MSPaintHellaFuntimeAdventureFriends/friends/).

### Rules
It was decided that each of the three players would choose 5 from the list linked previously. These companions would accompany them on a short test journey because role playing 4 years would be too hard for us as new players. Each player starts with three of their "Hella Funtime Friends" and the other two will show up later. 

# Players
This is a list of all the player pages:
{% for page in site.pages %}
{% if page.lead_text == "Player Page" and page.tags == "Second Game"%}
<a href="{{ page.url }}">{{ page.title }}</a>
{% endif %}
{% endfor %}
