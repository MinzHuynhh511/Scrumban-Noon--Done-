# 看板·日 — Scrumban & Noon Done (Unified Productivity Workspace)

> **Hợp nhất hoàn chỉnh giữa Bảng Kanban Agile (Scrumban) và Sổ tay Năng suất Buổi trưa (Noon Done).**  
> Thiết kế đồng bộ theo phong cách **Japanese Zen Dark Theme (和風)** dịu mắt, chống chói, tối ưu trải nghiệm và hiệu suất làm việc cả ngày dài.

---

## 🌟 Tổng quan tính năng hợp nhất

Ứng dụng được đóng gói hoàn chỉnh trong một file duy nhất.

### 1. 📋 Không gian Kanban & Agile Scrumban
- **3 Cột Kanban trực quan**: 待機 (Cần làm) ➡️ 進行 (Đang làm) ➡️ 完了 (Hoàn thành).
- **Thẻ Sticky Note giấy Washi**: Hỗ trợ 6 màu truyền thống Nhật Bản (Washi, Sakura, Matcha, Indigo, Fuji, Kohaku), hiệu ứng xoay góc ngẫu nhiên tự nhiên và băng dính Washi ở mép trên.
- **Kéo thả mượt mà**: Hỗ trợ HTML5 Drag & Drop mượt mà giữa các cột.
- **Quản lý Story Points (SP)**: Dãy Fibonacci (1, 2, 3, 5, 8, 13 SP), tính điểm và tiến độ tự động.
- **WIP Limit Warning (Giới hạn công việc đang làm)**: Cảnh báo thông minh khi cột Doing vượt quá 3 công việc ("Stop starting, start finishing").
- **⚡ Chế độ Scrum / Simple chuyển đổi nhanh**:
  - Bật để quản lý Sprint 14 ngày, biểu đồ Burndown Chart, Backlog, Daily Standup và Retrospective.
  - Tắt để quay về bảng Kanban kéo thả tối giản, rộng rãi.
- **Biểu đồ Burndown Chart thời gian thực**: Vẽ trên Canvas HTML5 hiển thị đường lý tưởng và đường thực tế.
- **Product Backlog & Lịch sử Sprint**: Quản lý User Stories, đưa vào Sprint bằng 1 click và xem lại velocity các Sprint trước.
- **Daily Standup & Retrospective (KPT)**: Ghi chú 3 câu hỏi sáng và đánh giá cuối kỳ (🌸 Tốt, 🍂 Cải thiện, 🎋 Hành động).
- **Widget "Bạn có biết? · Mẹo Kaizen"**: Carousel tự động chuyển 8 bí quyết làm việc hiệu quả với nút tạm dừng/tiếp tục.

---

### 2. ☀️ Không gian Noon Done (Buổi trưa nhìn lại — Buổi chiều làm đúng)
- **⭐ Việc quan trọng nhất chiều nay (Priority Task)**: Chọn duy nhất 1 việc trọng tâm để tạo đòn bẩy cho buổi chiều.
- **Bảng kép Sáng & Chiều (Morning & Afternoon)**: Thiết kế dòng kẻ tập vở viết tay (notebook ruled lines), đánh dấu hoàn thành nhanh.
- **🌱 Học kỹ năng mỗi ngày (Daily Skill Practice)**:
  - Đặt bài học nhỏ cam kết gạch bỏ mỗi ngày (tiếng Nhật, coding, đọc sách...).
  - **🔥 Chuỗi ngày liên tục (Streak Counter)**: Tự động đếm chuỗi kỷ luật không gián đoạn.
  - **Bản đồ nhiệt 30 ngày (30-Day Heatmap)**: Theo dõi trực quan thói quen trong tháng.
  - **Gợi ý nhanh (Quick Chips)**: 1-click chọn bài học mẫu.
- **📖 Nhìn lại tuần qua (Weekly Review)**:
  - Xem dòng thời gian từng ngày (Thứ 2 đến Chủ nhật) kèm việc đã làm/chưa làm.
  - Tổng kết số việc hoàn thành, số ngày học kỹ năng và ngày có hoạt động.
  - Khung phản tư tuần (Weekly Reflection) lưu trữ theo tuần.

---

