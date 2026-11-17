### **Bước 1: Phân tích lỗi của Prompt cũ**
Khi sử dụng prompt cũ *(“Yêu cầu: Hãy giải thích ngắn gọn các nội dung của Chain-of-Thought, Prompt Chaining, xử lý đứt gãy”)*, AI thường phản hồi kèm theo các thành phần thừa thãi sau:

1. **Lời chào hỏi / Xã giao mở đầu:** Ví dụ như *"Chào bạn! Dưới đây là phần giải thích ngắn gọn về các nội dung bạn yêu cầu..."* -> Làm mất thời gian cuộn trang và không cần thiết khi copy vào báo cáo.

2. **Lời dẫn dắt chuyển ý vòng vo:** Ví dụ như *"Để hiểu rõ hơn, chúng ta hãy cùng tìm hiểu từng khái niệm một cách chi tiết nhé..."* -> Kéo dài văn bản và làm loãng thông tin cốt lõi.

3. **Lời kết / Chúc xã giao cuối bài:** Ví dụ như *"Hy vọng thông tin trên hữu ích cho công việc và học tập của bạn! Nếu cần thêm gì hãy hỏi mình nhé."* -> Cần phải thủ công xóa đi trước khi dán vào tài liệu.
### **Bước 2: Viết Prompt tối ưu (Đã gắn ràng buộc định dạng)**
**Prompt tối ưu:**

Plaintext

`Hãy giải thích khái niệm cốt lõi của các kỹ thuật sau: Chain-of-Thought, Prompt Chaining, và Xử lý đứt gãy.` ```[Ràng buộc định dạng bắt buộc]:` `- TUYỆT ĐỐI KHÔNG viết lời chào, lời dẫn mở đầu hay lời kết xã giao. Đi thẳng vào nội dung chính.` `- Trình bày toàn bộ dưới dạng danh sách gạch đầu dòng (bullet points).` `- Mỗi khái niệm chỉ trình bày tối đa trong 2 câu ngắn gọn, súc tích.` 
### **Bước 3: Kết quả phản hồi mẫu từ AI (Sạch chữ thừa, chuẩn báo cáo)**
- Chain-of-Thought (Chuỗi tư duy): Kỹ thuật hướng dẫn AI chia nhỏ vấn đề phức tạp thành các bước suy luận logic tuần tự trước khi đưa ra kết quả cuối cùng.

- Prompt Chaining (Chuỗi Prompt): Kỹ thuật chia một quy trình dài thành nhiều prompt nhỏ liên tiếp, trong đó đầu ra của prompt trước làm đầu vào cho prompt sau.

- Xử lý đứt gãy (Error Handling): Cơ chế thiết lập các phương án dự phòng, điều kiện kiểm tra hoặc prompt bổ sung để xử lý khi AI trả về kết quả sai lệch hoặc bị ngắt quãng giữa chừng.


