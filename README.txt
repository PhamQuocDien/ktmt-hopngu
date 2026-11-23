LEARNHUB – CẤU TRÚC NHIỀU KHÓA HỌC

MỞ
1. Giải nén toàn bộ gói ZIP.
2. Mở index.html ở thư mục gốc bằng Chrome hoặc Edge.
3. Chọn khóa học trong Danh mục khóa học. Hiện tại chỉ có KTMT được triển khai.

CẤU TRÚC
index.html                         Trang chủ / danh mục khóa học
courses/ktmt/ktmt.html            Trang hiện tại của khóa KTMT
courses/ktmt/mindmap-data.json      Dữ liệu sơ đồ kiến thức
courses/ktmt/pdf_chapters/          Sáu PDF Chapter 00–05

MỞ RỘNG THÊM MÔN HỌC (VỀ SAU)
1. Tạo thư mục courses/<slug-khoa-hoc>/.
2. Đặt trang môn học tại courses/<slug-khoa-hoc>/course.html.
3. Thêm một thẻ khóa học và một record vào mảng courses trong script của index.html gốc.
4. Giữ tài nguyên, CSS/JS và khóa localStorage riêng trong thư mục/namespace của khóa học đó.

Mỗi khóa học nên quản lý tiến độ, tài liệu, bài tập và dữ liệu riêng; trang chủ chỉ làm nhiệm vụ điều hướng/catalog.

KHÓA HIỆN CÓ
- Kiến trúc máy tính và Hợp ngữ HCMUTE: 9/20 buổi (45%), phạm vi sơ đồ hiện tại Buổi 01–09.
