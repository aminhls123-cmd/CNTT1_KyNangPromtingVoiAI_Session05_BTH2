# Xây dựng chuỗi Prompt viết bài PR sản phẩm công nghệ

## Nội dung 3 phần prompt
### Prompt 1
- Bạn là chuyên gia nghiên cứu thị trường và hành vi khách hàng trong lĩnh vực công nghệ AI.
- Hãy nghiên cứu đối tượng khách hàng mục tiêu cho sản phẩm AI Chatbot dành cho doanh nghiệp.
- Phân tích:
    - Chân dung khách hàng mục tiêu.
    - Nhu cầu và hành vi sử dụng.
    - Những khó khăn (Pain Points) trong chăm sóc khách hàng.
    - Những vấn đề AI Chatbot có thể giải quyết.
    -  Lợi ích và giá trị sản phẩm mang lại.
- Đầu ra bắt buộc theo cấu trúc:
- [CUSTOMER_CONTEXT]
  - Target_Audience:
  - Customer_Needs:
  - Pain_Points:
  - Product_Solutions:
  - Key_Benefits:
  - Customer_Insights:
- Chỉ sử dụng thông tin sản phẩm được cung cấp hoặc ghi rõ giả định. Không tự tạo số liệu nghiên cứu.
> Đây là dữ liệu đầu vào bắt buộc cho Prompt 2.

### Prompt 2
Bạn là chuyên gia Content Marketing và SEO.

Dựa hoàn toàn trên dữ liệu [CUSTOMER_CONTEXT] từ Prompt 1, hãy xây dựng dàn ý chi tiết cho bài PR giới thiệu giải pháp AI Chatbot mới dành cho doanh nghiệp.

Yêu cầu:
1. Xây dựng tiêu đề thu hút.
2. Viết định hướng đoạn mở đầu (Lead) đánh đúng Pain Points.
3. Chia bài viết thành các tiêu đề H2 và H3 logic.
4. Mỗi phần phải có nội dung chính và mục tiêu truyền tải.
5. Đề xuất từ khóa SEO chính và từ khóa phụ.
6. Xây dựng CTA rõ ràng ở cuối bài.

Định hướng:
- Độ dài bài hoàn chỉnh: 1.000–1.500 từ.
- Giọng văn chuyên nghiệp, đáng tin cậy.
- Không lặp ý giữa các phần.

Đầu ra:

[ARTICLE_OUTLINE]
- Headline:
- Lead:
- SEO_Keywords:
- H2_H3_Structure:
- Key_Messages:
- CTA:
- Tone_Of_Voice:

Dữ liệu [ARTICLE_OUTLINE] là đầu vào bắt buộc của Prompt 3. Không tự ý thay đổi cấu trúc khi triển khai.

### Prompt 3
Bạn là chuyên gia Content Marketing và SEO Copywriting.

Sử dụng đầy đủ hai dữ liệu:
- [CUSTOMER_CONTEXT] từ Prompt 1.
- [ARTICLE_OUTLINE] từ Prompt 2.

Hãy triển khai bài PR chuyên sâu giới thiệu giải pháp AI Chatbot cho doanh nghiệp.

Yêu cầu:
1. Độ dài 1.000–1.500 từ.
2. Giữ nguyên giọng văn chuyên nghiệp, tin cậy.
3. Có Headline hấp dẫn.
4. Lead giải quyết trực tiếp Pain Points.
5. Sử dụng đầy đủ các H2, H3 trong dàn ý.
6. Phân tích sâu lợi ích và giải pháp của AI Chatbot.
7. Tối ưu từ khóa SEO tự nhiên, tránh nhồi nhét.
8. Có CTA rõ ràng ở cuối bài.
9. Không tự tạo thông tin, số liệu hoặc tính năng sản phẩm chưa được xác nhận.
10. Đảm bảo nội dung giữa các phần liên kết chặt chẽ, không lặp ý.

Nếu bài viết bị ngắt do giới hạn token:
- Dừng tại ranh giới câu hoặc đoạn hoàn chỉnh nếu có thể.
- Ghi lại phần đã hoàn thành và tiêu đề tiếp theo.
- Khi được yêu cầu tiếp tục, phải giữ nguyên Outline, Tone_Of_Voice và SEO_Keywords.
- Không viết lại nội dung đã hoàn thành.

Đầu ra cuối cùng là bài PR hoàn chỉnh, có cấu trúc chuẩn SEO và được kiểm tra tính nhất quán.

