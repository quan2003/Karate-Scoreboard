# 🚀 HƯỚNG DẪN SỬ DỤNG NHANH - KUMITE SCOREBOARD

## 📺 CÁCH MỞ HỆ THỐNG:

### 1. Mở Admin Panel:

```
Mở file: Kumite Scoreboard/admin.html
Hoặc: http://127.0.0.1:5500/Kumite%20Scoreboard/admin.html
```

### 2. Mở Display Screen:

- Click nút **"📺 Open Display Window"** trong Admin Panel
- Hoặc mở riêng: `Kumite Scoreboard/display.html`
- Nhấn **F11** để fullscreen

---

## ⚙️ THIẾT LẬP BAN ĐẦU:

1. **Event Title**: Nhập "Thảm 1", "Thảm 2"... (mặc định: Thảm 1)
2. **Red Name**: Tên VĐV đỏ (AKA)
3. **Blue Name**: Tên VĐV xanh (AO)
4. **Category**: Hạng cân (mặc định: PENALTY)
5. **Vòng thi đấu**: Chọn vòng (Chung Kết, Bán Kết...)

---

## 🎮 SỬ DỤNG KHI THI ĐẤU:

### ⏱️ Điều khiển Timer:

- **Start**: Bắt đầu đồng hồ
- **Stop**: Dừng đồng hồ
- **Reset**: Đặt lại về 3:00
- **+/-**: Điều chỉnh giây
- **Speed**: Tốc độ (1x, 2x, 5x, 10x)

### 🥋 Cho điểm:

#### Cho AKA (Đỏ) điểm:

- **Yuko**: +1 điểm → Màn hình đỏ "YUKO 1 POINT"
- **Waza-ari**: +2 điểm → Màn hình đỏ "WAZA-ARI 2 POINTS"
- **Ippon**: +3 điểm → Màn hình đỏ "IPPON 3 POINTS"
- **Senshu**: Đánh dấu ghi điểm trước → Hiển thị ô "S" đỏ

#### Cho AO (Xanh) điểm:

- Tương tự nhưng nút bên phải, màn hình xanh

### ⚠️ Cho Warning (Phạt):

Tick checkbox:

- **C1, C2, C3**: Cảnh cáo → Màn hình vàng "WARNING C1/C2/C3"
- **HC**: Hansoku Chui → Màn hình vàng "WARNING HC"
- **H**: Hansoku (loại) → Màn hình vàng "WARNING H"

### 🔄 Xóa điểm:

- **-Yuko**: Trừ 1 điểm
- **-Waza-ari**: Trừ 2 điểm
- **-Ippon**: Trừ 3 điểm

### 🏆 Kết thúc trận:

- **Red Wins**: AKA thắng (màn hình nhấp nháy đỏ)
- **Blue Wins**: AO thắng (màn hình nhấp nháy xanh)
- **🏁 Kết Thúc Trận & Lưu Kết Quả**: Lưu vào bảng medals

### 🔄 Reset:

- **Reset All**: Đặt lại tất cả về 0

---

## 👥 CHẾ ĐỘ ĐỒNG ĐỘI:

### Chuyển sang chế độ đồng đội:

1. Click **"👥 Đồng Đội"**
2. Hiển thị thêm thông tin Round

### Quản lý Round:

- **Round hiện tại**: Hiển thị "1 / 5"
- **✅ Kết Thúc Round**: Lưu kết quả round, chuyển sang round tiếp theo
- **📜 Xem Lịch Sử**: Xem kết quả các round đã đấu
- **Điểm đồng đội**: Tự động cập nhật "AKA: 2 - AO: 1"

---

## 🎯 HIỆU ỨNG ĐẶC BIỆT:

### Khi cho điểm:

✅ Hiển thị fullscreen 2 giây:

- Background màu đỏ/xanh
- Tên điểm cỡ chữ khổng lồ
- Số điểm bên dưới

### Khi cho warning:

✅ Hiển thị fullscreen 2 giây:

- Background màu vàng
- Chữ "WARNING"
- Loại lỗi (C1, C2...)

### Khi có Senshu + Điểm:

✅ Hiển thị tuần tự:

1. Hiển thị điểm (2 giây)
2. Đợi 0.5 giây
3. Hiển thị Senshu (2 giây)

---

## 📊 XEM KÉT QUẢ:

Click **"🏆 Quản Lý Kết Quả & Huy Chương"**

- Xem danh sách tất cả trận đã lưu
- Xem bảng huy chương
- In/Export kết quả

---

## 💡 MẸO:

1. **Luôn mở Display trên màn hình riêng** (màn hình thứ 2, TV, projector)
2. **Admin ở màn hình chính** để điều khiển
3. **Fullscreen Display (F11)** cho trải nghiệm tốt nhất
4. **Kiểm tra Event Title** trước khi bắt đầu
5. **Lưu kết quả** sau mỗi trận (nút 🏁)
6. **Upload CSV** để load nhanh danh sách VĐV

---

## ⌨️ PHÍM TẮT:

- **Space**: Start/Stop timer
- **R**: Reset timer (khi không focus vào input)

---

## 🐛 KHẮC PHỤC SỰ CỐ:

### Display không cập nhật?

1. Refresh Display window (F5)
2. Kiểm tra Console (F12) xem có lỗi không
3. Đóng và mở lại Display window

### Timer không chạy?

1. Click Start lại
2. Check Speed (phải là 1x trở lên)

### Điểm không đúng?

1. Dùng nút -Yuko, -Waza-ari, -Ippon để sửa
2. Hoặc Reset All và nhập lại

---

**Chúc bạn tổ chức giải đấu thành công! 🥋🏆**
