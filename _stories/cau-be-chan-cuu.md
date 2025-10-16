---
layout: default
short_name: cau-be-chan-cuu
title: Cậu Bé Chăn Cừu
description: Truyện về hậu quả của việc nói dối.
author: Aesop
---
# Giới Thiệu Truyện: Cậu Bé Chăn Cừu
Cậu bé nghịch ngợm hay kêu "Sói đến!" để lừa dân làng. Nhưng khi sói thật đến, không ai tin nữa.

## Danh Sách Chương
<ul>
  {% assign filtered_chapters = site.posts | where: 'story', page.short_name %}
  {% for chapter in filtered_chapters %}
    <li><a href="{{ chapter.url }}">{{ chapter.title }}</a></li>
  {% endfor %}
</ul>
