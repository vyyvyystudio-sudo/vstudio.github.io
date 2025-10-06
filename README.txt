V STUDIO - static website for GitHub Pages

Cách tạo file .zip:
1. Tạo thư mục 'vstudio-site' và đặt tất cả file & thư mục (index.html, gallery.html, services.html, about.html, contact.html, css/, assets/).
2. Trên Windows: chuột phải -> Send to -> Compressed (zipped) folder.
   Trên Mac: chuột phải -> Compress "vstudio-site".
   Trên Linux: zip -r vstudio-site.zip vstudio-site

Cách upload lên GitHub Pages:
1. Tạo tài khoản GitHub (github.com) nếu bạn chưa có.
2. Tạo repository mới với tên EXACT: vstudio.github.io (public).
3. Vào repository -> Add file -> Upload files -> upload tất cả nội dung của thư mục vstudio-site (không upload cả thư mục vstudio-site; upload file bên trong).
4. Commit changes.
5. Vào Settings -> Pages -> Source -> Deploy from branch: chọn branch 'main' và folder '/' -> Save.
6. Đợi vài phút. Truy cập https://vstudio.github.io

Ghi chú:
- Nếu muốn dùng ảnh nội bộ thay cho link Unsplash, tải ảnh vào thư mục assets/ và sửa src trong file HTML tương ứng.
- Nếu bạn có logo khác, thay file assets/logo.svg
- Zalo chat link sử dụng: https://zalo.me/0366401841
