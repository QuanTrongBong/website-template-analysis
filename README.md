# Phân tích và xây dựng cấu trúc Website Template

## Trang web được phân tích

Trang chủ Mozilla: [https://www.mozilla.org/en-US/](https://www.mozilla.org/en-US/)

Trang tham khảo được chụp vào ngày 14/10/2026. Ảnh chụp trang gốc được lưu tại [`reference/original-mozilla-homepage.png`](reference/original-mozilla-homepage.png).

## Phân tích bố cục

- **Header:** logo Mozilla đặt ở góc trái, mục Menu ở góc phải; nền sáng tạo tương phản rõ với phần nội dung bên dưới.
- **Navigation Menu:** các liên kết sản phẩm và chủ đề được mở từ Menu. Menu giữ phần điều hướng gọn để nội dung chính có nhiều không gian.
- **Content Section:** phần đầu trang dùng nền tối, tiêu đề lớn, đoạn giới thiệu ngắn và liên kết tìm hiểu. Các phần bên dưới trình bày sản phẩm, chủ đề và nội dung của tổ chức theo từng nhóm.
- **Footer:** gom các liên kết trợ giúp, sản phẩm, chính sách và thông tin tổ chức ở cuối trang.
- **Cách bố trí:** trang dùng header và navigation ở đầu, nội dung chính theo chiều dọc với tiêu đề nổi bật, footer toàn chiều rộng ở cuối. Tương phản nền sáng/tối giúp phân biệt rõ khu vực.

## Bố cục dựng lại

`index.html` và `style.css` dựng một trang mẫu riêng theo cùng cấu trúc tổng quát:

1. Header có tên trang.
2. Menu điều hướng có bốn liên kết.
3. Nội dung chính có phần giới thiệu và các thẻ nội dung.
4. Footer có thông tin bản quyền và các liên kết.

Đây là bài dựng lại bố cục để luyện tập, không sao chép nội dung hoặc tài sản thương hiệu của trang tham khảo.

## Xem trang

Mở `index.html` trực tiếp trên trình duyệt. Bài không cần cài thư viện hoặc build.
