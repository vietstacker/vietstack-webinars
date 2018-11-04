## CÁC THỨ CẦN CHUẨN BỊ

* Laptop (để chạy được devstack mượt mà thì máy nên có từ 16GB RAM) và kết nối Internet ổn định.
* Nếu bạn quyết định xài máy ảo bạn có thể download file máy ảo đã được chuẩn bị sẵn này về 
  chạy với VirtualBox (file này lấy từ Upstream Institute ở OpenStack Summit Vancouver tháng 5
  vừa rồi): http://bit.ly/vm-2018-vancouver-v1
* Nếu bạn muốn tự tạo máy ảo từ đầu:
  * Tạo một máy ảo chạy Ubuntu 16.04 với > 6GB RAM.
  * Ngoài ra bạn có thể xài máy ảo tạo trên các dịch vụ cloud như Digital Ocean, AWS, Microsoft Azuze v.v.
  * Kiểm tra xem bạn đã có kết nối SSH được với máy ảo đó từ laptop chưa.

## NỘI DUNG

* Cài đặt môi trường phát triển
* Giới thiệu về cách OpenStack đang được vận hành
  * Cách OpenStack được điều hành
  * Chu kì release phiên bản mới của OpenStack
  * Cách thức mà các team dự án OpenStack giao tiếp
  * Cài đặt IRC
  * Các sự kiện của OpenStack
* Workflow và các công cụ cần thiết
  * Thiết lập các tài khoản
  * Sơ lược về quy trình đóng góp
  * Cách theo dõi task
  * Cài đặt git và thông điệp ghi vào commit của bạn
  * Cấu hình Gerrit
  * Sử dụng Gerrit để review code
