# 💰 Quản Lý Tài Chính Cá Nhân (Personal Finance App)

![Flutter](https://img.shields.io/badge/Frontend-Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Node.js](https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Status](https://img.shields.io/badge/Status-Production-success?style=for-the-badge)

Một giải pháp toàn diện giúp theo dõi, quản lý luồng thu chi cá nhân với trải nghiệm liền mạch trên thiết bị di động. Ứng dụng được thiết kế theo kiến trúc Offline-First, kết hợp tính năng đồng bộ đám mây (Cloud Sync) để đảm bảo an toàn dữ liệu.

🔥 **[BẤM VÀO ĐÂY ĐỂ TẢI APP (APK) VÀ TRẢI NGHIỆM THỰC TẾ](https://drive.google.com/drive/folders/1uX3f1ohw20olG5HzCIzDcJeydovqityj?usp=sharing)** 🔥

---

## 🔗 Các thành phần hệ thống (Repositories)
Dự án được chia thành 2 module độc lập để dễ dàng bảo trì và mở rộng:

* 📱 **Frontend (Mobile App):** [BẤM VÀO ĐÂY ĐỂ XEM CODE FLUTTER](https://github.com/MDHNam611/quan_ly_tai_chinh_flutter_FE.git)
* ⚙️ **Backend (RESTful API):** [BẤM VÀO ĐÂY ĐỂ XEM CODE NODE.JS](https://github.com/MDHNam611/quan_ly_tai_chinh_flutter_BE.git)

---

## ✨ Tính năng nổi bật & Kiến trúc Kỹ thuật

* **Kiến trúc Offline-First:** Sử dụng `SQLite` lưu trữ cục bộ, cho phép người dùng ghi chép giao dịch ngay cả khi không có kết nối mạng.
* **Đồng bộ Đám mây (Cloud Sync):** Xử lý luồng PUSH/PULL dữ liệu giữa SQLite và MongoDB Atlas (Được triển khai trên Render Server), bảo toàn dữ liệu khi người dùng đổi thiết bị.
* **Xác thực bảo mật đa lớp:** * Xác thực truyền thống với `JWT Token`.
  * Đăng nhập một chạm với **Google Sign-In (OAuth 2.0 / Firebase)**.
  * Khôi phục mật khẩu an toàn qua mã OTP tự động gửi về Email.
* **Tối ưu hóa UX/UI Thực chiến:** Tự động chặn lỗi nhập liệu, khóa các luồng nạp/rút tiền, và giới hạn hiển thị để chống vỡ giao diện với các con số cực lớn.

---

## 📸 Hình ảnh thực tế (Screenshots)

### 1. 🔐 Đăng nhập & Xác thực (Authentication)
<div align="center">
  <img src="https://github.com/user-attachments/assets/40179d5a-2fe1-4604-aa6f-123626c5e266" width="200" alt="Đăng nhập" />
  <img src="https://github.com/user-attachments/assets/30637124-37af-44ee-85da-e87c41cd3e39" width="200" alt="Đăng ký" />
  <img src="https://github.com/user-attachments/assets/907dbd81-6a35-4cdc-a3fa-6e2b53902a9e" width="200" alt="Đăng nhập Google" />
  <img src="https://github.com/user-attachments/assets/c12fd4ba-21e3-4f6f-b35b-cc06ab4bd6f1" width="200" alt="Profile Menu" />
</div>
<div align="center">
  <i>Đăng nhập thường | Đăng ký | Đăng nhập Google Sign-In | Menu Cá nhân & Đồng bộ đám mây</i>
</div>

<br>

### 2. 📧 Khôi phục mật khẩu qua Email (OTP Recovery)
<div align="center">
  <img src="https://github.com/user-attachments/assets/90c50de2-4720-4247-8e5d-681468df039e" width="200" alt="Yêu cầu OTP" />
  <img src="https://github.com/user-attachments/assets/2d9f94da-852a-4293-a0a4-846774ad0b10" width="200" alt="Xác thực & Đổi mật khẩu" />
</div>
<div align="center">
  <img src="https://github.com/user-attachments/assets/09e4dd9b-fac8-4699-9f85-2cf9edf315c2" width="410" alt="Email Template OTP" />
</div>
<div align="center">
  <i>Gửi yêu cầu OTP | Nhập OTP & Mật khẩu mới | Giao diện Email thông báo tự động từ hệ thống</i>
</div>

<br>

### 3. 📊 Tổng quan & Thống kê (Overview & Dashboard)
<div align="center">
  <img src="https://github.com/user-attachments/assets/dd6adcdd-256e-486d-9f9d-0e305dc96767" width="250" alt="Biểu đồ chi phí" />
  <img src="https://github.com/user-attachments/assets/e787f05f-0074-402c-acd0-66c6f71b8c09" width="250" alt="Biểu đồ Thu nhập" />
  <img src="https://github.com/user-attachments/assets/79bf4c09-1c6c-41dd-a8b7-3e8cc174840b" width="250" alt="Chọn kỳ thống kê" />
</div>
<div align="center">
  <i>Biểu đồ Chi phí theo tháng | Biểu đồ Thu nhập | Trình chọn thời gian (Tuần/Tháng/Năm)</i>
</div>

<br>

### 4. 💳 Quản lý Tài khoản & Ví (Accounts)
<div align="center">
  <img src="https://github.com/user-attachments/assets/bf226b0b-fbce-49fc-aa60-3805d9249c9c" width="250" alt="Danh sách Ví" />
  <img src="https://github.com/user-attachments/assets/f0196fff-3004-4f43-a879-662f7c68fa87" width="250" alt="Tùy chọn Ví" />
  <img src="https://github.com/user-attachments/assets/3f1df8ef-21f4-4059-9429-fe3cb8099e86" width="250" alt="Chuyển khoản" />
</div>
<div align="center">
  <i>Danh sách Ví hiện có | Menu Thao tác (Rút/Nạp/Chỉnh sửa) | Giao diện Chuyển khoản nội bộ</i>
</div>

<br>

### 5. 🏷️ Danh mục Thu/Chi (Categories)
<div align="center">
  <img src="https://github.com/user-attachments/assets/3005c7b2-5996-4145-af24-86c4d32a6005" width="250" alt="Biểu đồ Danh mục" />
  <img src="https://github.com/user-attachments/assets/f1c0e4f5-4e93-4cee-bd3a-ca4d4a56e674" width="250" alt="Tùy chỉnh Icon" />
  <img src="https://github.com/user-attachments/assets/554459fd-71bb-44d9-8444-837eaee0496b" width="250" alt="Thêm danh mục" />
</div>
<div align="center">
  <i>Biểu đồ Tỷ trọng Chi tiêu | Trình chọn Biểu tượng & Màu sắc động | Thêm Danh mục phân nhóm</i>
</div>

<br>

### 6. 📝 Quản lý Giao dịch (Transactions)
<div align="center">
  <img src="https://github.com/user-attachments/assets/05994261-cc2b-4498-b693-c66bb10a22d1" width="250" alt="Lịch sử giao dịch" />
  <img src="https://github.com/user-attachments/assets/c2e876ec-a593-4ab2-89c0-06b78039b3dc" width="250" alt="Thêm Giao dịch" />
  <img src="https://github.com/user-attachments/assets/4eb03eed-962c-488a-962b-833ac522a808" width="250" alt="Bộ lọc Tìm kiếm" />
</div>
<div align="center">
  <i>Lịch sử Giao dịch theo ngày | Form Nhập liệu trực quan | Bộ lọc nâng cao (Đa điều kiện)</i>
</div>

---

## 👨‍💻 Thông tin tác giả
* **Nhà phát triển:** Mai Đức Hoàng Nam
* **Sinh viên năm 4:** Ngành Công nghệ Thông tin - HUTECH (Chuyên ngành Công nghệ Phần mềm)
* **Vai trò:** Fullstack Mobile Developer (Xây dựng trọn bộ giải pháp từ Mobile App đến RESTful API & Cloud Database).
