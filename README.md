# Jewelry Store Management System (Hệ Thống Quản Lý Cửa Hàng Trang Sức)

Dự án thiết kế cơ sở dữ liệu **Hệ thống Quản lý Cửa hàng Trang sức** cho học phần **Thực hành Cơ sở dữ liệu (IT3290)** tại **Trường Công nghệ Thông tin & Truyền thông - Đại học Bách khoa Hà Nội**.

## 👥 Thành Viên Thực Hiện (Nhóm 11)
* Quách Nguyễn Quỳnh Anh
* Nguyễn Nhật Linh
* Đinh Xuân Thanh

## 📐 Sơ Đồ Thực Thể & Quan Hệ (ERD)
Hệ thống sử dụng sơ đồ quan hệ thực thể bao gồm các mối quan hệ giữa `CUSTOMERS`, `ORDERS`, `PRODUCTS` và thực thể trung gian `ORDER_ITEMS` cùng thực thể quản trị `USERS`.

## ⚡ Các Tính Năng Nổi Bật Bằng PL/pgSQL
* Triggers tự động: Chuẩn hóa số điện thoại, kiểm tra hàng tồn kho trước khi xuất bán, tự động trừ/hoàn trả kho, tự động cộng dồn tổng tiền hóa đơn, và tự động nâng hạng khách hàng VIP dựa trên chi tiêu tích lũy.
* Hàm nghiệp vụ: Tìm sản phẩm bán chậm, tự động tăng/giảm giá bán hàng loạt theo mức tồn kho, cảnh báo số lượng đơn hàng bị hủy vượt ngưỡng và lọc đối tượng tiếp thị marketing tiềm năng.
