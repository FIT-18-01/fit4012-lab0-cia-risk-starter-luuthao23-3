# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Dữ liệu điểm của sinh viên
- Tài khoản đăng nhập của giảng viên và sinh viên

**CIA mapping:**
- Sự cố A -> Availability (A)
- Sự cố B -> Integrity (I)
- Sự cố C -> Confidentiality (C)

**Phân tích sự cố B:**
- Threat: Người dùng trái phép hoặc hacker thay đổi dữ liệu điểm
- Vulnerability: Hệ thống chưa có cơ chế phân quyền chặt chẽ và không ghi log thay đổi dữ liệu
- Mitigation: Áp dụng phân quyền rõ ràng, ghi log hệ thống và sử dụng xác thực mạnh (2FA)

### 4. Kết luận ngắn
Qua bài lab này, em đã hiểu rõ hơn về ba yếu tố quan trọng trong an toàn thông tin là Confidentiality, Integrity và Availability. Em cũng học được cách xác định tài sản cần bảo vệ và phân tích một sự cố dựa trên threat, vulnerability và mitigation. Phần khó nhất là phân biệt giữa threat và vulnerability vì hai khái niệm này khá dễ nhầm lẫn. Ngoài ra, em nhận thấy khi phân tích một sự cố cần phải nhìn từ nhiều góc độ khác nhau để đưa ra giải pháp phù hợp. Bài lab giúp em làm quen với quy trình làm việc thực tế và sử dụng GitHub để quản lý bài làm.