# Portfolio-Project-1
# 1. Các thông tin tổng quan về tình huống 

a.	Giới thiệu tổng quan về công ty: 

 Công ty TNHH Thương Mại SME là một công ty nhập hàng hóa từ nhiều hãng khác nhau và phân phối lại cho một số đại lý khác thông qua đội ngũ bán hàng trực tiếp. Đồng thời, cũng có bán tới người dùng cuối thông qua cửa hàng trưng bày, website, sàn thương mại điện tử, và các nền tảng mạng xã hội. 

•	Mô hình kinh doanh: bán sỉ và bán lẻ. 

•	Lĩnh vực kinh doanh: ấn phẩm như sách và các thiết bị điện tử chuyên dụng. 

•	Qui mô công ty: dưới 50 nhân viên. 

b.	Mô tả dữ liệu của công ty: 

•	File data chứa thông tin thống kê số lượng đơn hàng đã hoàn tất (order) theo từng khách hàng (customer). Khách hàng là những visitor_id có trong file data. 

•	File visitor information chứa thông tin lần đầu tiên (create_date) khách ghé vào (visitor) một trong các địa điểm Online và Offline của công ty (visitor_source). 

•	Cả 2 File dữ liệu này đều được xuất ra từ hệ thống báo cáo SAP và cơ sở dữ liệu nội bộ của công ty. 

# 2. Các yêu cầu cần thực hiện 
a. Chị Yên – cửa hàng trưởng có yêu cầu như sau 

Hi team, 
Chị muốn xin một thông tin để chuẩn bị cho sự kiện sẽ diễn ra tại cửa hàng sau 14 ngày nữa. Đây là một sự kiện chỉ dành riêng cho những ai biết tới công ty lần đầu tiên bằng cách ghé qua cửa hàng và đã mua hàng của công ty. 
Mục tiêu chính của sự kiện này là để giới thiệu về các phụ kiện mới của công ty đi kèm với sản phẩm đã bán ra trước đó. Để thu hút các khách hàng cũ của mình quay lại, mình sẽ có phần tặng quà cho những ai tham gia. Một điểm đặc biệt là với khách hàng nữ thì mình muốn thiết kế phần quà nó khác đi một tí và hạn chế tối đa việc thiếu quà của khách nữ vì họ rất tiềm năng. 
Với dữ liệu của mình hiện giờ thì tỉ lệ khách hàng nữ của mình là bao nhiêu %? Số liệu này sẽ được sử dụng để ước tính tỉ lệ quà cho khách hàng nữ cần chuẩn bị cho sự kiện. 
Cám ơn team. 
 
b. Chị Nhung – giám đốc kinh doanh mới có yêu cầu như sau 

Hi team, 
Rất vui vì được làm quen với mọi người. Chị tên Nhung, chị vừa bắt đầu công việc được vài ngày dưới vai trò giám đốc kinh doanh. Chị có được chia sẻ sơ qua về tình hình kinh doanh đang bị giảm sút do ảnh hưởng của dịch bệnh nhưng cũng chưa nắm rõ thực tế số liệu giảm sút như thế nào. 
Team giúp chị tổng hợp lại thông tin trong một trang để chị có thể nhìn nhanh được bức tranh của công ty từ đầu tới giờ và có thể sử dụng để theo dõi nhanh tiến độ bán hàng hằng tuần nhằm đưa ra những chỉ dẫn kịp thời cho phòng kinh doanh. Chị thường có cuộc họp toàn phòng kinh doanh vào sáng thứ 6 hằng tuần để đánh giá và đưa ra định hướng bán hàng.  
Ngoài ra, sẽ rất tuyệt nếu team có thể hỗ trợ dự báo số lượng đơn hàng tới cuối tháng để chị tham khảo và so sánh với kế hoạch bán hàng đề xuất của phòng kinh doanh. 
Cám ơn team. 

c. Anh Nhật – CEO có yêu cầu như sau 

Hi team, 
Anh đang đánh giá lại mức độ hiệu quả của hoạt động quảng cáo và truyền thông. Các hoạt động này đang giúp mang lại lượng khách hàng mới cho công ty trên tất cả các kênh bán hàng. Đây cũng là một trong những hoạt động rất quan trọng để giữ chân khách hàng cũ. 
Trong cuộc họp với giám đốc Marketing tuần trước, bên cạnh các thông tin chiến dịch về Marketing thì anh có nhận được thông tin là tỉ lệ chuyển đổi hằng ngày đang rất tốt. Thông tin này đang dựa theo cảm nhận chung của các bạn bán hàng là “khách nào có ghé vào thì cũng mua hàng hết”. Mọi người giúp anh kiểm chứng thông tin này theo dữ liệu hiện tại. Thêm vào đó, một báo cáo theo dõi cụ thể tỉ lệ chuyển đổi hằng ngày cũng sẽ giúp ích rất nhiều cho bộ phận Marketing trong việc định hướng hoạt động quảng cáo và truyền thông. 
Ngoài ra, có một thông tin khác mà anh cần để đánh giá sức khỏe doanh nghiệp trong dài hạn đó là tỉ lệ giữ chân khách hàng. Mọi người thảo luận trình bày cho anh vào chủ nhật tuần sau nữa nhé. 
Cám ơn team. 
