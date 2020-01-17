# App_KiemTraNongDoCon
Mô tả app: 

- App giúp người dùng xác định được nồng độ cồn trong máu. Các mức hình phạt dựa vào thông tin người dùng nhập và số lượng thức uống có cồn khi lựa chọn.
- App sẽ thông báo nhắc nhở người dùng kiểm tra nồng độ vào các khoảng thời gian chiều tối (cái này để khuyến khích mọi người sử dụng app)
- app sẽ định vị vị trí, khi người dùng ở các quán, nhà hàng sẽ hiện thông báo nhắc nhở kiểm tra để tránh bị nguy hiểm khi đi tham gia giao thông và bị phạt.
Công thức tính nồng độ:

-------------------------------------------
Công thức tính khối lượng rượu nguyên chất:
	A = 0,79V.c/100
	A là khối lượng rượu nguyên chất (g)
	V là thể tích rượu (ml)
	c là nồng độ rượu (đơn vị tính là % hoặc độ)

Công thức tính nồng độ cồn trong máu:
	A= W.C.10.r/1,056
	Trong đó:
	A là khối lượng rượu nguyên chất (g)
	C là nồng độ cồn trong máu (g/100ml)
	W là trọng lượng cơ thể (kg)
	r là hằng số hấp thụ rượu theo giới tính (người phương Tây r = 0,7 đối với nam giới và r = 0,6 với nữ giới)


App cần những thông tin để tính được nồng độ:
 - Cân nặng
 - Giới tính
 - Số lượng thức uống ( Bia(lon), Rượu(ml) )

-------------------------------------------
Database: https://docs.google.com/spreadsheets/d/1OWTXYl2TF0-EiuHTvBQ2FJG1cG9uC-1fvXYwmHlsGdQ/edit?usp=sharing
Đã thống kê được hơn 45 loại Bia và 10 loại Rượu (bao gồm tên loại bia, độ cồn, thể tích).

------------
Quy trình sử dụng app:
1. Người dùng vào app
2. Nhập các thông tin: giới tính, cân nặng, phương tiện(phiên tiện dùng để làm nội dung cảnh báo)
3. Chọn loại thức uống Bia hoặc Rượu, chọn số lượng Bia thì chọn số lượng lon, Rượu thì chọn ml
4. Sau khi chọn nhấn nút xem kết quả
5. Kết quả sẽ hiển thị trên màng hình, màu đỏ là cảnh báo nguy hiểm, màu xanh là an toàn.
