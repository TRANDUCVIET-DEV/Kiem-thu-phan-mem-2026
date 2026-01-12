# Bài thực hành JUnit - Student Analyzer

## Mục tiêu
- Đếm số học sinh đạt loại Giỏi (>= 8.0)
- Tính điểm trung bình các điểm hợp lệ (0–10)

## Mô tả
Các điểm < 0 hoặc > 10 được xem là dữ liệu sai và bị bỏ qua.

## Công nghệ sử dụng
- Java 17
- Maven
- JUnit 5

## Cách chạy kiểm thử

### Cách 1: Trong IntelliJ
Chuột phải vào StudentAnalyzerTest → Run

### Cách 2: Bằng Maven
```bash
mvn test
