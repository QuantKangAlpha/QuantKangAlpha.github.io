---
layout: default
title: 네이버 블로그와 최근 글 목록
permalink: /blogs/
---

{% for blog in site.blogs %}
  <a href="{{ blog.url }}">{{ blog.title }}</a>
{% endfor %}
