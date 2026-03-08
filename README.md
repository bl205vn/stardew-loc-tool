# Tool chuyển JSON → CSV hỗ trợ dịch thuật

🔗 **[Dùng online tại đây](https://bl205vn.github.io/stardew-loc-tool/)**

Tool hỗ trợ so sánh và kiểm tra bản dịch game bằng cách chuyển file JSON sang CSV. 
Được tạo ra chủ yếu để phục vụ việc Việt hóa Stardew Valley — đặc biệt để 
tạo file CSV cho AI (LLM) đọc và hỗ trợ dịch thuật, nhưng hoạt động với mọi 
bộ JSON cùng cấu trúc thư mục.

## Tính năng

- Kéo thả file, nhiều file, hoặc cả thư mục (đệ quy)
- Ghép bản gốc (EN) và bản dịch (VI) theo đường dẫn tương đối tự động
- Hiển thị thống kê: tổng key, số đã dịch, số còn thiếu
- Lọc theo file, trạng thái dịch, hoặc tìm kiếm theo text
- Xuất file CSV chuẩn UTF-8 (mở đúng tiếng Việt trong Excel, Google Sheets và LLM)

## Cách dùng

1. Kéo thư mục **EN** vào ô trái, thư mục **VI** vào ô phải
2. Tool tự ghép theo đường dẫn tương đối — ví dụ `Content/Characters/Dialogue/Abigail.json` → cột **File** hiển thị `Characters/Dialogue/Abigail`
3. Lọc các dòng **CÒN THIẾU** để biết cần dịch thêm chỗ nào
4. Bấm **Xuất CSV** để tải về

> Không cần cài đặt gì. Mở bằng Chrome là chạy.
