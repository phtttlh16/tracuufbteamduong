# Team Dương Tra Cứu — GitHub Pages

## Đưa website lên GitHub
1. Tạo repository mới trên https://github.com/ (ví dụ `team-duong-tra-cuu`).
2. Giải nén ZIP này trên máy tính.
3. Mở repository → **Add file** → **Upload files**.
4. Tải lên `index.html` và thư mục `docs` (không tải file ZIP nguyên bản).
5. Bấm **Commit changes**.
6. Vào **Settings → Pages**.
7. Chọn **Deploy from a branch**, branch `main`, folder `/(root)`, rồi **Save**.
8. Chờ GitHub triển khai. Địa chỉ thường là `https://TEN-GITHUB.github.io/team-duong-tra-cuu/`.

## Ghi chú
Website hiện là giao diện tĩnh để duyệt tài liệu. Nó chưa thực hiện yêu cầu Facebook API. Muốn kết nối API thật cần backend, ứng dụng Meta, quyền/đánh giá phù hợp và bảo vệ token ở máy chủ. Không đưa access token, cookie hay App Secret vào `index.html` hoặc repository công khai.
