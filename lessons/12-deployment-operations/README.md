# Chặng 12 — Triển khai, vận hành và bảo trì website

**Mục tiêu:** chuyển website từ môi trường phát triển trên máy cá nhân sang môi trường người dùng có thể truy cập, đồng thời biết theo dõi và phục hồi khi có sự cố.

## Danh sách bài học

| Mã | Bài học | Nội dung trọng tâm |
|---|---|---|
| 12.1 | Local và production | Khác biệt giữa máy phát triển và máy chạy thật |
| 12.2 | Chọn môi trường triển khai | Máy chủ, nền tảng cloud và tiêu chí chọn |
| 12.3 | Linux và terminal cơ bản | Thư mục, quyền và tiến trình |
| 12.4 | Cấu hình ứng dụng | Config và biến môi trường |
| 12.5 | Cài runtime và phụ thuộc | Python, venv, requirements |
| 12.6 | Chạy ứng dụng trên máy chủ | Tiến trình và cổng |
| 12.7 | Reverse proxy | Vai trò của proxy phía trước app |
| 12.8 | Domain và DNS | Trỏ tên miền |
| 12.9 | HTTPS và TLS | Chứng chỉ và kết nối an toàn |
| 12.10 | Firewall và cổng mạng | Chỉ mở dịch vụ cần thiết |
| 12.11 | Quản lý tiến trình | Tự khởi động lại và dừng an toàn |
| 12.12 | Deploy từ Git | Quy trình cập nhật phiên bản |
| 12.13 | Migration database | Cập nhật schema an toàn |
| 12.14 | Backup và restore | Lịch sao lưu và thử phục hồi |
| 12.15 | Monitoring và logging | Theo dõi tình trạng ứng dụng |
| 12.16 | Xử lý sự cố | Phân loại, khoanh vùng và rollback |
| 12.17 | Cập nhật bảo mật | Thư viện và cấu hình |
| 12.18 | Chi phí vận hành | Tài nguyên, domain và lưu trữ |
| 12.19 | Hướng dẫn người dùng | Tài liệu, hỗ trợ và quy trình phản hồi |
| 12.20 | Kế hoạch bảo trì | Cập nhật định kỳ và sao lưu |

## Quy trình triển khai mẫu
1. Kiểm tra test và code review.
2. Tạo bản sao lưu dữ liệu cần thiết.
3. Chuẩn bị biến môi trường và bí mật.
4. Cài đặt phiên bản phụ thuộc đã khóa.
5. Cập nhật ứng dụng và database theo kế hoạch.
6. Khởi động ứng dụng và kiểm tra health.
7. Kiểm tra luồng đăng nhập và chức năng cốt lõi.
8. Theo dõi log và chỉ số sau triển khai.
9. Có kế hoạch rollback nếu bản phát hành gây lỗi.

## Checklist nghiệm thu
- [ ] Ứng dụng chạy ổn định trong môi trường đích.
- [ ] Domain truy cập đúng.
- [ ] HTTPS hoạt động.
- [ ] Bí mật không nằm trong repository.
- [ ] Database có backup và đã thử restore.
- [ ] Có log để điều tra lỗi.
- [ ] Có cách khởi động lại và rollback.
- [ ] Đã thử các luồng quan trọng như đăng nhập, tạo và đọc dữ liệu.
- [ ] Đã kiểm tra hiển thị trên màn hình máy tính và điện thoại.
- [ ] Có hướng dẫn vận hành cơ bản.

**Không có checklist nào bảo đảm tuyệt đối không xảy ra sự cố.** Mục tiêu là giảm rủi ro, phát hiện sớm và phục hồi có kiểm soát.