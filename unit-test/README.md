# Unit Test - StudentAnalyzer

**Sinh viên:** Trần Đức Việt  
**MSSV:** BIT230450  
**Môn:** Kiểm thử phần mềm 2026

---

## 1. Mô tả bài toán

Bài tập yêu cầu viết chương trình Java để **phân tích điểm số học sinh**:

- **countExcellentStudents(List<Double> scores):**
    - Đếm số học sinh đạt loại Giỏi (>=8.0).
    - Bỏ qua các điểm <0 hoặc >10.
    - Trả về 0 nếu danh sách rỗng.

- **calculateValidAverage(List<Double> scores):**
    - Tính trung bình các điểm hợp lệ (0-10).
    - Trả về 0 nếu danh sách rỗng.

---

## 2. Cấu trúc dự án

unit-test/
├── README.md
├── src/
│ └── main/java/com/example/StudentAnalyzer.java
├── test/
│ └── java/com/example/StudentAnalyzerTest.java
└── images/
├── Screenshot 2026-01-12 094149.png
├── Screenshot 2026-01-12 085646.png
└── Screenshot 2026-01-12 085558.png


> Folder `images/` chứa tất cả ảnh minh họa kết quả test.

---

## 3. Cách chạy chương trình

1. Mở dự án bằng **IntelliJ IDEA** (hoặc IDE Java khác).
2. Maven sẽ tự động quản lý dependency **JUnit 5**.
3. Chạy chương trình chính hoặc test:

- Chạy tất cả test: **Right click → Run 'All Tests'**
- Chạy từng test case: **Right click → Run 'StudentAnalyzerTest'**

---

## 4. Kết quả test

Các test case đã thực hiện:

1. **countExcellentStudents()**
    - Danh sách có điểm hợp lệ & không hợp lệ
    - Danh sách trống
    - Danh sách toàn 0 hoặc 10

2. **calculateValidAverage()**
    - Tính trung bình các điểm hợp lệ
    - Trường hợp danh sách rỗng

### Hình minh họa kết quả test:
![Kết quả 1](src/images/Screenshot%202026-01-12%20085558.png))  
![Kết quả 2](src/images/Screenshot%202026-01-12%20085646.png)
![Kết quả 3](src/images/Screenshot%202026-01-12%20094149.png)

---

## 5. GitHub Issues

- **Issue #1:** Viết hàm `countExcellentStudents()`
- **Issue #2:** Viết hàm `calculateValidAverage()`
- **Issue #3:** Viết test cho 2 hàm trên
- **Issue #4:** Viết README.md

> Mỗi commit đã link với issue tương ứng để quản lý lịch sử rõ ràng.

---

## 6. Chú ý

- Mọi file code & test nằm trong folder `src/` và `test/`.
- Folder `images/` dùng để chứa tất cả ảnh minh họa.
- README.md đã được định dạng Markdown đẹp, hiển thị tốt trên GitHub.