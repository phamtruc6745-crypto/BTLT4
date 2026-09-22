# BaiTap1_6651071085_PhamThanhTruc_MenuTraSua — Trúc's Tea 🧋

## Cấu trúc thư mục

```
BaiTap1_MSSV_HoTen_MenuQuanAn/
├── html/
│   └── index.html          ← Trang chính (mở file này để xem)
├── css/
│   └── style.css           ← Toàn bộ CSS
├── images/
│   ├── placeholder.png     ← Ảnh thay thế tự động khi chưa có ảnh thật
│   ├── logo.png            ← Logo quán (tùy chọn)
│   ├── header-bg.jpg       ← Ảnh nền header
│   ├── hero-bg.jpg         ← Ảnh nền banner
│   ├── tradao_camsa.jpg
│   ├── trasua_oolong.jpg
│   ├── suatuoi_tranchau.jpg
│   ├── trasua_hochocolate.jpg
│   ├── trasua_khoaimon.jpg
│   ├── traxanh_macchiato.jpg
│   ├── luctradau_yakult.jpg
│   ├── tra_oi.jpg
│   ├── tra_dautam.jpg
│   ├── oolong_macchiato.jpg
│   ├── hong_tra_macchiato.jpg
│   └── bactruc_macchiato.jpg
└── README.md
```

## Cách mở trang web

1. Mở file `html/index.html` bằng bất kỳ trình duyệt nào (Chrome, Edge, Firefox).
2. Trang sẽ hiển thị đầy đủ kể cả khi chưa có ảnh (dùng placeholder tự động).

## Thêm ảnh thật

- Đặt ảnh vào thư mục `images/` với **đúng tên file** ở bảng trên.
- Khuyến nghị kích thước: **800×800px** (tỷ lệ 1:1) để layout đồng đều.
- Định dạng: `.jpg` hoặc `.png` đều được.

## Đổi thông tin cá nhân

1. **Tên thư mục gốc:** Đổi thành `BaiTap1_<MSSV>_<HoTen>_MenuQuanAn`
2. **Footer bản quyền** trong `index.html` dòng cuối: thay `MSSV_HoTen` bằng thông tin thực.

## Checklist các yêu cầu CSS ✅

| Yêu cầu | Vị trí trong CSS |
|---------|-----------------|
| Universal `*` | Dòng reset `* { margin: 0; ... }` |
| Tag selector | `body`, `h1`, `h3`, `img`, `a`, `table`... |
| Class selector | `.menu-card`, `.btn-order`, `.card-price`... |
| ID selector | `#site-header`, `#main-nav`, `#sidebar`... |
| Descendant | `#main-nav ul`, `.bestseller-item .bs-img`... |
| Child `>` | `#main-nav > ul > li` |
| Group `,` | `.promo-block, .hours-block` | 
| Adjacent sibling `+` | `.nav-list li + li`, `.topping-item + .topping-item` |
| `:hover` | `.nav-link:hover`, `.menu-card:hover`, `.btn-order:hover`... |
| `:first-child` | `.cards-grid .menu-card:first-child`, `.bestseller-list li:first-child` |
| `::before` | `.nav-link::before`, `.section-title::before`, `.promo-block::before`, `.social-link.facebook::before`... |
| `::after` | `.nav-link::after`, `.section-title::after`, `.footer-inner h3::after` |
| `border-radius` | Cards (14px), images (12px), buttons (30px) |
| `box-shadow` | `.menu-card`, `.logo-img`, `.btn-hero` |
| `border-image` | `.promo-block` (gradient border) |
| `background-size` | Header, hero, footer |
| `background-position` | Header, hero, footer |
| `background-origin` | `#site-header::before`, `.section-title` |
| `background-clip` | `#site-header::before`, `.section-title`, `.promo-block` |
| Multiple backgrounds | Header (pattern + gradient), Hero (overlay + bg-img), Footer (3 layers) |
