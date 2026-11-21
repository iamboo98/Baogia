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
- **In / PDF**: in ra giấy hoặc lưu thành PDF.

## Dùng

Mở `index.html` bằng trình duyệt. App là một file duy nhất, không cần cài gì thêm, nhưng cần có mạng để tải font và tạo ảnh.

### Đưa lên mạng bằng GitHub Pages

Vào **Settings → Pages**, phần **Source** chọn `Deploy from a branch`, nhánh `main`, thư mục `/ (root)`, rồi bấm Save.
Sau khoảng 1 phút, app sẽ chạy ở địa chỉ `https://<tên-tài-khoản>.github.io/<tên-repo>/`.
