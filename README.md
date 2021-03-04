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



