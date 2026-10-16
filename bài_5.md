# Xây dựng bộ tài liệu kỹ thuật cho dự án Smart Farm

## Phần 1. Phân tích hệ thống & Xử lý sự cố
 **Input / Output** 

- Input: Cảm biến độ ẩm đất, cảm biến nhiệt độ DHT22.

- Output: Máy bơm nước, hệ thống phun sương.

**Mô hình DIKW Quy trình dữ liệu**
- Data: Thông số thô 34.5 độ C, độ ẩm 28%
- Infomation: Khu vực trồng lan đang thiếu nước nghiêm trọng 
- Knowledge: Ngưỡng nhiệt độ này làm héo hoa lan, cần kích hoạt phun sương
- Wisdom: Tự động bật máy bơm và lưới che nắng để bảo vệ vườn 

**Xử lý sự cố tràn RAM**
- Tạm dừng ghi log thời gian thực qua CLI 
- Khởi động lại vi điều khiển 
- Cấu hình giới hạn bộ nhớ đệm để tránh lặp lại 

## Phần 2. File README.md
# 🚀 Smart-Farm Lan System

Hệ thống IoT tự động chăm sóc hoa lan cho trang trại.

## ⚙️ Cài đặt hệ thống
```bash
git clone [https://github.com/hgb2007-hcm/stage-10.git](https://github.com/hgb2007-hcm/stage-10.git)
cd stage-10
npm install smart-farm-iot-lib