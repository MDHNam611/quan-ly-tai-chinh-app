# 💰 Quản Lý Tài Chính Cá Nhân (Personal Finance App)

![Flutter](https://img.shields.io/badge/Frontend-Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Node.js](https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

Một giải pháp toàn diện giúp theo dõi, quản lý luồng thu chi cá nhân với trải nghiệm liền mạch trên thiết bị di động. Ứng dụng được thiết kế theo kiến trúc Offline-First, kết hợp tính năng đồng bộ đám mây (Cloud Sync) để đảm bảo an toàn dữ liệu.

## 🔗 Các thành phần hệ thống (Repositories)
Dự án được chia thành 2 module độc lập để dễ dàng bảo trì và mở rộng:

* 📱 **Frontend (Mobile App):** [BẤM VÀO ĐÂY ĐỂ XEM CODE FLUTTER](https://github.com/MDHNam611/quan_ly_tai_chinh_flutter_FE.git)
* ⚙️ **Backend (RESTful API):** [BẤM VÀO ĐÂY ĐỂ XEM CODE NODE.JS](https://github.com/MDHNam611/quan_ly_tai_chinh_flutter_BE.git)

---

## ✨ Tính năng nổi bật

* **Kiến trúc Offline-First:** Sử dụng `SQLite` lưu trữ cục bộ, cho phép người dùng ghi chép giao dịch ngay cả khi không có kết nối mạng.
* **Đồng bộ Đám mây (Cloud Sync):** Xử lý luồng PUSH/PULL dữ liệu giữa SQLite và MongoDB, bảo toàn dữ liệu khi người dùng đổi thiết bị.
* **Xác thực bảo mật đa lớp:** * Xác thực truyền thống với `JWT Token`.
  * Đăng nhập một chạm với **Google Sign-In (OAuth 2.0 / Firebase)**.
* **Quản lý Thu Chi (CRUD):** Thêm, sửa, xóa, thống kê phân loại giao dịch (Income/Expense) theo thời gian thực.

---

## 📸 Hình ảnh thực tế (Screenshots)
*(Gợi ý: Hãy chụp 3 tấm ảnh giao diện app bằng điện thoại/máy ảo, kéo thả trực tiếp vào giao diện chỉnh sửa của GitHub để nó tự tạo link ảnh, rồi dán link vào đây)*

<div align="center">
  <img src="[link-anh-1]" width="250"/>
  <img src="[link-anh-2]" width="250"/>
  <img src="[link-anh-3]" width="250"/>
</div>

---

## 👨‍💻 Thông tin tác giả
* **Nhà phát triển:** Mai Đức Hoàng Nam
* **Vai trò:** Fullstack Mobile Developer (Tự xây dựng từ A-Z cả Frontend lẫn Backend).
