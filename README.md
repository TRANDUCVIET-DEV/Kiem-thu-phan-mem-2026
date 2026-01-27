# Báo cáo thực hành môn Kiểm thử phần mềm
**Sinh viên:** Trần Đức Việt  
**MSSV:** [BIT230450]

## Bài tập tuần 1: Trải nghiệm chất lượng giao diện
Dưới đây là kết quả từ cantunsee.space:

![Kết quả Cantunsee](Screenshot%202026-01-08%20102436.png)


# 🧪 BÁO CÁO BÀI THỰC HÀNH CYPRESS

## 👨‍🎓 Thông tin sinh viên
- Họ tên: Trần Đức Việt
- Môn học: Kiểm thử phần mềm
- Nội dung: Kiểm thử tự động với Cypress (End-to-End Testing)

---

## 🎯 Mục tiêu bài thực hành
- Làm quen với công cụ kiểm thử tự động Cypress.
- Viết test case tự động cho các chức năng cơ bản của website.
- Thực hành cấu trúc project Cypress chuẩn.
- Biết cách chạy test và đọc kết quả kiểm thử.
- Quản lý mã nguồn bằng GitHub.

---

## 🗂️ Cấu trúc thư mục dự án

cypress-exercise
├── cypress
│ ├── e2e
│ │ ├── cart_spec.cy.js
│ │ └── login_spec.cy.js
│ ├── fixtures
│ └── support
├── node_modules
├── cypress.config.js
├── package.json
├── README.md
└── Screenshot ...


---

## 🧪 Nội dung kiểm thử

### ✅ 1. Kiểm thử chức năng đăng nhập (login_spec.cy.js)
- Kiểm tra đăng nhập với tài khoản hợp lệ.
- Kiểm tra hiển thị thông báo lỗi khi nhập sai thông tin.
- Đảm bảo hệ thống phản hồi đúng sau khi đăng nhập.

---

### ✅ 2. Kiểm thử chức năng giỏ hàng (cart_spec.cy.js)
- Kiểm tra thêm sản phẩm vào giỏ hàng.
- Kiểm tra số lượng sản phẩm.
- Kiểm tra xóa sản phẩm khỏi giỏ hàng.
- Đảm bảo dữ liệu hiển thị chính xác.

---

## ▶️ Kết quả chạy kiểm thử

### 📸 Hình ảnh kết quả Cypress

**Giao diện chạy test trên Cypress:**

![Cypress Result 1](Screenshot%202026-01-27%20101808.png)

**Kết quả test case chi tiết:**

![Cypress Result 2](Screenshot%202026-01-27%20101821.png)

---

## ✅ Đánh giá kết quả
- Tất cả các test case đều chạy thành công (PASS).
- Các chức năng hoạt động đúng như mong đợi.
- Không phát hiện lỗi trong quá trình kiểm thử.
- Hệ thống ổn định khi chạy test tự động.

---

## 📌 Kết luận
Thông qua bài thực hành, sinh viên đã:
- Hiểu cách cài đặt và cấu hình Cypress.
- Viết được test tự động cho website.
- Biết cách tổ chức source code kiểm thử.
- Nâng cao kỹ năng kiểm thử phần mềm và làm việc với Git.

---

## 📤 Hướng dẫn chạy project

```bash
npm install
npx cypress open

---

# ✅ BƯỚC 3 – Lưu & Push lên GitHub

Trong terminal:

```bash
git add .
git commit -m "docs: update README with Cypress report and screenshots"
git pull
git push
