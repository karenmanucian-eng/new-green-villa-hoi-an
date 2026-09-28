# Website New Green Villa Hội An

Dựng trên đúng khung code của canho-fourstower.com (Astro).

## Chạy trên máy
```
npm install
npm run dev
```
Mở http://localhost:4321

## Sửa thông tin chung — chỉ 1 file: `src/config.ts`
- Số điện thoại, Zalo
- Tên / địa chỉ / mã số thuế đơn vị phân phối
- Google Form (FORM_ACTION và 3 mã entry) — đang dùng tạm form FourS Tower
- SITE_URL — tên miền thật khi có

## Sửa nội dung từng phần — thư mục `src/components/`
| File | Phần trên web |
|---|---|
| Hero.astro | Ảnh slider đầu trang |
| Overview.astro | Tổng quan |
| Policy.astro | Chính sách bán hàng |
| Location.astro | Vị trí + bản đồ |
| FloorPlan.astro | Mặt bằng + 4 loại lô |
| Amenities.astro | Tiện ích |
| Progress.astro | Hạ tầng thực tế |
| PriceList.astro | Bảng giá |
| Faq.astro | Hỏi đáp |
| Contact.astro | Liên hệ |
| PopupForm.astro | Popup báo giá (hiện sau 10 giây) |

## Thay ảnh
Các ảnh trong `public/images/` đang là ảnh tạm (ghi chữ "ẢNH TẠM"). Chép ảnh thật đè lên **đúng tên file**, định dạng .webp:

- phoi-canh-new-green-villa-hoi-an-1.webp, -2.webp — slider đầu trang (tỉ lệ 16:9)
- tong-quan-new-green-villa-hoi-an.webp — ảnh cạnh bảng tổng quan
- chinh-sach-ban-hang-new-green-villa-hoi-an.webp — banner chính sách
- vi-tri-new-green-villa-hoi-an.webp — bản đồ vị trí
- mat-bang-tong-the-new-green-villa-hoi-an.webp — mặt bằng tổng thể
- mat-bang-giai-doan-1-…, mat-bang-phan-lo-… — 2 ảnh mặt bằng (bấm phóng to được)
- tien-ich-new-green-villa-hoi-an.webp — banner tiện ích
- cho-lai-nghi-…, cong-vien-…, home-lake-…, trung-tam-thuong-mai-… — 4 ảnh tiện ích
- ha-tang-thuc-te-new-green-villa-hoi-an-1…4.webp — ảnh hạ tầng thực tế
- bang-gia-new-green-villa-hoi-an.webp — ảnh cạnh bảng giá
- logo-ngv.svg (header), logo-ngv-dark.svg (phần liên hệ) — logo tạm dạng chữ

Ảnh .jpg/.png có thể đổi sang .webp miễn phí tại squoosh.app.
