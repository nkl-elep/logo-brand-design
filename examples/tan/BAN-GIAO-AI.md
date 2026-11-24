# Phiếu bàn giao cho AI · Tần

**Phiên bản dùng trong demo** · demo-1.0. Đây là thương hiệu giả định. Người nghe lưu lịch phát, giữ vé và theo dõi các đoạn nhạc.

## Tài nguyên cần mở

1. Đọc [cẩm nang thương hiệu Tần](README.md) và [thông số thương hiệu](brand-tokens.json).
2. Đặt [master đậm](logo/logo-dam.svg) lên nền sáng, [master sáng](logo/logo-sang.svg) lên nền đậm. Khi chỉ đủ chỗ cho biểu tượng, lấy [dấu rời](logo/dau.svg).
3. Dùng [ấn phẩm online đã dựng](ung-dung/lich-phat.svg) để đối chiếu chữ, lề và nội dung. So với [ảnh của cả bộ](xem/ung-dung.jpg) khi chuyển kênh.

## Quyết định nền

- **Logo.** Sáu thanh vát xếp thành một biên độ sóng âm. Chừa quanh logo tối thiểu bề ngang một thanh tín hiệu. Cụm đủ tên từ 120 px và dấu rời từ 24 px.
- **Màu.** Than đĩa #121419, Tín hiệu #E1FF47, Tím lạnh #AEB7FF. Lấy cặp chữ và nền ở trường approved_text_background_pairs.
- **Chữ.** Barlow Condensed 800 cho tiêu đề và IBM Plex Mono 400 cho nội dung. Các font gốc và giấy phép nằm trong [fonts](fonts/).
- **Bố cục và lời văn.** Tiêu đề nén, chữ giờ mono, lưới thẳng và ảnh đen trắng. Ghi tên phiên, giờ và định dạng trước lời giới thiệu.

## Brief để dùng ngay

> Tạo ảnh nhắc giờ cho Phiên 003 lúc 21:00, khổ 1080 × 1920. Đọc các file bàn giao ở trên, giữ logo gốc và nội dung đã cho. Giao PNG và SVG sửa được. Thông tin chưa có thì để chỗ điền rõ ràng.

**Trước khi giao.** Mở PNG ở kích thước điện thoại. Đối chiếu hình học logo với master, kiểm dấu tiếng Việt và cặp màu thực dùng. Mở lại SVG, sửa một dòng chữ rồi xuất lại. Ghi rõ phần tự chọn và dữ liệu còn thiếu. Nếu brief mới có thay đổi về logo hoặc màu, ghi thay đổi thành phiên bản mới trước khi cập nhật tài nguyên khác.
