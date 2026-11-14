# Congcu_xuly_DN0306

## Chạy ứng dụng trên GitHub Pages

Ứng dụng là trang HTML tĩnh, được triển khai tự động lên GitHub Pages bằng GitHub Actions.

1. Đảm bảo `index.html` nằm ở thư mục gốc của repository.
2. Trong GitHub, mở **Settings → Pages** và đặt **Source** thành **GitHub Actions**.
3. Đẩy thay đổi lên nhánh `main`, hoặc chạy thủ công workflow **Deploy static site to GitHub Pages** trong tab **Actions**.
4. Mở URL Pages hiển thị trong workflow sau khi triển khai thành công.

Các lần cập nhật tiếp theo trên `main` sẽ tự động triển khai lại trang.
