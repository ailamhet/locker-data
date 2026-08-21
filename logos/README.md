# Logo hãng vận chuyển

Đặt file logo vào thư mục này. Tên file phải khớp chính xác:

| Hãng (giá trị trong dữ liệu) | Tên file |
|---|---|
| Correos      | `correos.svg`     (hoặc `correos.png`) |
| SameDay      | `sameday.svg`     (hoặc `.png`) |
| Cargus       | `cargus.svg`      (hoặc `.png`) |
| FAN Courier  | `fan-courier.svg` (hoặc `.png`) |
| InPost       | `inpost.svg`      (hoặc `.png`) |
| GLS          | `gls.svg`         (hoặc `.png`) |

Quy tắc đặt tên: chữ thường, khoảng trắng đổi thành dấu gạch ngang.

Quy cách ảnh:
- **SVG** nếu có (nét nhất, nhẹ nhất) — widget ưu tiên tìm .svg trước
- Không có SVG thì **PNG nền trong suốt, cao 80px**, ngang tự do
- Logo hiển thị ở chiều cao 20px, rộng tối đa 76px

Thiếu file cũng không sao — widget tự hiện tên hãng bằng chữ như cũ.

Thêm/sửa logo xong thì chạy `push-locker-data.cmd` trên Desktop,
rồi tăng `DATA_VERSION` trong script LadiPage lên 1 và Xuất bản lại.
