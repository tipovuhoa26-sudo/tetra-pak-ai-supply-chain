# Tetra Pak — AI Supply Chain Strategy Report & Hypothesis-Led Discovery Plan

Báo cáo chiến lược chuyển đổi chuỗi cung ứng Tetra Pak: Vượt qua nghịch lý Hai Hệ Điều Hành, hóa giải nút thắt kinh tế học quyết định chuỗi cung ứng, và kiến trúc hệ sinh thái Microsoft AI (Fabric, Foundry, Teams Adaptive Cards, SAP Clean Core) kết hợp hồ sơ 100 bằng chứng thực chứng được kiểm toán độc lập.

## 🌟 Điểm Nổi Bật (Key Highlights)

- **Chuẩn Mực Trình Bày Ban Điều Hành (C-Level Executive Grade)**: Giao diện trực quan, khoa học, phân tầng thông tin rõ ràng theo cấu trúc báo cáo quản trị McKinsey/BCG.
- **Tối Ưu Hóa Đa Thiết Bị (100% Multi-Screen Responsive)**: Tương thích hoàn hảo từ mobile (320px, 375px, 414px) đến tablet (768px, 1024px), laptop (1280px) và widescreen (1440px+). Đã qua kiểm thử tự động không tràn ngang (zero horizontal overflow).
- **Hệ Màu Nhận Diện Thương Hiệu Sunext**: Nền trắng tinh khôi ưu tiên (`#ffffff`), Tím hoàng gia chủ đạo 1 (`#7c3aed`), Cam sáng chủ đạo 2 (`#ea580c`), tích hợp chuyển đổi Sáng/Tối (Light/Dark Switcher).
- **100 Bằng Chứng Kiểm Toán Độc Lập (Audited Evidence Database)**: Tra cứu và lọc thời gian thực theo trạng thái FACT (79), INFERENCE (8), BENCHMARK (12) và 6 danh mục nghiệp vụ.
- **Kiểm Toán Hiện Trạng 16 Miền Công Nghệ (Technology Audit)**: Chẩn đoán độ trưởng thành 0–5 điểm đối soát thực tế tại Tetra Pak & Nhà máy Bình Dương (€217M).
- **Đối Sánh Năng Lực 8 Tập Đoàn Máy Móc & Bao Bì (Competitor Benchmarking)**: Đánh giá mô hình thương mại hóa số của Tetra Pak, SIG Group, Krones, Sidel, GEA, Elopak, KHS, Syntegon.
- **Bộ Giả Lập Tồn Kho An Toàn & Quyết Định (Interactive Simulator)**: Thanh trượt tham số thời gian thực tính toán tồn kho an toàn $SS = Z \cdot \sqrt{\bar{L}\sigma_D^2 + \bar{D}^2\sigma_L^2}$ và ngày dự trữ bảo đảm (Days of Supply).
- **4 Hợp Đồng Dữ Liệu Chuẩn Quốc Tế (ODCS Data Contracts)**: Schema JSON cụ thể cho Vòng đời PO, Độ lệch Lead Time, Phân loại Ngoại lệ và Event Sourcing.

## 📁 Cấu Trúc Dự Án (Repository Structure)

```text
├── index.html                                    # Báo cáo chiến lược hoàn chỉnh (Single Page Web Report)
├── tetra-pak-master-ai-supply-chain-strategy.html# File báo cáo gốc
├── vercel.json                                   # Cấu hình một chạm cho Vercel Deployment
├── README.md                                     # Tài liệu tổng quan dự án
└── .gitignore                                    # Loại bỏ file nhạy cảm và rác hệ thống
```

## 🚀 Hướng Dẫn Sử Dụng & Triển Khai (Deployment)

1. **Mở cục bộ (Local)**:
   Mở trực tiếp file `index.html` hoặc `tetra-pak-master-ai-supply-chain-strategy.html` trên bất kỳ trình duyệt web hiện đại nào (Chrome, Safari, Edge, Firefox).

2. **Triển khai đám mây (Cloud Deployment)**:
   - Dự án đã tích hợp sẵn file `vercel.json`. Chỉ cần kết nối repository GitHub với Vercel để triển khai tự động với URL riêng.
   - Hoặc bật tính năng **GitHub Pages** trong phần cài đặt của Repository (Settings -> Pages -> Deploy from branch `main`).

---
*Bản quyền nội dung thuộc về Sunext Strategy Advisory & Nhóm Chuyên gia Tư vấn Chuyển đổi AI.*
