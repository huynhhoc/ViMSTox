# toxic-detection

## Giới thiệu
Repo này phục vụ **quá trình thiết kế khảo sát và thu thập dữ liệu** cho luận văn thạc sĩ của **Diệp Thị Thanh Thảo** với đề tài:

**“NGHIÊN CỨU VÀ XÂY DỰNG MÔ HÌNH NHẬN DIỆN NGÔN NGỮ ĐỘC HẠI TRONG HỆ THỐNG TRỢ LÝ HỌC TẬP CHO HỌC SINH TRUNG HỌC CƠ SỞ”**  
**Giảng viên hướng dẫn:** **TS. Huỳnh Thái Học**

Mục tiêu nghiên cứu hướng đến việc xây dựng mô hình/giải pháp nhận diện **ngôn ngữ độc hại (toxic/harmful)** trong bối cảnh **trợ lý học tập (chatbot) dành cho học sinh THCS**, nhằm hỗ trợ an toàn nội dung và giảm thiểu rủi ro tương tác.

## Trạng thái hiện tại
🚧 **Đang trong giai đoạn khảo sát và thu thập dữ liệu** (data collection in progress).

Trong giai đoạn này, repo tập trung vào:
- Triển khai biểu mẫu khảo sát theo các nhóm nội dung/tiêu chí.
- Ghi nhận câu trả lời của người tham gia.
- Tổng hợp dữ liệu khảo sát để phục vụ các bước tiếp theo: làm sạch dữ liệu, phân tích, xây dựng tập dữ liệu gán nhãn và huấn luyện/đánh giá mô hình.

## Nội dung trong repo
- `index.html`: Trang khảo sát (các câu hỏi và lựa chọn trả lời).
- `thanks.html`: Trang cảm ơn sau khi người tham gia gửi khảo sát.
- `README.md`: Mô tả mục tiêu và tiến độ thu thập dữ liệu.

## Nguyên tắc dữ liệu và đạo đức nghiên cứu
- Dữ liệu thu thập **chỉ phục vụ mục đích nghiên cứu** trong phạm vi luận văn.
- Khuyến nghị **không thu thập thông tin định danh cá nhân (PII)** như: họ tên đầy đủ, số điện thoại, địa chỉ, CCCD…
- Dữ liệu được xử lý theo nguyên tắc: **ẩn danh – tối thiểu hóa – bảo mật**, và chỉ dùng để xây dựng/đánh giá mô hình nhận diện ngôn ngữ độc hại.

## Ghi chú
Nếu sử dụng lại hoặc mở rộng bộ câu hỏi/dữ liệu từ repo này cho mục đích khác, vui lòng trích dẫn/ghi nhận đóng góp theo quy định của nhóm nghiên cứu.
