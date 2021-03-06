---
layout: page
title: IBus BoGo
tagline: Type with fun
---
{% include JB/setup %}

### Thông báo

Phát hành _IBus Bogo v0.2_ với nhiều cái tiến và tính năng mới.
Chi tiết tại [đây](http://bogoengine.github.com/2012/11/15/release-notes-v02/).

***

## Giới thiệu


**IBus BoGo** là một engine xử lý gõ tiếng Việt cho IBus, một phần mềm quản lý các bộ gõ phổ biến trong Linux.
**IBus BoGo** được viết bằng ngôn ngữ Python và xử dụng engine xử lý
tiếng Việt **BoGoEngine**.

## Hướng dẫn nhanh


1. [Cài đặt](https://github.com/BoGoEngine/ibus-bogo-python/wiki/C%C3%A0i-%C4%91%E1%BA%B7t-%7C-Install) và sử dụng
2. Chia sẻ cho người thân
3. Nếu có câu hỏi, hãy trò chuyện với chúng tôi ở [mailing list của nhóm](bogoengine-dev@googlegroups.com)
4. [Thông báo lỗi và đóng góp ý tưởng](https://github.com/BoGoEngine/ibus-bogo-python/issues?state=open)
5. Fork, vọc code và [tham gia đóng góp](https://github.com/BoGoEngine/ibus-bogo-python/wiki/Tham-gia-d%E1%BB%B1-%C3%A1n-%7C-Contribute)

## Giấy phép xuất bản (License)


**IBus BoGo** là phần mềm tự do nguồn mở.

Toàn bộ mã nguồn của **IBus BoGo** và **BoGoEngine** cùng tất cả các
tài nguyên đi kèm đều được phát hành dưới các quy định ghi trong 
Giấy phép Công cộng GNU, phiên bản 3.0 (GNU General Public License v3.0).
Xem tệp *COPYING* để biết thêm chi tiết.

## Credits


Bản quyền (C) năm 2012 bởi:

* [Đàm Tiến Long](https://github.com/milkycoffee)
* [Trung Ngo](https://github.com/lewtds)

Nhóm phát triển xin chân thành gửi lời cảm ơn đặc biệt đến:

* [Ngô Huy](https://github.com/NgoHuy)
* [Nguyễn Hà Dương](https://github.com/CMPITG)
* [Hà Quang Dương](https://github.com/haqduong)

***

_Các bài cũ hơn_


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
