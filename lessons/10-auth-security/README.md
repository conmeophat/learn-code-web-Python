# Chặng 10 — Tài khoản, xác thực, phân quyền và bảo mật web

**Mục tiêu:** hiểu các rủi ro thường gặp và xây dựng các luồng tài khoản cơ bản có kiểm soát.

## Danh sách bài học

| Mã | Bài học | Nội dung trọng tâm |
|---|---|---|
| 10.1 | Bảo mật là gì? | Tài sản, mối đe dọa và rủi ro |
| 10.2 | Authentication và authorization | Xác thực khác phân quyền |
| 10.3 | Đăng ký người dùng | Kiểm tra dữ liệu và chính sách tài khoản |
| 10.4 | Mật khẩu và hashing | Không lưu mật khẩu dạng rõ |
| 10.5 | Salt và thuật toán lưu mật khẩu | Dùng thư viện chuyên dụng, cấu hình phù hợp |
| 10.6 | Đăng nhập và đăng xuất | Luồng phiên đăng nhập |
| 10.7 | Session và cookie | Vòng đời phiên và cờ bảo vệ |
| 10.8 | Phân quyền theo vai trò | Role và permission |
| 10.9 | Kiểm tra quyền ở backend | Không chỉ ẩn nút trên giao diện |
| 10.10 | Kiểm tra đầu vào | Kiểu, độ dài, định dạng và giới hạn |
| 10.11 | SQL injection | Truy vấn tham số hóa |
| 10.12 | XSS và nội dung không tin cậy | Encode, sanitize và hiển thị an toàn |
| 10.13 | CSRF và các thao tác thay đổi dữ liệu | Hiểu mô hình tấn công và biện pháp phù hợp |
| 10.14 | HTTPS và truyền dữ liệu | TLS khi triển khai |
| 10.15 | Bí mật cấu hình | API key, token, biến môi trường |
| 10.16 | Rate limiting và chống lạm dụng | Giới hạn thử đăng nhập, spam |
| 10.17 | Upload tệp an toàn | Kiểu tệp, kích thước, tên và quyền |
| 10.18 | Log bảo mật | Không ghi mật khẩu hoặc token |
| 10.19 | Sao lưu và quyền truy cập dữ liệu | Nguyên tắc tối thiểu cần thiết |
| 10.20 | Checklist trước khi mở công khai | Rà soát bảo mật |

## Dự án nhỏ
**Bổ sung tài khoản cho website quản lý công việc:** đăng ký, đăng nhập, đăng xuất; người dùng chỉ xem và chỉnh sửa dữ liệu được phép; tài khoản quản trị có quyền riêng.

## Quy tắc bắt buộc
- Không tự thiết kế thuật toán hash mật khẩu.
- Không lưu mật khẩu dạng văn bản thường.
- Không tin dữ liệu gửi từ trình duyệt; backend phải kiểm tra lại.
- Không dùng việc ẩn nút trên giao diện làm cơ chế phân quyền.
- Không đưa bí mật vào GitHub.
- Không tự tuyên bố ứng dụng an toàn chỉ vì đã có màn hình đăng nhập.

## Tiêu chí hoàn thành
- [ ] Giải thích được authentication và authorization.
- [ ] Mật khẩu được lưu bằng giải pháp hash chuyên dụng.
- [ ] Kiểm tra quyền ở phía máy chủ.
- [ ] Bí mật được cấu hình ngoài mã nguồn.
- [ ] Kiểm tra dữ liệu đầu vào và các tình huống lạm dụng cơ bản.
- [ ] Hoàn thành checklist bảo mật trước khi triển khai.