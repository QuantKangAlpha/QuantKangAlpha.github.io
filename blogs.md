---
layout: splash
title: 네이버 블로그와 최근 글 목록
header:
  overlay_image: "/assets/images/report.jpg"
permalink: /blogs/
---

{% for blog in site.blogs %}
  <a href="{{ blog.url }}">{{ blog.title }}</a>
{% endfor %}
