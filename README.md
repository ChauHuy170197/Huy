# Trả Lời Các Câu Hỏi
# Phần 1: Hiểu biết về server và linux căn bản
1: Phần cứng server là những bộ phận có thể nhìn thấy được, bao gồm như là chíp CPU(trung tâm xử lý), Mainboard(mạch điện chính, kết nối các phần thiết bị trong máy), ổ cứng(lưu trữ dữ liệu), Ram(có 2 loại Ram là SDR và DRR), Chassis server(thùng máy bảo vệ linh kiện bên trong), Card Raid.

2: Tủ Rack hiểu nó là tủ đựng các thiết bị mạng của doanh nghiệp, giúp tối ưu hóa các thiết bị mạng, tùy theo nhu cầu mà chọn loại tủ khác nhau, đơn vị đo kích thước của tủ là U, số U càng lớn thì khả năng lưu trữ nó càng lớn.

3: Server có 3 loại: phân loại server theo kiểu dáng(Tower server, Rack server, Blade server).Phân loại server theo cách xây dựng và thiết lập(Máy chủ Vật lý, Máy chủ ảo, Máy chủ đám mây). Phân loại server theo chức năng(DNS server, WEB server, DHCP server, Mail server.....).

4: Chuẩn server 1U, 2U, 3U.... Thể hiện kích thước thùng đựng của thiết bị mạng, 1U = 1,75 inch =4,45 cm. Dùng quy ước đo kích thước của các thiết bị mạng, nhằm thuận tiện cho người dùng và nhà sản xuất.

5: Server TWIN còn gọi là máy chủ cặp, một TWIN server 1U có 2 máy chủ con gọi node. Mỗi node có 0,5U theo chiều ngang, 2 node dùng chung nguồn điện để tối ưu năng lượng, giúp giảm nguồn điện, chi phí làm mát, không gian đặt chố và tăng hiệu xuất so với máy chủ truyền thống 1U.

6: Mainboard là mạch điện chính hay còn gọi là bo mạch chủ

   + Nó gắn kết tất cả các linh kiện và thiết bị ngoại vi thành một khối thống nhất.

   + Điều khiển tốc độ và đường đi của các luồng dữ liệu.

   + Cung cấp và phân phối điện áp cho các linh kiện gắn trên mainboard.

   + Mainboard có 2 chíp set quan trọng là chíp sét cầu bắc và chíp sét cầu nam, xử lý tốc độ bus của các thiết bị cắm vào mainboard, nên máy tính có thể hoạt động một cách thống nhất.


7: RAM còn gọi là bộ nhớ truy cập ngẫu nhiên, nói lên rằng dù dữ liệu được lưu ở bất kỳ đâu trên RAM thì đều có thể truy cập được. Mọi thông tin lưu trữ trên RAM chỉ là tạm thời, khi máy tính bị ngắt đột ngột sẽ mất hết dữ liệu. Trong một khoảng thời gian nhất định, máy tính có thể xử lý được bao nhiêu luồng dữ liệu hay thông tin, phụ thuộc phần lớn vào RAM. Phần mềm máy tính chạy chậm hay chơi game giật lag, phụ thuộc phần lớn vào RAM. RAM có 2 loại là SDRAM(RAM động đồng bộ) và DRR(Tốc độ dữ liệu kép). RAM DRR là bản cải tiến của RAM SDR,tăng gấp đôi tốc độ truyền tải dữ liệu mà không làm tăng tần số xung nhịp.

8: Ổ cứng có 2 loại là ổ HDD và SSD.

+ Ổ cứng HDD hay còn gọi ổ cứng từ, là thiết bị lưu trữ, trên bề mặt được phủ vật liệu từ tính. Dung lượng lưu trữ lớn, giá thành rẻ, tốc độ đọc/ghi dữ liệu thấp. Dễ hỏng do tác động vật lý bên ngoài.Dùng để lưu trữ ngắn hạn, có thể mất dữ liệu khi mất nguồn điện đột ngột.

+ Ổ cứng SSD còn gọi là ổ cứng dạng Rắn. Cũng là thiết bị lưu trữ, Trạng thái Rắn. Dung lượng lưu trữ nhỏ hơn HDD, giá thành cao, tốc độ đọc/ghi dữ liệu lớn gắp nhiều lần HDD. Không dễ bị hỏng do tác dộng vật lý bên ngoài. Dùng để lưu trữ dài hạn, không bị mất dữ liệu khi mất nguồn điện đột ngột.

+ Ổ cứng SANTA là ổ cứng dựa vào nó người ta cải tiến ổ SANTA tạo ra ổ cứng SSD hay dùng hiện nay. Nó xuất hiện 2003, dung lượng lưu trữ lớn có thể lên tới 16TB, tốc độc cao hơn chuẩn của IDE cụ thể là 600MB/s. Nếu cần thiết bị lưu trữ lớn với giá rẻ lại không cần tốc độ đọc/ghi cao thì nó là lựa chọn tốt. Tuy nhiên nó có nhược điểm dữ liệu dễ bị phân mảnh khiến cho tốc dộ truy cập vào chương trình chậm.

