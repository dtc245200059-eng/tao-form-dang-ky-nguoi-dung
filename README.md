# [Bài tập] Tạo Giao Diện Form Đăng Ký Người Dùng

Bài thực hành tạo form đăng ký người dùng với HTML5 & CSS3 theo tiêu chuẩn giáo trình CodeGym.

---

## 📋 Yêu cầu bài tập

Tạo một form đăng ký người dùng gửi dữ liệu lên một website đã được chuẩn bị sẵn ở phía server:
- **Địa chỉ gửi dữ liệu (Action)**: `http://demo.codegym.vn/6/registration_form/register.php`
- **Phương thức (Method)**: `POST` (Bắt buộc)
- **Các trường dữ liệu**:
  - Trường “Họ và tên”: `name="name"`
  - Trường “Email”: `name="email"`
  - Trường “Số điện thoại”: `name="phone"`
  - Trường “Giới tính”: `name="gender"` (Radio button: Nam, Nữ, Khác)
- **Các nút chức năng**:
  - Nút “Đăng ký”: Submit form
  - Nút “Nhập lại”: Reset form

> **Lưu ý**: Bài tập này sử dụng một địa chỉ máy chủ mẫu để thực hành cách gửi dữ liệu bằng `POST`. Đây là endpoint thử nghiệm của bài học và có thể không còn hoạt động hoặc trả về lỗi Not Found do máy chủ đã thay đổi/ngừng cung cấp. Form đã khai báo chính xác `action`, `method="POST"` và `name` theo đúng yêu cầu đề bài.

---

## 📁 Cấu trúc thư mục

```text
├── index.html        # Mã nguồn giao diện Form đăng ký người dùng
└── README.md         # Hướng dẫn chi tiết bài thực hành
```

---

## 🚀 Hướng dẫn mở và kiểm tra bài làm

1. Mở file [index.html](index.html) trực tiếp bằng trình duyệt web (Google Chrome, Microsoft Edge, Firefox,...).
2. Nhập đầy đủ thông tin: Họ và tên, Email, Số điện thoại và chọn Giới tính.
3. Nhấn nút **Đăng ký** để gửi thông tin qua phương thức `POST` lên server CodeGym demo.
4. Nhấn nút **Nhập lại** để xóa trắng dữ liệu đã nhập về mặc định.
