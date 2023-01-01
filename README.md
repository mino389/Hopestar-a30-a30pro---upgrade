# HƯỚNG DẪN NÂNG CẤP PHẦN CỨNG LOA DI ĐỘNG HOPESTAR A30/A30PRO.

Hopestar A30 2021 là sự tiếp nối hợp lý của dòng A20. Loa 55W mang lại âm thanh tuyệt vời. Và nhờ chức năng "Bass Boost" mới, âm trầm sâu hơn. Do đó, mô hình này, trước hết, sẽ phù hợp với những người hâm mộ nhạc hip-hop và câu lạc bộ. Cũng đáng chú ý là thiết kế mới và giảm trọng lượng của loa. Loa không sợ ẩm và bụi IPX6, bạn có thể kết nối 2 loa phát nhạc bằng điện thoại thông minh với nó cùng một lúc, có bộ tản nhiệt thụ động ở hai bên giúp âm thanh trở nên to và phong phú hơn. Sạc đầu phát/điện thoại thông minh, Kết nối với PC, Kết nối với TV, Chức năng rảnh tay, chất liệu vỏ nhựa. Pin 6000 mAh tích hợp cho phép loa hoạt động mà không cần sạc lại tới 8 giờ. Tất cả các đầu nối tiếp xúc đều được bảo vệ an toàn và kín bằng phích cắm cao su. 
* Homepage: http://hopestar.hk
# THÔNG SỐ KỸ THUẬT:
* Giao thức không dây: Bluetooth 5.0
* Không dây: lên đến 10 m
* Loa: Ф 66mm *2 chiếc , 102mm * 1 chiếc
* Công suất đầu ra: 55W (10W*2+35W)
* Đáp ứng tần số: 100Hz - 20kHz
* Tỷ lệ tín hiệu trên tạp âm SNR: 80dB
* Độ nhạy đầu vào: 400mV
* Pin tích hợp: Li-ion 18650, 7.4V
* Pin 6000mAh với chức năng sạc dự phòng (lên đến 8 giờ nghe nhạc)
* Sạc: 3 giờ, 5V/2000mA
* Kích thước: 347 x 130 x 147mm
* Trọng lượng: 2380 gam
* Chất liệu: nhựa ABS, kim loại, cao su
* Hỗ trợ chức năng TWS
* Micrô tích hợp để gọi rảnh tay
* thiếu đài phát thanh
# HÌNH ẢNH
# NÂNG CẤP PHẦN CỨNG ĐẠT HIỆU SUẤT TỐT HƠN.
* trước tiên hãy xem những thành phần có trên bo mạch chủ
1. ic giải mã âm thanh jieli AC6921A
2. ic tiền khuếch đại âm thanh
3. ic khuếch đại âm thanh loa tweeter AD52068
4. ic khuếch đại công suất loa subwoofer TPA3118
5. ic sạc 5080
6. ic tăng áp HT7166 7.4v -> 13v max 10A DC to DC
- mặt sau ta có tụ điện 16v 2200uf
* VẤN ĐỀ VỀ NĂNG LƯỢNG
Loa được trang bị pin 18650 7.4v 3000mah so với 6000mah thông số nhà sản xuất, có thể thấy ic khuếch đại subwoofer TPA3118 cần tới 8ah để hoạt động ổn định, bạn sẽ cần 8 cell pin 2s để đạt tới công suất tối ưu cho loa subwoofer,không khuyến khích cung cấp nguồn pin 12v cho việc này, có thể gây hỏng bảng mạch chủ của bạn. Tất nhiên 12v cũng sẽ được cấp cho toàn bộ ic công suất ra loa bởi ic tăng áp HT7166 công suất đầu ra có thể đạt tới 10A, vì vậy không quá lo ngại ở đây. Để đảm bảo công suất mà chip HT7166 cấp ra ổn định và bền bỉ trong quá trình chơi nhạc max volume - bassboster thời gian dài thì chúng ta cần thay thế tụ điện ở mặt sau 16v 2200uf bằng tụ 16v 20000uf, điều này sẽ làm cho ic HT7166 bớt nóng hơn khi chơi nhạc công suất cao, subwoofer sẽ ổn định hơn và bass sẽ rất căng.
* VẤN ĐỀ MÀNG CỘNG HƯỞNG
Bạn cần phải gia cố lại nó,bởi vì bên trong nó là một miếng mút xốp và nhà sản xuất dán rất ít keo gây hiện tượng rè khi mở loa lớn.
* TÓM TẮT
Những gì bạn cần: 8 cell pin 3.7v liên kết với mạch pin 2s từ pin gốc của nhà sản suất, mắc nối tiếp 4 cặp cell pin mỗi cặp sẽ cho ra 7.4v 2000mah, tiếp tục nối song song 4 cell pin này lại sẽ được 7.4v 8000mah. Tất nhiên sẽ cần chút kiến thức về mạch cell pin 2s.
Tiếp theo: 1 tụ điện nhôm 16v 20000uf và một loại keo chuyên dụng có độ đàn hồi tốt "dog glue..."