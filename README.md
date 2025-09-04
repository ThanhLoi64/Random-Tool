Liên Quân Random Tool 🎲

Một ứng dụng nhỏ được xây dựng bằng Next.js giúp bạn random tướng và lane trong game Liên Quân Mobile.
Chỉ cần nhập tên người chơi, hệ thống sẽ tự động gán tướng + lane ngẫu nhiên cho họ.

Dữ liệu tướng được crawl tự động từ một nguồn web bên ngoài để luôn cập nhật mới nhất.

🚀 Getting Started

Chạy server development:

npm run dev
# hoặc
yarn dev
# hoặc
pnpm dev
# hoặc
bun dev


Mở http://localhost:3000
 trên trình duyệt để bắt đầu sử dụng.

⚡ Tính năng

🎮 Nhập tên người chơi → random tướng + lane.

🌀 Random công bằng, không trùng lặp giữa các người chơi.

🌐 Crawl dữ liệu tướng từ web khác → đảm bảo luôn cập nhật khi game ra tướng mới.

⚡ Giao diện đơn giản, chạy mượt với Next.js + TypeScript + TailwindCSS.

📂 Cấu trúc chính

app/page.tsx → giao diện nhập tên người chơi và random kết quả.

utils/crawler.ts → hàm crawl dữ liệu tướng từ web.

utils/randomizer.ts → logic random tướng + lane.

🔗 Learn More

Next.js Documentation

TailwindCSS

Liên Quân Mobile (official site)

🚀 Deploy

Bạn có thể deploy trực tiếp trên Vercel
 để dùng online:

vercel
