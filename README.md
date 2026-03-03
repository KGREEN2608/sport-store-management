# 🏪 HỆ THỐNG QUẢN LÝ CỬA HÀNG THỂ THAO

## 📌 Giới thiệu dự án

Đây là dự án học tập thuộc môn **Công nghệ Phần mềm**, tập trung vào:

- Phân tích yêu cầu hệ thống
- Thiết kế test case
- Thực hiện Manual Testing
- Kiểm thử luồng nghiệp vụ bán hàng

Hệ thống mô phỏng phần mềm quản lý cửa hàng thể thao với các chức năng thực tế như quản lý sản phẩm, nhân viên, đơn hàng và thống kê doanh thu.

---

## 🎯 Mục tiêu đạt được

- Phân tích yêu cầu từ góc nhìn người dùng
- Thiết kế test case dựa trên nghiệp vụ thực tế
- Thực hiện kiểm thử chức năng (Functional Testing)
- Báo cáo và theo dõi lỗi
- Hiểu quy trình phát triển phần mềm (SDLC)

---

## 🛠 Công nghệ sử dụng

- **Ngôn ngữ:** C#
- **Framework:** .NET MVC
- **Database:** SQL Server
- **IDE:** Visual Studio
- **Testing:** Manual Testing

---

# 🖥 Giao diện & Chức năng hệ thống

---

## 🔐 1. Màn hình Đăng nhập

![Đăng nhập](https://drive.google.com/uc?export=view&id=1n31KOL71R228hGyeMOhRIEItz1Sz95jY)

**Mô tả:**
- Xác thực Email và Mật khẩu
- Phân quyền người dùng (Admin / Nhân viên)
- Validate dữ liệu đầu vào

---

## 🏠 2. Trang Home

![Home](https://drive.google.com/uc?export=view&id=1TNdrSq6EWU8M5XzM-eUXuOChN-k_z0xX)

**Mô tả:**
- Giao diện chính sau khi đăng nhập
- Thanh menu điều hướng các chức năng
- Thiết kế trực quan, dễ sử dụng

---

## 👨‍💼 3. Quản lý nhân viên

![Quản lý nhân viên](https://drive.google.com/uc?export=view&id=11BqEyUCNorMgqdyjdoiauB_gSu4oS7_n)

**Chức năng:**
- Thêm / Sửa / Xóa nhân viên
- Tìm kiếm theo tên
- Quản lý cấp bậc & lương
- Phân quyền hệ thống

---

## 📦 4. Danh sách sản phẩm

![Danh sách sản phẩm](https://drive.google.com/uc?export=view&id=1Cjintlz2Ec6L44KJvyETMJXz8xy1rqxv)

**Chức năng:**
- Hiển thị danh sách sản phẩm
- Tìm kiếm theo tên
- Quản lý tồn kho
- Xem chi tiết sản phẩm

---

## ➕ 5. Thêm sản phẩm

![Thêm sản phẩm](https://drive.google.com/uc?export=view&id=1jXZja1kkHrKR7u4f7oEUCHOI5sR79wrT)

**Chức năng:**
- Nhập thông tin sản phẩm
- Upload hình ảnh
- Chọn loại hàng, hãng sản xuất
- Thiết lập bảo hành & số lượng

---

## ✏️ 6. Sửa sản phẩm

![Sửa sản phẩm](https://drive.google.com/uc?export=view&id=1idHbuq-9NWbdeGRcqvgeZzxXtUEojQLE)

**Chức năng:**
- Cập nhật thông tin sản phẩm
- Thay đổi giá, tồn kho
- Xem trước hình ảnh

---

## 🧾 7. Quản lý đơn hàng

![Quản lý đơn hàng](https://drive.google.com/uc?export=view&id=1ORoX4kit5jG5xKMkJ4zb1DAf7EESSYf1)

**Chức năng:**
- Danh sách hóa đơn
- Tìm kiếm theo khách hàng
- Xem chi tiết đơn hàng
- Xóa đơn hàng

---

## 📄 8. Chi tiết hóa đơn

![Chi tiết hóa đơn](https://drive.google.com/uc?export=view&id=1CqpaLdIK7VBh_HmvQQtgcrQNsvRrzeSZ)

**Mô tả:**
- Hiển thị danh sách sản phẩm trong hóa đơn
- Số lượng & đơn giá
- Tổng tiền thanh toán

---

## 🧾 9. Bill xuất PDF

![Bill](https://drive.google.com/uc?export=view&id=1vBq01yK6bBa2TKYxEx0WjCSKSpet4nO-)

**Mô tả:**
- Xuất hóa đơn dạng PDF
- Thông tin khách hàng & nhân viên
- Danh sách sản phẩm
- Tổng thanh toán

---

## 📊 10. Tổng doanh thu

![Tổng doanh thu](https://drive.google.com/uc?export=view&id=1vdJnYOUCWukGClNTCPS1padLJPKJW65u)

**Chức năng:**
- Thống kê doanh thu
- Top sản phẩm bán chạy
- Tình trạng tồn kho
- Phần trăm khuyến mãi

---

## 💳 11. Thanh toán QR Code

![QR Code](https://drive.google.com/uc?export=view&id=16qjF5tJyIE7PI0xIRpDfDXVywT7aCP7i)

**Mô tả:**
- Tạo mã QR thanh toán
- Hỗ trợ thanh toán điện tử
- Tích hợp ví điện tử

---

# 🧪 Phạm vi kiểm thử

- Phân tích yêu cầu chức năng
- Thiết kế Test Case
- Kiểm thử:
  - Login validation
  - CRUD sản phẩm
  - CRUD nhân viên
  - Luồng tạo đơn hàng
  - Tính toán tổng tiền
  - Xuất hóa đơn PDF
  - Kiểm tra thống kê doanh thu
- Ghi nhận và báo cáo lỗi

---

# 🔑 Tài khoản demo

**Admin**  
Email: admin@example.com  
Password: admin123  

**Nhân viên**  
Email: staff@example.com  
Password: staff123  

---

# 🚀 Hướng dẫn chạy dự án

1. Import file `databaseSql.sql` vào SQL Server
2. Mở solution bằng Visual Studio
3. Build project
4. Run chương trình

---

# 👤 Tác giả

**Nguyễn Minh Khang**  
Fresher QA / Manual Tester  

**Nguyễn Tấn Phát**  
Developer  

---
