---
layout: inner
title: 'Hella Funtime Friends'
lead_text: "Index of Hella Funtime Friends" 
---
{% for page in site.pages %}
{% if page.layout == "friends_page" %}
<center>{{ page.content }}</center>
***
{% endif %}
{% endfor %}
