# Đặc tả dự án cuối khóa — Website quản lý công việc và học tập cá nhân

Đây là dự án tổng hợp sau khi đã hoàn thành các chặng nền tảng. Không bắt đầu dự án này ngay từ đầu khóa.

## 1. Mục tiêu
Xây dựng một website cá nhân bằng Python và NiceGUI để quản lý công việc, danh mục và tiến độ học tập. Website là dự án giáo dục; dữ liệu ban đầu không chứa thông tin nhạy cảm.

## 2. Nhóm người dùng
- Khách chưa đăng nhập: xem trang giới thiệu và trang đăng nhập.
- Người dùng: quản lý dữ liệu thuộc tài khoản của mình.
- Quản trị viên: quản lý người dùng và xem các chức năng quản trị cần thiết.

## 3. Chức năng bắt buộc

### Tài khoản
- Đăng ký và đăng nhập.
- Đăng xuất.
- Kiểm tra quyền truy cập ở backend.
- Mật khẩu lưu bằng cơ chế hash chuyên dụng.
- Không cho người dùng đọc hoặc sửa dữ liệu của tài khoản khác.

### Quản lý công việc
- Tạo công việc.
- Xem danh sách.
- Xem chi tiết.
- Chỉnh sửa tiêu đề, mô tả, hạn hoàn thành và trạng thái.
- Xóa sau khi xác nhận.
- Tìm kiếm, lọc và sắp xếp.
- Hiển thị trạng thái khi danh sách rỗng.

### Theo dõi học tập
- Tạo mục tiêu học tập.
- Ghi buổi học và ghi chú.
- Đánh dấu bài học hoàn thành.
- Hiển thị tổng quan tiến độ.

### Quản trị
- Xem danh sách tài khoản ở mức cần thiết.
- Khóa hoặc mở khóa tài khoản theo quyền.
- Không hiển thị dữ liệu bí mật hoặc mật khẩu.

## 4. Yêu cầu phi chức năng
- Giao diện dễ hiểu, dùng được trên máy tính và điện thoại.
- Kiểm tra dữ liệu đầu vào.
- Thông báo lỗi dễ hiểu nhưng không tiết lộ thông tin nội bộ.
- Có log phù hợp.
- Có kiểm thử cho nghiệp vụ quan trọng.
- Có hướng dẫn cài đặt, chạy và cấu hình.
- Bí mật được quản lý ngoài mã nguồn.
- Có quy trình backup và restore dữ liệu.

## 5. Cấu trúc kiến trúc gợi ý

    app/
      main.py
      pages/
      components/
      services/
      repositories/
      models/
      security/
      config/
    tests/
    docs/

Đây là hướng phân tách trách nhiệm, không phải bắt buộc tạo mọi thư mục ngay từ đầu. Người học phải giải thích tại sao một phần được đặt ở vị trí đó.

## 6. Các mốc thực hiện

| Mốc | Kết quả |
|---|---|
| M1 — Phân tích | Yêu cầu, user flow, wireframe, danh sách chức năng |
| M2 — Prototype | Các trang và điều hướng với dữ liệu mẫu |
| M3 — Nghiệp vụ | Tạo, đọc, sửa, xóa và validation |
| M4 — Database | SQLite, schema và repository |
| M5 — Tài khoản | Đăng nhập, đăng xuất và phân quyền |
| M6 — Kiểm thử | Test nghiệp vụ, test quyền và xử lý lỗi |
| M7 — Hoàn thiện | Giao diện responsive, hướng dẫn và log |
| M8 — Triển khai | Môi trường máy chủ, HTTPS, backup và kiểm tra sau deploy |

## 7. Tiêu chí nghiệm thu

### Chức năng
- [ ] Các luồng tài khoản cơ bản hoạt động.
- [ ] Người dùng không thể truy cập dữ liệu người khác bằng cách thay URL hoặc gửi yêu cầu khác.
- [ ] Các thao tác CRUD hoạt động.
- [ ] Tìm kiếm và lọc cho kết quả hợp lý.
- [ ] Dữ liệu còn sau khi khởi động lại.

### Chất lượng
- [ ] Kiểm thử các trường hợp chính và trường hợp biên.
- [ ] Xử lý lỗi database và dữ liệu nhập sai.
- [ ] Không ghi mật khẩu/token vào log.
- [ ] Có README hướng dẫn cài đặt và chạy.
- [ ] Không có bí mật trong GitHub.

### Triển khai
- [ ] Ứng dụng chạy trong môi trường đích.
- [ ] HTTPS được bật nếu công khai trên Internet.
- [ ] Có backup và thử restore.
- [ ] Có log và quy trình khôi phục/rollback.
- [ ] Kiểm tra trên nhiều kích thước màn hình.

## 8. Điều kiện được xem là hoàn thành
Người học tự trình bày được luồng dữ liệu từ giao diện đến service và database; giải thích cách xác thực/phân quyền; chạy lại bộ test; triển khai và mô tả quy trình backup/restore. Không chỉ trình diễn một lần rồi kết luận hệ thống hoàn toàn không có lỗi.
