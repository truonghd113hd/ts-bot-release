# MD Bot 1.1.0 — bản nháp (chưa build)

> Ghi chú cho bản phát hành sắp tới. Số phiên bản, tên file và SHA-256 sẽ được điền sau khi build xong.

## Tải về
| File | Dùng khi | SHA-256 |
|---|---|---|
| `MD-Bot-Setup-1.1.0.exe` | cài vào máy (chọn thư mục, có gỡ cài đặt) | _điền sau khi build_ |
| `MD-Bot-1.1.0-portable.exe` | chạy thẳng, không cài | _điền sau khi build_ |

## Mới so với 1.0.0
- **Tab Train riêng:** skill khi train, tự mua bình HP/SP và "Bắt đầu train" theo **map đã lưu** (map tự lưu mỗi lần bắt đầu train). Các acc đã chọn cùng tìm **một kênh còn đủ slot** rồi vào train.
- **Event 40 NPC / Nhị Kiều** (tab Hành động, các khung thu gọn được): danh sách tầng + NPC đại diện + toàn bộ địch, tầng đang đánh / đã thắng; **dừng sau tầng N**; **Telegram kết quả thắng / thua / bỏ chạy từ tầng N** (thua tính theo HP chủ party); **kịch bản xuất chiến** theo khoảng tầng cho nhân vật và pet (preset hoặc skill cố định, đổi skill khi địch còn ít).
- **Template skill đánh của pet** (chung cho mọi acc): skill, khi địch còn dưới X dùng skill khác, skill theo hệ của mục tiêu, thêm pet theo tên; chỉnh số lượt Lưu Bị thủ đầu trận.
- **Ghi đè ID skill** ở bảng vai trò, template pet và kịch bản event: tên skill, SP và mô tả đổi theo ID.
- **Hồi HP/SP khi các trận nối liền nhau** (train, event, boss): dùng bình ngay trong trận hoặc tạm ngừng báo sẵn sàng khi train để có khoảng trống hồi.
- Mở kho / gửi / rút / nhận thư, "Đi mua ngay" và thông báo bình: **độc lập theo từng acc** (không khoá nút của acc khác).
- Tổ đội: bật quản lý tổ đội mà chưa vào đội thì chủ party và acc thành viên bỏ chạy khi vào trận; tắt thì train chạy bình thường.
- Bản cài **không cần điền cấu hình đăng nhập** (đã nhúng sẵn); bản cài không chứa dữ liệu chạy thử của máy build.

## Lưu ý
- Lần đầu mở app cần nhập **mã khoá** do người phát hành gửi riêng.
- File exe **chưa ký số**: Windows SmartScreen có thể cảnh báo — chọn "More info" → "Run anyway".
- Nhiều chức năng chưa kiểm chứng đầy đủ trên server thật; dùng thử trên acc phụ trước.
