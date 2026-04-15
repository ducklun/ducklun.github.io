Arduino LM35 Temperature Monitor
Mô tả dự án
Hệ thống giám sát nhiệt độ thời gian thực sử dụng cảm biến LM35 và vi điều khiển Arduino. Dự án đọc dữ liệu từ 3 kênh cảm biến (A0, A1, A2), đóng gói dưới định dạng chuỗi JSON và gửi qua cổng Serial để giao tiếp với máy tính.

Tính năng
Đọc nhiệt độ từ 3 cảm biến LM35 độc lập.
Xử lý và lọc nhiễu tín hiệu ADC cơ bản.
Xuất dữ liệu qua cổng Serial với định dạng chuẩn JSON.
Hỗ trợ xem dữ liệu trực quan qua ứng dụng C# trên PC (hoặc Proteus).
Phần cứng cần thiết
Thiết bị	Số lượng	Ghi chú
Arduino UNO R3	1	Board vi điều khiển trung tâm
Cảm biến LM35	3	Cảm biến nhiệt độ Analog
Dây cắm	Nhiều	Dây cắm testboard
Cách sử dụng
Clone repository này về máy tính.
Mở file firmware/LM35_TempReader/LM35_TempReader.ino bằng Arduino IDE.
Cắm cáp kết nối Arduino với PC và chọn đúng cổng COM.
Bấm Upload để nạp code.
Mở Serial Monitor (Baudrate 9600) để xem dữ liệu JSON trả về.
Cấu trúc thư mục
Arduino_LM35_TempMonitor/
├── docs/
├── firmware/
│   └── LM35_TempReader/
│       └── LM35_TempReader.ino
├── libs/
├── pc_app/
├── simulation/
└── README.md
