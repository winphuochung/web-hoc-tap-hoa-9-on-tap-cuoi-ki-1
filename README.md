# Web/app học tập — Hóa học 9, Ôn tập kiểm tra cuối kì I

**Ôn tập kiểm tra cuối kì I** — Phạm vi: Bài 1, 18–28 (Kim loại, phi kim,
hợp chất hữu cơ và nhiên liệu). Tuần 16, Tiết 33–34.
Môn Khoa học tự nhiên 9 (phân môn Hóa học) — Chương trình GDPT 2018, sách Kết nối tri thức với cuộc sống.

Giáo viên: Lê Văn Thắng — Trường TH và THCS Phước Hưng, xã Nhơn Hội, tỉnh An Giang.

## Nội dung

Web/app học tập 6 phần: Khởi động, Hệ thống kiến thức, Mô phỏng, Sơ đồ tư duy,
Luyện tập (10 câu trắc nghiệm tự chấm), Vận dụng.

Mô phỏng gồm:
1. Phản ứng cháy của butane — bật lửa gas butane, bình tam giác, nước vôi trong (4 bước).
2. Điều chế và thử tính chất của ethylene — cồn 96° + H2SO4 đặc, đun nóng;
   đốt cháy ở đầu ống vuốt nhọn (ngọn lửa màu vàng); dẫn qua nước bromine (5 bước).
   Cả hai mô phỏng đều có hình minh họa SVG thay đổi theo từng bước.
   Không gắn video thí nghiệm (video butane chỉ 240p, Thầy chưa quyết).

Khóa đáp án trắc nghiệm: 1C 2D 3A 4B 5C 6A 7D 8B 9C 10A
(khóa gốc PDF: 1C 2C 3B 4B 5B 6A 7C 8B 9C 10A — đã xáo vị trí phương án vì
key gốc lệch: chữ D không xuất hiện, chữ B lặp 3 câu liên tiếp).

Ghi chú sửa PDF: PDF ghi ngọn lửa ethylene "màu xanh" là sai (nhầm với ngọn
lửa xanh mờ của ethanol) — web/app dùng màu vàng cho ngọn lửa ethylene,
đúng như Bài 24.

## Trạng thái gửi điểm: CHỜ /exec

Registry chưa có webAppUrl cho khóa `hoa9-ontap-cki` nên file này CHƯA gắn
fetch gửi điểm về Google Sheets. Điểm hiện chỉ lưu localStorage trên máy học
sinh (điểm cao nhất). Khi có link Web App deployment, patch thêm fetch vào
hàm nộp bài trong `index.html` rồi đẩy lại GitHub/Vercel.

## Cách dùng

- Mở file `index.html` bằng trình duyệt bất kì (không cần máy chủ).
- Học sinh đăng nhập bằng Họ tên + Lớp, học 6 phần, làm 10 câu trắc nghiệm rồi nộp bài.

## File trong repo

- `index.html` — web/app hoàn chỉnh, tự chứa (hình ảnh nhúng base64).
- `Web_Hoc_Tap_Hoa9_OnTap_CKI.md` — bản sao toàn bộ mã nguồn kèm khóa đáp án.
- `Code.gs` — Apps Script ghi điểm về Google Sheets (tab KetQua); deploy khi có /exec.
- `README.md` — file này.
- `assets-flow/` — 3 ảnh nền gốc (Gemini, 1376×768) + logo cá nhân của Thầy.
