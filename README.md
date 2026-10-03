# Sổ Tiết Kiệm (PWA cho iPhone)

App theo dõi sổ tiết kiệm của vợ & chồng: tiền gốc, lãi suất, kỳ hạn → lãi mỗi ngày / mỗi tháng, dashboard có biểu đồ & animation.
Không cần App Store hay tài khoản Apple Developer.

## Cài lên iPhone
1. Bật GitHub Pages: repo → Settings → Pages → Source: *Deploy from a branch* → Branch `main`, thư mục `/ (root)` → Save. Sau 1–2 phút app có ở `https://meohocgioi.github.io/VuaDemCua/`.
2. Mở link bằng **Safari** trên iPhone → nút **Chia sẻ** → **Thêm vào MH chính**.
3. Mở từ icon ngoài màn hình chính: app chạy toàn màn hình, dùng được offline.

## Lưu ý
- Dữ liệu lưu trên từng điện thoại (localStorage). Mỗi máy trong gia đình có dữ liệu riêng; dùng **Sao lưu & cài đặt → Xuất/Nhập** để chuyển sang máy khác hoặc sao lưu.
- Lãi tính đơn: gốc × lãi suất ÷ 365 mỗi ngày, ÷ 12 mỗi tháng. Dữ liệu không đi đâu ra ngoài máy.
- Chạy thử trên máy tính: `python3 -m http.server 8000`.
