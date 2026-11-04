# Hệ Thống Ôn Tập & Thi Thử Giữa Kì 12 (GDPT 2018)

> **🚀 Phát triển bởi TDat (Dev by TDat)**  
> Kho đề thi thử trực tuyến & ôn tập trắc nghiệm toàn diện lớp 12 chạy 24/24 trên GitHub Pages.

Cổng ôn tập trực tuyến tổng hợp toàn bộ các môn học thi giữa kì lớp 12 theo chương trình GDPT 2018 mới nhất:
- **Toán Học:** Tổng ôn chương 1 & kỹ thuật máy tính Flexio FX-799VN
- **Vật Lí:** Chương 1: Vật Lí Nhiệt (Nhiệt độ, nhiệt dung riêng, nhiệt nóng chảy, nhiệt hóa hơi)
- **Hóa Học:** Este - Lipit, Carbohydrate, Amin, Amino acid, Peptit (Đề 50 phút)
- **Ngữ Văn:** Văn học tinh hoa - Luyện đề cấu trúc đổi mới
- **Lịch Sử:** Ngân hàng trắc nghiệm Lịch sử 12 Giữa học kì 1
- **Tiếng Anh:** Đề thi trắc nghiệm format mới (Mobile First)
- **Tin Học:** Trí tuệ nhân tạo (AI) & Mạng máy tính
- **Công Nghệ:** Công nghệ Lâm nghiệp & Nông nghiệp 2026 – 2027

---

## Tính Năng Hệ Thống
1. **Giao diện Portal trung tâm (`index.html`):** Tìm kiếm và chọn môn học nhanh chóng.
2. **Khung làm bài tích hợp:** Xem và làm đề thi trực tiếp trong trang hoặc mở tab độc lập.
3. **Chế độ Sáng / Tối (Dark / Light Mode):** Tự động ghi nhớ tùy chọn qua `localStorage`.
4. **Hỗ trợ chia sẻ đường dẫn trực tiếp:** Ví dụ `#toan`, `#vat-li`, `#hoa`, `#lich-su`, `#tieng-anh`, `#tin-hoc`, `#ngu-van`, `#cong-nghe`.
5. **Chạy tĩnh 100% (No build step):** Sẵn sàng chạy 24/24 trên GitHub Pages hoàn toàn miễn phí.

---

## Hướng Dẫn Treo Web Lên GitHub Pages 24/24

### Cách 1: Tải trực tiếp trên giao diện web GitHub (Không cần cài Git)
1. Đăng nhập [GitHub](https://github.com) và bấm [Tạo Repository Mới](https://github.com/new).
2. Đặt tên Repo (ví dụ `on-tap-12`), chọn **Public** rồi bấm **Create repository**.
3. Chọn mục **uploading an existing file**, kéo toàn bộ file trong thư mục này thả vào và bấm **Commit changes**.
4. Vào **Settings** &rarr; chọn mục **Pages** ở cột trái &rarr; tại **Branch** chọn `main` / `root` &rarr; bấm **Save**.
5. Sau 1 phút, trang web sẽ hoạt động 24/24 tại:
   `https://<ten-tai-khoan>.github.io/on-tap-12/`

### Cách 2: Sử dụng dòng lệnh Git
```bash
git init
git add .
git commit -m "Khoi tao he thong on thi giua ki 12"
git branch -M main
git remote add origin https://github.com/<ten-tai-khoan>/on-tap-12.git
git push -u origin main
```
Sau đó vào **Settings &rarr; Pages &rarr; chọn nhánh `main` &rarr; Save**.
