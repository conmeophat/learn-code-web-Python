# Chặng 11 — Kiểm thử, chất lượng và bảo trì

**Mục tiêu:** kiểm tra ứng dụng có hoạt động đúng trong các tình huống dự kiến và dễ sửa đổi khi phát triển.

## Danh sách bài học

| Mã | Bài học | Nội dung trọng tâm |
|---|---|---|
| 11.1 | Vì sao phải kiểm thử? | Lỗi, rủi ro và độ tin cậy |
| 11.2 | Test case | Đầu vào, bước thực hiện và kết quả mong đợi |
| 11.3 | Unit test | Kiểm thử một hàm hoặc đơn vị nhỏ |
| 11.4 | pytest nhập môn | Test function và assertion |
| 11.5 | Arrange, Act, Assert | Cấu trúc bài kiểm thử |
| 11.6 | Kiểm thử biên | Giá trị nhỏ nhất, lớn nhất và rỗng |
| 11.7 | Kiểm thử ngoại lệ | Đảm bảo lỗi được xử lý đúng |
| 11.8 | Mock và test double | Thay dịch vụ ngoài trong kiểm thử |
| 11.9 | Integration test | Kiểm tra các thành phần kết nối |
| 11.10 | Database test | Dùng database thử nghiệm |
| 11.11 | Kiểm thử giao diện và luồng người dùng | Luồng quan trọng |
| 11.12 | Regression test | Ngăn lỗi cũ quay trở lại |
| 11.13 | Logging và quan sát lỗi | Thông tin đủ để điều tra |
| 11.14 | Code review | Tính đúng, dễ đọc, an toàn |
| 11.15 | Refactor | Cải thiện cấu trúc mà không đổi hành vi |
| 11.16 | Hiệu năng nhập môn | Đo trước khi tối ưu |
| 11.17 | CI cơ bản | Tự chạy kiểm tra khi có thay đổi |
| 11.18 | Release checklist | Chuẩn bị phiên bản |

## Ma trận kiểm thử tối thiểu
Với mỗi chức năng, thử ít nhất:
- Trường hợp bình thường.
- Đầu vào rỗng.
- Đầu vào sai kiểu hoặc sai định dạng.
- Giá trị ở biên giới hạn.
- Người dùng không đủ quyền.
- Database hoặc API gặp lỗi.
- Thao tác lặp lại hoặc gửi nhiều lần.

## Dự án thực hành
Viết test cho logic đăng ký, đăng nhập, tạo công việc, chỉnh sửa, tìm kiếm và xóa. Dùng database thử nghiệm, không chạy test phá hủy dữ liệu thật.

## Tiêu chí hoàn thành
- [ ] Viết được test cho các hàm nghiệp vụ quan trọng.
- [ ] Dùng assertion để so sánh kết quả mong đợi.
- [ ] Kiểm tra trường hợp biên và trường hợp lỗi.
- [ ] Có thể chạy lại test sau khi sửa code.
- [ ] Có checklist phát hành và ghi nhận lỗi.