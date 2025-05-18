# TradingView Bot Telegram

## Giới thiệu
Bot Telegram này hỗ trợ người dùng lấy dữ liệu nến lịch sử từ TradingView, vẽ biểu đồ nến và hiển thị các chỉ báo kỹ thuật như MA, EMA, Bollinger Bands, SAR, và AVL. 

## Link bài viết: https://www.facebook.com/share/p/19QhtaXqWa/

## Chức năng
- Lấy dữ liệu nến lịch sử của một cặp tiền điện tử hoặc tài sản tài chính.
- Vẽ biểu đồ nến kèm các chỉ báo kỹ thuật.
- Hỗ trợ các chỉ báo:
  - MA (Moving Average)
  - EMA (Exponential Moving Average)
  - Bollinger Bands
  - SAR (Parabolic SAR)
  - AVL (Average Volume Level)
- Hỗ trợ người dùng qua các lệnh Telegram.

## Yêu cầu
- Python 3.x
- `telebot` để kết nối với Telegram API.
- `matplotlib` để vẽ biểu đồ.
- `numpy` để tính toán chỉ báo kỹ thuật.
- `pandas` để xử lý dữ liệu lịch sử.
- và 1 số thư viện khác

## Cài đặt
Cài đặt các thư viện cần thiết bằng lệnh.

```sh
khi chạy file sẽ tự động cài đặt thư viện cần thiết. 
```

## Lưu ý
- Cập nhật `BOT_TOKEN` trong mã nguồn để sử dụng bot.
- Bot cần quyền gửi ảnh trên Telegram.
- Timeframe hợp lệ theo sàn giao dịch tính theo phút (minutes)

# Screenshot 

## Ví dụ với đồng DOGEUSDT thì các biểu đồ với chỉ báo bot tạo ra từ dữ liệu là.

## Chỉ báo MA
![image](https://github.com/user-attachments/assets/d58a4f81-8ec6-497e-8452-40fea0edbd1e)

## Chỉ báo EMA
![image](https://github.com/user-attachments/assets/bb8ca346-e90e-472c-9e5d-6a9ebfbfdfd0)

## Chỉ báo Boll
![image](https://github.com/user-attachments/assets/397f53a1-b850-45ee-86b1-08d8d0374c6f)

## Chỉ báo SAR
![image](https://github.com/user-attachments/assets/834992c8-6e8f-4da3-ba70-b4d97fa4e375)

## Chỉ báo AVL
![image](https://github.com/user-attachments/assets/b78c87aa-8844-4d75-aba5-3265690cad43)







