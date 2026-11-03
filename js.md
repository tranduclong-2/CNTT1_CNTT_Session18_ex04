# Bài 4: Sự cố xung đột phiên đăng nhập trên trình duyệt

## Phần 1. Phân tích
- Incognito Mode: Chế độ ẩn danh, dữ liệu duyệt web sẽ bị xóa sau khi đóng cửa sổ.
- Dedicated Profile: Hồ sơ riêng, lưu lại tài khoản, mật khẩu, Bookmark và lịch sử duyệt web.
Kết luận: Nên sử dụng 3 Profile riêng biệt để tránh xung đột tài khoản.

## Phần 2. Triển khai

### 1. Tạo 3 Profile:
- Personal: Tài khoản cá nhân.
- Work: Tài khoản công việc GreenLog.
- Sandbox: Tài khoản kiểm thử.

### 2. Đồng bộ Cloud Sync:
- Đăng nhập tài khoản Google.
- Bật tính năng đồng bộ hóa.
- Chọn đồng bộ Bookmark và dữ liệu cần thiết.
- Đăng nhập trên máy tính khác để khôi phục dữ liệu.

### 3. Tạo thư mục Bookmark:
Bookmarks
├── Personal
├── Work
│   ├── GitHub
│   ├── Canvas LMS
│   └── GreenLog Portal
└── Sandbox


## Phần 3. Kiểm thử
Khi sử dụng máy tính công cộng:
- Sử dụng Guest Profile.
- Không lưu mật khẩu.
- Không đăng nhập tài khoản cá nhân nếu không cần thiết.
- Đăng xuất sau khi sử dụng.
- Đóng trình duyệt khi hoàn thành.
Kết luận: Sử dụng các Profile riêng biệt giúp quản lý tài khoản dễ dàng và hạn chế rủi ro lộ thông tin.
