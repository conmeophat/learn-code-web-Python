# Chặng 09 — Cơ sở dữ liệu và SQLite

**Mục tiêu:** lưu trữ dữ liệu bền vững, truy vấn được và tách thao tác dữ liệu khỏi giao diện NiceGUI.

## Danh sách bài học

| Mã | Bài học | Nội dung trọng tâm |
|---|---|---|
| 09.1 | Cơ sở dữ liệu là gì? | Vì sao dữ liệu trong RAM không đủ |
| 09.2 | Database, table, row và column | Cấu trúc bảng |
| 09.3 | SQLite | Cơ sở dữ liệu dạng tệp |
| 09.4 | SQL và câu lệnh SELECT | Đọc dữ liệu |
| 09.5 | INSERT | Thêm dữ liệu |
| 09.6 | UPDATE | Cập nhật dữ liệu |
| 09.7 | DELETE | Xóa dữ liệu |
| 09.8 | WHERE, ORDER BY và LIMIT | Lọc, sắp xếp và giới hạn |
| 09.9 | Khóa chính | Primary key |
| 09.10 | Khóa ngoại | Foreign key |
| 09.11 | Quan hệ một-một, một-nhiều, nhiều-nhiều | Mô hình dữ liệu |
| 09.12 | Chuẩn hóa dữ liệu nhập môn | Giảm trùng lặp |
| 09.13 | Tham số hóa truy vấn | Tránh ghép chuỗi SQL tùy tiện |
| 09.14 | Transaction | Commit, rollback và tính toàn vẹn |
| 09.15 | Index | Tăng tốc truy vấn khi phù hợp |
| 09.16 | Kết nối Python với SQLite | Mở, truy vấn, đóng kết nối |
| 09.17 | Repository pattern đơn giản | Tách truy vấn khỏi giao diện |
| 09.18 | Migration và thay đổi cấu trúc bảng | Quản lý phiên bản schema |
| 09.19 | Sao lưu và phục hồi | Kiểm tra bản sao lưu |
| 09.20 | Giới hạn SQLite và bước tiếp theo | Khi nào cân nhắc PostgreSQL |

## CRUD
CRUD là bốn nhóm thao tác cơ bản:
- Create: tạo dữ liệu.
- Read: đọc dữ liệu.
- Update: cập nhật dữ liệu.
- Delete: xóa dữ liệu.

## Dự án nhỏ
**Website quản lý công việc có SQLite:** người dùng tạo, xem, sửa, tìm kiếm và xóa công việc; dữ liệu vẫn tồn tại sau khi khởi động lại ứng dụng.

## Bài kiểm thử dữ liệu
- Thêm bản ghi thiếu trường bắt buộc.
- Thêm hai bản ghi trùng mã duy nhất.
- Cập nhật mã không tồn tại.
- Xóa bản ghi đang được dữ liệu khác tham chiếu.
- Mô phỏng lỗi giữa transaction và xác nhận rollback.
- Sao lưu rồi khôi phục vào một bản sao thử nghiệm.

## Nguyên tắc an toàn
- Luôn dùng truy vấn tham số hóa.
- Không ghép trực tiếp dữ liệu người dùng vào chuỗi SQL.
- Xác định ràng buộc dữ liệu ở database, không chỉ ở giao diện.
- Không coi file SQLite là giải pháp tự động phù hợp cho mọi quy mô hoặc mọi cấu hình nhiều máy ghi đồng thời.

## Tiêu chí hoàn thành
- [ ] Thiết kế được bảng với khóa chính.
- [ ] Viết được truy vấn CRUD.
- [ ] Dùng tham số hóa truy vấn.
- [ ] Biết transaction có tác dụng gì.
- [ ] Kết nối NiceGUI với lớp truy cập dữ liệu.
- [ ] Sao lưu và kiểm tra khôi phục dữ liệu.