  #  **Phần 1. Thiết kế Kiến trúc Prompt**
Dưới đây là đoạn Prompt hoàn chỉnh được viết bằng Markdown áp dụng công thức 3 phần, có tích hợp Task List và điều kiện kiểm soát Edge Case:

Markdown
## 1. Bối cảnh
Bạn là một gia sư AI thân thiện, giỏi sư phạm. Người học là sinh viên năm 1 mới bước vào ngành công nghệ và đang gặp khó khăn trong việc hiểu về "Mô hình IPO (Input - Process - Output) trong trang trại thông minh".

## 2. Nội dung
Hãy giải thích khái niệm Mô hình IPO áp dụng cho một hệ thống trang trại thông minh cụ thể (ví dụ: hệ thống tưới cây tự động dựa trên độ ẩm đất).

## 3. Yêu cầu & Ràng buộc
- [ ] Trình bày rõ ràng 3 thành phần: Input (Đầu vào), Process (Xử lý), và Output (Đầu ra).
- [ ] Sử dụng ví dụ thực tế, gần gũi với đời sống hàng ngày để dễ hình dung.
- [ ] Giữ văn phong ngắn gọn, súc tích, phù hợp với sinh viên năm 1.

## Không cần
- Không dùng quá nhiều thuật ngữ kỹ thuật phức tạp hoặc tiếng Anh chuyên ngành dày đặc.
- Không viết dài dòng lan man, tổng độ dài giải thích dưới 300 từ.
Phần 2. Sản phẩm (Mẫu file .md lưu kết quả trả về của AI)
Dưới đây là cấu trúc tệp mo_hinh_ipo_trang_trai_thong_minh.md mô phỏng nội dung AI trả về sau khi nhận được Prompt trên:

Markdown
## Mô hình IPO trong Trang Trại Thông Minh (Ví dụ: Hệ thống tưới cây tự động)

Mô hình **IPO** viết tắt của **Input - Process - Output** (Đầu vào - Xử lý - Đầu ra). Đây là cách một hệ thống tự động nhận thông tin, suy nghĩ và hành động.

## 1. Input (Đầu vào)
* **Là gì?** Dữ liệu thu thập từ môi trường thông qua các cảm biến.
* **Ví dụ:** Cảm biến đo độ ẩm của đất báo về là **20%** (đất đang khô).

## 2. Process (Xử lý)
* **Là gì?** Bộ não (vi điều khiển/AI) nhận dữ liệu từ đầu vào, so sánh với điều kiện cài đặt sẵn để ra quyết định.
* **Ví dụ:** Bộ điều khiển trung tâm nhận thấy độ ẩm < 30%, ra lệnh: *"Cần bật máy bơm ngay!"*

## 3. Output (Đầu ra)
* **Là gì?** Hành động thực tế thực hiện ra bên ngoài.
* **Ví dụ:** Máy bơm nước tự động bật lên và tưới nước cho vườn rau cho đến khi độ ẩm đạt 70%.