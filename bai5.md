# Bài tập 5

## Phần 1. Phân tích: Cơ chế "Google Search của bảng tính" thông qua tính năng AutoFilter

Trong quản lý dữ liệu bảng tính, tính năng AutoFilter (Bộ lọc tự động) được ví như "Google Search của bảng tính" nhờ khả năng tra cứu, lọc và truy xuất thông tin tức thì dựa trên các điều kiện cụ thể:

*   **Truy vấn nhanh chóng như công cụ tìm kiếm:** Giống như cách người dùng gõ từ khóa vào thanh tìm kiếm của Google để thu hẹp kết quả từ hàng triệu trang web, AutoFilter cho phép lọc ngay lập tức các dòng dữ liệu (record) thỏa mãn điều kiện từ hàng nghìn dòng trong bảng tính chỉ với vài cú click chuột.
*   **Hỗ trợ đa điều kiện (Multi-criteria Filtering):** Cho phép kết hợp nhiều tiêu chí lọc cùng lúc (ví dụ: vừa lọc theo loại mã độc "Cao" vừa lọc theo khoảng thời gian sự cố), giúp người dùng cô lập chính xác bản ghi cần tìm mà không cần cuộn thủ công hay viết hàm phức tạp.
*   **Trực quan hóa vùng dữ liệu:** Tự động ẩn đi các dòng không phù hợp và chỉ hiển thị tập kết quả trọng tâm, giúp phân tích sự cố an ninh mạng nhanh chóng và chính xác.


## Phần 2. Triển khai: Báo cáo NetGuard hoàn chỉnh

*   **1. Word (Báo cáo sự cố an ninh mạng Incident Report):** Sử dụng Navigation Pane kết hợp thiết lập Auto TOC để quản lý cấu trúc tài liệu nhiều trang, đảm bảo mục lục tự động cập nhật chính xác số trang khi báo cáo thay đổi.
*   **2. Excel (Tra cứu mã độc):** 
    *   Sử dụng hàm VLOOKUP kết hợp hàm `TRIM` ở giá trị dò tìm để làm sạch khoảng trắng thừa (ví dụ: `=VLOOKUP(TRIM(A2), 'Cơ sở dữ liệu virus'!$A$2:$B$500, 2, FALSE)`).
    *   Cố định tuyệt đối vùng tham chiếu bằng ký tự `$` và bắt buộc chọn chế độ tìm chính xác (`FALSE`).
*   **3. PowerPoint (Chiến lược phòng thủ 3 tầng):** 
    *   Tuân thủ quy định tuyệt đối không dùng font Times New Roman, thay thế bằng các font chữ hiện đại, rõ nét như **Montserrat** hoặc **Inter** để hiển thị rõ ràng khi thuyết trình qua Projector.
    *   Trình bày chiến lược phòng thủ 3 tầng bằng sơ đồ phân cấp trực quan.

