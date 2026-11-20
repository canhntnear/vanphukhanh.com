Vạn Phú Khánh GPS — vanphukhanh.com
Website giới thiệu dịch vụ lắp đặt định vị 4G & camera AI hợp chuẩn Bộ Công an tại Khánh Hòa.
Live: https://vanphukhanh.com
Thương hiệu: GIAMSATXE.NET — https://giamsatxe.net
Dịch vụ
Định vị GPS 4G Viview DV4G (hộp đen) — truyền dữ liệu thời gian thực về Cục CSGT, chuẩn QCVN 06:2024/BCA, Thông tư 71/2024/TT-BCA.
Camera AI giám sát tài xế (Nghị định 10) — cảnh báo ngủ gật, mất tập trung trong chưa đầy 2 giây, lưu video 72 giờ.
Lắp đặt tận nơi tại Khánh Hòa — cắm giắc zin, an toàn điện xe 12V–24V, xong trong 30–45 phút.
Miễn phí 100% thiết bị khi nâng cấp từ định vị 2G/3G lên 4G.
4 trạm kỹ thuật lưu động dọc QL1A: Ninh Hòa, Nha Trang, Vân Phong, Cam Ranh — có mặt tận xe, hỗ trợ 24/7.
Cấp hồ sơ đăng kiểm ngay trong ngày.
Công nghệ
Trang tĩnh (static site): một file index.html, không cần build.
Tối ưu SEO & AI SEO: meta, Open Graph, canonical, sitemap.xml, robots.txt, llms.txt, dữ liệu có cấu trúc JSON-LD (LocalBusiness, Product, FAQPage).
Video hero tự phát, lặp lại, không tiếng, không nút điều khiển.
Cấu trúc thư mục
.
├── index.html            # Trang chính (nội dung, CSS, JS)
├── assets/
│   ├── hero-fleet.mp4    # Video hero bản nhẹ (1,3 MB, 960×540, ~1 Mbps, 10 giây)
│   ├── hero-poster.jpg   # Ảnh chờ của video hero (khung hình đầu của video)
│   ├── camera-ai.webp    # Minh họa camera AI
│   └── technician.webp   # Minh họa kỹ thuật viên lắp đặt
├── README.md
├── llms.txt
├── robots.txt
└── sitemap.xml
Triển khai (Deploy)
Đẩy code lên nhánh main của repo này.
Vercel tự động triển khai lại vanphukhanh.com từ nhánh main.
Sau khi deploy xong, tải lại trang bằng Ctrl + F5 (hard refresh) để tránh cache cũ.
Lưu ý: luôn đẩy kèm cả index.html và thư mục assets/. Chỉ đẩy index.html thì video hero sẽ không có file để phát và trang chỉ hiện ảnh chờ.
Video hero
File: assets/hero-fleet.mp4 — bản nhẹ 1,3 MB, 960×540, ~1 Mbps, keyframe mỗi 2 giây, faststart, không tiếng.
Tự phát, lặp lại, không tiếng, không nút phát/dừng; ảnh chờ tự gỡ khi video bắt đầu chạy.
Không dùng link raw.githubusercontent.com làm nguồn video: GitHub trả file dạng application/octet-stream kèm nosniff nên trình duyệt từ chối phát.
Muốn thay video khác: mã hóa H.264 (yuv420p, +faststart, bỏ rãnh âm thanh, keyframe mỗi 2 giây), ghi đè assets/hero-fleet.mp4, chụp một khung hình làm assets/hero-poster.jpg.
Liên hệ
Công ty TNHH Vạn Phú Khánh — Thôn Tân Mỹ, xã Tân Định, Ninh Hòa, Khánh Hòa
Hotline: 0585.114.114 (kỹ thuật: 0588.588.114)
Email: ctyvanphukhanh@gmail.com
Website: https://vanphukhanh.com
