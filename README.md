# Phân tích thiết kế hệ thống thông tin nâng cao - IS6301.CH18
### GVHD: TS. Cao Thị Nhạn

* Học viên thực hiện:
1. **Đỗ Trung Thuận - 230104025@grad.uit.edu.vn**
2. **Nguyễn Trần Hoàng Hiếu - 230104013@grad.uit.edu.vn**
   
## Mục tiêu cụ thể:
1. Giúp khách hàng mua hàng có thể mua thông qua trang chủ trực tuyến. Xem sản phẩm và giá thành cũng như các ưu đãi khác.
2. Giúp chủ doanh nghiệp có thể theo dõi chi tiết các đơn hàng của mình. Quản lý toàn bộ đơn hàng từ khách hàng.
3. Giúp chủ doanh nghiệp có thể dự đoán được các đơn hàng là đơn ảo hay đơn thật.

## Mô hình chức năng chính:
### 1. Người dùng:
- Người có nhu cầu mua sắm thời trang tại ThuanHieu.
- Người quản lý các đơn hàng của ThuanHieu.
### 2. Dữ liệu và công nghệ:
- Dữ liệu: Thu thập từ các trang google và dữ liệu nội bộ của thành viên trong nhóm.
- Công nghệ áp dụng: ASP.Net MVC.
### 3. Các module chính:
#### 3.1 Khách hàng:
- Tìm kiếm/xem/tra cứu thông tin sản phẩm.
- Thêm các sản phẩm vào giỏ hàng.
- Đăng Ký.
- Xác nhận Email khi đăng ký.
- Lấy lại mật khẩu bằng Email.
- Đăng Nhập.
- Mua Hàng.
- Gửi mail khi thanh toán thành công.
- Xem Tin Tức.
#### 3.2 Admin:
- Quản lý đơn hàng (Xóa, sửa).
- Xem báo cáo về dự đoán về đơn hàng (đơn ảo hay thật).
#### 4. Hệ thống:
- Sau khi nhận được thông tin về đơn hàng của khách mua hàng, hệ thống sẽ tự động chạy thuật toán (máy học và AI) để đưa ra khuyến nghị liệu đơn hàng này có phải là đơn ảo hay không.
