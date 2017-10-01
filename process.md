---
layout: post
title: process
---

{% assign posts = site.posts | sort: 'date' | reverse %}

  {% for post in posts %}
  <div class="">
    <img src="{{post.img}}"/>
  </div>

  {% endfor %}
