
-   input: cảm biến nhiệt độ/độ ẩm đất, lịch tưới từ người nông dân
-  output:bật/tắt bơm nước, hiển thị trạng thái và lưu nhật ký
- Phối hợp phần cứng: cảm biến → ESP32 → RAM → relay → bơm; dữ liệu cũng gửi lên dashboard
- #  Smart-Farm
*Tự động tưới cây*
| Thiết bị | Chức năng |
|---|---|
| ESP32 | Xử lý |
| Bơm | Tưới |

> CPU nhận lệnh và bật bơm.

Đất khô → Bật bơm.

RAM đầy → Xóa log cũ.
