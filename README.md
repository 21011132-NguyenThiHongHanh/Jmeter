
# Mô tả bài tập
- Mô tả bài tập: Bài tập này nhằm mục đích kiểm tra hiệu suất của trang web "baomoi.com" lấy tên HomePage .Quan tâm đến thời gian phản hồi, tỉ lệ lỗi, và khả năng xử lý request của máy chủ
# Kịch bản kiểm tra
- Kịch bản kiểm tra:
    + Tạo một HTTP Request để truy cập vào trang "baomoi.com".
    + Sử dụng JMeter để tạo tải trọng với 999 request.
    + Thu thập dữ liệu về thời gian phản hồi, tỉ lệ lỗi, và khả năng xử lý request của máy chủ.
# Jmeter
+ Tên http request : HomePage
+ Số lượng request đã thực hiện : 999
+ Thời gian phản hồi trung bình: 9313ms
+ Thời gian sử ly request ở giữa: 8319ms
+ 90% Line: nghĩa là 90% số requests sẽ có trong đáp ứng nhỏ hơn giá trị hiện thị trong table, 10% số requests còn lại sẽ có thời gian đáp ứng lớn hơn gtri hiển thị trong table là 13885ms 
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
![Screenshot 2024-05-30 085355](https://github.com/21011132-NguyenThiHongHanh/Jmeter/assets/124747121/77d4a2f7-9553-48b3-b9b6-5198019f1b46)

![Screenshot 2024-05-30 090607](https://github.com/21011132-NguyenThiHongHanh/Jmeter/assets/124747121/96ac17aa-d3fa-4707-821f-cca7543c062d)
# Kết luận về hiệu năng trang web
+ Thời gian phản hồi trung bình khá cao, đạt 9319ms --> điều này có thể làm giảm trải nghiệm người dùng và cần được cải thiện
+ Tỉ lệ lỗi đáng lo ngại (83.78%) cần phải tìm hiểu nguyên nhân để khắc phục
+ Số request server có thể xử lý mỗi giây là 39.9, điều này có thể là một hạn chế đối với việc đáp ứng nhu cầu của người dùng.
+ Nhóm Chủ Đề 1-211: Trong nhóm này, thời gian tải và độ trễ ổn định, không gặp phải lỗi. Điều này cho thấy rằng không phải tất cả các phần của trang web đều gặp vấn đề về hiệu suất
  -->Dựa vào các vấn đề trên, để kiểm tra hiệu năng của trang web, cần thực hiện các bước sau:
- Phân tích và Điều tra nguyên nhân:
    + Xác định nguyên nhân của thời gian phản hồi chậm và tỉ lệ lỗi cao.
    + Kiểm tra xem có vấn đề về cấu hình máy chủ, mã nguồn, hoặc tài nguyên hệ thống không.
- Thử nghiệm và đánh giá lại
    + Thực hiện kiểm tra lại sau khi thực hiện các biện pháp tối ưu hóa để xác định hiệu quả của chúng.
    + Theo dõi và đánh giá lại các chỉ số hiệu suất để đảm bảo rằng đã đạt được cải thiện.
- Giám sát liên tục:
    + Thực hiện giám sát liên tục để phát hiện và xử lý sớm các vấn đề về hiệu suất.
    + Sử dụng các công cụ giám sát hệ thống để theo dõi và phản ứng nhanh chóng khi có vấn đề xảy ra.
# Tổng kết đánh giá: 
+ Thời gian phản hổi trung bình cho các request trên HomePage khá cao là 9313ms
+ Tỉ lệ % lỗi của trang web khá cao là 83.78%
+ Trong nhóm chủ đề 1-211, không có lỗi nào được báo cáo và thời gian phản hồi là 8374ms, độ trễ là 7675ms, đều ổn định
+ Kích thước tổng thể của trang web khá lớn đòi hỏi tốc độ mạng cao để tải và không gây cản trở cho người dùng
--> Tóm lại, trang web cần cải thiện hiệu suất và giảm tỉ lệ lỗi để cung cấp trải nghiệm tốt hơn cho người dùng
