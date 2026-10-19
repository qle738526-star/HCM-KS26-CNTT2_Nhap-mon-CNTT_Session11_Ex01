# HCM-KS26-CNTT2_Nhap-mon-CNTT_Session11_Ex01
---

## 1. Phân tích Nguyên nhân Lỗi

### Lỗi "No table of contents entries found"
- **Nguyên nhân:** Định dạng thủ công (phóng to cỡ chữ, in đậm) chỉ làm thay đổi hình thức bên ngoài. Về mặt cấu trúc, Word vẫn nhận diện đây là kiểu **Normal** (văn bản thường).
- **Hậu quả:** Hệ thống Auto TOC không tìm thấy thẻ nhãn **Heading** nào nên không thể trích xuất mục lục.

### Lỗi đoạn văn 5 trang xuất hiện trong Mục lục
- **Nguyên nhân:** Bôi đen nhầm toàn bộ đoạn văn 5 trang và gán nhãn **Heading 1** (hoặc dùng phím `Shift + Enter` thay vì `Enter` khi ngắt dòng).
- **Hậu quả:** Word hiểu toàn bộ 5 trang là nội dung của một tiêu đề duy nhất và kéo tất cả vào bảng mục lục.

---

## 2. Quy trình Sửa lỗi & Chuẩn hóa Tài liệu

### Bước 1: Khắc phục lỗi gán nhãn sai cho đoạn văn
1. Bôi đen toàn bộ khối văn bản 5 trang bị hiển thị sai trên mục lục.
2. Tại thẻ **Home** → nhóm **Styles**, chọn **Normal** (hoặc nhấn `Ctrl + Shift + N`).

### Bước 2: Gán lại nhãn Heading chuẩn cấp bậc
- **Heading 1** *(cho tiêu đề chính như "1. Giới thiệu", "2. Yêu cầu chức năng")*:
  - Bôi đen tiêu đề → thẻ **Home** → chọn **Heading 1** (phím tắt `Ctrl + Alt + 1`).
- **Heading 2** *(cho mục con như "2.1 Yêu cầu người dùng", "2.2 Yêu cầu hệ thống")*:
  - Bôi đen mục con → thẻ **Home** → chọn **Heading 2** (phím tắt `Ctrl + Alt + 2`).

### Bước 3: Chèn Bảng mục lục tự động (Auto TOC)
1. Đặt con trỏ chuột tại vị trí cần chèn mục lục.
2. Chọn thẻ **References** → **Table of Contents** → Chọn mẫu **Automatic Table 1** hoặc **Automatic Table 2**.

### Bước 4: Cập nhật Bảng mục lục khi có thay đổi
- Nhấp chuột vào bảng mục lục → Chọn **Update Table...** (hoặc chọn bảng và nhấn phím `F9`):
  - **Update page numbers only:** Chỉ cập nhật lại số trang (khi chỉnh sửa nội dung).
  - **Update entire table:** Cập nhật toàn bộ tiêu đề và số trang (khi thêm/bớt/đổi tên mục).
