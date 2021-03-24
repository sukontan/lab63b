# การทดลองที่6 การเขียนโปรแกรมสร้างไวไฟแอคเซสพ้อยต์(wifi Ap)

## วัตถุประสงค์
1. เพื่อใช้platform io ในการเขียนโปรแกรม
2. เพื่อสร้างไวไฟแอคเซสพ้อยต์

## อุปกรณ์
* microcontroller ESP-01
* USB
* โทรศัพท์มือถือ

## ศึกษาข้อมูลเบื้องต้น
  * digital https://youtu.be/8ErQEAMUAlQ 
  * voltage https://youtu.be/ZsGuyLhPhbM
  * computer https://youtu.be/9s2qB71o3Xc
  * internet https://youtu.be/pSAqgVDv8xU
  * program lang https://youtu.be/TrZzCv0kVUM
  * platformio https://youtu.be/APdBR37Ukxg
  * iotset1 https://youtu.be/9aF0upI9Gic
  * run wifi AP https://youtu.be/T26DVHePlTs
### ซอสโค้ด
ซอสโค้ดของการทดลองที่6 https://github.com/choompol-boonmee/lab63b/tree/master/examples/06_Wifi-AP-Web-Server

## วิธีทำการทดลอง
1. ต่อmicrocontrollerเข้าทางserial port

![Imgur](https://imgur.com/TVfw2Hb.jpg)


2. สามารถเเก้ซอสโค้ดก่อน upload โปรแกรมเข้าไปยังmicrocontrollerโดยคำสั่ง  pip run -t upload

ในที่นี้กำหนดชื่อwifiเป็นTUENG-ESP-WIFI เเละกำหนดpassword เป็นchoompol

![Imgur](https://imgur.com/HF6lOM0.jpg)

3. กดปุ่มสีดำเเละแดง เพื่อให้รับโปรแกรมใหม่

4. รันคำสั่ง pio device monitor เพื่อดูผลลัพท์ที่แสดงผลออกมาจากคอมพิวเตอร์

![Imgur](https://imgur.com/FvTbQoB.jpg)

5. ใช้โทรศัพท์มือถือเพื่อค้นหาไวไฟ

## บันทึกผลการทดลอง

ค้นหาไวไฟ

![Imgur](https://imgur.com/g8GZ491.jpg)

## อภิปรายผลการทดลอง

จากการทดลองเมื่อรันคำสั่งsoftAPจะทำให้สามารถสร้างไวไฟแอคเซสพ้อยต์

## คำถามท้ายการทดลอง

ถาม:หากไม่ใช่โทรศัพท์มือถือยกตัวอย่าวอุปกรณ์ที่ใช้แทนได้ 

ตอบ: คอมพิวเตอร์ 

