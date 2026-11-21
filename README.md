# Học lập trình Web bằng Python & NiceGUI

> Giáo trình tự học từ con số 0, dành cho người chưa có nền tảng lập trình. Mục tiêu là hiểu bản chất, tự viết mã nguồn, tự tìm và sửa lỗi, rồi tự xây dựng một website hoàn chỉnh.

## Nguyên tắc quan trọng

**Không học bằng cách sao chép code. Học để hiểu và tự làm được.**

Repository này được tổ chức như một cuốn giáo trình thực hành. Mỗi bài học đi từ ví dụ đời thường đến khái niệm, cú pháp, ví dụ nhỏ, bài tập và phần tự giải thích lại. Người học tự gõ code trong VS Code; giáo trình không yêu cầu chép nguyên một website có sẵn.

Không có cách nào bảo đảm một website thành công 100% trong mọi môi trường. Thay vào đó, chúng ta học cách chia nhỏ yêu cầu, kiểm thử, xử lý lỗi, bảo mật và triển khai có kiểm soát.

## Công nghệ sử dụng

| Công cụ | Vai trò |
|---|---|
| Python | Ngôn ngữ lập trình chính |
| VS Code | Viết và quản lý mã nguồn |
| NiceGUI | Tạo giao diện web bằng Python |
| SQLite | Cơ sở dữ liệu cho các dự án ban đầu |
| Git và GitHub | Theo dõi lịch sử, lưu trữ và quản lý dự án |
| PowerShell | Làm việc trên Windows |

Trọng tâm là Python và NiceGUI. HTML/CSS sẽ được giải thích khi cần để hiểu và tùy chỉnh giao diện. Chưa cần học JavaScript hay một frontend framework riêng ở giai đoạn đầu.

## Lộ trình học

| Chặng | Nội dung | Sản phẩm thực hành |
|---|---|---|
| 0. Làm quen | Máy tính, chương trình, mã nguồn, Python, VS Code | Chạy chương trình Python đầu tiên |
| 1. Python căn bản | Biến, kiểu dữ liệu, toán tử, điều kiện, vòng lặp | Máy tính, quản lý điểm, quản lý chi tiêu |
| 2. Hàm và cấu trúc dữ liệu | Hàm, tham số, return, list, tuple, dict, set | Ứng dụng quản lý công việc |
| 3. Tổ chức mã nguồn | Module, package, import, môi trường ảo, pip, Git | Một chương trình chia thành nhiều tệp |
| 4. NiceGUI căn bản | Thành phần giao diện, input, button, sự kiện, bố cục | Trang giới thiệu và máy tính web |
| 5. Website nhiều trang | Điều hướng, biểu mẫu, trạng thái, xác thực dữ liệu | Website quản lý công việc |
| 6. Cơ sở dữ liệu | SQLite, CRUD, truy vấn, quan hệ dữ liệu cơ bản | Website lưu và quản lý dữ liệu |
| 7. Hoàn thiện ứng dụng | Đăng nhập, phân quyền, bảo mật, kiểm thử, xử lý lỗi | Ứng dụng có người dùng |
| 8. Triển khai | Cấu hình, biến môi trường, máy chủ, domain, HTTPS, sao lưu | Website có thể truy cập qua Internet |

Các chặng có thể được điều chỉnh theo tốc độ tiếp thu. Không chuyển chặng chỉ vì đã đọc xong; cần hoàn thành bài tập và giải thích được kiến thức cốt lõi.

## Phương pháp Feynman cho từng bài

1. **Hiểu bằng ví dụ đời thường:** liên hệ khái niệm với thứ quen thuộc.
2. **Nắm bản chất:** khái niệm này giải quyết vấn đề gì?
3. **Đọc cú pháp:** giải thích từng thành phần, dấu câu và cách viết.
4. **Tự thực hành:** người học tự gõ, chạy và quan sát kết quả.
5. **Giải thích lại:** diễn đạt bằng lời của mình, sau đó làm bài kiểm tra ngắn.
6. **Sửa lỗi và ôn tập:** hiểu nguyên nhân lỗi thay vì chỉ thay code cho chạy.

Mỗi bài học cần có: mục tiêu, kiến thức tiên quyết, giải thích, cú pháp, ví dụ nhỏ, nhiệm vụ thực hành, câu hỏi kiểm tra và tiêu chí hoàn thành.

## Cách tổ chức thư mục dự kiến

```text
learn-code-web-Python/
├── README.md
├── ROADMAP.md
├── STUDY_METHOD.md
├── lessons/
│   ├── 00-programming-is-what/
│   ├── 01-python-first-steps/
│   ├── 02-variables-and-data-types/
│   ├── 03-operators/
│   ├── 04-conditions/
│   ├── 05-loops/
│   ├── 06-functions/
│   ├── 07-data-structures/
│   └── ...
├── projects/
│   ├── 01-first-python-program/
│   ├── 02-basic-calculator/
│   ├── 03-grade-manager/
│   ├── 04-expense-manager/
│   ├── 05-task-manager/
│   └── ...
├── notes/
│   ├── glossary.md
│   └── common-errors.md
└── progress/
    └── learning-log.md
```

Đây là cấu trúc mục tiêu; các thư mục sẽ được bổ sung dần theo bài học. Mỗi dự án thực hành độc lập có thể có môi trường ảo và tệp riêng khi phù hợp. Không cần tạo tất cả thư mục ngay ngày đầu tiên.

## Quy tắc làm việc

- Mỗi dự án nhỏ có một mục tiêu rõ ràng.
- Không đưa toàn bộ chương trình vào một tệp khi đã đến lúc cần tách module.
- Tên tệp và thư mục dùng chữ thường, không dấu, phân cách bằng dấu gạch ngang hoặc gạch dưới một cách nhất quán.
- Mỗi bài tập phải được người học tự viết trước khi xem lời giải hoặc gợi ý đầy đủ.
- Khi gặp lỗi, ghi lại thông báo lỗi, dòng gây lỗi, nguyên nhân và cách khắc phục.
- Không lưu mật khẩu, API key, token hoặc thông tin bí mật lên GitHub.
- Chỉ đánh dấu hoàn thành khi có thể chạy thử và giải thích được cách hoạt động.

## Bắt đầu từ đâu?

1. Đọc [phương pháp học](STUDY_METHOD.md).
2. Xem [lộ trình](ROADMAP.md).
3. Bắt đầu tại [Bài 00 – Lập trình là gì?](lessons/00-programming-is-what/README.md).
4. Ghi lại tiến độ trong [Learning Log](progress/learning-log.md).

---

**Mục tiêu cuối cùng:** người học có thể tự phân tích yêu cầu, thiết kế cấu trúc dự án, viết Python, xây giao diện NiceGUI, lưu dữ liệu, kiểm thử, bảo mật và triển khai website của chính mình.
