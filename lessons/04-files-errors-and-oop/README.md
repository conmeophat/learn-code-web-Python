# Chặng 04 — Tệp, lỗi, dữ liệu và lập trình hướng đối tượng nhập môn

**Mục tiêu:** lưu dữ liệu ra ngoài chương trình, xử lý tình huống lỗi và hiểu cách tổ chức các đối tượng khi chương trình lớn hơn.

## Danh sách bài học

| Mã | Bài học | Nội dung trọng tâm |
|---|---|---|
| 04.1 | Lỗi cú pháp, lỗi thực thi và lỗi logic | Phân biệt ba nhóm lỗi |
| 04.2 | Đọc traceback | Tệp, dòng, loại ngoại lệ |
| 04.3 | try và except | Bắt lỗi có chủ đích |
| 04.4 | else và finally | Luồng xử lý ngoại lệ |
| 04.5 | raise | Chủ động báo lỗi phù hợp |
| 04.6 | Đường dẫn tệp | Path, thư mục hiện hành |
| 04.7 | Mở và đóng tệp | with và open |
| 04.8 | Đọc và ghi văn bản | Encoding UTF-8 |
| 04.9 | JSON | Lưu dữ liệu có cấu trúc |
| 04.10 | CSV | Đọc và ghi dữ liệu dạng bảng |
| 04.11 | Vì sao cần class? | Mô hình hóa đối tượng |
| 04.12 | Class và instance | Lớp và đối tượng cụ thể |
| 04.13 | Thuộc tính và phương thức | Dữ liệu và hành vi |
| 04.14 | __init__ và self | Khởi tạo đối tượng |
| 04.15 | Đóng gói ở mức cơ bản | Giữ dữ liệu và hành vi liên quan cùng nhau |
| 04.16 | Khi nào không cần OOP? | Tránh phức tạp hóa thiết kế |

## Bài tập thực hành
1. Yêu cầu người dùng nhập số; nếu không hợp lệ, thông báo dễ hiểu và hỏi lại.
2. Lưu danh sách công việc vào tệp JSON.
3. Đọc danh sách công việc khi chương trình khởi động.
4. Xuất bảng chi tiêu ra CSV.
5. Tạo lớp SinhVien có dữ liệu và một số hành vi cơ bản.
6. Thiết kế lớp TaiKhoan ở mức mô phỏng, chưa xử lý thông tin tài chính thật.

## Dự án nhỏ
**Quản lý công việc lưu tệp:** thêm, xem, sửa trạng thái và xóa công việc; dữ liệu tồn tại sau khi chương trình đóng nhờ JSON.

## Lưu ý an toàn
Không dùng pickle để trao đổi dữ liệu không đáng tin cậy. Không lưu mật khẩu hoặc bí mật dưới dạng văn bản thuần. Khi ghi tệp, cần nghĩ tới trường hợp tệp không tồn tại, dữ liệu hỏng hoặc quyền truy cập bị từ chối.

## Tiêu chí hoàn thành
- [ ] Đọc được traceback để tìm vị trí lỗi.
- [ ] Dùng try/except cho tình huống có thể dự đoán.
- [ ] Đọc và ghi tệp UTF-8.
- [ ] Lưu và tải dữ liệu JSON.
- [ ] Phân biệt class với instance.
- [ ] Biết khi nào hàm và module đơn giản phù hợp hơn class.