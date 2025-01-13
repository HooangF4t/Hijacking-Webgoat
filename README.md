# Hijacking-Webgoat
A1:Chiếm đoạt một phiên 
- Khái niệm: Các nhà phát triển ứng dụng phát triển ID phiên của riêng họ thường quên kết hợp sự phức tạp và ngẫu nhiên cần thiết cho bảo mật. Nếu ID phiên cụ thể của người dùng không phức tạp và ngẫu nhiên, thì ứng dụng rất dễ bị tấn công brute force dựa trên phiên.
- Mục tiêu: Có quyền truy cập vào phiên đã xác thực thuộc về người khác.

tới chỗ thử thách xem hint
Ctrl + shift + i -> strorage -> cookies
copy value của thk JSESSIONID sẽ dùng tới sau
- b1: tải www.cygwin.com - nếu không biết setuo thì có thể tham khảo tại đây https://courses.cs.washington.edu/courses/cse154/19sp/resources/assets/shells/cygwin.html tôi recommend https://download.nus.edu.sg (sing hoặc đài loan https://ftp.ntu.edu.tw).
- b2: lấy tệp hacking.sh - https://github.com/tuyendt0112/hijacking hoặc bản tùy chỉnh của mình https://github.com/HooangF4t/Hijacking-Webgoat/tree/main
- b3: Lấy JSESSION lúc nãy để thay vào
- b4: mở cygdrive
- b5: cmd di chuyển tới chỗ lưu tệp hacking.sh - cd D:/1\ GDU/Inprogress/An\ toan\ thuong\ mai\ dien\ tu/Webgoat/hijacking-main
- b6: Thay đổi thông tin trong tệp hacking.sh (chỗ này là tài khoản mật khẩu và JSESSIONID
- b7: chạy file sh hacking.sh
