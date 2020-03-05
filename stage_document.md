# Stage Process
![Image of Stage Process](https://github.com/hodu2019/photography/blob/master/photo_2020-02-26_20-19-51.jpg?raw=true)

### Thông tin về các Stage và Status
<details open>
<summary>L0: Junc Lead (Lead trùng, sai số điện thoại không gọi được).</summary>


* L0A - Trùng lead: 
    - Dùng để chứa các lead trùng, lead test, lead cũ không có số điện thoại
* L0B - Sai số điện thoại: 
    - Dùng để chứa các lead khi gọi bị thuê bao, thiếu số, dư số
</details>


<details open>
<summary>L1: Lead (Lead chưa xử lý).</summary>

* L1A - Chưa xử lý: 
    - Chứa các lead chưa xử lý từ website, leadform, landing page, Database và các nguồn khác
    - Lead cần được xử lý và phân loại ngay từ status này"
* L1B - Bận, gọi lại sau: 
    - Chứa các lead từ L1A sau khi gọi mà KH báo bận, chưa nghe tư vấn được và cần gọi lại để tư vấn
* L1C - Chưa nghe máy:
    - Chứa các lead từ L1A sau khi gọi mà chưa bắt máy và cần gọi lại
</details>


<details open>
<summary>L2: Cold Lead (Contact Lạnh).</summary>

* L2A - Không có nhu cầu: 
    - Chứa các lead từ L1A sau khi tư vấn mà KH bảo là không có nhu cầu
* L2B - Sai đối tượng (ngoài khu vực): 
    - Chứa các lead từ L1A sau khi tư vấn mà KH từ chối tư vấn hoặc không có nhu cầu vì ngoài khu vực
* L2C - Sai đối tượng (độ tuổi, chưa có con...): 
    - Chứa các lead từ L1A sau khi tư vấn mà KH từ chối tư vấn hoặc không có nhu cầu vì không đúng độ tuổi
* L2D - L3 hủy: 
    - Chứa các lead từ L3ABCD sau khi tư vấn nhiều lần nhưng KH vẫn không đồng ý trải nghiệm/đăng ký
* L2E - Hủy lịch trải nghiệm và hết yêu cầu
    - Chứa các lead từ L4A, sau khi tư vấn và hẹn trải nghiệm nhiều lần nhưng khách hàng từ chối và không còn nhu cầu nữa
* L2F - Fail trải nghiệm/Fail test:
    - Chứa các lead từ L4B: dù đã trải nghiệm rồi nhưng không còn nhu cầu nữa
* L2G - L5 hủy:
    - Chứa các lead từ L5A: dù đã confirm rồi nhưng vẫn hủy đơn hàng, không đồng ý học nữa
* L2X - Sai đối tượng (chưa rõ nguyên nhân)
</details>


<details open>
<summary>L3: Warm Lead (Lead có nhu cầu cần tư vấn).</summary>

* L3A - Có quan tâm nhưng đang bận
* L3B - Đã tư vấn, KH quan tâm ít
* L3C - Đã tư vấn, cần gửi email
* L3D - Đã tư vấn, KH quan tâm nhiều
</details>


<details open>
<summary>L4: Hot lead (Lead đồng ý học trải nghiệm).</summary>

* L4A - Đồng ý học trải nghiệm/ Test:
    - Chứa các lead đã có lịch hẹn trải nghiệm
* L4B - Đã học trải nghiệm/ Tested:
    - Chứa các lead đã tham gia trải nghiệm / làm test
* L4X - Đang chấm test:
    - Chứa các lead đang trong giai đoạn chấm test
</details>

<details open>
<summary>L5: Order (Lead có order).</summary>

* L5A - New order, chờ thanh toán:
    - Chứa các lead mà khách đã xác nhận sẽ đi học
* L5B - Order - Đã thanh toán một phần:
    - Chứa các lead mà khách đã đóng 1% - 99% học phí
* L5C - Order - Đã thanh toán toàn phần:
    - Chứa các lead mà khách đã đóng 100%
* L5D - Đóng thừa tiền nhưng không đi học nữa:
    - Chứa các lead đóng tiền thừa nhưng không đi học
</details>

### Các quy định về việc chuyển Status

|Status |Được phép chuyển sang  | Quy định 	|
|---	|---	|---	|
|L0A - Trùng lead   	|   	|   	|
|L0B - Sai số điện thoại   	|   	|   	|
|L1A - Chưa xử lý   	| Hầu hết các status khác | Lead chỉ được ở L1A trong 2 ngày kể từ ngày tạo (không tính nguồn database)  	|
|L1B - Bận, gọi lại sau  	|   	|Lead chỉ được ở L1B trong 3 ngày và sau 3 cuộc gọi   	|
|L1C - Chưa nghe máy   	|   	|Lead chỉ được ở L1C trong 3 ngày và sau 3 cuộc gọi   	|
|L2A - Không có nhu cầu   	|   	|   	|
|L2B - Sai đối tượng (ngoài khu vực)   	|   	|   	|
|L2C - Sai đối tượng (độ tuổi, chưa có con...) |   	|   	|
|L2D - L3 hủy  	|   	|   	|
|L2E - Hủy lịch trải nghiệm và hết yêu cầu | Đặt lại 1 reminder để nhắc thời gian cần tái tiếp cận khách hàng   	|   	|
|L2F - Fail trải nghiệm/Fail test|Đặt lại 1 reminder để nhắc thời gian cần tái tiếp cận khách hàng  	|   	|
|L2G - L5 hủy   	|   	|   	|
|L2X - Sai đối tượng (chưa rõ nguyên nhân)  	|   	|   	|
|L3ABCD - Có quan tâm   	|  - KH đồng ý trải nghiệm: chuyển sang L4A  <br> - KH đồng ý đi học luôn: chuyển sang L5A <br> - KH không còn nhu cầu: chuyển sang L2D"|- Sau n lần gọi chăm sóc hoặc sau x ngày thì mới được chuyển về L2D nếu khách không còn nhu cầu <br> - Tất cả các lead  L3 đều có ít nhất 1 reminder"|
|L4A - Đồng ý học trải nghiệm/ Test   	|- Khách đã trải nghiệm xong: chuyển sang L4B <br> - Khách hủy lịch trải nghiệm: chuyển sang L2E <br> - Khách hẹn 1 thời gian gian khác để lên TN: vẫn để L4A + đặt thêm 1 appointment khác để theo dõi <br> - Khách không hẹn thời gian nhưng vẫn còn nhu cầu, hẹn tháng sau, hè tới vẫn để L4A + đặt 1 reminder nhắc gọi lại cho KH. |"- Sau n lần gọi chăm sóc hoặc sau x ngày thì mới được chuyển về L2E nếu khách không còn nhu cầu <br>- Tất cả các lead ở L4A dều có ít nhất 1 appointment" |
|L4B - Đã học trải nghiệm/ Tested   	| - Khách đồng ý đi học: chuyển sang L5A <br> - Khách không muốn đi học: chuyển sang L2F  <br> - Khách chưa xác nhận thời gian đi học: đặt reminder để nhắc thời gian cần gọi lại cho khách 	|- Sau n lần gọi chăm sóc hoặc sau x ngày thì mới được chuyển về L2F nếu khách không còn nhu cầu <br> - Tất cả các lead ở L4A dều có ít nhất 1 appointment   	|
|L4X - Đang chấm test   	|- Chuyển sang L4B   	|   	|
|L5A - New order, chờ thanh toán   	|   	|- Sau n lần gọi chăm sóc hoặc sau x ngày thì mới được chuyển về L2G nếu khách không còn nhu cầu <br> - Lead chỉ được phép ở L5A cho tới ngày khai giảng + 2 tuần |
|L5B - Order - Đã thanh toán một phần  	|   	|   	|
|L5C - Order - Đã thanh toán toàn phần  	|   	|   	|
|L5D - Đóng thừa tiền nhưng không đi học nữa|   	|   	|

