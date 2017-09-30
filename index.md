---
title: Home
---
{% for review in site.reviews %}
  <h2><a href="{{review.url}}">{{ review.title }}</a></h2>
  <p>{{ review.excerpt }}</p>
{% endfor %}
