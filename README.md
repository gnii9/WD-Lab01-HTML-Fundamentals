# WD-Lab01: HTML Fundamentals & Document Structure

Dự án Portfolio cá nhân và sáu chuyên đề thực hành HTML5 chuẩn semantic, được thiết kế theo hướng tiếp cận hiện đại (UI/UX Design System bằng Vanilla CSS) và quản lý mã nguồn qua Git/GitHub.

---

## 🚀 Hướng dẫn Chạy trên Localhost (XAMPP)

1. Sao chép hoặc clone thư mục `html-fundamentals-lab` vào thư mục `C:\xampp\htdocs\`.
2. Mở **XAMPP Control Panel**, nhấn **Start** dịch vụ **Apache** (cổng mặc định 80).
3. Mở trình duyệt web bất kỳ và truy cập đường dẫn:
   ```
   http://localhost/html-fundamentals-lab/
   ```

---

## 📂 Cấu trúc Tệp & Thư mục

- `index.html`: Trang Portfolio cá nhân chính gồm đầy đủ các mục chuẩn: Giới thiệu (About), Kỹ năng (Skills), Dự án (Projects), Kế hoạch Học tập (Education với Table dữ liệu), Mục tiêu học tập, Nhật ký thực hành, Danh mục 6 bài thực hành và Biểu mẫu liên hệ tĩnh (Contact).
- `bai-1-headings.html` đến `bai-6-topic.html`: Sáu trang chuyên đề thực hành độc lập thuộc Phần 1 theo đúng yêu cầu đề bài.
- `style.css`: Hệ thống thiết kế Vanilla CSS hiện đại (Design Tokens, Typography Plus Jakarta Sans, Card Layout, Responsive Mobile-first).
- `images/`: Chứa các tài nguyên hình ảnh bài học (`cats.gif`, `scene.jpg`, `space.jpg`, `book.jpg`) và các đồ họa vector SVG (`profile-hong.svg`, `project-web-lab.svg`, `project-data-plan.svg`).

---

## 🎯 Điểm nổi bật về Kỹ thuật & UI/UX

1. **Chuẩn ngữ nghĩa HTML5 (Semantic Structure):**
   - Sử dụng triệt để các thẻ cấu trúc: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<figcaption>`, `<footer>`.
   - Cấu trúc lồng thẻ LIFO nghiêm ngặt, không crossing tags.
   - Thẻ `<table>` phân cấp chuẩn: `caption`, `thead`, `tbody`, `tr`, `th scope="col"`, `td`.
   - Biểu mẫu tĩnh chuẩn trợ năng (Accessibility): `label for` liên kết chính xác 100% với `input id`.

2. **Nâng cấp UI/UX Hiện đại:**
   - Font chữ Google Fonts `Plus Jakarta Sans` chuyên nghiệp, sắc nét.
   - Bảng màu hài hòa Slate & Royal Blue mang phong cách website công nghệ/học thuật hiện đại.
   - Điều hướng mượt mà với hiệu ứng hover và nút cuộn về đầu trang `#top`.
   - Nút quay lại `← Về trang chính` trên tất cả 6 bài con giúp trải nghiệm điều hướng liền mạch.

---

## 🛠️ Quản lý Mã nguồn (Git/GitHub)

- **Repository:** `https://github.com/gnii9/WD-Lab01-HTML-Fundamentals.git`
- **Nhánh chính:** `main`
