@@ -1,30 +0,0 @@
# VPSSIM
FIx VPSSIM chạy được 06/2020

Dành cho CentOS 7
```python
curl -sO https://script.manhkhanh.net/vpssim/vpssim_fix && bash vpssim_fix
```
Nếu chạy trên VPS của Amazon thực hiện lệnh bên dưới trước khi cài đặt

```python
sudo su -
```

Đây là bản Fix giúp bạn chạy được bình thường sau khi cài đặt VPSSIM ( cài đặt mới hoàn toàn ), không còn bị lỗi không chạy được PHP nữa

**Đã Test trên CentOS 7 của**

+ Amazon Lightsail
+ OVH
+ Linode
+ Vultr
+ VPS Viettel

Lưu ý: Bản cài đặt này chỉ Fix lỗitrong quá trình cài đặt, còn lại các thành phần của VPSSIM không thay đổi. Việc nhập được KEY hay không phụ thuộc vào bên vpssim.

Nếu bạn có gì cần hỏi, vui lòng chát qua Telegram https://t.me/manhkhanh
