# Quản Lý Kho - Frontend

Đây là dự án giao diện người dùng cho hệ thống quản lý kho hàng, giúp quản lý hàng hóa, theo dõi nhập xuất kho và cung cấp báo cáo tồn kho.

## Mục lục

- [Chức năng chính](#chức-năng-chính)
- [Công nghệ sử dụng](#công-nghệ-sử-dụng)
- [Yêu cầu hệ thống](#yêu-cầu-hệ-thống)
- [Cấu trúc thư mục](#cấu-trúc-thư-mục)

## Chức năng chính

- **Quản lý hàng hóa:** Thêm, sửa, xóa và xem thông tin chi tiết về hàng hóa.
- **Quản lý nhập kho:** Tạo và quản lý các phiếu nhập hàng từ nhà cung cấp.
- **Quản lý xuất kho:** Tạo và quản lý các phiếu xuất hàng cho khách hàng.
- **Quản lý nhà cung cấp:** Thêm, sửa, xóa và xem thông tin nhà cung cấp.
- **Quản lý khách hàng:** Thêm, sửa, xóa và xem thông tin khách hàng.
- **Báo cáo:** Xem báo cáo tồn kho, lịch sử nhập xuất và các báo cáo liên quan khác.
- **Quản lý người dùng:** Phân quyền và quản lý thông tin người dùng hệ thống.

## Công nghệ sử dụng

- HTML5, CSS3, JavaScript
- [Tên framework hoặc thư viện JavaScript, ví dụ: React.js, Vue.js, Angular]
- [Các công nghệ hoặc thư viện khác, ví dụ: Bootstrap, Axios]

## Yêu cầu hệ thống

- Node.js phiên bản 14.x trở lên
- Trình quản lý gói npm hoặc yarn
- Trình duyệt web hiện đại (Chrome, Firefox, Safari, Edge)

## Cấu trúc thư mục

Dưới đây là cấu trúc thư mục chính của dự án:

```

quanlykho-frontend/
├── public/
│   ├── dist/
│      ├── css/
│      ├── img/
│      └── js/
├── pages/
│   ├── lichsugiaohang/
│   ├── quanlygiaohang/
│   ├── quanlyhanghoa/
│   ├── quanlykho/
│   ├── quanlynguoidung/
│   └── quanlyphieu/
├── plugins/
├── dashboard.html
└── login.html
```



- **dist/**: Chứa các css, hình ảnh và js chính.
- **pages/**: Chứa các tệp tĩnh và tệp HTML chính.
  - **lichsugiaohang/**: Chứa hình ảnh, biểu tượng và các tệp tĩnh khác.
  - **quanlygiaohang/**: Chứa các thành phần giao diện dùng chung.
  - **quanlyhanghoa/**: Chứa các trang của ứng dụng.
  - **quanlykho/**: Chứa các tệp liên quan đến gọi API và xử lý logic.
  - **quanlynguoidung/**: Tệp chính của ứng dụng React.
  - **quanlyphieu/**: Điểm vào của ứng dụng React.
