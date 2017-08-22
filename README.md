### Yêu cầu dự án
#### 1. Trang tin điện tử 
1. Trang Web với khoảng 11 chuyên mục (Thời sự, Kinh Tế, Giáo Dục, …)
- Hiển thị tối ưu trên mọi thiết bị, từ PC, laptops, tablets, smartphones
- Tối ưu với công cụ tìm kiếm Google, và chia sẻ trên Facebook

#### 2. Phần mềm quản lý nội dung 
1. Cho phép xuất nội dung ra giao diện 2 website khác nhau (bổ sung thêm website mới thì tính phí phát sinh dựa theo nội dung trong phụ lục) 
- Cho phép quản lý nội dung  phân quyền cho nhiều cấp theo quy trình đăng tin: nhập bài, duyệt bài, đăng bài …
- Gửi thông báo khi có thông tin mới cho các thành viên liên quan (để duyệt hoặc đăng bài, …)
- Lưu trữ lịch sử thay đổi, cho phép truy vết các nội dung thay đổi khi cần
- Thống kê số lượng truy cập theo từng bài
- Quản lý tác giả: nhuận bút
- Cho phép mở rộng sau này để quản lý nội dung cho các chuyên trang nằm ở các tên miền khác.

#### 3. Tính năng Phân quyền và Bảo mật
1. Trang tin cho phép đáp ứng lượng truy cập lớn 
- Bảo mật tốt, có cơ chế hạn chế khi bị tấn công
- Phân quyền truy cập vào phần quản lý nội dung 
- Bảo mật hệ thống quản lý thông tin nội bộ, không bị truy cập đăng bài trái phép

## Giải pháp thực hiện

### Front: sử dụng EasyWeb để thực hiện
- xây dựng giao diện
- nhập các bài viết ban đầu

### Admin: Aurelia 
- trang quản trị users
- quản trị nội dung bài viết, tạo mới, edit, tìm kiếm

### API backend: loopback

### Ngân sách dự trù: 15 triệu

- Front: 3 triệu
- Admin: 5 triệu
- API back-end 7 triệungân 

#### Giải ngân
- Demo Prototype: 40%
- Hoàn chỉnh: 40%
- Sau 1 tháng triển khai: 20%
