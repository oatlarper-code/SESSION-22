# 3.Yêu cầu chức năng
- Context: Tôi là sinh viên năm nhất đang cần đẩy code lên Github để kịp deadline 
- Issues: Terminal báo lỗi error: open(".git/FETCH_HEAD"): Permission denied khi thực hiện Git
- Demand: Hãy giải thích nguyên nhân một các bình dân nhất và đưa ra cụ thể từng bước để sửa lỗi 


```
ADMINISTRATOR: WINDOWS Terminal
Microsoft Windows [Version 10.0.26300.9818]
(c) Microsoft Corporation. All rights reserved.

PS C:\Users\My Laptop> git push HN-KS26CNTT2_NMCNTT_SESSION22_Ex06
Error: open(" .git/README.md"): Permission denied
fatal: unable to access '.git/README.md': Permission denied
PS C:\Users\My Laptop> icacls .git /grant <User>:<Permission>
Processed file: .git\README.md
Successfully processed 1 files.
PS C:\Users\My Laptop> git push HN-KS26CNTT2_NMCNTT_SESSION22_Ex06
Everything up-to-date
```
> Soạn một tin nhắn nhờ giảng viên hỗ trợ tuân thủ đúng Bug Reporting Framework

Em chào thầy/cô ạ.

Em đang thực hiện đẩy bài tập lên Git thì gặp lỗi không phân quyền được và chưa khắc phục được. Em xin gửi chi tiết báo cáo lỗi em nhờ thầy/cô hỗ trợ ạ.\
 Context: Tôi là sinh viên năm nhất đang cần đẩy code lên Github để kịp deadline \
 Issues: Terminal báo lỗi error: open(".git/README.md"): Permission denied khi thực hiện Git\
 Demand: Hãy giải thích nguyên nhân một các bình dân nhất và đưa ra cụ thể từng bước để sửa lỗi \
Lỗi log:\
Error: open(" .git/README.md"): Permission denied\
fatal: unable to access '.git/README.md': Permission denied

- Các bước thực hiện:\
1.Sử dụng Administrator Terminal để thử\
2.Kiểm tra thuộc tính của thư mục

Em gửi kèm ảnh chụp màn hình Terminal mô tả lỗi. Em nhờ thầy/cô tìm cách xử lý giúp em với ạ. Em cảm ơn thầy/cô nhiều.