# Chặng 05 — Tổ chức mã nguồn và quy trình dự án

**Mục tiêu:** quản lý một ứng dụng có nhiều tệp, thư viện và thay đổi theo thời gian.

## Danh sách bài học

| Mã | Bài học | Nội dung trọng tâm |
|---|---|---|
| 05.1 | Khi nào cần tách tệp? | Trách nhiệm và ranh giới module |
| 05.2 | Module Python | Một tệp .py có thể được import |
| 05.3 | import và from ... import ... | Cách dùng tên từ module |
| 05.4 | Package | Tổ chức các module trong thư mục |
| 05.5 | __init__.py | Vai trò trong package |
| 05.6 | Điểm bắt đầu chương trình | __name__ == "__main__" |
| 05.7 | Đường dẫn import | Chạy từ thư mục gốc và tránh import khó hiểu |
| 05.8 | Môi trường ảo | venv, vì sao mỗi dự án cần môi trường riêng |
| 05.9 | pip | Cài và gỡ thư viện |
| 05.10 | requirements.txt | Ghi lại phụ thuộc |
| 05.11 | Phiên bản Python và thư viện | Khả năng tương thích |
| 05.12 | Git là gì? | Theo dõi lịch sử thay đổi |
| 05.13 | status, add, commit | Ghi nhận thay đổi |
| 05.14 | Branch và merge | Làm việc trên nhánh |
| 05.15 | GitHub remote, push và pull | Đồng bộ mã nguồn |
| 05.16 | README và .gitignore | Hướng dẫn dự án và bỏ qua tệp riêng |
| 05.17 | Cấu hình và biến môi trường | Không hard-code bí mật |
| 05.18 | Logging cơ bản | Ghi lại sự kiện và lỗi |
| 05.19 | Thiết kế module theo trách nhiệm | Tránh tệp quá lớn và phụ thuộc vòng |
| 05.20 | Đọc tài liệu thư viện | Tìm đúng thông tin từ tài liệu chính thức |

## Cấu trúc dự án tham khảo

    my_project/
    ├── README.md
    ├── requirements.txt
    ├── .gitignore
    ├── .env.example
    ├── app/
    │   ├── __init__.py
    │   ├── main.py
    │   ├── services/
    │   └── data/
    └── tests/

Đây là ví dụ để hiểu cách phân chia. Không phải dự án nào cũng cần mọi thư mục; cấu trúc phải phản ánh yêu cầu thật.

## Dự án nhỏ
**Tái cấu trúc ứng dụng quản lý công việc:** tách phần giao tiếp người dùng, xử lý nghiệp vụ và lưu trữ thành các module riêng. Người học tự chọn ranh giới và giải thích lý do.

## Quy tắc Git an toàn
- Không commit .env, mật khẩu, token hoặc dữ liệu cá nhân.
- Dùng .env.example để mô tả tên biến cấu hình và giá trị mẫu không nhạy cảm.
- Commit nhỏ, thông điệp nêu rõ thay đổi.
- Trước khi cập nhật từ remote, kiểm tra thay đổi đang có trên máy.
- Git không thay thế cho bản sao lưu dữ liệu người dùng.

## Tiêu chí hoàn thành
- [ ] Tạo và kích hoạt venv.
- [ ] Cài và ghi lại thư viện cần thiết.
- [ ] Import module do mình tạo.
- [ ] Giải thích được cấu trúc thư mục.
- [ ] Tạo commit và đẩy lên GitHub.
- [ ] Không để bí mật trong repository.