9: CARD RAID là hình thức ghép nhiều ổ đĩa cứng vật lý thành một hệ thống ổ đĩa cứng có chức năng tăng tốc độ đọc ghi, tăng tính bảo đảm an toàn cho dữ liệu. Nó là giải pháp tăng tính bảo mật an toàn dữ liệu người dùng, còn tăng tốc độ truy suất dữ liệu, tốc độ đọc/ghi dữ liệu bằng cách chia đều cho các ở cứng cùng hoạt động đồng thời. RAID được chia thành 2 loại, RAID phần cứng và RAID phần mềm. RAID được chia thành 5 cấp độ chính từ RAID 0, RAID 1, RAID 5, RAID 6, RAID 10.

10: Ưu nhược điểm

 + RAID 0 gộp 2 ổ cứng thành 1 ổ cứng, dung lượng bằng tổng 2 ổ cộng lại, tăng tốc độ truy xuất dữ liệu nhưng chỉ cần một trong 2 ổ hỏng là mất hết tất cả dữ liệu.

 + RAID 1 gộp 2 ổ cứng thành 1 ổ cứng, dung lượng bằng một nửa tổng 2 ổ, dùng để đảm bảo dữ liệu không bị mất, một trong 2 ổ hỏng dữ liệu vẫn còn không mất.

 + RAID 5 nâng cấp của RAID 0, có thể gộp nhiều ổ cứng thành một ổ, vừa đảm bảo dữ liệu không bị mất khi có ổ cứng hỏng vừa tăng tốc độ truy xuất dữ liệu. Dữ liệu được phân tách  thành 2 vị trí lưu trữ trên 2 ổ cứng khác nhau.

 + RAID 6 nâng cấp của RAID 5, yêu cầu ít nhất 4 ổ cứng, cho phép hỏng 2 ổ cứng vẫn làm việc bình thường, chỉ sử dụng ở máy chủ quan trọng.

 + RAID 10 yêu cầu tối thiểu 4 ổ cứng, chỉ cho phép 1 ổ cứng hỏng, nhưng tốc độ truy xuất dữ liệu, đọc\ghi dữ liệu cao hơn RAID 6.

11: NIC Card hay còn gọi là card mạng, giúp máy tính kết nối ra môi trường bên ngoài, ví dụ kết nối internet, kết nối 2 máy tính hay kết nối trong môi trường mạng LAN. Cho phép kết nối có dây và không dây. Chuyển đổi các dữ liệu máy tính ra môi trường bên ngoài đến phương tiện khác và ngược lại. Hoạt động song song cùng một lúc vừa gửi và nhận cùng lúc. Trong card mạng có 2 phần quan trọng là địa chỉ IP và địa chỉ MAC. Địa chỉ IP để liên lạc giữa các mạng, địa chỉ MAC mã định danh duy nhất của card mạng, không thể thay đổi được.

12: IPMI là giao diện quản lý nền tảng thông minh, giúp chúng ta thực hiện các tác vụ khác nhau trên một máy chủ như truy cập vào phần cứng, giám sát, khởi động , tắt máy. IPMI là phần cứng gắn với mainboard, và hoạt động từ nó.

  + Giám sát phần cứng quan trọng từ xa bằng nền tảng thông minh IPMI.

  + Tạo các bản ghi và theo dõi hệ điều hành, giúp khắc phục sự cố khi hệ điều hành lỗi.

  + Tạo một kết nối VPN với IPMI phần cứng trong mainboard, tạo người dùng và mật khẩu kết nối để cho an toàn.

13: Storage là những thiết bị lưu trữ như ổ cứng, ổ đĩa, USB.... Có các loại thiết bị lưu trữ sau:

  + Ổ cứng(HDD và SSD)

  + Ổ cứng di động(kích thước nhỏ gọn, kết nối qua cổng USB)

  + Đĩa Quang(CD,DVD,HD)

  + Nas Synology(tập trung hóa dữ liệu người dùng dễ quản lý)

  + USB

14: Hostpare được sử dụng như một cơ chế chuyển đổi dự phòng để cung cấp độ tin cậy trong cấu hình hệ thống. Hostspare được kết nối và như một phần của hệ thống làm việc. Khi một phần quan trọng của hệ thống gặp trục trặc, hostpare sẽ chuyển sang trạng thái sẵn sàng để khắc phục. Khi thiết lập chế độ này, ví dụ ta có RAID 1 gồm 2 ổ cứng HDD gộp thành, và một ổ gặp trục trặc, thay vì chúng ta phải tìm một HDD cùng serial thay thế thì Hostpare sẽ tự động thay vào thay thế HDD lỗi kia và tự động rebuild system RAID cho bạn.

15: Cấu hình các RAID, đã tập cấu hình các RAID 0,1,5... 6 và 10 thì chưa

16: 
