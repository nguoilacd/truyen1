---
title: Trang Chủ
layout: default  # Sử dụng layout mặc định của theme
---

# Danh Sách Truyện

Đây là danh sách tất cả truyện trên site.

<ul>
  {% for story in site.stories %}
    <li>
      <h2><a href="{{ story.url }}">{{ story.title }}</a></h2>
      <p>{{ story.description }}</p>
    </li>
  {% endfor %}
</ul>
