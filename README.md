# Jmeter
# Mục tiêu
- Sử dụng jMeter để tạo một kịch bản kiểm tra mô phỏng người dùng truy cập trang web https://phenikaa-uni.edu.vn/vi.
- Chạy kịch bản kiểm tra và ghi lại kết quả.
- Phân tích kết quả kiểm tra, bao gồm thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v.
- Dựa trên kết quả phân tích, đưa ra kết luận về hiệu năng của trang web.

# Kịch bản kiểm tra
- Thread Group:
+ Số lượng thread: 100
+ Thời gian chạy: 100 giây
+ Ramp-up period: 10 giây
- HTTP Request:
+ URL: https://phenikaa-uni.edu.vn/vi
+ Method: GET
+ Content encoding: UTF-8
- Listeners:
+ View Results Tree
+ Aggregate Report

# Kết quả kiểm tra
![a](https://github.com/Kien1804/Jmeter/assets/124127812/94ed8d6b-b754-484f-a281-032ca921584d)

HTTP request
![b](https://github.com/Kien1804/Jmeter/assets/124127812/9e15e37a-11d9-45d7-a01a-a9a784717adc)
Kết quả 100 người truy cập cùng 1 lúc

![c](https://github.com/Kien1804/Jmeter/assets/124127812/81618117-0d3c-455e-8277-0fcb2e8e9e04)

- Phân tích:

+ Tỷ lệ thành công cao: 503/510
