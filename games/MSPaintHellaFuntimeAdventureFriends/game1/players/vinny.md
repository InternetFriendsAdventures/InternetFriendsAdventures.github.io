---
layout: player_page
title: Vinny
lead_text: "Player Page" 
tags: "First Game"
---
# Hella Funtime Friends:

***

## Friends now

{% for page in site.pages %}
{% if page.title == "Blinky"  or page.title == "Cleptsy" or page.title == "WombaWomba" %}
{{ page.content }}
{% endif %}
{% endfor %}

***

## Friends who have yet to show up
{% for page in site.pages %}
{% if page.title == "Gwendolyn"  or page.title == "Bones" %}
{{ page.content }}
{% endif %}
{% endfor %}

***

# Stuff:

## Inventory
  
  | Item | Amount |  Description |
  |------|---------|-------------|
  | knapsack | 1 | holds things |
  | rope | 20 feet | it's some sort of... rope |
  | food | 1 week | food that will make him not die |
  | water | 1 week | food that will make him not die... probably |

***

## Ownership

  | Item | Amount |  Location | Description |
  |------|---------|----------|-------------|
  | alien fire | N/A | Vinny Spawn (south) coast | built by cleptsy, about the size of a breadbox, never goes out |
