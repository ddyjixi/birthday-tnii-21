# TNii’s Retro Birthday Scrapbook 🎂

Website chúc sinh nhật tương tác, chạy bằng HTML/CSS/JavaScript thuần. Không cần npm, backend, database, tài khoản hay API key.

## Xem web trên máy
Mở `index.html` trong Chrome/Edge/Firefox. Hoặc sử dụng VS Code + Live Server.

## Phiên bản dành cho Thủy Nhi (TNii)
- Ngày sinh: 15/10/2005; sinh nhật 21 tuổi: 15/10/2026.
- Cung hoàng đạo theo ngày sinh: Thiên Bình ♎.
- Hãy thay chữ ký người gửi và thêm ảnh kỷ niệm thật trước khi gửi.

## Thay nội dung
Mở `index.html`, tìm `const CONFIG = {` gần cuối file:
- `recipient`: tên người được chúc
- `sender`: tên bạn
- `letter`: toàn bộ nội dung bức thư; giữ dấu backtick bao quanh
- `photos`: sửa `title`, `description`, `photo` cho 3 kỷ niệm
- `gifts`: 3 câu trả lời khi mở quà

## Thêm ảnh
1. Tạo thư mục `photos` cạnh `index.html`.
2. Chép ảnh vào thư mục, ví dụ `photos/anh-1.jpg`.
3. Sửa `photo:''` thành `photo:'photos/anh-1.jpg'` ở ảnh tương ứng.
4. Nên nén ảnh dưới 1 MB mỗi tấm để tải nhanh trên điện thoại.

## Đưa lên mạng miễn phí (Netlify Drop)
1. Vào https://app.netlify.com/drop
2. Kéo cả thư mục `retro-birthday` (chứa `index.html` và `photos`, nếu có) vào vùng upload.
3. Lấy URL `*.netlify.app` được tạo và gửi bạn thân.
4. Khi chỉnh web, deploy thư mục lại. Tính năng và hạn mức gói miễn phí có thể thay đổi theo Netlify.

## GitHub Pages
Đưa `index.html` và `photos/` vào một repository, vào Settings → Pages, chọn deploy từ nhánh `main`/root. Web sẽ có URL dạng `https://username.github.io/repository/`.

## Lưu ý
- Nội dung được lưu trên web công khai, đừng dùng ảnh hoặc lời nhắn riêng tư nếu chưa được đồng ý.
- Trang dùng Google Fonts; khi không có mạng font sẽ tự thay bằng font sẵn có.
- Không có nhạc tự phát, mic hay quyền truy cập thiết bị. Thổi nến bằng nút chạm, chạy được trên điện thoại.
