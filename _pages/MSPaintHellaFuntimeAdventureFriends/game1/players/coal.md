---
layout: player_page
title: Coal
lead_text: "Player Page" 
permalink: /MSPaint_Game1/playsers/coal
---
# Hella Funtime Friends

## Friends now

{% for page in site.pages %}
{% if page.title == "Mildred"  or page.title == "Kazoo" or page.title == "Murray" %}
{{ page.content }}
{% endif %}
{% endfor %}

## Friends who have yet to show up

{% for page in site.pages %}
{% if page.title == "HellRider"  or page.title == "MrPepper" %}
{{ page.content }}
{% endif %}
{% endfor %}

# Stuff:

## Inventory

  | Item | Amount |  Description |
  |------|---------|-------------|
  | knapsack | 1 | holds things |
  | rope | 20 feet | |
  | food | 1 week | food that will make him not die |
  | chicken wings | a bunch | thanks a lot mildred |
  | water | 1 week | food that will make him not die... probably |

## Ownership
  
  | Item | Amount |  Location | Description |
  |------|---------|----------|-------------|
  | sticks | pile | ocean shore where he woke up | sticks that have been thoroughly molested by Mildred |
