# Chặng 06 — Bắt đầu xây dựng giao diện bằng NiceGUI

**Mục tiêu:** hiểu ứng dụng web chạy như thế nào và tạo được giao diện cơ bản bằng cú pháp Python của NiceGUI.

## Kiến thức web tối thiểu

| Mã | Bài học | Kết quả cần đạt |
|---|---|---|
| 06.1 | Website, trình duyệt và máy chủ | Giải thích vai trò client/server |
| 06.2 | Request và response | Hiểu trình duyệt gửi yêu cầu, máy chủ phản hồi |
| 06.3 | URL, localhost và port | Phân biệt địa chỉ và cổng của ứng dụng |
| 06.4 | Giao diện và trải nghiệm người dùng | Biết màn hình cần hỗ trợ nhiệm vụ nào |

## Danh sách bài học NiceGUI

| Mã | Bài học | Cú pháp / ý tưởng trọng tâm |
|---|---|---|
| 06.5 | Thư viện NiceGUI là gì? | Library, framework và tài liệu API |
| 06.6 | Cài NiceGUI trong môi trường ảo | pip và venv |
| 06.7 | Import đối tượng ui | from nicegui import ui |
| 06.8 | Khởi động ứng dụng | ui.run() và tham số cơ bản |
| 06.9 | Hiển thị văn bản | ui.label() |
| 06.10 | Nút bấm | ui.button() |
| 06.11 | Ô nhập văn bản | ui.input() |
| 06.12 | Ô nhập số | ui.number() |
| 06.13 | Lựa chọn | ui.select() |
| 06.14 | Checkbox và công tắc | ui.checkbox(), ui.switch() |
| 06.15 | Hiển thị thông báo | ui.notify() |
| 06.16 | Bố cục hàng và cột | ui.row(), ui.column() |
| 06.17 | Thẻ và nhóm thành phần | ui.card(), ui.grid() |
| 06.18 | Biểu tượng và hình ảnh | Thành phần icon/image |
| 06.19 | Tiêu đề và nội dung trang | Phân cấp thông tin |
| 06.20 | Mở và xem ứng dụng trên trình duyệt | Local development cycle |

## Quy tắc khi học cú pháp NiceGUI
Với mỗi thành phần, phải trả lời:
1. Thành phần đó hiển thị hoặc làm nhiệm vụ gì?
2. Nó nhận dữ liệu nào?
3. Những tham số nào thường dùng?
4. Dấu ngoặc và dấu phẩy có vai trò gì?
5. Làm sao thay đổi nội dung hoặc kiểu hiển thị?
6. Làm sao kiểm tra kết quả trên trình duyệt?

Không học thuộc toàn bộ tham số. Bắt đầu bằng thuộc tính cốt lõi, sau đó tra tài liệu chính thức khi cần.

## Dự án nhỏ
1. **Trang giới thiệu cá nhân:** tiêu đề, đoạn mô tả và liên kết.
2. **Bảng điều khiển tĩnh:** card, hàng, cột và các nhãn số liệu mẫu.
3. **Biểu mẫu đầu tiên:** nhập tên và chọn một tùy chọn; ở chặng tiếp theo mới xử lý sự kiện đầy đủ.

## Tiêu chí hoàn thành
- [ ] Giải thích được trình duyệt, máy chủ, localhost và port.
- [ ] Tự cài NiceGUI trong venv.
- [ ] Tạo và chạy ứng dụng NiceGUI tối thiểu.
- [ ] Dùng được label, button, input và bố cục row/column.
- [ ] Biết tra tài liệu API thay vì đoán tham số.