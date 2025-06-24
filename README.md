# _(Một dự án tạo bằng AI sử dụng canvas trên `Gemini 2.5 Pro`._
# Vòng Quay May Mắn (Interactive Lucky Wheel)

Đây là một ứng dụng web "Vòng Quay May Mắn" tương tác, được xây dựng hoàn toàn bằng `HTML`, `CSS` và `JavaScript`. Ứng dụng cho phép người dùng tạo và tùy chỉnh vòng quay của riêng mình cho các trò chơi, sự kiện, hoặc để đưa ra quyết định một cách ngẫu nhiên và vui vẻ.

## Tính năng nổi bật

* **Vòng quay tương tác**: Giao diện vòng quay được vẽ bằng `Canvas`, có thể quay với hiệu ứng chuyển động mượt mà.
* **Tùy chỉnh toàn diện**:
    * *Sửa đổi Tiêu đề*: Dễ dàng thay đổi tiêu đề chính của vòng quay.
    * *Quản lý Lựa chọn*: Thêm, sửa đổi tên, hoặc xóa các ô trên vòng quay một cách trực quan.
    * *Điều chỉnh Xác suất*: Tùy chỉnh "tỷ lệ" (trọng số) cho mỗi ô, giúp tăng hoặc giảm khả năng trúng của ô đó.
* **Hai chế độ quay**:
    * *Loại bỏ ô đã trúng (mặc định)*: Mỗi ô sau khi trúng sẽ bị làm mờ và không được quay lại cho đến khi reset.
    * *Quay lặp lại*: Tất cả các ô luôn có sẵn để quay trúng nhiều lần.
* **Hiệu ứng sống động**:
    * *Âm thanh thực tế*: Tiếng "tích tắc" hồi hộp khi quay, chậm dần khi sắp dừng lại.
    * *Âm thanh chiến thắng*: Giai điệu vui tươi khi có kết quả.
    * *Tung hoa ăn mừng*: Hiệu ứng tung hoa giấy (confetti) đẹp mắt bắn ra khi có người chiến thắng.
* **Giao diện hiện đại & đẹp mắt**:
    * Thiết kế bóng bẩy với hiệu ứng chuyển màu, đổ bóng.
    * Vòng quay, kim chỉ và chân đế được trang trí theo phong cách vật lý, tạo cảm giác 3D.
    * Font chữ vui nhộn, phù hợp với không khí trò chơi.
    * Hộp thoại thông báo kết quả nổi bật và trang trọng.
* **Điều khiển tiện lợi**:
    * Nút "Reset" để chơi lại từ đầu bất cứ lúc nào.
    * Nút "Tùy Chỉnh" để ẩn/hiện bảng điều khiển, giúp giao diện gọn gàng.

## Công nghệ sử dụng

* **`HTML5`**: Cấu trúc cơ bản của trang web.
* **`CSS3` & `Tailwind CSS`**: Tạo kiểu và thiết kế giao diện hiện đại, responsive.
* **`JavaScript (ES6+)`**: Xử lý toàn bộ logic của trò chơi, tương tác người dùng và hiệu ứng.
* **`Canvas API`**: Vẽ và quản lý vòng quay.
* **`Web Audio API`**: Tạo và điều khiển các hiệu ứng âm thanh "tích tắc" và âm thanh chiến thắng.
* **`canvas-confetti.js`**: Thư viện dùng để tạo hiệu ứng tung hoa.
* **Google Fonts**: Sử dụng các font chữ đẹp (`Paytone One`, `Be Vietnam Pro`).

## Hướng dẫn sử dụng

1.  Tải về toàn bộ mã nguồn.
2.  Mở tệp `index.html` trong trình duyệt web mà bạn yêu thích (ví dụ: Chrome, Firefox, Edge).
3.  Để thay đổi các lựa chọn, nhấn vào nút "Tùy Chỉnh" ở dưới cùng.
4.  Nhấn nút "Quay!" để bắt đầu.
5.  Nhấn nút "Reset" để làm mới lại tất cả các ô trên vòng quay.
