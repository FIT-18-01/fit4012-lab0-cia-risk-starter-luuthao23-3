# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Lưu Phương Thảo

**MSSV:** 1871020681

**Lớp/Nhóm:** CNTT 18-01

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Dữ liệu điểm của sinh viên
- Asset 2: Tài khoản đăng nhập của giảng viên và sinh viên
- Asset 3 (nếu có): Hệ thống server và cơ sở dữ liệu

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A ->Availability (A)
- Sự cố B ->Integrity (I)
- Sự cố C ->Confidentiality (C)

---

## 3. Phân tích sự cố B
- Threat: Người dùng trái phép hoặc hacker truy cập hệ thống và thay đổi điểm
- Vulnerability:
Hệ thống không kiểm tra phân quyền chặt chẽ
Không có cơ chế ghi log hoặc kiểm tra thay đổi dữ liệu
- Mitigation:
Áp dụng phân quyền rõ ràng (chỉ giảng viên được sửa điểm)
Ghi log tất cả các thay đổi dữ liệu
Sử dụng xác thực mạnh (ví dụ: 2FA)

---

## 4. Reflection
Em sẽ ưu tiên xử lý sự cố B trước vì đây là vấn đề liên quan đến tính toàn vẹn của dữ liệu. Khi điểm số bị thay đổi, nó ảnh hưởng trực tiếp đến kết quả học tập và quyền lợi của sinh viên. Nếu không xử lý kịp thời, hệ thống sẽ mất uy tín và gây ra nhiều tranh chấp. Sau đó, em sẽ xử lý sự cố A để đảm bảo hệ thống luôn sẵn sàng phục vụ người dùng. Cuối cùng, em sẽ giải quyết sự cố C nhằm tăng cường bảo mật và tránh rò rỉ thông tin ra bên ngoài.


---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em: FIT4012{A-A-B-I-C-C}

