# Lộ trình học Python và xây dựng website bằng NiceGUI

Lộ trình chia thành các chặng nhỏ. Học đủ nền tảng trước khi dùng thư viện; không đánh giá tiến độ chỉ bằng số giờ học.

## Chặng 0 — Làm quen với lập trình
**Mục tiêu:** hiểu chương trình, mã nguồn, VS Code, Python, terminal và tệp .py.

Bài học: Lập trình là gì? Mã nguồn và chương trình; Python thực thi mã như thế nào; VS Code và terminal; chạy chương trình đầu tiên.

**Hoàn thành khi:** tự tạo và chạy được một tệp Python, giải thích được điều gì xảy ra.

## Chặng 1 — Cú pháp Python cơ bản
**Mục tiêu:** biết cách biểu diễn dữ liệu và điều khiển luồng chương trình.

Bài học: print(), input(), biến, phép gán, str, int, float, bool, chuyển đổi kiểu, toán tử, if/elif/else, for, while, range(), thụt lề và quy tắc đặt tên.

**Dự án nhỏ:** chương trình giới thiệu bản thân; máy tính cơ bản; chương trình tính điểm; trò chơi đoán số.

**Hoàn thành khi:** tự viết chương trình ngắn có nhập dữ liệu, tính toán và rẽ nhánh.

## Chặng 2 — Hàm và cấu trúc dữ liệu
**Mục tiêu:** chia chương trình thành phần có nhiệm vụ rõ ràng và làm việc với nhiều dữ liệu.

Bài học: def, tham số, đối số, return, trường hợp không có return, phạm vi biến; list, tuple, dictionary, set; vòng lặp trên dữ liệu; xử lý chuỗi; đọc/ghi tệp; try/except.

**Dự án nhỏ:** danh sách công việc; quản lý điểm; quản lý thu chi.

**Hoàn thành khi:** biết chọn cấu trúc dữ liệu phù hợp và chia một chương trình thành các hàm.

## Chặng 3 — Tổ chức dự án chuyên nghiệp
**Mục tiêu:** quản lý nhiều tệp mà vẫn hiểu cách chúng phối hợp.

Bài học: module, import, package, __init__.py, đường dẫn, trách nhiệm từng module, môi trường ảo (venv), pip, đọc tài liệu, traceback, Git và GitHub.

**Dự án nhỏ:** ứng dụng quản lý công việc chia thành nhiều module, có hướng dẫn cài đặt và chạy.

**Hoàn thành khi:** giải thích được mỗi tệp chịu trách nhiệm gì và dữ liệu đi qua các module thế nào.

## Chặng 4 — NiceGUI căn bản
**Mục tiêu:** hiểu cách Python tạo giao diện và phản hồi hành động của người dùng.

Bài học: giao diện người dùng; cài NiceGUI; from nicegui import ui; ui.label, ui.button, ui.input, ui.number; on_click, on_change; hàm callback; row, column, card, grid; classes, style, props; @ui.page và ui.run.

**Dự án nhỏ:** trang giới thiệu; máy tính web; biểu mẫu; dashboard dữ liệu mẫu.

**Hoàn thành khi:** tự tạo được giao diện, nhận dữ liệu nhập và xử lý hành động nhấn nút.

## Chặng 5 — Website nhiều trang
**Mục tiêu:** biến các màn hình riêng lẻ thành ứng dụng có luồng sử dụng rõ ràng.

Bài học: phân tích yêu cầu; luồng người dùng; tách trang, thành phần giao diện và logic nghiệp vụ; điều hướng; trạng thái giao diện; kiểm tra dữ liệu; thông báo; bảng, bộ lọc và tìm kiếm.

**Dự án nhỏ:** website quản lý công việc gồm tổng quan, danh sách, tạo mới và chỉnh sửa.

## Chặng 6 — Cơ sở dữ liệu
**Mục tiêu:** lưu dữ liệu để dữ liệu vẫn còn sau khi đóng website.

Bài học: cơ sở dữ liệu, bảng, hàng, cột, khóa chính; SQLite và SQL căn bản; CRUD; truy vấn có điều kiện; ràng buộc; tách lớp truy cập dữ liệu khỏi giao diện; sao lưu.

**Dự án nhỏ:** chuyển website quản lý công việc sang lưu dữ liệu bằng SQLite.

## Chặng 7 — Người dùng, bảo mật và kiểm thử
**Mục tiêu:** chuẩn bị ứng dụng cho nhiều người dùng và dữ liệu thực tế.

Bài học: đăng ký, đăng nhập, hash mật khẩu, phiên đăng nhập, phân quyền, biến môi trường, quản lý bí mật, kiểm tra đầu vào, xử lý lỗi an toàn, kiểm thử và nhật ký lỗi.

**Dự án nhỏ:** bổ sung tài khoản, đăng nhập và phân quyền.

## Chặng 8 — Triển khai website
**Mục tiêu:** đưa ứng dụng từ máy cá nhân lên môi trường có thể truy cập qua Internet.

Bài học: local và máy chủ; cấu hình môi trường; máy chủ, domain, DNS; HTTPS/TLS; triển khai và cập nhật; giám sát, log và sao lưu.

**Dự án cuối:** website NiceGUI có giao diện, nhiều trang, cơ sở dữ liệu, xác thực, kiểm thử và hướng dẫn triển khai.

## Điều kiện chuyển chặng
Chỉ chuyển chặng khi người học có thể giải thích khái niệm bằng lời của mình, tự viết ví dụ nhỏ, dự đoán kết quả, đọc lỗi và hoàn thành bài thực hành.