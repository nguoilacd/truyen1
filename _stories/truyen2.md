---
short_name: truyen1  # Tên ngắn, unique, không dấu
title: Truyện 2: Trước đây chị rõ ràng mấy lần nói với em rằng rất ghen tị với phòng của em, còn nói thích lắm
description: Mô tả ngắn về truyện 2.
author: Tác Giả A
---

# Giới Thiệu Truyện 2

hiệu quả lại càng được khuếch đại lên vô số lần.
Mẹ tôi rưng rưng, trên mặt thoáng hiện chút áy náy và xót xa.
Cha tôi thì lạnh giọng quyết định:

## Danh Sách Chương

<ul>
  {% assign filtered_chapters = site.posts | where: 'story', page.short_name %}
  {% for chapter in filtered_chapters %}
    <li><a href="{{ chapter.url }}">{{ chapter.title }}</a></li>
  {% endfor %}
</ul>
