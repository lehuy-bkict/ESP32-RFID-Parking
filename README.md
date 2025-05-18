# ESP32-RFID-Parking
Dự án này là hệ thống kiểm soát bãi đỗ xe sử dụng ESP32 và đầu đọc RFID. Khi quét thẻ, dữ liệu được gửi về server qua MQTT và hiển thị lên giao diện web theo thời gian thực bằng Socket.IO. Dữ liệu sẽ được lưu vào mongoDB để kiểm soát dữ liệu vào/ra.

Phần cứng yêu cầu:
ESP32-RF522

Tiếp đó hãy kết nối phần cứng và nạp code ở folder ESP32_RC522

Vào thư mục server_run cấu hình file .env cho đúng kiểu dữ liệu và bắt đầu chạy file .exe

Nếu bạn có bất kỳ câu hỏi nào, vui lòng liên hệ với tôi:

✉ email: huyle.bkict@gmail.com

LinkedIn: www.linkedin.com/in/hoang-huy-le-35603b342
