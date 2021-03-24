 # การทดลองที่2 การเขียนโปรแกรมค้นหาไวไฟ
 
 ## วัตถุประสงค์
1. เพื่อใช้platform io ในการเขียนโปรแกรม
2. เพื่อค้นหาไวไฟ

## อุปกรณ์
* microcontroller ESP-01
* USB

## ศึกษาข้อมูลเบื้องต้น
  * digital https://youtu.be/8ErQEAMUAlQ 
  * voltage https://youtu.be/ZsGuyLhPhbM
  * computer https://youtu.be/9s2qB71o3Xc
  * internet https://youtu.be/pSAqgVDv8xU
  * program lang https://youtu.be/TrZzCv0kVUM
  * platformio https://youtu.be/APdBR37Ukxg
  * iotset1 https://youtu.be/9aF0upI9Gic
  * run example 2 https://youtu.be/yBjab0UNuB8

### ซอสโค้ด
ซอสโค้ดของการทดลองที่2 https://github.com/choompol-boonmee/lab63b/tree/master/examples/02_Scan-Wifi

## วิธีทำการทดลอง
1. ต่อmicrocontrollerเข้าทางserial port

![Imgur](https://imgur.com/TVfw2Hb.jpg)

2. upload โปรแกรมscan wifi เข้าไปยังmicrocontrollerโดยคำสั่ง  pip run -t upload

3. กดปุ่มสีดำเเละแดง เพื่อให้รับโปรแกรมใหม่

4.รันคำสั่ง pio device monitor เพื่อดูผลลัพท์ที่แสดงผลออกมาจากคอมพิวเตอร์

## บันทึกผลการทดลอง

![GitHub Logo](/images/logo.png) Format: ![Alt Text](url)

## อภิปรายผลการทดลอง   

* เมื่อสังเกตจากcodeของโปรแกรมจะได้ว่า มี2ส่วนคือส่วนของset upและส่วนของloop โดยเริ่มจากset up เตรียม set wifi ให้พร้อมใช้งาน จากนั้นวนลูปโดยเเสดงผลเ่มต้นค้นหาwifi จากนั้นเมื่อพบwifiจะเเสดงผลเป็นชื่อwifiiที่พบ

## คำถามท้ายการทดลอง
คำถาม: เมื่อกดปุ่มสีแดงจะเกิดอะไรขึ้น
* ตอบ: โปรแกรมจะresetเเละเริ่มค้นหาwifiใหม่
