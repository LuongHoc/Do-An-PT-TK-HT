# Đồ án phân tích và thiết kế hệ thống
# Lương Văn Học - K225480106025
# Đề bài: Phân tích và thiết kế hệ thống quản lý bãi gửi xe thông minh tại trường Đại học kỹ thuật Công nghiệp Thái Nguyên
## I. Giới thiệu
### 1. Lý do chọn đề tài
- Bãi gửi xe trong trường thường xuyên quá tải, khó quản lý.
- Phương pháp truyền thống (ghi vé giấy, kiểm tra thủ công) gây mất thời gian và dễ thất thoát doanh thu.
- Cần hệ thống thông minh giúp tự động hóa quy trình gửi xe, thanh toán điện tử và quản lý dữ liệu hiệu quả.
### 2. Phạm vi và đối tượng áp dụng
- Địa điểm: Bãi gửi xe của Đại học Kỹ thuật Công nghiệp Thái Nguyên.
- Đối tượng sử dụng: Sinh viên, giảng viên, nhân viên quản lý bãi xe, quản trị viên hệ thống.
## II. Khảo sát hệ thống hiện tại và yêu cầu hệ thống mới
### 1. Thực trạng quản lý bãi xe tại trường
- Hiện tại sử dụng vé giấy hoặc thẻ cứng, dễ mất vé hoặc gian lận.
- Không có cơ chế kiểm soát thời gian gửi xe chính xác.
- Giờ cao điểm dễ gây ùn tắc.
### 2. Yêu cầu hệ thống mới
#### Chức năng dành cho khách hàng (Sinh viên, Giảng viên, Nhân viên gửi xe)
- Đăng ký xe: 
Đăng ký thông tin xe (biển số, loại xe, chủ sở hữu).
Cấp thẻ RFID hoặc kích hoạt nhận diện biển số.
- Gửi xe vào bãi: 
Quét thẻ RFID hoặc nhận diện biển số.
Hệ thống kiểm tra thông tin và hiển thị số chỗ trống còn lại.
Barrier tự động mở nếu hợp lệ.
- Lấy xe ra khỏi bãi: 
Quét thẻ hoặc nhận diện biển số.
Hệ thống kiểm tra thời gian gửi, tính phí (nếu có).
Thanh toán online hoặc tiền mặt.
Barrier mở khi thanh toán thành công.
- Tra cứu thông tin gửi xe: 
Xem lịch sử vào/ra.
Kiểm tra thời gian gửi xe hiện tại.
Kiểm tra số dư tài khoản (nếu dùng ví điện tử).
- Thanh toán tiền gửi xe: 
Hỗ trợ thanh toán bằng:
Momo, ZaloPay, VietQR, thẻ ngân hàng.
Thanh toán trực tiếp tại quầy.
#### Chức năng dành cho nhân viên bãi xe
- Quản lý xe vào/ra: 
Kiểm tra biển số hoặc thẻ RFID.
Xác minh thông tin xe hợp lệ.
Giải quyết sự cố khi nhận diện thất bại.
- Quản lý vé gửi xe: 
Cấp vé cho khách vãng lai.
Hỗ trợ khách mất thẻ, quên thông tin.
- Xử lý sự cố: 
Giải quyết trường hợp xe không hợp lệ.
Hỗ trợ kiểm tra xe nghi vấn (điều tra mất cắp).
- Quản lý doanh thu: 
Kiểm tra số tiền thu từ gửi xe theo ca làm việc.
Xuất báo cáo doanh thu theo ngày/tháng/năm.
#### Chức năng dành cho quản trị viên
- Quản lý tài khoản: 
Tạo/sửa/xóa tài khoản nhân viên.
Phân quyền truy cập cho từng loại nhân viên.
- Quản lý bãi gửi xe: 
Xác định số chỗ trống, số xe đang gửi.
Điều chỉnh mức phí gửi xe theo loại xe, thời gian.
- Báo cáo & Thống kê: 
Báo cáo lượng xe vào/ra theo thời gian.
Báo cáo doanh thu từ vé gửi xe.
Thống kê lỗi, sự cố xảy ra trong hệ thống.
- Cấu hình hệ thống: 
Cấu hình phương thức thanh toán
Điều chỉnh quy định gửi xe (thời gian tối đa, mức phạt).
## III. Phân tích hệ thống
## IV. Thiết kế hệ thống
## V. Triển khai hệ thống
## VI. Kết luận
