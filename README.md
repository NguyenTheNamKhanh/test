# GÓC LỚP 12

Website tĩnh tiếng Việt dành cho học sinh lớp 12: cổng thông tin về áp lực học tập, tâm lý, định hướng tương lai, giải pháp, công cụ học tập và Góc học sinh.

## Cấu trúc

```text
GOC-LOP-12/
├── index.html
├── ap-luc.html
├── giai-phap.html
├── cong-cu.html
├── goc-hoc-sinh.html
├── tim-ho-tro.html
└── assets/
    ├── css/
    │   └── style.css
    └── js/
        ├── main.js
        ├── advice.js
        └── tools.js
```

## Chạy thử

Mở `index.html` trong trình duyệt. Để kiểm tra gần giống khi xuất bản, có thể dùng tiện ích Live Server trong VS Code.

## Đưa lên GitHub Pages

1. Tải ZIP này và giải nén.
2. Trong repository GitHub, tải lên **các file bên trong thư mục `goc-lop-12`**, để `index.html` nằm ngay ở thư mục gốc repository.
3. Mở **Settings → Pages**.
4. Trong **Build and deployment**, chọn **Deploy from a branch**, chọn nhánh `main` và thư mục `/(root)`, rồi nhấn **Save**.
5. Sau khi GitHub Pages hoàn tất triển khai, URL website sẽ hiện tại trang Settings → Pages.

## Ghi chú

- Giữ nguyên cấu trúc thư mục `assets/css` và `assets/js`; các đường dẫn đang tham chiếu đến đúng vị trí này.
- Góc học sinh hiện dùng thư viện phản hồi viết sẵn theo chủ đề, cảm xúc và một số từ khóa. Đây chưa phải chatbot AI và không gửi lời nhắn đến máy chủ.
- Trình lập kế hoạch và đồng hồ tập trung chạy ngay trên trình duyệt.
