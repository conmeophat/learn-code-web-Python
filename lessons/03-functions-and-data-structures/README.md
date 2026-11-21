# Chặng 03 — Hàm và cấu trúc dữ liệu

**Mục tiêu:** tổ chức chương trình thành những phần nhỏ, tái sử dụng được; lưu trữ và xử lý nhiều giá trị.

## Phần A — Hàm

| Mã | Bài học | Cú pháp / ý tưởng |
|---|---|---|
| 03.1 | Vì sao cần hàm? | Chia việc thành nhiệm vụ |
| 03.2 | Định nghĩa hàm | def, tên hàm, dấu ngoặc, dấu : |
| 03.3 | Gọi hàm | Thực thi phần việc đã định nghĩa |
| 03.4 | Tham số và đối số | Parameter và argument |
| 03.5 | return | Trả một kết quả về nơi gọi |
| 03.6 | Hàm không có return tường minh | Giá trị None |
| 03.7 | Giá trị mặc định | Default parameter |
| 03.8 | Nhiều kết quả và unpacking | Tuple unpacking |
| 03.9 | Phạm vi biến | Local và global ở mức nhập môn |
| 03.10 | Docstring và tên hàm | Viết hàm dễ đọc, dễ kiểm tra |

## Phần B — Cấu trúc dữ liệu

| Mã | Bài học | Cú pháp / ý tưởng |
|---|---|---|
| 03.11 | List | Danh sách có thứ tự, có thể thay đổi |
| 03.12 | Truy cập và cắt list | Index và slicing |
| 03.13 | Thêm, sửa, xóa phần tử | append, insert, remove, pop |
| 03.14 | Duyệt list | for, enumerate |
| 03.15 | Tuple | Dãy có thứ tự, không sửa phần tử trực tiếp |
| 03.16 | Dictionary | Cặp khóa và giá trị |
| 03.17 | Set | Tập hợp phần tử duy nhất |
| 03.18 | Chuỗi nâng cao | split, join, strip, replace |
| 03.19 | Sắp xếp và tìm kiếm cơ bản | sorted, sort, key |
| 03.20 | Chọn cấu trúc dữ liệu | So sánh ưu và nhược điểm |

## Nguyên tắc quan trọng về hàm
- def định nghĩa hàm; lời gọi hàm mới làm phần thân hàm chạy.
- Tham số là tên nhận dữ liệu trong định nghĩa; đối số là giá trị truyền khi gọi.
- return gửi kết quả về nơi gọi và kết thúc lần thực hiện hàm đó.
- Nếu hàm không trả về giá trị tường minh, Python trả về None.
- Không phải thao tác nào cũng cần viết thành hàm; hãy tách khi có nhiệm vụ rõ ràng hoặc cần tái sử dụng.

## Bài tập thực hành
1. Viết hàm tính diện tích hình chữ nhật.
2. Viết hàm kiểm tra số nguyên tố sau khi đã học đủ điều kiện và vòng lặp.
3. Đếm số lần một từ xuất hiện trong danh sách.
4. Lưu thông tin sinh viên bằng dictionary.
5. Tạo danh sách chi tiêu và tính tổng.
6. Tìm phần tử lớn nhất, nhỏ nhất và trung bình.

## Dự án nhỏ
**Quản lý điểm:** lưu nhiều sinh viên; mỗi sinh viên có mã, tên và điểm; có chức năng thêm, xem danh sách, tìm kiếm và tính điểm trung bình. Ban đầu dữ liệu có thể nằm trong bộ nhớ; chưa cần database.

## Tiêu chí hoàn thành
- [ ] Phân biệt định nghĩa hàm với gọi hàm.
- [ ] Giải thích được tham số, đối số, return và None.
- [ ] Chọn được list, tuple, dict hoặc set phù hợp.
- [ ] Biết duyệt, tìm, thêm, sửa và xóa phần tử.
- [ ] Chia dự án quản lý điểm thành các hàm có trách nhiệm rõ ràng.