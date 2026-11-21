# Chặng 07 — Sự kiện, trạng thái, biểu mẫu và nhiều trang NiceGUI

**Mục tiêu:** làm giao diện phản hồi với thao tác người dùng và tổ chức website thành nhiều trang.

## Danh sách bài học

| Mã | Bài học | Cú pháp / ý tưởng trọng tâm |
|---|---|---|
| 07.1 | Giao diện tĩnh và giao diện tương tác | Phân biệt hiển thị với hành vi |
| 07.2 | Hàm callback | Hàm được gọi khi có sự kiện |
| 07.3 | on_click | Xử lý thao tác nhấn nút |
| 07.4 | on_change | Phản hồi khi giá trị thay đổi |
| 07.5 | Đọc giá trị input | Lấy dữ liệu người dùng nhập |
| 07.6 | Cập nhật thành phần giao diện | Thay đổi nội dung sau sự kiện |
| 07.7 | Trạng thái giao diện | Lưu thông tin cần dùng giữa các thao tác |
| 07.8 | Kiểm tra dữ liệu đầu vào | Rỗng, sai định dạng, ngoài giới hạn |
| 07.9 | Form và submit | Nhóm trường và gửi dữ liệu |
| 07.10 | Select, checkbox, radio | Những cách nhập dữ liệu khác nhau |
| 07.11 | Bảng dữ liệu | Hiển thị danh sách có cấu trúc |
| 07.12 | Dialog và xác nhận | Hỏi trước thao tác quan trọng |
| 07.13 | Thông báo và trạng thái tải | Phản hồi cho người sử dụng |
| 07.14 | Tạo trang bằng @ui.page | Khai báo route/trang |
| 07.15 | Điều hướng giữa các trang | Link, URL và điều hướng |
| 07.16 | Thành phần tái sử dụng | Tạo hàm dựng một nhóm giao diện |
| 07.17 | CSS class và style | Tùy chỉnh khoảng cách, màu, kích thước |
| 07.18 | Responsive cơ bản | Giao diện cho màn hình hẹp và rộng |
| 07.19 | Xử lý trạng thái trống và lỗi | Không có dữ liệu, nhập sai, thao tác thất bại |
| 07.20 | Trải nghiệm người dùng | Nhãn, thông báo, khả năng truy cập |

## Bài tập thực hành
1. Nút bấm tăng một bộ đếm.
2. Biểu mẫu chào người dùng theo tên nhập vào.
3. Máy tính web có hai ô số và lựa chọn phép toán.
4. Biểu mẫu đăng ký giả lập có kiểm tra dữ liệu bắt buộc.
5. Bảng công việc có trạng thái hoàn thành.
6. Website ba trang: Trang chủ, Danh sách và Giới thiệu.

## Dự án nhỏ
**Website quản lý công việc phiên bản giao diện:** xem danh sách mẫu, thêm công việc, đánh dấu hoàn thành và điều hướng giữa các trang. Ban đầu dữ liệu có thể chỉ nằm trong bộ nhớ; chưa coi đây là ứng dụng lưu trữ bền vững.

## Lỗi thường gặp cần hiểu
- Truyền kết quả gọi hàm thay vì truyền hàm callback khi thành phần cần gọi sau này.
- Đọc nhầm đối tượng input với giá trị bên trong input.
- Quên cập nhật giao diện sau khi trạng thái thay đổi.
- Dùng biến toàn cục thiếu kiểm soát cho dữ liệu nhiều người dùng.
- Không kiểm tra dữ liệu trước khi ghi hoặc xử lý.

## Tiêu chí hoàn thành
- [ ] Phân biệt callback và lời gọi hàm thông thường.
- [ ] Nhận dữ liệu từ các thành phần nhập.
- [ ] Xử lý on_click và on_change.
- [ ] Cập nhật giao diện sau sự kiện.
- [ ] Tạo nhiều trang và điều hướng được.
- [ ] Thiết kế được trạng thái rỗng, lỗi và thành công.