# 🥥 Website Thương Hiệu Dừa Dòn Thành Nhân

Bộ mã nguồn website giới thiệu và đặt hàng trực tuyến cho thương hiệu **Dừa Dòn Thành Nhân**, được thiết kế tối ưu cho tốc độ, chuẩn SEO và triển khai miễn phí trên **GitHub Pages**.

---

## 📁 Cấu trúc các tệp trong gói `.zip`

1. **`index.html`**: Trang chủ giao diện chính (Hero banner, Điểm nổi bật, Danh sách sản phẩm chọn quy cách 250gr/500gr, Câu chuyện thương hiệu, Đánh giá khách hàng, Giỏ hàng trượt).
2. **`styles.css`**: Hệ thống giao diện mang tông màu ấm áp tự nhiên (Nâu vỏ dừa già, Vàng đường cát, Kem sữa dừa), tương thích hoàn hảo trên cả Điện thoại và Máy tính.
3. **`app.js`**: Xử lý logic chọn gói 250gr (32.000₫) / 500gr (60.000₫), lưu giỏ hàng tự động (`localStorage`), tính phí vận chuyển và tạo tin nhắn đặt hàng qua Zalo.
4. **`products.json`**: Tệp dữ liệu trung tâm chứa thông tin thương hiệu, số điện thoại Zalo, giá bán và danh sách sản phẩm. Bạn chỉ cần sửa tệp này để cập nhật thông tin mà không cần can thiệp vào code.
5. **`README.md`**: Tài liệu hướng dẫn sử dụng và triển khai.

---

## 🛠️ Hướng dẫn thay đổi thông tin liên hệ & hình ảnh thực tế

Mở tệp **`products.json`** bằng Notepad hoặc bất kỳ trình soạn thảo văn bản nào và cập nhật mục `"brand"`:

```json
"brand": {
    "name": "Dừa Dòn Thành Nhân",
    "phone": "09xx.xxx.xxx",
    "zalo": "09xxxxxxxx",
    "address": "Địa chỉ cơ sở của bạn",
    "email": "emailcuaban@gmail.com"
}
```

- **Thay hình ảnh sản phẩm thực tế**: Tạo thêm thư mục `images/`, chép ảnh chụp thật của gói Dừa Dòn 250gr và 500gr vào đó, sau đó đổi đường dẫn trong mục `"images"` của `products.json` (ví dụ: `"images/dua-don-500g.jpg"`).

---

## 🚀 Hướng dẫn đưa lên GitHub Pages (Miễn phí 100%)

1. Giải nén tệp `dừa dòn.zip`.
2. Đăng nhập vào [GitHub](https://github.com) và tạo một Repository mới (ví dụ: `dua-don-thanh-nhan`).
3. Tải toàn bộ 5 tệp (`index.html`, `styles.css`, `app.js`, `products.json`, `README.md`) lên Repository.
4. Vào mục **Settings** -> **Pages** -> Tại phần **Branch**, chọn `main` (hoặc `master`) và nhấn **Save**.
5. Đợi khoảng 1–2 phút, website của bạn sẽ hoạt động chính thức!
