# Vườn Thương Em Bé Cam 🌷

Trang web chúc mừng 20/10 dành cho Em Bé Cam: truyện tranh Mầm & Bé Cam, vườn hoa nở khi chạm, ảnh polaroid kéo thả, thư tay và trái tim thả tim, kèm nhạc piano tự phát bằng Web Audio.

Thuần HTML + CSS + JS, không cần build.

## Chạy thử trên máy
Mở `index.html` bằng trình duyệt là xong.

## Đưa lên GitHub Pages
1. Tạo repo mới trên GitHub, ví dụ `vuon-thuong-em-be-cam`.
2. Trong thư mục này chạy:
   ```bash
   git remote add origin https://github.com/<ten-github>/vuon-thuong-em-be-cam.git
   git branch -M main
   git push -u origin main
   ```
3. Vào repo → **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` / `(root)` → **Save**.
4. Sau 1–2 phút trang có ở: `https://<ten-github>.github.io/vuon-thuong-em-be-cam/`

## Thay ảnh
Thay các file trong `assets/` (giữ nguyên tên file):
- `photo-full.jpg` — ảnh polaroid lớn (tỉ lệ 3:2)
- `photo-face.jpg`, `photo-bouquet.jpg` — 2 polaroid nhỏ + con tem (vuông)
- `photo-heart.jpg` — ảnh trong khung trái tim (vuông)

> Lưu ý: repo public thì ai cũng xem được ảnh. Muốn riêng tư hơn có thể để repo private và deploy bằng Netlify/Vercel.
