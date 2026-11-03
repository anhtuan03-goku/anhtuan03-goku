# IDP MONTHLY CHECKPOINT REPORT – GIAI ĐOẠN 1 (THÁNG 10/2026)

*Báo cáo theo dõi và đánh giá tiến độ phát triển năng lực cá nhân*

**Kỳ báo cáo:** Tháng 10/2026 (Giai đoạn 1: 09/2026 – 10/2026)

---

## 1. THÔNG TIN NHÂN VIÊN

| Hạng mục | Thông tin chi tiết |
| :--- | :--- |
| **Nhân viên thực hiện** | **Nguyễn Anh Tuấn** |
| **Chức danh hiện tại** | Junior Frontend Developer |
| **Vị trí / Mục tiêu phát triển** | **Middle Frontend Developer** – Phát triển năng lực và phạm vi công việc, đạt Middle cho Readiness Review 03/2027 |
| **Quản lý trực tiếp** | **Lý Gia Hoàng** – Web Leader |
| **Ngày lập kế hoạch** | 23/09/2026 |
| **Giai đoạn áp dụng** | 09/2026 – 03/2027 |
| **Bản kế hoạch IDP gốc** | [muc-tieu-phat-trien-ca-nhan.html](https://anhtuan03-goku.github.io/anhtuan03-goku/muc-tieu-phat-trien-ca-nhan.html) |

---

## 2. EXECUTIVE SUMMARY – TỔNG QUAN TIẾN ĐỘ IDP THÁNG 10/2026

Trong giai đoạn đầu tiên (Tháng 10/2026), em tập trung vào **2 mục tiêu trọng tâm trong IDP** và **3 hạng mục đóng góp mở rộng (Plus Points)** cho đội ngũ:

1. **Mục tiêu ngắn hạn – Chuẩn hóa Tech Stack & Xây dựng Frontend Base/Template (`Đạt 100%`):**
   * Thực hiện chuẩn hóa bộ thư viện (`package.json`) và cấu trúc thư mục Frontend đồng nhất qua 2 dự án thực tế đại diện cho 2 dòng sản phẩm chính của công ty: **SkySOLIS** ([https://360.skysolis.my/](https://360.skysolis.my/) – Căn hộ cao tầng, 40 tầng, 386 căn) và **Đảo Kim Quy** ([https://vr360.daokimquy.vn/](https://vr360.daokimquy.vn/) – Đô thị đảo thấp tầng, 571 căn).
   * Kết quả đối chiếu mã nguồn nhánh `main`: **76.7% cấu trúc file code (`181/236` files)** được dùng chung giữa 2 dự án (trong đó **39.8% = `94` files giống nhau 100%** không cần chỉnh sửa và **36.9% = `87` files** tái sử dụng khung logic, chỉ thay đổi dữ liệu/giao diện đặc thù). Nhờ đó rút ngắn **~40–50% thời gian khởi tạo dự án mới** và đảm bảo tính đồng nhất khi bảo trì.
   * **Báo cáo chi tiết (Web):** [https://anhtuan03-goku.github.io/anhtuan03-goku/short-term-tech-stack-report.html](https://anhtuan03-goku.github.io/anhtuan03-goku/short-term-tech-stack-report.html)
2. **Mục tiêu dài hạn – Giảm phụ thuộc vào một công nghệ duy nhất (`Đạt mục tiêu nghiên cứu bước đầu`):**
   * Thực hiện nghiên cứu chuyên sâu 3 phương án công nghệ Web360 thay thế đã đề ra trong IDP: **Photo Sphere Viewer (PSV v5)**, **Marzipano** và **Three.js Custom Panorama Engine**.
   * Lập bảng đánh giá chi tiết giữa 3 công nghệ trên 12 tiêu chí (hiệu năng hiển thị Multi-res tiles, tích hợp React/Next.js, khả năng tùy biến UI/Hotspot, khả năng mở rộng sang không gian 3D, bản quyền, tính khả thi...).
   * **Kết luận:** Đã xác lập được phương án dự phòng công nghệ (Plan B) và thống nhất **tiếp tục xây dựng POC thử nghiệm thực tế trong thời gian tới**.
   * **Báo cáo chi tiết (Web):** [https://anhtuan03-goku.github.io/anhtuan03-goku/long-term-web360-krpano-comparison.html](https://anhtuan03-goku.github.io/anhtuan03-goku/long-term-web360-krpano-comparison.html)
3. **Các điểm cộng mở rộng trong Tháng 10/2026 (`Plus Points`):**
   * **Phát triển & cải tiến dòng dự án Landing Page + CMS:** Thực hiện dự án nội bộ **[https://goku.agency/](https://goku.agency/)** và dự án khách hàng **[https://thecollection688.com.vn/](https://thecollection688.com.vn/)**, hoàn thiện giao diện theo thiết kế và kết nối hệ thống CMS cho Backend, hướng tới việc rút kinh nghiệm rồi chuẩn hóa quy trình thực hiện một dự án Landing Page.
   * **Hỗ trợ dự án Imperia Sensa Park:** Hướng dẫn và hỗ trợ đồng nghiệp bóc tách dữ liệu đầu vào từ khách hàng, làm rõ thông tin phân khu thấp tầng để triển khai dự án với thông tin chính xác.
   * **Hỗ trợ dự án Keppel Celesta:** Hỗ trợ đồng nghiệp cấu hình và build ứng dụng cho màn hình Touchscreen tại Sale Gallery dựa trên cấu hình mà khách hàng cung cấp.
   * **Tổng hợp báo cáo trực quan (Web):** [https://anhtuan03-goku.github.io/anhtuan03-goku/bao-cao-idp-thang-10-2026.html](https://anhtuan03-goku.github.io/anhtuan03-goku/bao-cao-idp-thang-10-2026.html)

---

## 3. COMPETENCY PROGRESS – ĐÁNH GIÁ TIẾN BỘ NĂNG LỰC QUA NHIỆM VỤ ĐƯỢC GIAO (70%)

### 3.1. Theo dõi năng lực qua nhiệm vụ được giao

| STT | Năng lực trọng tâm trong IDP | Baseline (09/2026) | Kết quả hiện tại (10/2026) | Dự án / Nhiệm vụ áp dụng | Minh chứng cụ thể |
| :-: | :--- | :--- | :--- | :--- | :--- |
| **1** | **Chuẩn hóa Tech Stack & Đưa ra lựa chọn kỹ thuật phù hợp** | Các dự án cài đặt thư viện rời rạc, cùng một chức năng (animation, zoom, fetch data) nhưng mỗi dự án dùng giải pháp khác nhau. | Đã đánh giá và thống nhất bộ dependency cốt lõi cho dòng dự án Web360/Sa bàn ảo; lọc ra các thư viện tối ưu nhất để đưa vào Base Template. | • **SkySOLIS** ([360.skysolis.my](https://360.skysolis.my/))<br>• **Đảo Kim Quy** ([vr360.daokimquy.vn](https://vr360.daokimquy.vn/)) | • Bộ `package.json` nhánh `main` đồng nhất 100% giữa 2 dự án.<br>• [Báo cáo Chuẩn hóa Tech Stack](https://anhtuan03-goku.github.io/anhtuan03-goku/short-term-tech-stack-report.html) |
| **2** | **Xây dựng kiến trúc Frontend rõ ràng, dễ maintain & tái sử dụng** | Các component gắn chặt với dữ liệu từng dự án, khó tái sử dụng khi chuyển từ dự án cao tầng sang thấp tầng. | Chuẩn hóa cấu trúc phân tầng rõ ràng (`components/shared`, `components/routes`, `hooks`, `zustand`, `service`, `data`, `scripts`). | • **SkySOLIS**<br>• **Đảo Kim Quy** | • **76.7% (`181/236` files)** chia sẻ chung cấu trúc giữa 2 dự án (**94 files** tái sử dụng nguyên bản 100%). |
| **3** | **Chủ động phát hiện và xử lý vấn đề Performance & UX** | Xử lý lỗi hiệu năng khi đã phát sinh ở giai đoạn cuối dự án. | Chủ động tối ưu tải ảnh đa phân giải 8K (Multi-res Tiles), throttle 120ms khi pan/zoom, giới hạn bộ nhớ Safari iOS và caching dữ liệu bảng hàng. | • **SkySOLIS**<br>• **Đảo Kim Quy** | • Module `ZoomableView`, `DeepZoomFloorPlan`, `useIOSMemoryTier`, `room.js` (ETag + `Map` index). |
| **4** | **Nghiên cứu công nghệ mới & Giảm phụ thuộc vào công nghệ đơn lẻ** | Chỉ sử dụng một giải pháp duy nhất cho hệ thống Web360, chưa có phương án dự phòng khi cần tùy biến cao. | Hoàn thành nghiên cứu cơ chế kỹ thuật và lập bảng đánh giá 3 công nghệ thay thế (Photo Sphere Viewer, Marzipano, Three.js Custom Engine) để chuẩn bị làm POC. | • Nghiên cứu R&D hệ thống Web360 | • Bảng đánh giá 12 tiêu chí.<br>• [Báo cáo Nghiên cứu Công nghệ Web360](https://anhtuan03-goku.github.io/anhtuan03-goku/long-term-web360-krpano-comparison.html) |
| **5** | **Tự chủ triển khai, phối hợp BE/PM & Hỗ trợ đồng nghiệp** | Tập trung giải quyết đầu việc cá nhân. | Tham gia làm rõ dữ liệu đầu vào, phối hợp BE ghép nối CMS và trực tiếp hỗ trợ kỹ thuật cho các thành viên khác trong team. | • [goku.agency](https://goku.agency/) & [thecollection688.com.vn](https://thecollection688.com.vn/)<br>• **Imperia Sensa Park**<br>• **Keppel Celesta** | • Sản phẩm Landing Page + CMS.<br>• Bộ dữ liệu phân khu thấp tầng Imperia Sensa Park & bản build Touchscreen Keppel Celesta. |

---

### 3.2. Phân tích tình huống tiêu biểu (Case Studies Trọng tâm)

#### **Assignment 1 (Mục tiêu ngắn hạn): Chuẩn hóa Tech Stack & Xây dựng Frontend Base qua 2 dự án SkySOLIS và Đảo Kim Quy**

* **Năng lực liên quan:** Chuẩn hóa Tech Stack; đưa ra lựa chọn kỹ thuật phù hợp; xây dựng kiến trúc Frontend rõ ràng, dễ bảo trì và tái sử dụng.
* **Bối cảnh / Thách thức:**
  * Công ty triển khai song song nhiều dự án Bất động sản tương tác có tính chất sản phẩm khác nhau: **SkySOLIS** ([https://360.skysolis.my/](https://360.skysolis.my/)) là dự án căn hộ cao tầng (tập trung vào xoay mặt đứng tòa nhà, lọc tầng, mặt bằng tầng 8K, căn hộ mẫu và góc nhìn ban công), trong khi **Đảo Kim Quy** ([https://vr360.daokimquy.vn/](https://vr360.daokimquy.vn/)) là dự án đại đô thị đảo thấp tầng (tập trung vào mặt bằng tổng thể phân khu biệt thự/nhà phố và 34 cảnh 360° thực tế/phối cảnh).
  * Cần chuẩn hóa một bộ Tech Stack và khung dự án (Frontend Base) để không phải xây dựng lại từ đầu cho mỗi dự án, đồng thời đảm bảo hiệu năng mượt mà trên cả Desktop và Mobile/Tablet.
* **Hành động & Giải pháp thực hiện:**
  1. **Đánh giá và chuẩn hóa bộ Dependency trọng tâm (theo 6 tiêu chí: Hiệu năng, Maintain, Hỗ trợ, Bundle size, Mở rộng, Phù hợp dự án công ty):**
     * **Core Framework:** Chọn **Next.js `15.5.4` (App Router, `output: "export"`) + React `19.1.0` + Tailwind CSS `v4`** giúp vừa xuất được bản tĩnh tốc độ cao cho Web, vừa đóng gói được thành ứng dụng chạy offline trên màn hình cảm ứng (Electron).
     * **State Management:** Chuẩn hóa về **Zustand (`^5.0.8`)** (nhẹ ~1.2KB, gọi được trực tiếp ngoài component qua `getState()`, phù hợp cho việc đồng bộ trạng thái ứng dụng và lưu cấu hình ngôn ngữ qua `persist`).
     * **Animation & Tương tác mặt bằng 2D:** Chuẩn hóa về **Framer Motion (`^11.18.2`)** kết hợp module **`ZoomableView` + `DeepZoomFloorPlan` tự phát triển** (thay vì phụ thuộc `react-zoom-pan-pinch` hay `@react-spring/web`). Giải pháp nội bộ sử dụng `useMotionValue` + throttle `120ms` giúp kéo/phóng mặt bằng 8K mượt ở 60fps mà không gây re-render toàn trang, đồng thời bổ sung cơ chế bảo vệ bộ nhớ trên iOS Safari (`useIOSMemoryTier` + hàng đợi giải mã ảnh FIFO tối đa 2 tiles cùng lúc).
     * **Data Fetching & Caching:** Xây dựng tầng service `src/service/room.js` tích hợp bộ nhớ đệm **ETag 5 phút (HTTP 304)** và **4 bảng chỉ mục `Map` ($O(1)$)** để truy vấn nhanh bảng hàng từ Google Sheets kèm dữ liệu dự phòng offline (thay thế nhu cầu dùng các thư viện nặng như `@tanstack/react-query` hay `minisearch` cho dự án tĩnh).
     * **Đa ngôn ngữ & Pipeline tối ưu tài sản:** Chuẩn hóa `next-intl` cho chuyển đổi ngôn ngữ tức thì (`vi/en`) và bộ script Node.js dùng `sharp` (`scripts/generate-all-tiles.mjs`, `generate-floorplan-tiles.mjs`, `optimize-critical-images.mjs`, `validate-critical-assets.mjs`) kết hợp `@gltf-transform` / `meshoptimizer` (`stream-optimize.mjs`) để tự động hóa việc cắt ảnh tile WebP và nén model 3D.
  2. **Rà soát và tinh gọn Base Template:**
     * Kiểm tra thực tế sử dụng trong code của cả 2 dự án để ghi nhận các thư viện không còn dùng tới (`@react-spring/web`, `react-zoom-pan-pinch`, `@tanstack/react-query`, `minisearch`, `tw-animate-css`...) nhằm loại bỏ khi đóng gói thành Template chuẩn cho dự án mới.
* **Kết quả đạt được:**
  * **76.7% cấu trúc dự án (`181/236` files code, config, scripts)** được chia sẻ giữa **SkySOLIS** và **Đảo Kim Quy**; trong đó **94 files (39.8%) giống nhau hoàn toàn 100%** (toàn bộ hệ thống `ZoomableView`, `bookingService`, các hooks `useMultiResTiles`, `useProgressiveImage`, `useTurnstile`, các stores và scripts cắt ảnh).
  * Giảm **~40–50% thời gian khởi tạo và dựng khung** khi triển khai dự án mới; các tính năng cốt lõi (phóng to mặt bằng 8K, đặt chỗ căn hộ, đa ngôn ngữ, điều hướng) hoạt động ổn định và đồng nhất.
* **Điều chứng minh về năng lực & Liên kết minh chứng:**
  * Thể hiện khả năng đánh giá công nghệ có cơ sở, thiết kế các module dùng chung có tính kế thừa cao giữa các loại hình dự án BĐS khác nhau.
  * **Sản phẩm thực tế:** [https://360.skysolis.my/](https://360.skysolis.my/) và [https://vr360.daokimquy.vn/](https://vr360.daokimquy.vn/)
  * **Báo cáo phân tích chi tiết (so sánh 6 tiêu chí, code mẫu, ảnh chụp màn hình):** [https://anhtuan03-goku.github.io/anhtuan03-goku/short-term-tech-stack-report.html](https://anhtuan03-goku.github.io/anhtuan03-goku/short-term-tech-stack-report.html)
* **Insight / Tự đánh giá / Bài học:**
  * Việc tách bạch rõ các component dùng chung (`src/components/shared/`) và component theo trang (`src/components/routes/`) cùng tầng dữ liệu (`src/service/`, `src/data/`) giúp việc chuyển đổi từ dự án cao tầng sang thấp tầng diễn ra rất nhanh.
  * *Điểm cần lưu ý:* Khi khởi tạo dự án mới bằng cách sao chép từ dự án trước, cần dọn dẹp sớm các file/thư viện cũ không dùng tới để giữ Base Template luôn gọn nhẹ.
* **Đánh giá từ Leader / Manager:** *(Dành cho Leader điền tại mục 8)*

---

#### **Assignment 2 (Mục tiêu dài hạn): Nghiên cứu các công nghệ Web360 thay thế nhằm giảm phụ thuộc vào một công nghệ duy nhất**

* **Năng lực liên quan:** Nghiên cứu công nghệ mới; chủ động đánh giá ưu/nhược điểm kỹ thuật và xây dựng phương án công nghệ dự phòng (Plan B) phục vụ định hướng **Web 3D & Spatial Experience**.
* **Bối cảnh / Thách thức:**
  * Đối với các công nghệ đang đóng vai trò quan trọng trong sản phẩm Web360 hiện tại, việc nghiên cứu thêm các phương án thay thế là cần thiết để hiểu rõ ưu/nhược điểm của từng hướng tiếp cận và xây dựng được **Plan B về mặt công nghệ** khi sản phẩm trong tương lai cần mức độ tùy biến giao diện sâu hơn hoặc kết hợp trực tiếp với không gian 3D.
* **Hành động & Nội dung nghiên cứu:**
  1. **Nghiên cứu chuyên sâu 3 phương án công nghệ được đề ra trong IDP:**
     * **Phương án 1 – Photo Sphere Viewer (PSV v5):** Thư viện mã nguồn mở (MIT) xây dựng bên trên `Three.js`, viết bằng TypeScript. Có sẵn các Adapter hiển thị ảnh đa phân giải (`CubemapTilesAdapter`, `EquirectangularTilesAdapter`) và hệ thống Plugin hoàn chỉnh (`MarkersPlugin`, `VirtualTourPlugin`, `MapPlugin`, `PlanPlugin`, `GalleryPlugin`).
     * **Phương án 2 – Marzipano:** Engine WebGL 360° siêu nhẹ (~55KB gzipped, Apache 2.0) do Google phát triển. Rất mạnh về thuật toán quản lý tháp ảnh đa phân giải (Multi-resolution tile pyramid) và hỗ trợ gắn trực tiếp phần tử DOM vào tọa độ cầu (`hotspotContainer().createHotspot`), nhưng chỉ cung cấp nhân hiển thị cốt lõi và không hỗ trợ cảnh 3D.
     * **Phương án 3 – Three.js Custom Panorama Engine:** Tự xây dựng engine panorama trên nền `three` + `@react-three/fiber` + `@react-three/drei` (những thư viện đã có sẵn trong Base Template). Cho phép toàn quyền lập trình Custom Shaders, đồng nhất 100% với React Component Tree và kết hợp trực tiếp mô hình tòa nhà 3D (`.glb`) với không gian 360° trong cùng một WebGL Canvas.
  2. **Lập bảng đánh giá hiệu năng, tính khả thi và các yếu tố kỹ thuật giữa 3 công nghệ (12 tiêu chí):**

| STT | Tiêu chí đánh giá (Trọng số) | 1. Photo Sphere Viewer (v5) | 2. Marzipano | 3. Three.js Custom Engine |
| :-: | :--- | :--- | :--- | :--- |
| **1** | **Hiệu năng Multi-Res Tiles (8K–16K) & Bộ nhớ Mobile** *(15%)* | **8.0/10** – Hỗ trợ sẵn `CubemapTilesAdapter` & `EquirectangularTilesAdapter` tải theo vùng nhìn; tiêu thụ VRAM ở mức khá. | **9.0/10** – Tối ưu rất tốt cho cấu trúc tháp ảnh đa phân giải, giải phóng texture GPU nhanh và rất nhẹ trên di động. | **7.5/10** – Mặc định tải toàn bộ texture; cần tự phát triển thêm Frustum Tile Loader hoặc nén GPU `KTX2` cho ảnh 8K–16K. |
| **2** | **Tích hợp React/Next.js & Đồng bộ State (`Zustand`)** *(15%)* | **8.5/10** – API TypeScript hướng sự kiện chuẩn, khởi tạo và hủy instance (`destroy()`) an toàn. | **8.0/10** – API đối tượng thuần JS rõ ràng, dễ đóng gói vào Custom Hook, hỗ trợ nhiều viewer cùng lúc. | **10/10** – Toàn bộ Scene/Camera/Hotspot là React Component, đọc/ghi trực tiếp `Zustand` không cần cầu nối. |
| **3** | **Tùy biến Hotspot UI, CSS & Đa ngôn ngữ (`next-intl`)** *(15%)* | **9.0/10** – `MarkersPlugin` hỗ trợ gắn trực tiếp HTML/DOM chuẩn, đổi ngôn ngữ tức thì. | **9.0/10** – `createHotspot(domNode)` cho phép render trực tiếp React Component qua Portal. | **10/10** – Dùng `<Html>` của `@react-three/drei`, render trực tiếp JSX + Tailwind + `next-intl`. |
| **4** | **Mở rộng sang Không gian 3D (*Dự án → Tòa nhà → Tầng → Căn hộ → Nội thất*)** *(15%)* | **6.5/10** – Xây trên Three.js nhưng camera bị cố định ở tâm quả cầu panorama. | **3.0/10** – Chỉ hỗ trợ hình học panorama, không có Scene Graph 3D cho mô hình `.glb`. | **10/10** – Cùng 1 WebGL Canvas duy nhất: vừa hiển thị tòa nhà 3D (`.glb`), vừa bay camera mượt vào quả cầu 360°. |
| **5** | **Tự động hóa Pipeline cắt ảnh (Node.js / `sharp`)** *(10%)* | **9.0/10** – Định dạng lưới ảnh chuẩn (`col_row.webp`), tích hợp ngay vào script `sharp` sẵn có của team. | **8.0/10** – Cấu trúc tile rõ ràng, cần thêm bước chuyển Equirectangular sang 6 mặt Cube. | **9.0/10** – Toàn quyền định nghĩa manifest và lưới ảnh đầu vào ngay trên pipeline `sharp` + `@gltf-transform`. |
| **6** | **Hiệu ứng chuyển cảnh (Transitions) & Custom Shaders** *(8%)* | **7.5/10** – Hỗ trợ fade + zoom transition sẵn có trong `VirtualTourPlugin`. | **6.5/10** – Hỗ trợ chuyển cảnh cơ bản qua hàm `transitionUpdate`. | **10/10** – Toàn quyền viết Custom GLSL Shaders (trộn Ngày/Đêm theo thanh trượt, Depth-map transition, Bloom). |
| **7** | **Hỗ trợ WebXR / VR & Cảm biến Gyroscope** *(5%)* | **8.0/10** – Có sẵn `GyroscopePlugin` và `StereoPlugin`. | **6.0/10** – Dựa trên chuẩn WebVR cũ, cần tự cập nhật sang WebXR mới. | **9.5/10** – Hỗ trợ chuẩn WebXR Device API mới nhất qua `@react-three/xr`. |
| **8** | **Kích thước Bundle (Bundle Size)** *(5%)* | **7.0/10** – Core + Plugins ~90KB (chạy trên nền `three` đã cài sẵn). | **9.5/10** – Siêu nhẹ (~55KB gzipped), không phụ thuộc thư viện 3D ngoài. | **8.0/10** – Tận dụng trực tiếp `three` + `R3F` đã có sẵn trong `package.json`, code riêng ~20KB. |
| **9** | **Bản quyền, Chi phí & Tính chủ động mã nguồn** *(5%)* | **10/10** – Mã nguồn mở MIT 100%, miễn phí thương mại, tự chủ hoàn toàn. | **9.5/10** – Mã nguồn mở Apache 2.0 miễn phí hoàn toàn. | **10/10** – Mã nguồn mở MIT 100%, công ty làm chủ hoàn toàn công nghệ lõi tự phát triển. |
| **10** | **Cộng đồng hỗ trợ, Tài liệu & Khả năng bảo trì** *(5%)* | **9.0/10** – Dự án tích cực, tài liệu rõ ràng, lập trình viên React tiếp cận rất nhanh. | **5.5/10** – Rất ổn định nhưng dự án ở chế độ duy trì, ít cập nhật mới. | **9.5/10** – Hệ sinh thái Three.js / R3F lớn nhất hiện nay, đúng định hướng phát triển của team. |
| **11** | **Thời gian triển khai ban đầu (Time-to-Market)** *(2%)* | **8.5/10** – Nhanh (1–2 tuần) nhờ có sẵn hệ thống plugin tương đương. | **7.0/10** – Trung bình (2–3 tuần) để xây dựng thêm lớp UI/Minimap bao quanh. | **5.5/10** – Cần 4–6 tuần R&D để hoàn thiện bộ tải multi-res tiles & công cụ đặt hotspot. |
| **12** | **ĐIỂM TỔNG HỢP & ĐÁNH GIÁ TÍNH KHẢ THI** | **8.36 / 10**<br>*(Khả thi cao nhất để triển khai nhanh trong ngắn & trung hạn)* | **7.18 / 10**<br>*(Phù hợp làm tham chiếu kỹ thuật về multi-res tile & DOM projection)* | **8.85 / 10**<br>*(Giá trị chiến lược cao nhất cho định hướng liên thông 3D ↔ 360°)* |

* **Kết luận & Định hướng tiếp theo:**
  * Qua đánh giá đa chiều, **Photo Sphere Viewer v5 (`8.36/10`)** là phương án có tính khả thi cao nhất khi cần triển khai nhanh một hệ thống tour 360° độc lập nhờ bộ plugin hoàn chỉnh; trong khi **Three.js Custom Panorama Engine (`8.85/10`)** là hướng đi chiến lược để hiện thực hóa trải nghiệm liên thông từ mô hình tòa nhà 3D vào không gian 360° nội thất.
  * **Quyết định trong thời gian tới:** **Tiếp tục thực hiện thử nghiệm thực tế (Build POC)** trong giai đoạn tiếp theo để kiểm chứng trực tiếp hiệu năng tải lưới ảnh đa phân giải, mức tiêu thụ bộ nhớ trên thiết bị di động và khả năng tùy biến giao diện.
  * **Báo cáo phân tích chi tiết (phân tích từng công nghệ, bảng chấm điểm 12 tiêu chí, code mẫu và lộ trình POC):** [https://anhtuan03-goku.github.io/anhtuan03-goku/long-term-web360-krpano-comparison.html](https://anhtuan03-goku.github.io/anhtuan03-goku/long-term-web360-krpano-comparison.html)
* **Đánh giá từ Leader / Manager:** *(Dành cho Leader điền tại mục 8)*

---

#### **Assignment 3 (Điểm cộng mở rộng – Plus Points Tháng 10/2026): Cải tiến dòng dự án Landing Page + CMS & Hỗ trợ Kỹ thuật Đội ngũ**

* **Năng lực liên quan:** Chuyển đổi dần sang TypeScript & Next.js; khả năng phối hợp với Backend/PM và hỗ trợ, hướng dẫn đồng nghiệp.
* **Các kết quả thực hiện cụ thể:**
  1. **Bước đầu nghiên cứu, thực hiện và cải tiến dòng dự án Landing Page có CMS ([https://goku.agency/](https://goku.agency/) & [https://thecollection688.com.vn/](https://thecollection688.com.vn/)):**
     * Trực tiếp tham gia xây dựng và cải tiến trang web nội bộ công ty **[https://goku.agency/](https://goku.agency/)** và dự án Landing Page cho khách hàng **[https://thecollection688.com.vn/](https://thecollection688.com.vn/)**.
     * Triển khai trên nền tảng **Next.js + TypeScript**, hoàn thiện giao diện bám sát thiết kế, tối ưu hiệu ứng chuyển động và tích hợp hệ thống **CMS cho Backend** để quản trị nội dung linh hoạt.
     * **Mục tiêu hướng tới:** Đúc kết các bài học thực tế từ 2 dự án này để từng bước **chuẩn hóa quy trình và cấu trúc thực hiện một dự án Landing Page** trong thời gian tới.
  2. **Hỗ trợ & Hướng dẫn đồng nghiệp triển khai dự án Imperia Sensa Park:**
     * Hỗ trợ đồng nghiệp thực hiện **bóc tách dữ liệu đầu vào từ khách hàng**, rà soát và làm rõ thông tin cho **phân khu thấp tầng**.
     * Giúp chuẩn hóa cấu trúc dữ liệu ngay từ bước đầu để đồng nghiệp triển khai dự án với thông tin chính xác, tránh sai sót phải chỉnh sửa nhiều lần.
  3. **Hỗ trợ đồng nghiệp build ứng dụng Touchscreen cho dự án Keppel Celesta:**
     * Vận dụng kinh nghiệm đóng gói ứng dụng Desktop/Touchscreen thực tế, hỗ trợ đồng nghiệp cấu hình và **build app chạy trên màn hình cảm ứng (Touchscreen) tại Sale Gallery của dự án Keppel Celesta** dựa sát trên cấu hình phần cứng mà khách hàng cung cấp.

---

### 3.3. So sánh tiến bộ so với thời điểm bắt đầu IDP (Baseline 09/2026 vs 10/2026)

| Tiêu chí đối chiếu | Baseline (09/2026 – Khi bắt đầu IDP) | Kết quả hiện tại (Cuối 10/2026) | Sự thay đổi & Minh chứng tiến bộ |
| :--- | :--- | :--- | :--- |
| **1. Quản lý Tech Stack & Kiến trúc dự án** | Các dự án dùng thư viện chưa đồng nhất, tốn nhiều thời gian thiết lập lại từ đầu. | Đồng nhất 100% `package.json` và chia sẻ **76.7% cấu trúc code** giữa **SkySOLIS** & **Đảo Kim Quy**. | Rút ngắn ~40–50% thời gian khởi tạo dự án mới; chất lượng các module cốt lõi (Zoom 8K, Booking, i18n) ổn định hơn rõ rệt. |
| **2. Chuyển đổi sang TypeScript & Quy trình Landing Page** | Chủ yếu làm việc trên các dự án JavaScript thuần. | Triển khai thực tế Next.js + TypeScript kết hợp hệ thống CMS trên [goku.agency](https://goku.agency/) và [thecollection688.com.vn](https://thecollection688.com.vn/). | Nắm bắt tốt cách tổ chức dự án với TypeScript và tích hợp CMS động, tạo cơ sở để chuẩn hóa quy trình làm Landing Page. |
| **3. Nghiên cứu phương án công nghệ Web360 thay thế (Plan B)** | Phụ thuộc vào một giải pháp duy nhất, chưa có tài liệu đánh giá các công nghệ thay thế. | Hoàn thành phân tích và lập bảng đánh giá 12 tiêu chí cho 3 công nghệ (Photo Sphere Viewer, Marzipano, Three.js). | Hiểu rõ ưu/nhược điểm từng giải pháp, sẵn sàng bước vào giai đoạn dựng POC thử nghiệm trong thời gian tới. |
| **4. Tác động đến Đội ngũ (Team Impact)** | Tập trung hoàn thành công việc cá nhân được giao. | Chủ động hỗ trợ đồng nghiệp ở dự án **Imperia Sensa Park** (bóc tách dữ liệu) và **Keppel Celesta** (build app Touchscreen). | Mở rộng phạm vi đóng góp sang hỗ trợ thành viên khác trong team, tiệm cận yêu cầu của vị trí Middle Developer. |

---

## 4. COACHING & MENTORING TRACKER (20%)

| Kỳ thực hiện | Hình thức | Nội dung trao đổi cùng Leader (Anh Lý Gia Hoàng) | Kết quả áp dụng sau trao đổi |
| :---: | :--- | :--- | :--- |
| **Tháng 10/2026** | Review mục tiêu hành động 1 & 3 hàng tháng | • Rà soát việc chuẩn hóa Tech Stack qua 2 dự án **SkySOLIS** và **Đảo Kim Quy**.<br>• Định hướng tiêu chí đánh giá các công nghệ Web360 thay thế sao cho sát với bài toán thực tế của công ty.<br>• Trao đổi về việc hỗ trợ dữ liệu dự án **Imperia Sensa Park** và đóng gói app **Keppel Celesta**. | • Hoàn thiện bảng đánh giá dependency trên 6 tiêu chí và lọc ra các gói dư thừa cần dọn dẹp.<br>• Hoàn thành bảng đánh giá 12 tiêu chí cho Photo Sphere Viewer, Marzipano và Three.js để chuẩn bị làm POC trong tháng 11. |

---

## 5. LEARNING & APPLICATION TRACKER (10%)

| Nội dung nghiên cứu & tự học | Tình huống áp dụng thực tế tại Goku | Kết quả đầu ra |
| :--- | :--- | :--- |
| **1. Chuẩn hóa Tech Stack & Tối ưu hiển thị ảnh 8K Multi-Res Tiles trên Mobile/Desktop** | Áp dụng vào cấu trúc dự án, module `DeepZoomFloorPlan`, `ZoomableView` và bộ script cắt ảnh `sharp` của **SkySOLIS** & **Đảo Kim Quy**. | Tái sử dụng 76.7% cấu trúc code; mặt bằng 8K phóng to mượt mà, không còn lỗi văng trình duyệt trên iOS. |
| **2. Nghiên cứu kiến trúc Photo Sphere Viewer v5, Marzipano & Three.js/R3F** | Nghiên cứu cơ chế tải Multi-res tiles, gắn React Hotspot đa ngôn ngữ và khả năng mở rộng không gian 3D của 3 công nghệ. | Hoàn thành báo cáo nghiên cứu chuyên sâu ([long-term-web360-krpano-comparison.html](https://anhtuan03-goku.github.io/anhtuan03-goku/long-term-web360-krpano-comparison.html)). |
| **3. Phát triển dự án với Next.js + TypeScript kết hợp hệ thống CMS** | Áp dụng vào dự án nội bộ **[goku.agency](https://goku.agency/)** và dự án khách hàng **[thecollection688.com.vn](https://thecollection688.com.vn/)**. | Hoàn thiện giao diện theo thiết kế và kết nối ổn định với hệ thống CMS của Backend. |

---

## 6. SELF-REFLECTION – TỰ ĐÁNH GIÁ VÀ BÀI HỌC

### 6.1. Điểm đã tiến bộ & Bài học quan trọng nhất
* **Tư duy chuẩn hóa và tái sử dụng:** Thay vì viết code chỉ để giải quyết cho một dự án đơn lẻ, em đã chú trọng thiết kế các module cốt lõi (như hệ thống phóng to mặt bằng, quản lý dữ liệu phòng, cấu trúc giao diện) sao cho có thể tái sử dụng giữa cả dự án cao tầng (**SkySOLIS**) và thấp tầng (**Đảo Kim Quy**).
* **Chủ động hỗ trợ đồng nghiệp và làm rõ dữ liệu đầu vào:** Qua việc hỗ trợ bóc tách dữ liệu phân khu thấp tầng dự án **Imperia Sensa Park** và build ứng dụng Touchscreen **Keppel Celesta**, em rút ra bài học rằng việc chuẩn hóa dữ liệu đầu vào từ khách hàng và nắm rõ cấu hình thiết bị ngay từ đầu giúp tiết kiệm rất nhiều thời gian phát triển.

### 6.2. Khoảng Gap còn tồn tại và Nguyên nhân
1. **Khoảng Gap 1 – Cần tách một Base Repository sạch hoàn toàn:** Khi nhân bản nhanh giữa các dự án dưới áp lực tiến độ, trong `package.json` và thư mục dự án vẫn còn sót một số thư viện hoặc component cũ không còn dùng tới. Cần tách hẳn thành một repo Base Template gọn sạch để dùng cho các dự án mới.
2. **Khoảng Gap 2 – Nghiên cứu công nghệ Web360 mới cần bước thử nghiệm thực tế (POC):** Đã hoàn thành việc phân tích ưu/nhược điểm và lập bảng đánh giá chi tiết cho 3 công nghệ (Photo Sphere Viewer, Marzipano, Three.js), nhưng cần dựng một bản POC chạy thử trên dữ liệu ảnh thực tế của dự án để đo đạc chính xác hiệu năng trên thiết bị di động.
3. **Khoảng Gap 3 – Quy trình thực hiện Landing Page + CMS mới ở bước đúc kết kinh nghiệm:** Sau khi thực hiện [goku.agency](https://goku.agency/) và [thecollection688.com.vn](https://thecollection688.com.vn/), cần hệ thống hóa lại thành quy trình và cấu trúc chuẩn để các dự án Landing Page sau triển khai nhanh và đồng bộ hơn.

### 6.3. Điều chỉnh & Hỗ trợ cần thiết
* Xin ý kiến đánh giá và định hướng từ anh Lý Gia Hoàng về việc lựa chọn kịch bản thử nghiệm (POC) cho công nghệ Web360 trong tháng 11/2026, cũng như góp ý cho khung tiêu chuẩn của dòng dự án Landing Page + CMS.

---

## 7. NEXT MONTH ACTION PLAN – KẾ HOẠCH HÀNH ĐỘNG THÁNG TIẾP THEO (11/2026)

| STT | Hành động cụ thể (Action Plan Tháng 11/2026) | Mục tiêu IDP liên quan | Kết quả kỳ vọng | Thời hạn | Tiêu chí đánh giá |
| :-: | :--- | :--- | :--- | :---: | :--- |
| **1** | **Tiếp tục thử nghiệm thực tế (Build POC) với các công nghệ Web360 đã nghiên cứu** | **Mục tiêu dài hạn:** Giảm phụ thuộc vào một công nghệ duy nhất & Nghiên cứu Web 3D | Xây dựng bản thử nghiệm (POC) bằng **Photo Sphere Viewer / Three.js** sử dụng dữ liệu ảnh thực tế của dự án để kiểm chứng hiệu năng tải tile, gắn React Hotspot đa ngôn ngữ và chuyển cảnh. | **25/11/2026** | Có bản demo chạy thực tế và số liệu đo đạc hiệu năng, khả năng tùy biến UI trên thiết bị thực tế. |
| **2** | **Hoàn thiện Base Template sạch & Đúc kết quy trình chuẩn cho dòng dự án Landing Page + CMS** | **Mục tiêu ngắn hạn:** Chuẩn hóa Tech Stack & Chuyển đổi dần sang TypeScript / Next.js | • Làm sạch các thư viện/file cũ không dùng trong Base Template Web360.<br>• Tổng hợp kinh nghiệm từ [goku.agency](https://goku.agency/) và [thecollection688.com.vn](https://thecollection688.com.vn/) thành quy trình/cấu trúc chuẩn cho dự án Landing Page có CMS. | **27/11/2026** | • Bộ Base Template tinh gọn, không còn thư viện thừa.<br>• Tài liệu/checklist cấu trúc chuẩn cho dự án Landing Page + CMS. |
| **3** | **Tổng hợp Guideline Tối ưu hệ thống hình ảnh & Checklist UX/UI** | **Mục tiêu ngắn hạn:** Tối ưu hệ thống hình ảnh & Nâng chất lượng UX/UI | Hệ thống hóa kinh nghiệm sử dụng `sharp` (chọn định dạng `.webp`/`.avif`, cắt multi-res tiles, lazy loading, quản lý bộ nhớ mobile) thành Guideline chung. | **30/11/2026** | Có tài liệu Guideline tối ưu hình ảnh và Checklist kiểm tra UX/UI trước khi bàn giao dự án. |

---

## 8. LEADER FEEDBACK & CHECKPOINT AGREEMENT *(Leader điền)*

*Phần này được hoàn thiện sau buổi checkpoint giữa nhân viên và Leader (Anh Lý Gia Hoàng).*

### 8.1. Feedback từ Leader
* ........................................................................................................................................................................
* ........................................................................................................................................................................

### 8.2. Thống nhất sau checkpoint
* ........................................................................................................................................................................
* ........................................................................................................................................................................
