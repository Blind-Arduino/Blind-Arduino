---
title: Welcome to the Blind Arduino Blog
---

The Blind Arduino Blog is a collection of news and information about blind makers working with Arduino. It includes tutorials, advice, and recommendations of particular interest to blind people working with electronics and microprocessors. The Project is based at The Lighthouse for the Blind and Visually Impaired in San Franscisco, and the Smith-Kettlewell Eye Research Institute and includes a number of partners and collaborators, some of whom are contributors to this blog.

# Recent Posts

{% for post in site.posts %}
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  
  {{ post.excerpt }}
  {% endfor %}
  
