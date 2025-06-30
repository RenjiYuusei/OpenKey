# Nhật ký sửa lỗi OpenKey

## Các lỗi đã được khắc phục

- **Lỗi mất biểu tượng trên thanh taskbar (#288):** Đã thêm độ trễ 1 giây khi khởi động để đảm bảo biểu tượng OpenKey luôn xuất hiện chính xác trên thanh taskbar.
- **Lỗi gõ tắt không hoạt động (#284):** Cải thiện khả năng tương thích với các ứng dụng Metro bằng cách thêm `ApplicationFrameHost.exe` vào danh sách các ứng dụng được xử lý đặc biệt.
- **Lỗi viết hoa khi bỏ dấu tiếng Việt (#285):** Cải thiện việc xử lý chuyển đổi chữ hoa/thường để đảm bảo tính nhất quán khi gõ tiếng Việt.
- **Tự động hoàn thành gõ tắt không cần dấu cách (#279):** Đã thêm logic mới để hỗ trợ tự động hoàn thành gõ tắt mà không cần nhấn phím cách, giúp tăng tốc độ gõ.
- **Lỗi gõ tiếng Việt trong Photoshop (#283):** Đã khắc phục các sự cố tương thích để đảm bảo việc gõ tiếng Việt trong Photoshop hoạt động trơn tru.
- **Lỗi 0xC0000409 khi khởi động cùng Windows (#273):** Đã sửa lỗi tràn bộ đệm trong quá trình tạo tác vụ tự động khởi động, giúp OpenKey khởi động ổn định hơn cùng Windows.
- **Lỗi tự động viết hoa không mong muốn (#259):** Đã sửa lỗi xử lý trạng thái phím Caps Lock, ngăn chặn việc tự động viết hoa không chính xác.
- **Không gõ được tiếng Việt trong game Steam (#266):** Đã thêm chế độ tương thích với game, sử dụng `SendMessage` để gửi ký tự, cải thiện khả năng tương thích với các ứng dụng game.