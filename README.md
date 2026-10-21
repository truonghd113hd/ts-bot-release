# MD Bot

Bot nhiều tài khoản cho game Tam Quốc (Windows 64-bit), chạy bằng giao diện web nhúng trong app.

> Kho này **chỉ chứa file cài đặt và ghi chú phát hành** (mục [Releases](../../releases)). Không chứa mã nguồn.

## Tải về

Vào **[Releases → bản mới nhất](../../releases/latest)** và tải:

| File | Dùng khi |
|---|---|
| `MD-Bot-Setup-x.y.z.exe` | **Khuyên dùng.** Trình cài đặt: chọn thư mục, có gỡ cài đặt. |
| `MD-Bot-x.y.z-portable.exe` | Chạy thẳng, không cần cài. |

Mỗi bản có mã SHA-256 của từng file trong phần mô tả của Release; đối chiếu sau khi tải nếu cần.

## Yêu cầu

- Windows 10 / 11 64-bit
- Tài khoản game (user, mật khẩu, server)

## Bắt đầu nhanh

1. Cài đặt và mở **MD Bot**.
2. Lần đầu mở app nhập **mã khoá** do người phát hành gửi riêng (chỉ nhập một lần trên mỗi máy).
3. Vào tab **Tài khoản**, thêm tài khoản game (user / mật khẩu / server) rồi đăng nhập. Không cần điền cấu hình đăng nhập nào khác.
4. Chọn vai trò (preset) cho từng acc ở tab **Preset & Skill**, bật **Bộ não tự đánh**.
5. Dùng tab **Train** (skill, tự mua bình, bắt đầu train theo map đã lưu) hoặc **Hành động** (daily, event) tuỳ nhu cầu.

## Cập nhật

Tải bản mới ở mục Releases và cài đè lên bản cũ. Tài khoản và cấu hình lưu trong thư mục dữ liệu của app (userData) nên **không mất** khi cài lại hoặc nâng cấp. App hiện chưa tự cập nhật.

## Lưu ý

- Bản cài chưa được ký số nên Windows SmartScreen có thể báo "Windows protected your PC": chọn **More info → Run anyway**.
- Nhiều chức năng viết theo phân tích gói tin và log, **chưa kiểm chứng đầy đủ trên server thật**; nên dùng thử trên acc phụ trước.
- Máy chủ đăng nhập của game có lúc trả 503 (bảo trì / quá tải): bot báo rõ và tự thử lại nếu bật "tự kết nối lại".
- Tài khoản và mật khẩu lưu dạng văn bản trong thư mục dữ liệu của app trên máy bạn.
- Ứng dụng tương tác với game như một người chơi; việc sử dụng thuộc trách nhiệm của bạn và có thể không được nhà phát hành game cho phép.

## Báo lỗi

Mở một **Issue** trong kho này, kèm: phiên bản app, mô tả lỗi, và đoạn log liên quan (xoá thông tin cá nhân trước khi gửi).
