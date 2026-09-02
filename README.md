# 📚 Lịch Học Tuần (Weekly Study Schedule)

Ứng dụng web toàn diện quản lý và theo dõi **Lịch Học Tuần** cá nhân theo phong cách thiết kế hiện đại **Dark Theme & Glassmorphism**. Hỗ trợ tùy biến khung giờ ca học không giới hạn, tùy biến môn học & mã màu, thao tác thêm/sửa/xóa trực quan, lưu trữ bền vững với `localStorage` và sao lưu trọn gói qua JSON.

---

## ✨ Các tính năng nổi bật

### 1. 📅 Lịch Học Tuần (Weekly Schedule)
- **Lưới thời khóa biểu tự động co giãn**: Hoạt động linh hoạt theo số ca học động (không còn giới hạn cứng nhắc 3 ca Sáng/Chiều/Tối).
- **Thao tác nhanh trên từng ca học**:
  - **Thêm ca học**: Bấm nút **"+ Thêm ca học"** trên thanh công cụ hoặc nhấp trực tiếp vào ô ca học trống.
  - **Chỉnh sửa ca học**: Hover vào ca học và bấm biểu tượng bút chì ✏️ để đổi môn học, thời gian hoặc icon.
  - **Xóa ca học**: Bấm biểu tượng thùng rác 🗑️ trên thẻ học (có hộp thoại xác nhận an toàn).
- **Tự động nhận diện tuần & ngày hiện tại**: Highlight ngày "Hôm nay" nổi bật với quầng sáng radar ping.
- **Đồng hồ thời gian thực (Live Clock)** đếm giây và hiển thị thứ ngày tháng tiếng Việt.
- **4 Thẻ thống kê động**: Tổng giờ học, tổng buổi học, số môn học đang học và số ngày học liên tục.
- **📊 Bảng Phân Bổ Thời Lượng Từng Môn**:
  - Tự động bóc tách và tính chuẩn xác số giờ học của từng môn (IELTS/Tiếng Anh, Frontend, Rikkei Academy, Chill...).
  - Thanh phân bổ đa sắc trực quan (Multi-segment Bar) kèm tỷ lệ phần trăm (%).
  - Thẻ chi tiết cho mỗi môn: hiển thị số giờ học, số buổi học và thanh tiến độ tương ứng.

### 2. ⚙️ Tùy Biến Ca Học & Môn Học (Settings)
- **Quản lý Ca Học & Khung Giờ (Slots)**:
  - Tự do sửa đổi giờ bắt đầu - kết thúc của bất kỳ ca nào (VD: đổi ca Sáng thành `08:00 - 11:30`).
  - Thêm ca học mới (VD: Ca Đêm `22:00 - 00:30`, Ca Chiều sớm, Ca 1, Ca 2...).
  - Xóa ca học không dùng đến. Thời khóa biểu sẽ tự động cập nhật số hàng tương ứng.
- **Quản lý Môn Học & Mã Màu (Subjects & Color Themes)**:
  - Tạo môn học mới (VD: *Python AI*, *Data Structures*, *Gym / Thể thao*...).
  - Gán mã màu theo bảng màu hiện đại (Sky, Indigo, Amber, Emerald, Rose, Purple, Teal, Orange, Fuchsia, Lime).
  - Tự động đồng bộ sang bảng chọn trong form thêm lịch và chú giải màu (Legend) ở cuối trang.

### 3. 💾 Lưu trữ & Sao lưu trọn gói
- Tự động lưu mọi thay đổi vào `localStorage` của trình duyệt.
- **Xuất JSON**: Tải về file sao lưu trọn gói chứa toàn bộ ca học, môn học và thời khóa biểu.
- **Nhập JSON**: Khôi phục lại toàn bộ dữ liệu chỉ với 1 click.
- **Đặt lại mặc định**: Khôi phục nhanh về bộ dữ liệu mẫu chuẩn ban đầu.

---

## 🛠️ Công nghệ sử dụng

- **HTML5 & Vanilla JavaScript (ES6+)**: Xử lý logic render động, điều hướng tab, CRUD dữ liệu và tương tác LocalStorage.
- **Tailwind CSS (CDN)**: Utility-first CSS framework cho layout và responsive.
- **Custom Glassmorphism CSS**: Thiết kế Dark Theme hiện đại, hiệu ứng kính mờ `backdrop-filter`, chuyển sắc gradient neon, quầng sáng orb.
- **Lucide Icons**: Bộ icon hiện đại, sắc nét.
- **Google Fonts (Plus Jakarta Sans)**: Font chữ cao cấp, sang trọng.

---

## 🚀 Hướng dẫn chạy ứng dụng

Dự án là ứng dụng Web tĩnh (Static Web App), không cần cài đặt Node.js hay bất kỳ build tool nào:
1. Mở thư mục dự án `Lịch học/`.
2. Nhấp đúp chuột vào file `index.html` để mở trực tiếp trên trình duyệt web (Chrome, Edge, Firefox, Brave,...).
3. Hoặc nhấp chuột phải vào `index.html` chọn **Open with Live Server** trong VS Code.

---

## 💡 Động lực & Triết lý

> *"Kỷ luật là cây cầu nối giữa mục tiêu và thành tựu."* — Jim Rohn
