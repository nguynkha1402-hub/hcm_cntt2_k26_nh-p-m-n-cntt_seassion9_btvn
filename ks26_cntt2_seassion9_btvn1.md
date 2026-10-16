**Họ và tên: Trần Nguyễn Kha**  
**Bài 1 : Xử lý xung đột tài liệu trên GitHub**  
Đề bài / Yêu cầu  
1. Mục tiêu  
Phân biệt bản chất giữa Plain Text (văn bản thô) và Rich Text.  
Nhận diện ưu thế của Markdown trong việc chống hư hại file và hỗ trợ Git Diff.  
2. Bối cảnh & Vấn đề  
Nam là sinh viên PTIT đang làm dự án nhóm. Nam viết tài liệu giới thiệu dự án bằng Microsoft Word (.docx) và đẩy lên GitHub. Tuy nhiên, các bạn trong nhóm phàn nàn rằng họ không thể xem nội dung trực tiếp trên trình duyệt và mỗi lần Nam sửa một dấu phẩy, hệ thống Git báo lỗi xung đột (Conflict) toàn bộ file.  
3. Hiện trường giả  
Nam lập luận: "Dùng Word tốt hơn vì có thanh công cụ chọn font chữ, màu sắc trực quan. Markdown chỉ là văn bản thô, không thể tạo được tài liệu chuyên nghiệp".  
4. Ràng buộc & Bẫy dữ liệu  
Bẫy: Nếu tệp Word của Nam bị lỗi mạng khi tải làm mất chỉ 1 byte dữ liệu, file sẽ hỏng hoàn toàn. Hãy đối chiếu với đặc tính của Markdown trong tình huống này.  
**5. Yêu cầu đầu ra**  
**Phần 1. Phân tích:**  
**Chỉ ra 2 sai lầm trong tư duy của Nam về việc dùng file Word cho lưu trữ mã nguồn. Giải thích tại sao Markdown lại an toàn và nhẹ hơn.**  
-Hai sai lầm của Nam:  
+Sai lầm 1: Cho rằng file Word phù hợp để quản lý mã nguồn/tài liệu trên GitHub. Thực tế, file Word là định dạng nhị phân, Git không thể đọc hiểu chi tiết bên trong dẫn đến lỗi Conflict toàn bộ file khi nhiều người cùng sửa.  
+Sai lầm 2: Đánh giá thấp Markdown là văn bản thô. Thực chất, Markdown hiển thị trực quan, chuyên nghiệp trên trình duyệt và được thiết kế tối ưu cho quản lý phiên bản (Git).  
-Ưu thế an toàn và nhẹ của Markdown:  
+Chống hư hại file: Markdown là Plain Text thuần túy; nếu lỗi mạng mất dữ liệu, các phần còn lại vẫn đọc bình thường  
+Hỗ trợ Git Diff: Theo dõi thay đổi và giải quyết xung đột theo từng dòng vô cùng nhẹ nhàng và chính xác.  
**Phần 2. Hoàn thiện:**  
**Sử dụng StackEdit để chuyển đổi một đoạn giới thiệu ngắn từ Word sang Markdown, đảm bảo file có định dạng .md.**  
*# Dự Án Quản Lý Nhóm - "Tên nhóm"*  
*## 1. Giới thiệu*  
***Tên nhóm** là nền tảng số hóa hỗ trợ học tập và quản lý tài nguyên nhóm, tối ưu hóa quy trình làm việc và theo dõi tiến độ dự án theo thời gian thực.*  
*## 2. Thành viên nhóm*  
** Thành viên A - Nhóm trưởng*  
** Thành viên B - Phát triển hệ thống*  
*## 3. Công nghệ*  
** **Ngôn ngữ:** Markdown, Python*  
** **Nền tảng:** GitHub, StackEdit*  
