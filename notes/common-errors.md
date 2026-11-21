# Sổ tay lỗi thường gặp

Đừng chỉ lưu cách sửa; hãy ghi nguyên nhân để tránh lặp lại.

## Mẫu ghi lỗi
### Tên lỗi
- **Thông báo đầy đủ:**
- **Tệp và dòng xảy ra lỗi:**
- **Mình đang muốn làm gì:**
- **Nguyên nhân:**
- **Cách sửa:**
- **Cách kiểm tra sau khi sửa:**
- **Điều rút ra:**

## Một số lỗi ban đầu cần nhận diện

### SyntaxError
Python không hiểu cú pháp được viết. Có thể thiếu dấu ngoặc, dấu nháy, dấu hai chấm hoặc viết sai cấu trúc.

### IndentationError
Các dòng lệnh không được thụt lề theo quy tắc. Python dùng thụt lề để nhận biết một khối lệnh.

### NameError
Chương trình sử dụng một tên mà Python không nhận ra, chẳng hạn tên biến chưa được tạo hoặc viết sai chính tả.

### TypeError
Một thao tác được thực hiện trên kiểu dữ liệu không phù hợp.

### ValueError
Giá trị được đưa vào có dạng hoặc nội dung không phù hợp với thao tác mong muốn.

### ModuleNotFoundError
Python không tìm thấy module hoặc package cần import. Có thể thư viện chưa được cài trong đúng môi trường, hoặc tên module bị viết sai.

## Nguyên tắc gỡ lỗi
1. Đọc dòng cuối của traceback để nhận diện loại lỗi.
2. Tìm tệp và số dòng liên quan.
3. Đọc những dòng ngay trước chỗ lỗi.
4. Kiểm tra tên biến, dấu câu, kiểu dữ liệu và thụt lề.
5. Thay đổi một yếu tố mỗi lần rồi chạy lại.
6. Ghi nguyên nhân đã xác nhận vào sổ tay.

Không gửi mật khẩu, API key hoặc dữ liệu riêng tư khi chia sẻ thông báo lỗi.