# NVNMC REST API Documentation

Tài liệu kỹ thuật chính thức cho nền tảng quản trị máy chủ **NVNMC REST API** (chuẩn Monochrome Minimalist Mintlify).

## 🚀 Trải Nghiệm Trực Tiếp
* **Mintlify Cloud:** Kết nối trực tiếp repo này vào [Mintlify Dashboard](https://dashboard.mintlify.com) để kích hoạt tên miền `nvnmc-api-docs.mintlify.app`.
* **NVNMC Panel:** [https://panel.nvnmc.cloud](https://panel.nvnmc.cloud)
* **Website Chính Thức:** [https://nvnmc.asia](https://nvnmc.asia)

## 📁 Cấu Trúc Dự Án
```text
├── mint.json                # Cấu hình navigation, theme Monochrome & branding
├── introduction.mdx         # Tổng quan kiến trúc REST API
├── quickstart.mdx           # Hướng dẫn tạo API Key & cURL đầu tiên
├── authentication.mdx       # Quy chuẩn Header Bearer & mã lỗi HTTP
├── api-reference/
│   ├── servers.mdx          # Chi tiết máy chủ & cấu hình limits
│   ├── resources.mdx        # Thông số CPU/RAM/Disk live
│   ├── power.mdx            # Điều khiển nguồn Start/Stop/Restart/Kill
│   ├── command.mdx          # Bắn lệnh console trực tiếp
│   ├── files.mdx            # Quản lý tệp tin (đọc/ghi/xóa/upload)
│   ├── backups.mdx          # Quản lý bản sao lưu dữ liệu
│   ├── network.mdx          # Cổng mạng Allocations & IP
│   └── websocket.mdx        # WebSocket live stream console
└── logo/                    # Vector Brand Logo & Favicon
```

## 🛠️ Chạy Thử Nghiệm Trên Máy Cục Bộ (Local Preview)
```bash
npm i -g mintlify
mintlify dev
```
