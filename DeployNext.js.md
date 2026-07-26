
# Bảng tóm tắt các cách Render & Deploy Next.js

Dưới đây là bảng so sánh chi tiết và dễ hiểu nhất về các phương pháp render và cách deploy trong Next.js (cập nhật 2026).

## Bảng so sánh

| Cách render                          | Static Hosting | Serverless | Edge     | Node Runtime | **Giải thích dễ hiểu** |
|--------------------------------------|----------------|------------|----------|--------------|------------------------|
| **CSR**                              | ✅             | ✅         | ✅       | ✅           | **Client-Side Rendering**<br>Trang web được render hoàn toàn bằng JavaScript ngay trên trình duyệt của người dùng. |
| **SSG**                              | ✅             | ✅         | ✅       | ✅           | **Static Site Generation**<br>Tạo trang HTML tĩnh một lần lúc build (rất nhanh, tốt cho SEO). |
| **SSR**                              | ❌             | ✅         | ✅       | ✅           | **Server-Side Rendering**<br>Mỗi lần người dùng truy cập, server sẽ render HTML mới ngay lập tức. |
| **ISR**                              | ❌             | ⚠️         | ⚠️       | ✅           | **Incremental Static Regeneration**<br>Kết hợp SSG + tự động cập nhật trang tĩnh sau một khoảng thời gian mà không cần rebuild toàn bộ. |
| **RSC (Server Components động)**    | ❌             | ✅         | ⚠️       | ✅           | **React Server Components** (phiên bản động)<br>Component chạy trên server, có thể lấy dữ liệu động, sau đó gửi về client. |
| **API Routes**                       | ❌             | ✅         | ⚠️       | ✅           | Các đường dẫn API (`/api/...`) để xử lý logic backend (lấy dữ liệu, xử lý form...). |
| **Server Actions**                   | ❌             | ✅         | ⚠️       | ✅           | Hàm chạy trên server để xử lý form, mutation dữ liệu (không cần viết API riêng). |
| **Middleware**                       | ❌             | ❌         | ✅       | ✅           | Code chạy **trước** khi trang được render (dùng để check quyền, redirect, authentication...). |
| **WebSocket Server**                 | ❌             | ❌         | ⚠️       | ✅           | Kết nối thời gian thực (chat, thông báo live, collaborative...). |

## Giải thích các kiểu Deploy

| Kiểu Deploy          | Tên đầy đủ                  | Dễ hiểu là gì? |
|----------------------|-----------------------------|---------------|
| **Static Hosting**   | Static Hosting / Static Export | Deploy trang web thuần tĩnh (chỉ HTML + CSS + JS). Rẻ, nhanh nhất, nhưng không làm được việc động. Dùng `output: 'export'` trong Next.js. |
| **Serverless**       | Serverless Functions        | Server tự động scale, chỉ chạy khi có người truy cập. Phổ biến trên Vercel, rẻ và dễ quản lý. |
| **Edge**             | Edge Runtime / Edge Network | Chạy code gần người dùng nhất (toàn cầu). Siêu nhanh nhưng **hạn chế** (không dùng được nhiều thư viện Node.js). |
| **Node Runtime**     | Node.js Runtime             | Chạy full Node.js truyền thống. Linh hoạt nhất, hỗ trợ gần như tất cả tính năng, nhưng chậm hơn Edge một chút. |

## Tóm tắt nhanh khi nào dùng gì

- **Static Hosting**: Blog, landing page, tài liệu, website ít thay đổi.
- **Serverless + Node Runtime**: Ứng dụng đầy đủ (có user, database, form...).
- **Edge**: Cần tốc độ cực nhanh (middleware, geo-routing, A/B testing).
- **Kết hợp**: Next.js cho phép **hybrid** (một số trang SSG, trang khác SSR).

---

**Chú thích**:
- ✅ = Hỗ trợ đầy đủ
- ⚠️ = Hỗ trợ nhưng có hạn chế (performance, thư viện, hoặc một số tính năng)
- ❌ = Không hỗ trợ
