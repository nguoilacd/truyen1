---
short_name: truyen1  # Tên ngắn, unique, không dấu
title: Truyện 1: Cuộc Phiêu Lưu Tiểu thư giả muốn nhường cho tôi chiếc thẻ đen
description: Mô tả ngắn về truyện 1.
author: Tác Giả A
---

# Giới Thiệu Truyện 1

ô ta dùng “tiếng lòng” nói với cả nhà:“Con chỉ cần tình yêu của ba mẹ thôi!”
Kiếp này, tôi — bậc thầy chỉnh sửa tiếng lòng — liền thêm một câu vào cuối dòng ấy:“Nếu chị không nhận, tức là chị không chấp nhận em! Em sẽ lên sân thượng, lấy m/á/u tỏ lòng trung!”
Ba mẹ nghe xong lập tức biến sắc, không hề do dự mà giật lấy thẻ đen nhét vào tay tôi:“Nhanh nhận đi! Đây là tấm lòng của em con, không được từ chối!”

## Danh Sách Chương

<ul>
  {% assign filtered_chapters = site.posts | where: 'story', page.short_name %}
  {% for chapter in filtered_chapters %}
    <li><a href="{{ chapter.url }}">{{ chapter.title }}</a></li>
  {% endfor %}
</ul>
