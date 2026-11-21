# Chặng 08 — Kiến trúc ứng dụng web, HTTP và tích hợp API

**Mục tiêu:** tổ chức ứng dụng để có thể mở rộng, bảo trì và kết nối dịch vụ ngoài mà không để toàn bộ logic nằm trong phần giao diện.

## Danh sách bài học

| Mã | Bài học | Nội dung trọng tâm |
|---|---|---|
| 08.1 | Phân tích yêu cầu website | Người dùng, mục tiêu và phạm vi |
| 08.2 | User flow và sơ đồ trang | Luồng thao tác và điều hướng |
| 08.3 | Frontend và backend | Vai trò và ranh giới trách nhiệm |
| 08.4 | Tầng giao diện | Pages và reusable components |
| 08.5 | Tầng nghiệp vụ | Services và quy tắc xử lý |
| 08.6 | Tầng dữ liệu | Repository/data access |
| 08.7 | Luồng dữ liệu | Từ form tới service và database |
| 08.8 | HTTP căn bản | Request, response, method và status code |
| 08.9 | JSON | Trao đổi dữ liệu có cấu trúc |
| 08.10 | REST API ở mức nhập môn | Resource, endpoint, method |
| 08.11 | Gọi API từ Python | Client, timeout và kiểm tra response |
| 08.12 | Xử lý API lỗi | Mạng lỗi, giới hạn tốc độ, dữ liệu sai |
| 08.13 | API key và secrets | Lưu cấu hình ngoài mã nguồn |
| 08.14 | Upload và download tệp | Kiểm tra loại, kích thước và quyền |
| 08.15 | Tìm kiếm và lọc | Query, filter, sort và pagination |
| 08.16 | Dashboard và biểu đồ | Chuẩn bị dữ liệu và hiển thị |
| 08.17 | Logging | Ghi sự kiện hữu ích, không ghi bí mật |
| 08.18 | Tài liệu hóa API nội bộ | Mô tả đầu vào, đầu ra và lỗi |

## Nguyên tắc kiến trúc

- Giao diện nhận thao tác và hiển thị kết quả; không nên chứa mọi quy tắc nghiệp vụ.
- Service chứa logic nghiệp vụ có thể kiểm tra độc lập.
- Tầng dữ liệu chịu trách nhiệm truy xuất và lưu trữ.
- Không để một trang giao diện phụ thuộc trực tiếp vào hàng loạt chi tiết truy vấn.
- Tách module vừa đủ; không tạo hàng chục lớp chỉ để trông có vẻ chuyên nghiệp.

## Dự án nhỏ
**Dashboard dữ liệu công khai:** lấy dữ liệu từ một API không nhạy cảm, đặt timeout, kiểm tra lỗi, chuẩn hóa dữ liệu và hiển thị. Không commit API key hoặc token.

## Kiểm tra chất lượng
Thử các trường hợp: mạng mất kết nối, máy chủ trả lỗi, dữ liệu rỗng, dữ liệu thiếu trường, phản hồi chậm và người dùng bấm tải lại nhiều lần.

## Tiêu chí hoàn thành
- [ ] Vẽ được luồng dữ liệu từ trang web tới nơi lưu trữ.
- [ ] Phân chia được pages, services và data access.
- [ ] Hiểu các HTTP method và status code phổ biến.
- [ ] Gọi được API với timeout và xử lý lỗi.
- [ ] Quản lý cấu hình nhạy cảm ngoài mã nguồn.
- [ ] Không để lỗi API làm sập toàn bộ giao diện.