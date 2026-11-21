# BÁO CÁO BÀI TẬP LỚN A3 — WEBSITE PORTFOLIO CÁ NHÂN
**Học phần:** Thiết kế web và triển khai hệ thống phần mềm (FIT4014)  
**Trường:** Trường Đại Học Đại Nam (DNU)  
**Khoa:** Công nghệ Thông tin (FIT)  
**Lớp học phần:** CNTT 20-04  
**Giảng viên giảng dạy:** ThS. Lê Thái Bảo  

---

## 1. THÔNG TIN SINH VIÊN THỰC HIỆN
- **Họ và tên:** Trần Hoài Nam
- **Mã sinh viên:** `2071020137`
- **Lớp hành chính:** CNTT 20-04 (Khóa K20, niên khóa 2024 – 2028)
- **Ngày sinh:** 05/06/2008
- **Tính cách:** Hòa đồng, nhiệt tình, sôi nổi
- **Sở thích:** Chơi game chiến thuật, chơi thể thao (bóng đá, cầu lông)
- **Facebook:** [https://www.facebook.com/tran.nam.289267](https://www.facebook.com/tran.nam.289267)
- **GitHub:** [https://github.com/TRANHOAINAM123](https://github.com/TRANHOAINAM123)
- **Gmail cá nhân:** `ttuan135789@gmail.com`
- **Email sinh viên DNU:** `2071020137@dnu.edu.vn`
- **Tên đề tài:** Xây dựng Website Portfolio cá nhân tĩnh cho sinh viên ngành Công nghệ Thông tin

---

## 2. PHÂN BỔ MÃ NGUỒN (60% KIẾN THỨC ĐÃ HỌC & 40% TỰ TÌM HIỂU NÂNG CAO)

Nhằm đảm bảo sản phẩm phản ánh đúng năng lực học tập thực tế của sinh viên năm nhất và đạt điểm cao theo Rubric A3 của thầy giáo, mã nguồn được phân bổ rõ ràng như sau:

### A. 60% Kiến thức cơ bản đã học trên lớp (Theo bài giảng & Lab 1 - Lab 5):
1. **Cấu trúc khung HTML5 chuẩn:** `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`, `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`.
2. **Các thẻ nội dung cơ bản:** `<h1>` đến `<h3>`, `<p>`, `<strong>`, `<em>`, `<ul>`, `<li>`, `<a>`, `<img>`, `<div>`, `<span>`.
3. **Bảng dữ liệu (Table):** Sử dụng `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>` trong phần Kế hoạch & Học phần.
4. **Biểu mẫu Form chuẩn Lab 5:** Thẻ `<form action="..." method="...">`, `<label>`, `<input type="text">`, `<input type="email">`, `<textarea>`, `<button type="submit">`, `<small>`.
5. **Định dạng CSS cơ bản:** Thiết lập Box Model (`margin`, `padding`, `border`, `box-sizing: border-box`), phông chữ (`font-family`, `font-size`, `line-height`), màu chữ và nền (`color`, `background-color`), bố cục Flexbox cơ bản cho Header và Hero, định dạng liên kết và trạng thái `:hover`, `:focus`.

### B. 40% Thẻ và thuộc tính tự tìm hiểu nâng cao (Ngoài bài giảng trên lớp):
1. **Thẻ ngữ nghĩa nâng cao (HTML5 Semantic):**
   - `<article>`: Định dạng thẻ độc lập cho từng dự án môn học.
   - `<aside>`: Đóng khung trích dẫn phương châm sống và mục tiêu học tập bên lề.
   - `<figure>` & `<figcaption>`: Chứa ảnh đại diện chân dung sinh viên và dòng chú thích chuẩn SEO.
   - `<time datetime="2008-06-05">`: Định dạng dữ liệu thời gian ngày sinh chuẩn máy đọc.
   - `<mark>`: Đánh dấu làm nổi bật các từ khóa công nghệ trọng tâm.
   - `<details>` & `<summary>`: Hộp tương tác đóng/mở tự nhiên bằng HTML thuần để xem chi tiết mục tiêu năm nhất mà không cần viết JavaScript.
   - `<svg>` & đồ họa vector: Các icon nhận diện thương hiệu cho từng kênh kết nối (Facebook, GitHub, Gmail, Email trường, Địa chỉ) hiển thị sắc nét trên mọi màn hình và hoạt động offline 100%.
2. **Thuộc tính HTML nâng cao:**
   - `loading="lazy"` trên thẻ `<img>` giúp tối ưu tốc độ tải trang.
   - `target="_blank" rel="noopener noreferrer"` trên các liên kết mạng xã hội đảm bảo an toàn bảo mật.
   - Các thuộc tính form: `minlength`, `maxlength`, `required`, `placeholder`.
3. **Kỹ thuật CSS3 hiện đại tự tìm hiểu:**
   - **CSS Variables (`:root`):** Khai báo bảng mã màu chuẩn Đại học Đại Nam (`--primary-color: #12457a`, `--accent-color: #e8a33d`) giúp quản lý giao diện tập trung và nhất quán.
   - **CSS Grid (`display: grid`):** Bố cục lưới linh hoạt cho phần Thông tin bản thân, Kỹ năng và Danh mục dự án.
   - **Hiệu ứng chuyển động mượt mà (`transition` & `transform`):** `transform: translateY(-5px)` kết hợp `box-shadow` tạo hiệu ứng nổi nhẹ khi di chuột vào thẻ dự án.
   - **Cuộn trang mượt mà (`scroll-behavior: smooth`):** Chuyển đổi vị trí êm ái khi nhấp vào menu điều hướng nội bộ.
   - **Màu xen kẽ bảng (`nth-child(even)`):** Giúp người đọc dễ theo dõi bảng học phần.
   - **Media Queries Responsive (`@media`):** Tự động dàn trang tối ưu cho điện thoại di động và máy tính bảng.

---

## 3. TIẾN ĐỘ HỌC TẬP & KẾ HOẠCH ĐÀO TẠO
- **Ngữ cảnh sinh viên:** Sinh viên năm nhất Khóa 20 (2024 &ndash; 2028), vừa hoàn thành xong **Học kỳ 1** (12/12 tín chỉ) và đang chuẩn bị bước vào **Học kỳ 2**.
- **Kết quả Học kỳ 1 (12 TC &ndash; Đã hoàn thành):**
  - **FIT4014 &bull; Thiết kế web và triển khai HT phần mềm (3 TC):** Đang báo cáo Bài tập lớn A3 (Website Portfolio này).
  - **FIT4022 &bull; Nhập môn CNTT (3 TC):** Hoàn thành &bull; Tư duy tin học và nền tảng thuật toán.
  - **FIT4013 &bull; Hệ thống máy tính (3 TC):** Hoàn thành &bull; Phần cứng, kiến trúc máy tính và hệ nhị phân.
  - **DNU1006 &bull; Kỹ năng mềm cơ bản (3 TC):** Hoàn thành &bull; Kỹ năng làm việc nhóm, thuyết trình và giao tiếp.
- **Kế hoạch Học kỳ 2 (12 TC &ndash; Sắp tới):**
  - **FIT4003 &bull; Lập trình cơ bản (3 TC):** Trọng tâm học kỳ 2 (Ngôn ngữ C/C++ và tư duy lập trình cấu trúc).
  - **FIT4002 &bull; Kiến trúc và hệ điều hành máy tính (3 TC):** Quản lý tiến trình, bộ nhớ và HĐH.
  - **FIT3001 &bull; Giải tích (3 TC):** Nền tảng toán giải tích cho ngành CNTT.
  - **ENG2001 &bull; Tiếng Anh 1 (3 TC):** Nâng cao khả năng giao tiếp và đọc tài liệu kỹ thuật.
- **Lộ trình dài hạn (Đào tạo 3 học kỳ / năm tại DNU):**
  - Học kỳ 3 (15 TC): Thiết kế Front-End (FIT4015), Cấu trúc dữ liệu & giải thuật (FIT4004)...
  - Năm thứ 3: Đăng ký lựa chọn **Chuyên ngành Phát triển phần mềm** (trong 4 chuyên ngành: Phát triển phần mềm, Robot & AI, Hệ thống nhúng & IoT, Hệ thống thông tin).

---

## 4. CẤU TRÚC THƯ MỤC DỰ ÁN
```text
portfolio/
├── index.html        # Trang Portfolio chính (Chuẩn Semantic HTML5)
├── css/
│   └── style.css     # Định kiểu CSS3 (Layout, màu sắc, responsive)
├── assets/
│   └── images/
│       └── avatar.jpg # Ảnh chân dung thực tế của sinh viên Trần Hoài Nam
└── README.md         # Báo cáo thuyết minh cấu trúc & phân bổ mã nguồn
```

---

## 5. HƯỚNG DẪN MỞ & KIỂM TRA
1. Vào thư mục `portfolio/`.
2. Nhấp đúp chuột vào tệp `index.html` để mở trang web bằng trình duyệt Google Chrome hoặc Microsoft Edge.
3. Kiểm tra tính năng menu liên kết cuộn trang tự động đến từng phần: Giới thiệu, Về bản thân, Kỹ năng, Dự án, Học phần, Liên hệ.
4. Nhấp vào các liên kết Facebook, GitHub, Email cá nhân.
5. Thử co giãn độ rộng cửa sổ trình duyệt để kiểm tra tính năng hiển thị Responsive trên màn hình nhỏ.
