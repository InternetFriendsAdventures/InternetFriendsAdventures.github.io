---
layout: player_page
title: Puffer
lead_text: "Player Page" 
permalink: /MSPaint_Game1/players/puffer
---
# Hella Funtime Friends:

***

## Friends now

{% for page in site.pages %}
{% if page.title == "Archie"  or page.title == "Cantelo" or page.title == "Boleslava" %}
{{ page.content }}
{% endif %}
{% endfor %}

***

## Friends who have yet to show up

{% for page in site.pages %}
{% if page.title == "Gilligan"  or page.title == "Rolf" %}
{{ page.content }}
{% endif %}
{% endfor %}

***

# Stuff:

## Inventory

  | Item | Amount |  Description |
  |------|---------|-------------|
  | knapsack | 1 | holds things |
  | rope | 20 feet | SNAKE! no, it's rope |
  | food | 1 week | food that will make him not die |
  | water | 1 week | food that will make him not die... probably |

***

## Ownership

  | Item | Amount |  Location | Description |
  |------|---------|----------|-------------|
  |Partially built house | N/A | near Boulder outcropping in a clearing| shoulder high walls, currently being built by archie |
  |mallows | the number of poops that a rabbit has on average | boulder outcropping | like marshmallows, only worse

