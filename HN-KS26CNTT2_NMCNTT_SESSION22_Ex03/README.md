# 4.Yêu cầu đầu ra
- Input: "Path Not Found" khi cài đặt python, AI đưa ra câu lệnh không có thật hoặc sai phiên bản hệ điều hành
- Process: Quy trình tra cứu bằng toán tử site:stackoverflow.com kết quả của google sẽ trả đúng đường dẫn đến trình duyệt web stackoverflow. Tách nhỏ các kết quả của AI và tra cứu kết hợp với toán tử và kiểm tra sự tương thích với hệ điều hành nào
- Output: Phân loại rõ các lệnh an toàn và không an toàn chỉ thêm đường dẫn python và Scripts vào môi trường path để kiểm tra xem mục nào cần tránh không an toàn
> Mẫu câu lệnh Prompt "Hỏi ngược lại" AI
- Đoạn lệnh bạn cung cấp cho tôi gặp hiện tượng Hallucination. Hãy giải thích giải thích độ an toàn của câu lệnh trước khi tôi thực thi.
1.Câu lệnh này có tương thích với hệ điều hành của tôi không?
2.Có những cách thủ công nào hoặc GUI để xử lý lỗi "Path Not Found" này một cách an toàn không?
3.Khi cài đặt Python nó ảnh hưởng đến thư mục nào và thiết lập hệ điều hành của tôi?