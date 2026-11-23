# Góc Lưu Trữ Comm (GitHub Pages)

## Cách đưa web lên GitHub Pages (3 phút)
1. Giải nén file `.zip` này ra để lấy file `index.html`.
2. Vào GitHub -> tạo một Repository mới (chọn chế độ **Public**).
3. Bấm **Add file** -> **Upload files** -> kéo thả file `index.html` vào rồi bấm **Commit changes**.
4. Vào tab **Settings** -> mục **Pages** (cột bên trái) -> ở phần **Branch**, chọn `main` và thư mục `/ (root)` -> bấm **Save**.
5. Đợi 1–2 phút, GitHub sẽ hiện link dạng `https://ten-cua-ban.github.io/ten-repo/`.

## Cách đồng bộ dữ liệu giữa 2 người
- **Mặc định (không cần cài thêm gì):** Dữ liệu lưu trên trình duyệt của từng máy. Có thể bấm nút **Sync -> Xuất/Nhập file JSON** để gửi qua lại.
- **Muốn 2 người cùng thêm/sửa thấy liền:** Tạo 1 project miễn phí trên [Supabase](https://supabase.com), chạy đoạn SQL có sẵn trong nút **☁ Sync** trên web, sau đó dán `Project URL` và `Anon Key` vào là xong.
