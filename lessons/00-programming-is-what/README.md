# Bài 00 — Lập trình là gì?

**Chặng 0 · Làm quen với lập trình · Chưa cần cài thêm thư viện**

## 1. Mục tiêu bài học
Sau bài này, bạn có thể:
- Giải thích lập trình bằng lời của mình.
- Phân biệt mã nguồn, chương trình và kết quả chạy.
- Phân biệt VS Code, Python và NiceGUI.
- Mô tả đơn giản máy tính làm theo chỉ dẫn như thế nào.

Chưa cần học thuộc cú pháp. Trước tiên hãy hiểu chúng ta đang làm công việc gì.

## 2. Hãy tưởng tượng bạn đang hướng dẫn một người làm bánh
Bạn muốn người đó làm một chiếc bánh. Bạn không thể chỉ nói “hãy làm bánh thật ngon” rồi mong họ tự biết mọi thứ. Bạn phải đưa ra chỉ dẫn đủ rõ: chuẩn bị nguyên liệu, đong lượng cần thiết, trộn theo thứ tự, nướng và kiểm tra thành phẩm.

Máy tính cũng tương tự. Máy tính rất nhanh, nhưng nó không tự hiểu mong muốn mơ hồ của chúng ta. Người lập trình phải viết các chỉ dẫn rõ ràng theo quy tắc của một ngôn ngữ lập trình.

**Lập trình** là quá trình thiết kế và viết các chỉ dẫn để máy tính thực hiện một nhiệm vụ.

## 3. Bốn khái niệm cần phân biệt

### Mã nguồn (source code)
Những chỉ dẫn do con người viết bằng ngôn ngữ lập trình, ví dụ Python. Mã nguồn giống như bản hướng dẫn làm bánh.

### Chương trình (program)
Tập hợp các chỉ dẫn được tổ chức để máy tính thực hiện một nhiệm vụ. Một chương trình có thể gồm một hoặc nhiều tệp.

### Thực thi (execution)
Quá trình chương trình được chạy. Máy tính xử lý các chỉ dẫn theo quy tắc của ngôn ngữ và môi trường tương ứng.

### Kết quả đầu ra (output)
Điều chương trình tạo ra hoặc gửi tới nơi nhận kết quả, chẳng hạn một dòng chữ hiển thị trên màn hình.

## 4. Python, VS Code và NiceGUI khác nhau thế nào?
Hãy tưởng tượng bạn viết một cuốn sách:
- **VS Code** là bàn làm việc và công cụ soạn thảo.
- **Python** là ngôn ngữ dùng để viết chỉ dẫn; trình thông dịch Python giúp thực thi mã Python.
- **NiceGUI** là thư viện cung cấp những thành phần và công cụ để tạo giao diện ứng dụng web bằng Python.

Ba thứ này không thay thế cho nhau. Bạn viết trong VS Code, chạy chương trình bằng Python, và khi học làm web sẽ dùng NiceGUI để xây dựng giao diện và tương tác.

## 5. Một dòng Python đầu tiên
Hãy quan sát dòng lệnh sau:

    print("Xin chào!")

Chưa cần gõ vội. Hãy hiểu từng phần:
- **print** là tên một hàm có sẵn của Python, dùng để hiển thị thông tin.
- **Dấu ngoặc tròn** chứa thông tin đưa vào hàm.
- **Dấu nháy kép** bao quanh một đoạn văn bản.
- **Xin chào!** là nội dung muốn hiển thị.

Khi chương trình chạy, kết quả được in ra là:

    Xin chào!

Điều quan trọng không phải là nhớ dòng lệnh này. Điều quan trọng là hiểu: bạn viết một chỉ dẫn, Python thực thi chỉ dẫn, và bạn quan sát kết quả.

## 6. Một website hoạt động ở mức cơ bản
Khi mở một trang web:
1. Trình duyệt là ứng dụng bạn dùng để xem và tương tác với trang.
2. Trình duyệt gửi yêu cầu tới máy chủ khi cần lấy trang hoặc dữ liệu.
3. Máy chủ chạy ứng dụng để xử lý yêu cầu.
4. Máy chủ gửi phản hồi về trình duyệt.
5. Trình duyệt hiển thị nội dung cho người dùng.

Với NiceGUI, chúng ta sẽ viết phần ứng dụng bằng Python. NiceGUI kết nối logic Python với giao diện trình duyệt. Ta sẽ học chi tiết sau khi có nền tảng Python.

## 7. Bài tập tư duy — chưa cần viết code
Hãy trả lời bằng lời của bạn:
1. Tại sao máy tính cần chỉ dẫn rõ ràng?
2. Mã nguồn và kết quả đầu ra khác nhau ở đâu?
3. VS Code có phải là Python không? Vì sao?
4. NiceGUI giúp ích gì khi làm website?
5. Khi chạy chương trình, điều gì xảy ra giữa lúc viết mã nguồn và lúc nhìn thấy kết quả?

## 8. Bài thực hành quan sát
Nếu Python đã được cài trên máy:
1. Mở VS Code.
2. Mở Terminal tích hợp trong VS Code.
3. Nhập lệnh kiểm tra phiên bản Python: **py --version**.
4. Quan sát dòng kết quả.
5. Giải thích: bạn vừa yêu cầu máy tính làm gì và kết quả nói cho bạn biết điều gì?

Nếu terminal báo không nhận ra lệnh py, đừng tự cài ngẫu nhiên nhiều phiên bản. Hãy gửi nguyên thông báo lỗi để xử lý đúng nguyên nhân.

## 9. Kiểm tra Feynman
Không nhìn lại phần giải thích, hãy viết 4–6 câu giải thích cho một người bạn chưa biết lập trình:
- Lập trình là gì?
- VS Code dùng để làm gì?
- Python dùng để làm gì?
- NiceGUI dùng để làm gì?

## 10. Tiêu chí hoàn thành
- [ ] Phân biệt được mã nguồn và kết quả đầu ra.
- [ ] Giải thích được VS Code, Python và NiceGUI.
- [ ] Hiểu ý nghĩa của dòng print đầu tiên.
- [ ] Trả lời được 5 câu hỏi tư duy.
- [ ] Tự giải thích lại mà không đọc nguyên văn giáo trình.

**Chưa chuyển sang bài tiếp theo nếu các khái niệm trên còn lẫn lộn.**

---
[Quay lại trang chủ](../../README.md) · [Xem lộ trình](../../ROADMAP.md) · [Phương pháp học](../../STUDY_METHOD.md)