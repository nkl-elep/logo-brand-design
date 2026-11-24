# Triển khai theo hành trình sử dụng

## Chọn đầu ra

Dựa vào nơi khách hàng biết đến thương hiệu, ra quyết định, nhận dịch vụ và quay lại. Hãy chọn một món có người dùng, nội dung và chức năng cụ thể ở mỗi điểm chạm quan trọng. Với ngành bán lẻ, bao bì và nhãn kệ có thể quan trọng hơn hồ sơ đề xuất. Với studio dịch vụ, email và tài liệu nghiệm thu thường hữu dụng hơn đồng phục.

| Điểm chạm | Online | Offline / POSM | Cần xem trên bản thực |
|---|---|---|---|
| Biết đến | Avatar, bài giới thiệu hoặc khung video | Biển, poster hoặc thẻ mời | Nhận ra thương hiệu ở kích thước thu nhỏ và khoảng cách đọc |
| Cân nhắc | Trang dịch vụ, carousel hoặc case study | Tờ giới thiệu, bảng giá hoặc bìa hồ sơ | Đọc được một lợi ích và biết bước tiếp theo |
| Giao dịch | Email xác nhận, giao diện đặt hàng hoặc đề xuất | Danh thiếp, phiếu hẹn hoặc bao bì | Trường tên dài, mã đơn, thông tin liên hệ, chỗ ghi tay |
| Sau giao dịch | Hướng dẫn, trang bàn giao hoặc email hỗ trợ | Phiếu bảo hành, nhãn hướng dẫn hoặc tài liệu bàn giao | Biết tra cứu hoặc liên hệ ở đâu |

Nếu yêu cầu chỉ là một logo, dùng bảng để chọn điểm chạm thử. Khi có yêu cầu cả bộ, tạo bộ nguồn dùng được, gồm ví dụ online và offline phù hợp ngành. Đánh dấu dữ liệu mẫu như số điện thoại, thành tích và số liệu dự án.

## Viết guideline từ file đã duyệt

- **Logo.** Lưu master vector, bản chữ đã chuyển thành đường nét và bản nguồn chỉnh được nếu có. Xuất bản chính, bản đơn sắc, bản tương phản và biểu tượng gọn theo nhu cầu. Vẽ trực tiếp đơn vị khoảng bảo vệ trên logo. Rút kích thước tối thiểu từ bản thử thay vì chọn một con số quen tay.
- **Màu.** Gán vai trò cho nền, chữ, nhấn và màu phụ. Chỉ ra một cặp chữ/nền dùng được bằng ví dụ thật. Ghi HEX/sRGB cho số. Nếu có đầu ra in, ghi profile và giá trị CMYK thực dùng hoặc ghi chờ nhà in. Màu vật liệu và mực đặc biệt cần mẫu vật lý để chốt.
- **Chữ.** Tách phần tên vẽ riêng với font cho tiêu đề, nội dung, số hoặc mã. Ghi family, weight, cỡ và khoảng dòng cho từng kênh. Thử một đoạn văn có dấu, chữ số và tên dài. Chỉ đóng gói font khi điều kiện phân phối cho phép, nếu không thì ghi nguồn và font thay thế.
- **Hình, bố cục, giọng văn.** Cho thấy một họa tiết khi đặt sát lề, một trang dày chữ và một bố cục nhiều khoảng trống. Viết lại cùng một thông điệp cho hai điểm chạm. Với video, thử một cảnh đọc phụ đề và một điểm chuyển cảnh. Các ví dụ dùng chung dữ liệu thương hiệu.
- **Ứng dụng.** Ghi kích thước, vùng an toàn, bố cục và file nguồn của từng mẫu. Bao gồm ví dụ đúng và lỗi dễ xảy ra như mất dấu, logo quá nhỏ hoặc chữ thiếu tương phản.

## Đóng gói nguồn cho người và AI

Giao thư mục logo, font hoặc nguồn font, màu, guideline, mẫu ứng dụng và file sản xuất theo phạm vi. Với ấn phẩm in, ghi khổ thành phẩm, tràn lề và vùng an toàn theo thông số nhà in. Phân biệt ảnh phối cảnh, file in và bản duyệt vật liệu.

Khi khách cần AI nối việc, tạo thêm một thư mục có thể mang sang máy khác. Đưa vào đó master được phép chia sẻ, thông số đã duyệt, quy tắc ngắn, một ví dụ và một brief. Sửa [brand-tokens.json](../assets/brand-tokens.json) cho đúng thương hiệu, trong đó giá trị null nghĩa là chưa có quyết định. Mỗi đường dẫn bắt đầu từ thư mục chứa JSON. Khi hai nguồn bất nhất, ưu tiên quyết định mới nhất đã được khách duyệt và đồng bộ các file dẫn xuất. Kèm một lệnh giao việc hoàn chỉnh, ví dụ “Tạo thư mời ra mắt theo master chính, dùng nội dung đính kèm, xuất bản in A6 và một bản gửi qua email”.

## Kiểm trước khi giao

1. Mở SVG, PNG và bản xuất ở kích thước sử dụng. Rà hình học, nền trong suốt, tên, dấu, chữ và logo ở các góc hiển thị nhạy cảm. Với PDF, xem trang đã render và kiểm khổ thực.
2. Mở ít nhất một nguồn chỉnh sửa, thay nội dung ngắn bằng nội dung dài rồi xuất lại. Thử thao tác chính trên mẫu tương tác và vùng an toàn trên bản mobile nếu có.
3. Giải nén gói sang một thư mục khác. Kiểm từng đường dẫn tới tài nguyên, font và brief. Tên file đích phải khớp phiên bản duyệt. Nêu rõ bản nào mới kiểm trên màn hình, bản nào đã in hoặc sản xuất thử.
