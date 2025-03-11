# Giao diện Frontend - Quản lý Kho

## 1. Giới thiệu

Dự án **Giao diện Frontend Quản lý Kho** được phát triển dựa trên template **AdminLTE**, cung cấp một hệ thống quản lý kho hàng hiện đại, dễ sử dụng với các tính năng:

- Quản lý sản phẩm, đơn hàng, nhà cung cấp, nhân viên.
- Theo dõi báo cáo thống kê trực quan.
- Cập nhật trạng thái đơn hàng và thông tin kho.

## 2. Công nghệ sử dụng

- **Template**: [AdminLTE](https://adminlte.io/) - Một giao diện quản trị phổ biến dựa trên Bootstrap.
- **HTML, CSS, JavaScript**: Xây dựng và định dạng giao diện người dùng.
- **jQuery, AJAX**: Xử lý yêu cầu bất đồng bộ, cập nhật dữ liệu không cần tải lại trang.
- **Bootstrap**: Tối ưu responsive và thiết kế giao diện thân thiện.

## 3. Tính năng chính

### a. Dashboard (Bảng điều khiển)

- Hiển thị tổng quan về kho hàng: số lượng sản phẩm, đơn hàng, doanh thu.
- Biểu đồ thống kê nhập - xuất hàng.
- Danh sách đơn hàng mới nhất.

### b. Quản lý Sản phẩm

- Xem danh sách sản phẩm (mã sản phẩm, tên, số lượng tồn kho, giá nhập, giá bán).
- Chức năng thêm, sửa, xóa sản phẩm.
- Tìm kiếm và lọc sản phẩm theo danh mục.

### c. Quản lý Đơn hàng

- Xem danh sách đơn hàng (mã đơn hàng, khách hàng, trạng thái, tổng tiền).
- Xem chi tiết và cập nhật trạng thái đơn hàng (Đang xử lý, Hoàn thành, Đã hủy).

### d. Quản lý Nhà cung cấp

- Xem danh sách nhà cung cấp và thông tin liên hệ.
- Thêm, sửa, xóa nhà cung cấp.
- Tìm kiếm nhà cung cấp.

### e. Quản lý Nhân viên

- Quản lý danh sách nhân viên và quyền hạn.
- Thêm, sửa, xóa nhân viên.
- Phân quyền truy cập theo chức năng.

### f. Báo cáo

- Thống kê nhập - xuất kho theo khoảng thời gian.
- Biểu đồ doanh thu, chi phí.
- Xuất báo cáo dưới dạng **Excel** hoặc **PDF**.

## 4. Hướng dẫn cài đặt

1. **Clone dự án về máy**:

```bash
git clone https://github.com/your-repo/quanlykho.git
```

2. **Chuẩn bị môi trường**:

- Đảm bảo máy tính có trình duyệt (Chrome, Firefox, Edge,...) để chạy file HTML.

3. **Chạy ứng dụng**:

- Mở thư mục chứa dự án và tìm đến file `index.html`.
- Nhấp đúp chuột vào file `index.html` để mở trên trình duyệt hoặc dùng lệnh sau để chạy bằng VSCode:

```bash
code .
```

4. **Truy cập ứng dụng**:

- Ứng dụng sẽ mở tại địa chỉ:

```bash
http://localhost:5500
```

## 5. Ghi chú

- Giao diện có thể được tùy chỉnh theo yêu cầu thực tế.
- Đảm bảo backend hỗ trợ các API phù hợp để frontend hoạt động mượt mà.
- Có thể tích hợp thêm các thư viện như **DataTables**, **SweetAlert** để nâng cao trải nghiệm người dùng.

## 6. Đường link dẫn tới GitHub Back-end

[Đường link GitHub Back-end](https://github.com/boypro5235/warehouse-management-backend.git).

## 7. Liên hệ

Nếu có bất kỳ thắc mắc hoặc đóng góp nào, vui lòng liên hệ qua email: [bit220123@st.cmcu.edu.vn](mailto:bit220123@st.cmcu.edu.vn).
