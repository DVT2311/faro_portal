# Faro Portal nội bộ · bản demo

Bản demo bấm được của Portal nội bộ Faro: khu nhân viên (mobile, 5 tab), khu quản trị (Vận hành, Tài khoản, Tài chính), đăng nhập bằng 5 tài khoản mẫu. **Toàn bộ dữ liệu là giả lập**, không có máy chủ, không lưu gì: tải lại trang là về trạng thái ban đầu.

## Mở trên điện thoại

1. Mở https://dvt2311.github.io/faro_portal/ trên điện thoại.
2. Chọn một tài khoản mẫu ở màn đăng nhập rồi bấm Đăng nhập.
3. Thêm vào màn hình chính để dùng như app:
   - iPhone: Safari → nút Chia sẻ → "Thêm vào MH chính".
   - Android: Chrome → menu ⋮ → "Cài đặt ứng dụng" / "Thêm vào màn hình chính".

## Tài khoản mẫu

| Mã NV | Người | Vào đâu |
|---|---|---|
| FR0005 | Nguyễn Thu Trang | Admin, khu quản trị |
| FR0002 | Lê Hoàng Anh | Ban giám đốc, khu quản trị |
| FR0031 | Trần Quốc Bảo | Nhân viên, Trưởng ca |
| FR0142 | Nguyễn Thị Mai Anh | NV mới: xác nhận dữ liệu và đổi mật khẩu tạm |
| FR0047 | Trịnh Văn Lộc | Đã nghỉ việc, bị khoá |

Mật khẩu nhập gì cũng được.

## Bật GitHub Pages (làm một lần)

Settings → Pages → Build and deployment → Source: **Deploy from a branch** → Branch: `main`, thư mục `/ (root)` → Save. Sau 1–2 phút link sẽ chạy.

## Cập nhật

Mã nguồn gốc là `designs/faro-portal-demo.html` trong thư mục dự án. Chạy `python3 designs/build-site.py` để tạo lại thư mục này, đổi `VERSION` trong `sw.js` để máy đã cài nhận bản mới, rồi đẩy lên repo.
