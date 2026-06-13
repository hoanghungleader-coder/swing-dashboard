# 🌊 Swing T+ Live — Săn Cổ Phiếu

Dashboard theo dõi paper-trade **20 chiến lược cổ phiếu T+** (gen-1 14 + gen-2 6) của hệ Săn Leader.

- **Tự cập nhật:** loop chạy local đẩy `state.json` mỗi 15' (giờ TT) → trang tự refresh 60s.
- **Nguồn giá:** DataPro (localhost) — tính NAV + lãi/lỗ tạm tính theo giá hiện tại.
- **Bảo mật:** chỉ hiển thị **alias con thú biển** + số liệu, giấu tên kỹ thuật chiến lược.
- **Phục vụ bởi:** Cloudflare Workers (static assets, xem `wrangler.jsonc`).

> Bầy biển (cổ phiếu, giữ nhiều phiên) — tách hẳn bầy thú trên cạn của phái sinh.
