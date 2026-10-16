# **Bài 3: Giảm chi phí vận hành Chatbot Al**
**HỌ VÀ TÊN:** Lâm Hữu Nghị

**LỚP:** HCM_CNTT1

**MÔN:** nhapmonCNTT

**BÀI:** SESSION10
 
 **BÀI TẬP:** EX03 giảm chi phí vận hành Chatbot Al
 ## **Phần 1. Phân tích bài toán:** 
# GreenTech - Hệ thống Chuyên gia Nông nghiệp AI

GreenTech là hệ thống hỗ trợ nông nghiệp thông minh, ứng dụng Mô hình ngôn ngữ lớn (LLM) để tiếp nhận và trả lời các thắc mắc về kỹ thuật canh tác, dịch bệnh và chăm sóc cây trồng của người nông dân theo thời gian thực.

## Tính năng nổi bật

*   **Tư vấn kỹ thuật 24/7:** Phân tích triệu chứng bệnh cây trồng và đưa ra giải pháp sinh học/hóa học tối ưu.
*   **Xử lý dữ liệu bằng Markdown:** Tối ưu hóa cấu trúc văn bản trả về giúp AI xử lý nhanh hơn, tiết kiệm chi phí và tăng độ chính xác.
*   **Thân thiện với người dùng:** Nội dung câu trả lời trực quan, dễ đọc ngay cả trên các thiết bị di động có cấu hình thấp hoặc mạng yếu.

## Tại sao hệ thống chọn Markdown thay vì HTML?

Để đảm bảo hiệu năng và tiết kiệm chi phí vận hành cho hệ thống "GreenTech", chúng tôi áp dụng định dạng Markdown trong lõi xử lý AI dựa trên các tiêu chí:

1.  **Tiết kiệm Token:** Giảm từ 30% - 50% số lượng token so với HTML rườm rà, giúp tối ưu chi phí API.
2.  **Giảm độ trễ (Latency):** Tốc độ sinh văn bản của AI nhanh hơn, phản hồi cho người nông dân ngay lập tức.
3.  **Human-readable:** Văn bản dạng Markdown dễ đọc, dễ hiểu trực tiếp mà không bị rối mắt bởi các thẻ kỹ thuật như `<div>`, `<p>`, `<strong>`.

### Bảng so sánh cấu trúc dữ liệu

| Tiêu chí | Định dạng Markdown | Định dạng HTML |
| :--- | :--- | :--- |
| **Cú pháp in đậm** | `**Lúa bị đạo ôn**` | `<strong>Lúa bị đạo ôn</strong>` |
| **Số lượng ký tự** | 18 ký tự | 31 ký tự |
| **Độ thân thiện (UI)** | Rất cao (Hiển thị dạng thô vẫn sạch sẽ) | Thấp (Bị lộ thẻ nếu lỗi render) |

## Hướng dẫn cài đặt và khởi chạy

### 1. Yêu cầu hệ thống
*   Python 3.10+
*   Khóa API của mô hình LLM (OpenAI, Gemini, hoặc Claude)

### 2. Cài đặt các thư viện cần thiết
Mở terminal và chạy lệnh sau để cài đặt các package phụ thuộc:
```bash
pip install -r requirements.txt
```

### 3. Cấu hình biến môi trường
Tạo tệp `.env` tại thư mục gốc và cấu hình key của bạn:
```env
AI_API_KEY=your_api_key_here
OUTPUT_FORMAT=MARKDOWN
```

### 4. Chạy ứng dụng
Khởi chạy hệ thống chatbot chuyên gia:
```bash
python main.py
```

## Kiến trúc luồng dữ liệu (Data Flow)
[Nông dân đặt câu hỏi]
-->
[Hệ thống GreenTech xử lý]
-->
[AI sinh câu trả lời (Dạng Markdown sạch)]
-->
[Frontend Render: Markdown --> HTML trực quan]
-->
[Nông dân nhận kết quả giao diện đẹp, tốc độ cao]

## Đóng góp dự án

Mọi ý tưởng đóng góp hoặc báo lỗi (Issues) xin vui lòng gửi về mục Pull Requests của kho lưu trữ này. GreenTech luôn chào đón sự chung tay từ cộng đồng để hỗ trợ người nông dân tốt hơn.

## Giấy phép

Dự án này được phát hành dưới bản quyền **MIT License**.
# HCM_CNTT_nhapmonCNTT_-LAMHUUNGHI-_SESSION10_EX03
# HCM_CNTT_nhapmonCNTT_-LAMHUUNGHI-_SESSION10_EX03
