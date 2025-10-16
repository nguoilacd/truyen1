---
layout: page  # Thêm để chắc chắn
short_name: rua-va-tho
title: Rùa Và Thỏ
description: Một câu chuyện ngụ ngôn về sự kiên trì và kiêu ngạo.
author: Aesop
---

# Giới Thiệu Truyện: Rùa Và Thỏ

Đây là truyện ngụ ngôn cổ điển dạy về việc chậm mà chắc thắng nhanh mà ẩu. Thỏ kiêu ngạo thách đua với Rùa, nhưng kết quả bất ngờ.

## Danh Sách Chương

<ul>
  {% assign filtered_chapters = site.posts | where: 'story', page.short_name %}
  {% for chapter in filtered_chapters %}
    <li><a href="{{ chapter.url }}">{{ chapter.title }}</a></li>
  {% endfor %}
</ul>
