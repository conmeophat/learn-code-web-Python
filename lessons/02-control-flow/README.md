# Chặng 02 — Điều kiện, vòng lặp và tư duy giải thuật

**Mục tiêu:** điều khiển chương trình chọn việc cần làm và lặp lại thao tác khi cần.

## Danh sách bài học

| Mã | Bài học | Cú pháp / ý tưởng trọng tâm |
|---|---|---|
| 02.1 | Giá trị đúng và sai | Truth value |
| 02.2 | Câu lệnh điều kiện | if |
| 02.3 | Nhiều trường hợp | elif, else |
| 02.4 | Khối lệnh và thụt lề | Dấu : và indentation |
| 02.5 | Điều kiện kết hợp | and, or, not |
| 02.6 | Điều kiện lồng nhau | Nested if và cách tránh lồng quá sâu |
| 02.7 | Vòng lặp while | Điều kiện tiếp tục |
| 02.8 | Vòng lặp for | Duyệt qua một tập hợp |
| 02.9 | range() | Điểm bắt đầu, điểm dừng, bước nhảy |
| 02.10 | break và continue | Dừng vòng lặp hoặc bỏ qua một lượt |
| 02.11 | Vòng lặp lồng nhau | Bảng, cặp phần tử, mẫu lặp |
| 02.12 | Tránh vòng lặp vô hạn | Cập nhật điều kiện và kiểm soát trạng thái |
| 02.13 | Theo dõi luồng thực thi | Trace từng bước bằng giấy |

## Tư duy cần nắm
- Điều kiện là một câu hỏi có kết quả đúng hoặc sai.
- if/elif/else quyết định khối lệnh nào được thực hiện.
- Vòng lặp phù hợp khi một thao tác cần thực hiện nhiều lần.
- while thường dựa trên điều kiện; for thường duyệt qua một chuỗi phần tử hoặc phạm vi.
- Mỗi vòng lặp cần có logic kết thúc rõ ràng.

## Bài tập thực hành
1. Kiểm tra một số là chẵn hay lẻ.
2. Xếp loại điểm theo các khoảng do đề bài quy định.
3. Tìm số lớn nhất trong ba số.
4. Tính tổng các số từ 1 đến n.
5. In bảng cửu chương.
6. Cho người dùng nhập lại cho đến khi dữ liệu hợp lệ.
7. Tạo trò chơi đoán số với số lần thử có giới hạn.

## Dự án nhỏ
**Trò chơi đoán số:** chương trình chọn một số bí mật; người chơi nhập dự đoán; chương trình gợi ý lớn hơn hoặc nhỏ hơn, đếm lượt và kết thúc khi đoán đúng hoặc hết lượt.

**Máy tính điểm:** nhận điểm, kiểm tra khoảng hợp lệ và xếp loại theo quy tắc rõ ràng. Không tự giả định thang điểm; ghi rõ quy tắc của bài tập.

## Kiểm thử
Thử điều kiện ở đúng ngưỡng, thấp hơn ngưỡng và cao hơn ngưỡng. Với vòng lặp, thử trường hợp chạy 0 lần, 1 lần và nhiều lần.

## Tiêu chí hoàn thành
- [ ] Viết được if/elif/else có nhiều nhánh.
- [ ] Chọn được while hoặc for phù hợp.
- [ ] Giải thích được điều kiện kết thúc vòng lặp.
- [ ] Nhận ra nguy cơ vòng lặp vô hạn.
- [ ] Hoàn thành dự án đoán số mà không sao chép lời giải.