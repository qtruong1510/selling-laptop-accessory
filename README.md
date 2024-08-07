# Website Bán Linh Kiện Máy Tính

## Mô Tả Dự Án

Dự án này là một website bán linh kiện máy tính, cung cấp cho người dùng khả năng tìm kiếm, xem và mua các sản phẩm linh kiện máy tính. Trang web được thiết kế với giao diện thân thiện, dễ sử dụng và có tính năng quản lý người dùng, sản phẩm, giỏ hàng và các chức năng quản trị khác.

## Công Nghệ Sử Dụng

### Front-end:
- **HTML**: Ngôn ngữ đánh dấu chuẩn để xây dựng giao diện người dùng.
- **CSS**: Được sử dụng để tạo kiểu dáng và bố cục cho trang web.
- **JavaScript**: Ngôn ngữ lập trình phía client để tạo ra các tương tác động trên trang web.
- **Thymeleaf**: Công cụ templating engine được tích hợp trong Spring Boot để kết xuất các trang HTML với dữ liệu từ back-end.
- **Bootstrap**: Framework CSS phổ biến giúp tạo ra giao diện responsive và hiện đại.

### Back-end:
- **Java Spring Boot**: Framework giúp phát triển ứng dụng web một cách nhanh chóng và hiệu quả, cung cấp các tính năng như quản lý phiên làm việc, bảo mật, và kết nối cơ sở dữ liệu.
- **Maven**: Công cụ quản lý dự án và phụ thuộc, giúp đơn giản hóa quá trình build và quản lý các thư viện bên ngoài.

### Cơ sở dữ liệu:
- **MySQL Workbench**: Công cụ quản lý cơ sở dữ liệu MySQL, được sử dụng để thiết kế và quản lý cơ sở dữ liệu của dự án.

## Các Tính Năng Chính

- **Quản lý người dùng**: Đăng ký, đăng nhập, quản lý thông tin cá nhân, thay đổi mật khẩu.
- **Quản lý sản phẩm**: Xem danh sách sản phẩm, tìm kiếm, xem chi tiết sản phẩm.
- **Giỏ hàng**: Thêm sản phẩm vào giỏ hàng, xem giỏ hàng, cập nhật số lượng sản phẩm, thanh toán.
- **Quản trị**: Thêm, sửa, xóa sản phẩm, quản lý danh mục, quản lý đơn hàng, quản lý người dùng.

## Cài Đặt

1. Clone dự án từ repository:
   ```bash
   git clone <repository-url>

2. Cấu hình cơ sở dữ liệu trong file "application.properties":
    spring.datasource.url=jdbc:mysql://localhost:3306/tên_database
    spring.datasource.username=tên_người_dùng
    spring.datasource.password=mật_khẩu
    spring.jpa.hibernate.ddl-auto=update
3. Build dự án bằng Maven:
    mvn clean install
4. Chạy ứng dụng:
    mvn spring-boot:run
5. Truy cập trang web tại: "http://localhost:8080"


## Tác giả
- Nguyễn Quang Trường