# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Phạm Anh Quân

**MSSV:** 1871020471

**Lớp/Nhóm:** CNTT18-02


## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Dữ liệu điểm số sinh viên
- Asset 2: Thông tin tài khoản đăng nhập
- Asset 3 (nếu có): Hệ thống quản lý điểm


## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Ảnh hưởng đến khả năng truy cập hệ thống(Availability)
- Sự cố B -> Làm sai lệch dữ liệu(Integrity)
- Sự cố C -> Rò rỉ thông tin nhạy cảm(Confidentiality)


## 3. Phân tích sự cố B
- Threat: Kẻ tấn công xâm nhập và thay đổi dữ liệu
- Vulnerability: Hệ thống bảo mật yếu, mật khẩu dễ đoán
- Mitigation: Áp dụng xác thực nhiều lớp (MFA) và kiểm soát quyền chỉnh sửa dữ liệu


## 4. Reflection
Viết 5-7 dòng.

Nếu ở vai trò quản trị hệ thống, em sẽ tập trung đảm bảo tính toàn vẹn của dữ liệu trước tiên. Việc điểm số bị thay đổi sai lệch có thể gây hậu quả nghiêm trọng đến sinh viên cũng như độ tin cậy của hệ thống. Để giảm thiểu rủi ro, em sẽ tăng cường các biện pháp bảo mật như xác thực đa yếu tố, phân quyền chi tiết theo vai trò và theo dõi nhật ký hệ thống. Ngoài ra, việc thiết lập quy trình kiểm duyệt khi chỉnh sửa điểm cũng rất cần thiết. Sau khi đảm bảo dữ liệu an toàn, em sẽ tiếp tục cải thiện hiệu suất và độ ổn định của hệ thống.


## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`
Flag của em:
FIT4012{A-AV-B-IN-C-CO}
