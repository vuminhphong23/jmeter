# jmeter

# Mục tiêu:
  - Sử dụng jMeter để tạo một kịch bản kiểm tra mô phỏng người dùng truy cập trang web https://www.facebook.com.
  - Chạy kịch bản kiểm tra và ghi lại kết quả.
  - Phân tích kết quả kiểm tra, bao gồm thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v.
  - Dựa trên kết quả phân tích, đưa ra kết luận về hiệu năng của trang web.
# Kịch bản kiểm tra:
  - Thread Group:
    + Số lượng thread: 100
    + Thời gian chạy: 180 giây
    + Ramp-up period: 10 giây
  - HTTP Request:
  - URL: https://www.facebook.com
  - Method: GET
  - Content encoding: UTF-8
# Listeners:
  - View Results Tree
  - Aggregate Report
# Kết quả kiểm tra:
![image](https://github.com/vuminhphong23/jmeter/assets/124127169/4a71c350-d809-438b-bcd6-aa8ebc3c93f3)

![image](https://github.com/vuminhphong23/jmeter/assets/124127169/bcc2fb69-1288-4ecc-b537-9cf471e1373b)

