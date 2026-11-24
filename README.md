# Góc Lưu Trữ Comm (Bản v4 — Đăng nhập & Chỉnh tên Creator)

## Tính năng mới ở bản v4
- **Đăng nhập / Đăng ký tài khoản (Supabase Auth):**
  - Khách chưa đăng nhập chỉ xem được thư viện, lọc, mở link và copy link.
  - Creator đăng nhập xong mới thấy nút **+ Thêm Comm**, **Sửa / Xóa** thẻ và chỉnh sửa giao diện trang.
- **Chỉnh tên Creator:**
  - Bấm vào tên/avatar của bạn ở góc trên phải để mở **Hồ sơ Creator**, đổi tên Creator và link avatar bất cứ lúc nào.
  - Có tùy chọn tự động đổi luôn tên Creator trên các comm cũ bạn đã đăng.
  - Bộ lọc Creator phía trên thư viện tự cập nhật theo tên Creator mới.

## Cập nhật lên GitHub, Vercel & Supabase
1. Giải nén file `.zip` để lấy `index.html` và đẩy đè lên GitHub (Vercel tự cập nhật sau 10–30 giây).
2. Mở web → bấm **☁ Supabase** → copy đoạn SQL mới chạy lại 1 lần trong **SQL Editor** trên Supabase để thêm cột `creator_name`, `user_id` và bật quyền chỉ người đăng nhập mới được sửa/xóa.
3. Trên Supabase, vào **Authentication → Providers → Email** (tắt *Confirm email* nếu bạn muốn đăng ký xong vào luôn không cần bấm link xác nhận mail).
