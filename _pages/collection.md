---
title: "Posts by Collection"
permalink: /collection/
layout: collectionlist
author_profile: true
---

{% for item in site.collections %}
  <h2>{{ item.title }}</h2>
  <p>{{ item.description }}</p>
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
{% endfor %}