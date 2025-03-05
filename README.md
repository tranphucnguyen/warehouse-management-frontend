# Quản Lý Kho - Frontend

Đây là dự án giao diện người dùng cho hệ thống quản lý kho hàng, giúp quản lý hàng hóa, theo dõi nhập xuất kho và cung cấp báo cáo tồn kho.

## Mục lục

- [Chức năng chính](#chức-năng-chính)
- [Công nghệ sử dụng](#công-nghệ-sử-dụng)
- [Yêu cầu hệ thống](#yêu-cầu-hệ-thống)
- [Hướng dẫn cài đặt và chạy dự án](#hướng-dẫn-cài-đặt-và-chạy-dự-án)
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

## Hướng dẫn cài đặt và chạy dự án

1. **Clone kho lưu trữ:**

   ```bash
   git clone https://github.com/tranphucnguyen/quanlykho-frontend.git
   ```



2. **Di chuyển vào thư mục dự án:**

   ```bash
   cd quanlykho-frontend
   ```



3. **Cài đặt các phụ thuộc:**

   Nếu bạn sử dụng npm:

   ```bash
   npm install
   ```



   Hoặc nếu bạn sử dụng yarn:

   ```bash
   yarn install
   ```



4. **Cấu hình môi trường:**

   Tạo tệp `.env` trong thư mục gốc và thêm các biến môi trường cần thiết. Ví dụ:

   ```env
   REACT_APP_API_URL=http://localhost:5000/api
   ```



5. **Chạy ứng dụng:**

   Nếu bạn sử dụng npm:

   ```bash
   npm start
   ```



   Hoặc nếu bạn sử dụng yarn:

   ```bash
   yarn start
   ```



6. **Truy cập ứng dụng:**

   Mở trình duyệt và truy cập `http://localhost:3000`.

## Cấu trúc thư mục

Dưới đây là cấu trúc thư mục chính của dự án:

```

quanlykho-frontend/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── App.js
│   └── index.js
├── .env
├── package.json
└── README.md
```



- **public/**: Chứa các tệp tĩnh và tệp HTML chính.
- **src/**: Chứa mã nguồn chính của ứng dụng.
  - **assets/**: Chứa hình ảnh, biểu tượng và các tệp tĩnh khác.
  - **components/**: Chứa các thành phần giao diện dùng chung.
  - **pages/**: Chứa các trang của ứng dụng.
  - **services/**: Chứa các tệp liên quan đến gọi API và xử lý logic.
  - **App.js**: Tệp chính của ứng dụng React.
  - **index.js**: Điểm vào của ứng dụng React.
