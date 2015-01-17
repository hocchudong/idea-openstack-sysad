# Sysad, DevOps - Thỏa sức sáng tạo cùng OpenStack
Các ý tưởng dành cho sysad, devops thể hiện chuyên môn về OpenStack

### LỊCH SỬ
* Dùng để mô tả các thay đổi trong tài liệu này: 

| Ngày thay đổi     | Người thay đổi      | Nội dung thay đổi  |
| ------------- |:-------------:| -----:|
| 16/01/2015    | CongTo | Tạo tài liệu |
| 17/01/2015    | CongTo      |   Bổ sung các mục lớn về Dashboard |
| |     |   |

### CÁCH DÙNG
* Mục tiêu là làm ra một trang web để quản trị OpenStack hay còn gọi là dashboard, portal, horizon ..
* Mô tả các ý tưởng, minh họa chúng bằng mọi cách
* Ghi chép các chú ý quan trọng.

### CÁC CHỨC NĂNG CHO DASHBOARD PHIÊN BẢN MỚI
#### Đối với người quản trị
##### Tính năng quản trị người dùng
- Tạo thêm người dùng (tạo mới tài khoản)
- Tính sửa người dùng  (thay đổi email, thay đổi email, số điện thoại, tên công ty/đơn vị.
- Tính năng khóa tạm thời
- Tính năng xóa vĩnh viễn
- Tính năng phân quyền cho người dùng (có role gì, thuộc tenant nào...)

# Tính năng quản lý image 
- Tính năng tạo mới image
- Tính năng sửa tên image
- Tính năng phân quyền sử dụng cho image
- 

# Tính năng quản lý hypervisor
- Thống kê tài nguyên của hypervisor mà OpenStack báo cáo
- Thống kế tài nguyên thật của hypervisor, kiểm tra tài nguyên của máy vật lý.

# Tính năng quản lý instance
- Liệt kê các instance, kể cả khác tenant, 
- Shutdown toàn bộ các instance, kể cả khác tenant
- Reboot toàn bộ các instance, kể cả khác tenant
- Stop toàn bộ các instance, kể cả khác tenant


### CÁC CHỨC NĂNG CỦA DASHBOARD MẶC ĐỊNH (BẢN ICEHOUSE TRỞ ĐI)

### TÀI LIỆU THAM KHẢO
- http://www.slideshare.net/delapsley1/openstack-horizon-controlling-the-cloud-using-django
- http://www.slideshare.net/delapsley1/20141002-delapsleyopenstacksummitrealtimestatisticsfinal
