# Cài GitHub Profile README

Thư mục này đã được cá nhân hóa cho tài khoản `ekancisme`.

## Cách cài nhanh

1. Trên GitHub, tạo repository public tên chính xác là `ekancisme`. Nếu repo này đã tồn tại, mở repo đó.
2. Tải toàn bộ nội dung trong thư mục này lên root của repository, giữ nguyên hai thư mục `assets` và `.github`.
3. Vào **Settings → Actions → General → Workflow permissions**, chọn **Read and write permissions**, rồi Save.
4. Mở tab **Actions** và chạy thủ công hai workflow lần đầu:
   - Generate contribution arcade
   - Generate 3D contribution calendar
5. Chờ workflow hoàn tất rồi tải lại `https://github.com/ekancisme`.

## Hiệu ứng đã dùng

- SVG tự thiết kế: gradient chuyển màu, glow, hạt bay, lưới trượt, viền chạy, terminal cursor, bánh răng xoay và wave.
- Typing SVG luân phiên nhiều chức danh.
- Badge động theo follower và lượt xem.
- Stats, top languages, streak và activity graph cập nhật từ dữ liệu GitHub.
- Contribution snake cùng 6 game Pac-Man, Breakout, Galaga, Puzzle Bobble, Bomberman và Minesweeper chạy bằng SVG, cập nhật hằng ngày qua Actions.
- Lịch đóng góp 3D được tạo hằng ngày.
- Light/dark mode cho các card và contribution animation.
- Mermaid timeline, details accordion, bảng dự án và icon công nghệ.

## Lưu ý

- GitHub loại bỏ JavaScript, iframe và CSS tùy ý trong README. Vì vậy chuyển động được đặt trong SVG/GIF hoặc ảnh do dịch vụ tạo.
- Các card bên ngoài có thể tạm thời không tải nếu dịch vụ bị giới hạn lượt gọi. Có thể tự triển khai các dịch vụ card về sau nếu cần độ ổn định cao hơn.
- README công khai không chứa ngày sinh, số điện thoại hay địa chỉ nhà từ CV.
