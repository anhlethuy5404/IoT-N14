# IoT-N14
File CameraWebServer.ino lưu code để nạp ESP32-CAM
- Sử dụng hàm startCameraServer() trong app_httpd.cpp
- Lấy config từ board_config.h, từ board_config.h dẫn tới camera_pins.h để lấy các chân cổng gán cho ESP cam (Y2_GPIO_NUM, Y3_GPIO_NUM);
- Setup nhận wifi và lấy được địa chỉ IP
