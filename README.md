# Locket Gold TLoc 💛

Trang web chính thức: https://tanlocnguyen910-ship-it.github.io/locket-gold-tloc/

## Tính năng cửa hàng (Khách hàng)
- **Bước 1 - Tra cứu tài khoản Locket:** Nhập username hoặc link Locket để kiểm tra thông tin tài khoản.
- **Bước 2 - Chọn gói Locket Gold & Tuỳ chọn:** Chọn ngày tham gia (`memberSinceDate`), gói nâng cấp (6 gói: Dùng Thử, Thường 3 Tháng, Thường 8 Tháng, VIP 1 Năm, VIP Vĩnh Viễn, Android APK) và áp dụng mã giảm giá (nếu có).
- **Bước 3 - Thanh toán & Hỗ trợ:** Chuyển khoản / MoMo qua `0948344850` (Nguyễn Đức Tấn Lộc) với nội dung `TLOC LOCKET` hoặc liên hệ Zalo hỗ trợ.
- **Bước 4 - Kích hoạt & Nhận link cài đặt DNS:** Nhấn kích hoạt để nhận link cài đặt cấu hình DNS (`/g/<slug>`).

## Bảng điều khiển Quản trị CTV / Chủ Web (API v1)
- **Cấu hình API CTV v1:** Nhập Base URL (`https://uplocket.io.vn`) và `LOCKET_API_KEY` (lưu trên trình duyệt) để tải dữ liệu.
- **Theo dõi hệ thống:** Kiểm tra số dư & lượt kích hoạt (`GET /api/v1/credits`) và danh sách hồ sơ DNS (`GET /api/v1/dns/activations?limit=50`).
- **Quản lý giá & khuyến mãi:** Tùy chỉnh giá bán lẻ 6 gói đối chiếu `minRetailPrice` và tạo mã giảm giá (%).
