---
layout: player_page
title: Flaamee
lead_text: "Player Page" 
tags: "Second Game"
---
# Hella Funtime Friends

***

## Friends now

{% for page in site.pages %}
{% if page.title == "Bones"  or page.title == "WombaWomba" or page.title == "Blinky" %}
{{ page.content }}
{% endif %}
{% endfor %}

***

# Stuff:

## Inventory

  | Item | Amount |  Description |
  |------|---------|-------------|
  | knapsack | 1 | holds things |
  | rope | 20 feet | it's probably some rope |
  | food | 1 week | food that will make him not die |
  | water | 1 week | food that will make him not die... probably |

***

## Ownership
  
  | Item | Amount |  Location | Description |
  |------|---------|----------|-------------|
  | | | | |
