# GitHub Pages Static - Giá vàng DOJI

Bộ code tĩnh chuyển từ HTML gốc sang bản chạy được trên GitHub Pages.

## File chính
- `index.html`

## Đã xử lý
- Giữ title/meta/canonical/OG/Twitter/schema JSON-LD.
- Giữ giao diện header, menu, marquee tỷ giá, hero, biểu đồ, bảng giá DOJI, lịch sử giá, FAQ, tin tức và footer.
- Chuyển lazy image `data-src` sang `src`.
- Xóa Cloudflare Rocket Loader/Beacon/CDN CGI.
- Thay script động bằng JavaScript tĩnh cho mobile menu, dropdown, filter bảng, biểu đồ SVG, modal chart và nút xem thêm.
- Không cần backend khi upload lên GitHub Pages.

## Cách dùng
Upload `index.html` vào root repository và bật GitHub Pages.
