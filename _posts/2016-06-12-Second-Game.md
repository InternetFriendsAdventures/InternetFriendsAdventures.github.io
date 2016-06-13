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
Each player chose 3 friends to join them on their adventure. You can see their drafts on their pages. 
# Players
This is a list of all the player pages:
{% for page in site.pages %}
{% if page.lead_text == "Player Page" and page.tags == "Second Game"%}
<a href="{{ page.url }}">{{ page.title }}</a>
{% endif %}
{% endfor %}
