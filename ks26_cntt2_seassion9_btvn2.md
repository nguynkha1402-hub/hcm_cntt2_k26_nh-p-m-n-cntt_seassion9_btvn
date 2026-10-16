Họ và tên: Trần Nguyễn Kha

**Bài 2 : Kiểm tra tài liệu trước khi xuất bản**

Đề bài / Yêu cầu

**1. Mục tiêu**

Làm chủ 6 cú pháp Markdown cơ bản: Heading, Emphasis, List, Link, Image, Blockquote.



Sửa lỗi logic trong cấu trúc phân cấp tiêu đề (Heading).



**2. Bối cảnh \& Vấn đề**

Một bạn sinh viên gửi cho bạn bản thảo Markdown nhưng khi đưa vào StackEdit thì kết quả render bên phải trông rất lộn xộn: ảnh không hiện, tiêu đề lúc to lúc nhỏ không theo thứ tự.



**3. Hiện trường giả**

Đoạn mã của bạn sinh viên:



\# Tiêu đề 1

\### Giới thiệu dự án

\[Logo PTIT] (https://ptit.edu.vn/logo.png)

Đây là đoạn văn bản in đậm.

\## Mục tiêu

\- Quản lý sinh viên

\- Quản lý môn học

**4. Ràng buộc \& Bẫy dữ liệu**

Bẫy: Quy tắc "Mỗi bài chỉ nên có 1 H1 duy nhất" và khoảng trắng sau ký tự #.



**5. Yêu cầu đầu ra**

**Phần 1. Phân tích:**

**Chỉ ra ít nhất 3 lỗi cú pháp trong đoạn mã trên và giải thích tại sao kết quả render không như ý.**

\-Lỗi chèn ảnh: *\[Logo PTIT] (\[https://ptit.edu.vn/logo.png](https://ptit.edu.vn/logo.png))* bị thừa khoảng trắng giữa *\[]* và *()*, đồng thời thiếu dấu chấm than *!* ở đầu để nhận diện ảnh.

\-Lỗi phân cấp tiêu đề (Heading): Nhảy cóc bất hợp lý từ H1 *(#)* xuống thẳng H3 (###), vi phạm thứ tự logic tiêu chuẩn (H1 -> H2 -> H3).

\-Lỗi định dạng văn bản: Thiếu cú pháp in đậm cho đoạn văn bản nhấn mạnh.



**Phần 2. Hoàn thiện:**

**Viết lại đoạn mã chuẩn để hiển thị: 1 ảnh Logo PTIT, tiêu đề phân cấp H1 -> H2, và một câu in đậm đúng quy tắc.**

*Markdown*

*# Giới thiệu Dự án PTIT*



*!\[Logo PTIT](https://ptit.edu.vn/logo.png)*



*## 1. Tổng quan*

*\*\*Đây là đoạn văn bản in đậm đúng quy tắc.\*\**



*## 2. Mục tiêu*

*\* Quản lý sinh viên*

*\* Quản lý môn học*

