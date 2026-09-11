# Giáo dục với Claude

Chuyên mục này giúp bạn sử dụng Claude để giải thích kiến thức, bài học và câu hỏi luyện tập.

## Prompt cơ bản

```text
Bạn là giáo viên có khả năng giải thích dễ hiểu.

Hãy giúp tôi học hoặc giảng dạy [CHỦ ĐỀ] cho [TRÌNH ĐỘ].

Bối cảnh:
[BỐI CẢNH]

Dữ liệu đầu vào:
[DÁN DỮ LIỆU HOẶC MÔ TẢ TỆP ĐÍNH KÈM]

Đối tượng sử dụng kết quả:
[ĐỐI TƯỢNG]

Yêu cầu:
1. [YÊU CẦU 1]
2. [YÊU CẦU 2]
3. [YÊU CẦU 3]

Định dạng đầu ra:
[BẢNG/DANH SÁCH/DÀN Ý/VĂN BẢN/CODE]

Quy tắc:
- Chỉ sử dụng dữ liệu tôi cung cấp khi được yêu cầu.
- Không tự tạo số liệu, nguồn, URL hoặc trải nghiệm.
- Đánh dấu [CẦN KIỂM CHỨNG] khi chưa đủ bằng chứng.
- Nếu thiếu thông tin, hãy hỏi tôi tối đa 5 câu trước khi làm.
```

## Prompt nâng cao

```text
Bạn là giáo viên có khả năng giải thích dễ hiểu.

Mục tiêu cuối cùng:
[MỤC TIÊU]

Bối cảnh và giới hạn:
[BỐI CẢNH, THỜI GIAN, NGÂN SÁCH, CÔNG CỤ]

Nguồn dữ liệu được phép sử dụng:
[DỮ LIỆU/TỆP/ĐƯỜNG DẪN]

Nếu phân tích tài liệu dài, hãy trích dẫn phần liên quan và nói rõ khi không tìm thấy bằng chứng.

Hãy làm theo quy trình:
1. Tóm tắt điều bạn hiểu.
2. Phân loại dữ kiện, suy luận và thông tin còn thiếu.
3. Đề xuất 3 phương án phù hợp với nguồn lực.
4. Chờ tôi chọn phương án.
5. Tạo bản nháp theo định dạng yêu cầu.
6. Tự kiểm tra độ chính xác, tính nhất quán và khả năng sử dụng.
7. Cung cấp phiên bản hoàn chỉnh.

Không chuyển sang bước tiếp theo nếu tôi yêu cầu xác nhận từng bước.
```

## Prompt kiểm tra kết quả

```text
Hãy kiểm tra kết quả trên theo bảng gồm:
- Tiêu chí
- Đạt hoặc chưa đạt
- Vấn đề phát hiện
- Cách sửa

Tiêu chí:
1. Đúng mục tiêu
2. Đúng dữ liệu đầu vào
3. Không có thông tin tự tạo
4. Rõ ràng và dễ sử dụng
5. Phù hợp với đối tượng
6. Đúng định dạng
7. Không vi phạm bảo mật hoặc bản quyền

Sau đó sửa các vấn đề và cung cấp phiên bản cuối cùng.
```

## Checklist

- [ ] Đã nêu rõ mục tiêu
- [ ] Đã cung cấp đủ bối cảnh
- [ ] Đã xác định đối tượng
- [ ] Đã kiểm tra dữ kiện và số liệu
- [ ] Đã phân biệt dữ kiện với suy luận
- [ ] Không có thông tin nhạy cảm
- [ ] Kết quả đã được con người đọc lại

[⬅ Quay lại Claude](../README.md)  
[🏠 Quay lại trang chủ](../../README.md)
