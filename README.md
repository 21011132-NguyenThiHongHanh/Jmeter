
# Mô tả bài tập
- Mô tả bài tập: Bài tập này nhằm mục đích kiểm tra hiệu suất của trang web "baomoi.com" .Quan tâm đến thời gian phản hồi, tỉ lệ lỗi, và khả năng xử lý request của máy chủ
# Kịch bản kiểm tra
- Kịch bản kiểm tra:
    + Tạo một HTTP Request để truy cập vào trang "baomoi.com".
    + Sử dụng JMeter để tạo tải trọng với 999 request.
    + Thu thập dữ liệu về thời gian phản hồi, tỉ lệ lỗi, và khả năng xử lý request của       máy chủ.
# Jmeter
+ Tên http request : HomePage
+ Số lượng request đã thực hiện : 999
+ Thời gian phản hồi trung bình: 9313 ms
+ Thời gian sử ly request ở giữa: 8319 ms
+ 90% Line: nghĩa là 90% số requests sẽ có trong đáp ứng nhỏ hơn giá trị hiện thị trong table, 10% số requests còn lại sẽ có thời gian đáp ứng lớn hơn gtri hiển thị trong table là 13885 ms 
+ 95% Line: nghĩa là 95% số requests sẽ có trong đáp ứng nhỏ hơn giá trị hiện thị trong table, 5% số requests còn lại sẽ có thời gian đáp ứng lớn hơn gtri hiển thị trong table là 14767ms
+ 99% Line: nghĩa là 95% số requests sẽ có trong đáp ứng nhỏ hơn giá trị hiện thị trong table, 1% số requests còn lại sẽ có thời gian đáp ứng lớn hơn gtri hiển thị trong table là 22295ms
+ Thời gian ngắn nhất: 2722ms
+ Thời gian phản hồi lớn nhất: 24941ms
+ Tỉ lệ % số request bị lỗi (không nhận được phản hồi từ server) là 83.78%
+ Số request server có thể sử lý: 39.9/sec
+ Thông lượng KB nhận được: 2056.94/s
+ Thông lượng KB gửi đi : 8.52/s

Hình ảnh
![Screenshot 2024-05-30 085310](https://github.com/21011132-NguyenThiHongHanh/Jmeter/assets/124747121/3fedee1e-fc0f-4c95-bced-19ab8abcfda5)


# Jmeter
+ Nhóm chủ đề :1-211
+ Thời gian bắt đầu: 2024-05-30 05:49:30
+ Thời gian tải: 8374ms
+ Thời gian kết nối:476ms
+ Độ trễ:7675ms
+ kích thước: 322899 bytes
+ Số bytes đã gửi : 224
+ Kích thước tiêu đề:502 bytes
+ Kích thước tổng thể:322397 bytes
+ số lượng mẫu :1
+ Số lượng lỗi :0
+ Kiểu dữ liệu: text
+ Phản hôi: 200
+ Tin nhắn phẩn hồi: OK

Hình ảnh
C:\Users\Hong Hanh\Pictures\Screenshots\Scr![Screenshot 2024-05-30 085355](https://github.com/21011132-NguyenThiHongHanh/Jmeter/assets/124747121/77d4a2f7-9553-48b3-b9b6-5198019f1b46)
eenshot 2024-05-30 085355.png
![Screenshot 2024-05-30 090607](https://github.com/21011132-NguyenThiHongHanh/Jmeter/assets/124747121/96ac17aa-d3fa-4707-821f-cca7543c062d)

# Tổng kết đánh giá: 
+ Thời gian phản hổi trung bình cho các request trên HomePage khá cao là 9313ms
+ Tỉ lệ % lỗi của trang web khá cao là 83.78%
+ Trong nhóm chủ đề 1-211, không có lỗi nào được báo cáo và thời gian phản hồi là 8374ms, độ trễ là 7675ms, đều ổn định
+ Kích thước tổng thể của trang web khá lớn đòi hỏi tốc độ mạng cao để tải và không gây cản trở cho người dùng
--> Tóm lại, trang web cần cải thiện hiệu suất và giảm tỉ lệ lỗi để cung cấp trải nghiệm tốt hơn cho người dùng
