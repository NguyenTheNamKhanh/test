# Nhật ký nâng cấp — GÓC LỚP 12

## Bản nâng cấp 18/11/2026

- Bổ sung trang `goc-chill.html` với trò ghép cặp, câu đố vui và gợi ý hoạt động thư giãn.
- Thêm mục Góc Chill vào thanh điều hướng và khu vực giới thiệu trên trang chủ.
- Bổ sung tính năng đọc thành tiếng cho phần gợi ý ở Góc học sinh bằng Web Speech API, có nút dừng đọc và thông báo trạng thái.
- Cập nhật README, cấu trúc dự án và hướng dẫn triển khai GitHub Pages.
- Giữ lại các trang và chức năng hiện có: danh sách việc cần làm, đồng hồ tập trung, biểu mẫu chia sẻ và phản hồi gợi ý theo chủ đề/cảm xúc.

## Kiểm tra kỹ thuật

- Đã kiểm tra cú pháp JavaScript bằng `node --check`.
- Đã rà soát liên kết nội bộ và ID HTML: không phát hiện liên kết nội bộ bị thiếu hoặc ID trùng.
- Trang web là website tĩnh; các chức năng tương tác chạy phía trình duyệt.

## Bản nâng cấp "Pro"

- Thêm `assets/css/pro.css` và `assets/js/pro.js`, nạp ở tất cả các trang.
- Chế độ tối/sáng (nhớ lựa chọn), thanh tiến trình cuộn, nút lên đầu trang, hiệu ứng hiện dần khi cuộn (tôn trọng chế độ giảm chuyển động).
- Trang chủ: đếm ngược kỳ thi, check-in tâm trạng 7 ngày (lưu cục bộ, gợi ý Góc học sinh/Tìm hỗ trợ khi mệt), câu nhắn nhủ mỗi ngày.
- Ngày thi nằm ở `data-exam-date` trong `index.html`; cần cập nhật theo thông báo chính thức.