### 3. 📊 Không gian Dashboard (Tổng quan năng suất)
- **Chỉ số tổng hợp theo thời gian thực**:
  - Tổng số Kanban Tasks & số việc hoàn thành.
  - 🔥 Chuỗi kỷ luật học kỹ năng liên tục.
  - Tổng Story Points (SP) đã tích lũy.
  - Tiến độ % và vòng tròn hoàn thành của Sprint hiện tại.
- **📈 Biểu đồ cột hoạt động 7 ngày qua**: Vẽ trực tiếp bằng Canvas HTML5, tự động tính tổng công việc hoàn thành từ cả Kanban và Noon Done.
- **Bản đồ nhiệt kỹ năng 30 ngày & Triết lý Kaizen**: Câu nói truyền cảm hứng ngẫu nhiên giúp duy trì năng lượng tích cực.

---

### 4. 🚀 Các tính năng tối ưu công việc mới bổ sung
1. **🍅 Đồng hồ Pomodoro nổi (Floating Timer)**:
   - Nhịp điệu 25 phút tập trung / 5 phút nghỉ ngơi / 15 phút nghỉ dài.
   - **Chuông thiền Zen (Zen Chime)**: Tạo âm thanh chuông bát xoay Tây Tạng (528 Hz) bằng Web Audio API thuần (không cần file âm thanh ngoài, chạy offline 100%).
   - Thu nhỏ góc trái hoặc mở nhanh bằng phím tắt `P`.
2. **🔍 Tìm kiếm nhanh toàn cục (`Ctrl + K`)**:
   - Tìm kiếm tức thì trong toàn bộ Kanban tasks, Backlog, danh sách sáng/chiều Noon Done, kỹ năng và ghi chú.
   - Nhấp vào kết quả để tự động chuyển tab và cuộn đến thẻ công việc.
3. **🔗 Tích hợp chéo 2 chiều (Cross-App Integration)**:
   - **Noon Done ➡️ Kanban**: Nút *"📋 Gửi việc chiều sang Kanban"* tự động chuyển việc chiều chưa làm thành thẻ Sticky Note ở cột To Do.
   - **Kanban ➡️ Noon Done**: Nút *"⭐"* trên từng Sticky Note cho phép đặt ngay việc đó làm *"Việc quan trọng nhất chiều nay"* trong Noon Done.
4. **💾 Sao lưu & Phục hồi dữ liệu hoàn chỉnh (JSON Backup & Restore)**:
   - Xuất file `.json` dự phòng chỉ với 1 click.
   - Nhập file `.json` để khôi phục hoặc đồng bộ dữ liệu giữa các máy tính.
   - Tùy chọn khôi phục dữ liệu mẫu hoặc xóa sạch để bắt đầu lại.
5. **⚙️ Cài đặt cá nhân hóa**:
   - Đặt tên người dùng (lời chào cá nhân hiển thị trên tiêu đề).
   - Đặt mục tiêu học kỹ năng mặc định mỗi ngày.
   - Cấu hình giới hạn WIP limit cho cột Doing (mặc định 3 việc).
   - Bật / Tắt chuông chuông thiền Pomodoro.
6. **❓ Hướng dẫn tương tác từng bước (Interactive Tour Guide)**:
   - Spotlight hướng dẫn 6 bước chi tiết cho người dùng mới.
7. **🌐 Đa ngôn ngữ (Tiếng Việt & English)**:
   - Chuyển đổi ngôn ngữ tức thì giữa `VI` và `EN`.

---

## ⌨️ Bảng phím tắt nhanh

| Phím tắt | Chức năng |
|---|---|
| `Ctrl + N` | Mở cửa sổ thêm công việc mới |
| `Ctrl + K` | Mở thanh tìm kiếm toàn cục |
| `1` | Chuyển sang bảng **Kanban** |
| `2` | Chuyển sang trang **Noon Done** |
| `3` | Chuyển sang trang **Dashboard** |
| `P` | Bật / Tắt đồng hồ **Pomodoro** |
| `?` | Mở bảng trợ giúp phím tắt |
| `Esc` | Đóng mọi cửa sổ bật lên / modal |

---

    ├── index.html               # File ứng dụng duy nhất (HTML + CSS + JS)
    └── README.md                # Tài liệu hướng dẫn sử dụng chi tiết
```

