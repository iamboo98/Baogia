# Tạo bảng báo giá

App web nhỏ để lập bảng báo giá và xuất thành ảnh, gửi khách qua Zalo hoặc Messenger.

## Tính năng

- Nhập hạng mục gồm tên, đơn vị tính, số lượng và đơn giá. Thành tiền và tổng cộng tự tính.
- Gõ giá nhanh: `350k` thành 350.000, `1.5tr` thành 1.500.000.
- Tự ghi tổng tiền bằng chữ.
- Có thể thêm giảm giá, VAT, ghi chú và tên khách hàng (không bắt buộc).
- Thông tin cửa hàng được lưu trên máy, lần sau không phải gõ lại.
- **Gửi ảnh**: trên điện thoại sẽ mở bảng chia sẻ (Zalo, Messenger…).
- **Tải ảnh**: lưu file PNG.
- **PDF**: lưu file PDF khổ A4 (trên điện thoại mở bảng chia sẻ để lưu vào Tệp hoặc gửi Zalo).

- **Lịch sử khách hàng**: lưu tên, SĐT, địa chỉ, hạng mục và thời hạn bảo hành của từng báo giá. Tìm theo tên hoặc SĐT, lọc khách còn bảo hành hoặc sắp hết bảo hành, bấm gọi ngay, mở lại hoặc báo giá lại cho khách cũ.
- **Sao lưu / khôi phục**: xuất lịch sử ra file `.json` để giữ an toàn hoặc chuyển sang máy khác.

## Dùng

Mở `index.html` bằng trình duyệt. App là một file duy nhất, không cần cài gì thêm, nhưng cần có mạng để tải font và tạo ảnh.

### Đưa lên mạng bằng GitHub Pages

Vào **Settings → Pages**, phần **Source** chọn `Deploy from a branch`, nhánh `main`, thư mục `/ (root)`, rồi bấm Save.
Sau khoảng 1 phút, app sẽ chạy ở địa chỉ `https://<tên-tài-khoản>.github.io/<tên-repo>/`.
