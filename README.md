# Data Scientist Testing 

## Description

Đây là tập sample lịch sử sử dụng dịch vụ truyền hình HD của tập user đã hủy hợp đồng hệ thống.

### Tasks
* Parse log lấy ra các thuộc tính: MAC, SessionMainMenu, AppName, LogID, Event, ItemID, RealTimePlaying.
     * Output: tập log mới với format là dạng row, column. Mỗi row tương ứng dòng log, mỗi column tương ứng trường thuộc tính. Mỗi column cách nhau dấu tab
* Kết hợp file user_info.txt và tập data đã parse, phân tích hành vi đặc điểm sử dụng dịch vụ của những user này
* Dựa vào kết quả phân tích, đề ra giải pháp dự đoán user dự đoán user có khả năng hủy sử dụng dịch vụ

## Note
* User_info.txt: lưu thông tin số ngày sử dụng dịch vụ của user
* Log data:
     * MAC: userID
     * SessionMainMenu: thời điểm user bắt đầu sử dụng dịch vụ
     * AppName: loại app user sử dụng
     * LogID: mã log
     * Event: thao tác user
     * ItemID: ID chương trình user xem
     * RealTimePlaying: thời lượng xem user.


## Built With

* [Dataset](http://www.mediafire.com/download/2cgxl82jc9eshfx/DataSampleTest.rar)
* Language: Python

## Authors

* [**Lanh Nguyen**](https://github.com/nguyenlanh)

