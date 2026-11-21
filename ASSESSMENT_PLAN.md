# Kế hoạch đánh giá và điều kiện hoàn thành

Mục đích là xác nhận năng lực thực hành, không phải chỉ đếm số bài đã đọc.

## 1. Cấu trúc đánh giá mỗi chặng

| Thành phần | Tỷ trọng gợi ý | Nội dung |
|---|---:|---|
| Hiểu khái niệm | 20% | Giải thích bằng lời của mình |
| Hiểu cú pháp | 20% | Phân tích từ khóa, dấu câu và luồng chạy |
| Bài tập cá nhân | 30% | Tự viết, chạy và sửa |
| Dự án nhỏ | 20% | Kết hợp kiến thức trong sản phẩm |
| Gỡ lỗi và tự đánh giá | 10% | Nêu nguyên nhân và cách kiểm tra |

Tỷ trọng là khung tự đánh giá, không phải chứng chỉ chính thức.

## 2. Thang đánh giá

| Mức | Mô tả |
|---|---|
| 0 — Chưa học | Chưa thể giải thích hoặc thực hiện |
| 1 — Nhận biết | Nhận diện được khái niệm khi nhìn thấy |
| 2 — Làm theo | Hoàn thành khi có hướng dẫn từng bước |
| 3 — Tự làm | Tự viết được bài tương tự và giải thích được |
| 4 — Vận dụng | Tự xử lý biến thể mới, biết kiểm thử và gỡ lỗi |

Một chủ đề cốt lõi chỉ được xem là vững khi đạt ít nhất mức 3. Chủ đề mở rộng có thể quay lại học sau.

## 3. Cổng kiểm tra trước khi chuyển chặng

### Sau Chặng 00
- Có thể tạo và chạy tệp Python.
- Phân biệt VS Code, Python, mã nguồn, chương trình và đầu ra.
- Biết gửi thông báo lỗi đầy đủ khi cần trợ giúp.

### Sau Chặng 01–02
- Viết chương trình nhập/xuất.
- Dùng biến, kiểu dữ liệu, toán tử.
- Dùng điều kiện và vòng lặp.
- Dự đoán kết quả trước khi chạy.

### Sau Chặng 03–04
- Tự viết hàm, dùng return đúng mục đích.
- Chọn list/dict/tuple/set phù hợp.
- Đọc/ghi tệp và xử lý lỗi cơ bản.
- Chia bài toán thành phần nhỏ.

### Sau Chặng 05
- Tạo môi trường ảo.
- Cài thư viện.
- Tổ chức module.
- Dùng Git commit và push.
- Không đưa bí mật vào repository.

### Sau Chặng 06–07
- Tạo giao diện NiceGUI.
- Nhận input và xử lý callback.
- Tạo nhiều trang.
- Kiểm tra dữ liệu và cập nhật giao diện.

### Sau Chặng 08–09
- Phân chia giao diện, nghiệp vụ và truy cập dữ liệu.
- Gọi API có timeout và xử lý lỗi.
- Thực hiện CRUD với database.
- Dùng truy vấn tham số hóa.

### Sau Chặng 10–11
- Có đăng nhập, đăng xuất và kiểm tra quyền ở phía máy chủ.
- Mật khẩu không lưu dạng văn bản thường.
- Có test cho logic và luồng quan trọng.
- Có checklist xử lý lỗi và bảo mật.

### Sau Chặng 12
- Triển khai được vào môi trường mục tiêu.
- Domain và HTTPS hoạt động nếu website công khai.
- Có log, backup, restore và quy trình rollback.
- Kiểm tra lại các luồng nghiệp vụ quan trọng.

## 4. Cách kiểm tra dự án
Với mỗi dự án:
1. Viết yêu cầu trước khi code.
2. Liệt kê trường hợp bình thường, biên và lỗi.
3. Chạy từng trường hợp và ghi kết quả.
4. Sửa lỗi và chạy lại toàn bộ test liên quan.
5. Mô tả giới hạn còn tồn tại.

## 5. Quy tắc không tự đánh lừa bản thân
- Chạy được một lần không có nghĩa là ứng dụng đã ổn định.
- Không có lỗi hiển thị không có nghĩa là không có lỗi logic hoặc bảo mật.
- Đọc code không đồng nghĩa với tự viết được code.
- Dự án chạy trên máy cá nhân không đồng nghĩa đã sẵn sàng cho Internet.
