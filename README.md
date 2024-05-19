# Nhận diện cử chỉ tay điều khiển xe robot
## Tổng quan:   
Dự án này phát triển một hệ thống điều khiển xe robot bằng cách nhận dạng cử chỉ tay. Hệ thống sử dụng thư viện Mediapipe, được phát triển bởi Google, để nhận diện và phân loại chính xác các cử chỉ tay thành năm lệnh: Dừng, Tiến, Lùi, Rẽ phải và Rẽ trái.

## Tác giả:
Trần Duy Thành  
Nguyễn Trung Thông  
Đỗ Thị Trang   
Vũ Văn Trí   
Người hướng dẫn: TS.Nguyễn Thị Bích Thủy

## Môi trường
Hệ điều hành: Windows 
Ngôn ngữ: Python 3.7 trở lên  
Thư viện: mediapipe, opencv-python  

## Cài đặt
1. Clone repository: git clone https://github.com/ThanhTranDz/NCKH_RobotCar.git
2. Cài đặt các thư viện yêu cầu.
3. Phần cứng:
NodeMCU ESP8266
Bộ điều khiển động cơ L298
Động cơ DC

## Phương pháp 
Nhận diện cử chỉ
Mediapipe và OpenCV: Sử dụng để phát hiện và phân loại các cử chỉ tay.
Các lớp cử chỉ: Hệ thống nhận diện năm cử chỉ: Dừng, Tiến, Lùi, Rẽ phải, Rẽ trái.
Điều khiển xe robot
NodeMCU ESP8266: Vi điều khiển sử dụng để nhận lệnh từ cử chỉ và điều khiển xe robot.
Bộ điều khiển động cơ L298: Sử dụng để điều khiển động cơ DC của xe robot.

## Kết quả
Hệ thống nhận diện chính xác các cử chỉ tay và điều khiển xe robot theo các lệnh đã được lập trình. 
