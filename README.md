<h1>Liên Quân Random Tool 🎲</h1>

<p>Một ứng dụng nhỏ được xây dựng bằng <strong>Next.js</strong> giúp bạn random tướng và lane trong game <strong>Liên Quân Mobile</strong>.<br>
Chỉ cần nhập tên người chơi, hệ thống sẽ tự động gán <strong>tướng + lane</strong> ngẫu nhiên cho họ.</p>

<p>Dữ liệu tướng được crawl tự động từ một nguồn web bên ngoài để luôn cập nhật mới nhất.</p>

<hr>

<h2>🚀 Getting Started</h2>

<p>Chạy server development:</p>

<pre><code>npm run dev
# hoặc
yarn dev
# hoặc
pnpm dev
# hoặc
bun dev
</code></pre>

<p>Mở <a href="http://localhost:3000">http://localhost:3000</a> trên trình duyệt để bắt đầu sử dụng.</p>

<hr>

<h2>⚡ Tính năng</h2>
<ul>
  <li>🎮 Nhập <strong>tên người chơi</strong> → random <strong>tướng + lane</strong>.</li>
  <li>🌀 Random công bằng, không trùng lặp giữa các người chơi.</li>
  <li>🌐 Crawl dữ liệu tướng từ web khác → đảm bảo luôn cập nhật khi game ra tướng mới.</li>
  <li>⚡ Giao diện đơn giản, chạy mượt với <strong>Next.js + TypeScript + TailwindCSS</strong>.</li>
</ul>

<hr>

<h2>📂 Cấu trúc chính</h2>
<ul>
  <li><code>app/page.tsx</code> → giao diện nhập tên người chơi và random kết quả.</li>
  <li><code>utils/crawler.ts</code> → hàm crawl dữ liệu tướng từ web.</li>
  <li><code>utils/randomizer.ts</code> → logic random tướng + lane.</li>
</ul>

<hr>

<h2>🔗 Learn More</h2>
<ul>
  <li><a href="https://nextjs.org/docs">Next.js Documentation</a></li>
  <li><a href="https://tailwindcss.com/">TailwindCSS</a></li>
  <li><a href="https://lienquan.garena.vn/">Liên Quân Mobile (official site)</a></li>
</ul>

<hr>

<h2>🚀 Deploy</h2>

<p>Bạn có thể deploy trực tiếp trên <a href="https://vercel.com">Vercel</a> để dùng online:</p>

<pre><code>vercel
</code></pre>
