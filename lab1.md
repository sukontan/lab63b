# การทดลองที่1 การเขียนโปรเเกรมเพื่อรันบนไมโครคอนโทรเลอร์

## วัตถุประสงค์
1. เพื่อใช้platform io ในการเขียนโปรแกรม
2. เพื่อรันบนไมโครคอนโทรเลอร์

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
  * run example 1 https://youtu.be/NLIUsWLEpmg
### ซอสโค้ด
ซอสโค้ดของการทดลองที่1 https://github.com/choompol-boonmee/lab63b/tree/master/examples/01_Serial-Monitor

## วิธีทำการทดลอง
1. ต่อmicrocontrollerเข้าทางserial port
![GitHub Logo](/images/logo.png) Format: ![Alt Text](url)

2. upload โปรแกรมเข้าไปยังmicrocontrollerโดยคำสั่ง  pip run -t upload

3. กดปุ่มสีดำเเละแดง เพื่อให้รับโปรแกรมใหม่

4. รันคำสั่ง pio device monitor เพื่อดูผลลัพท์ที่แสดงผลออกมาจากคอมพิวเตอร์

## บันทึกผลการทดลอง

![GitHub Logo](/images/logo.png) Format: ![Alt Text](url)

## อภิปรายผลการทดลอง

* จาการทดลองเมื่อกดปุ่มสีดำเเละแดง เพื่อผลลัพท์ที่เเสดงผลออกมาจากคอมพิวเตอร์ จะเห็นได้ว่าตัวเเปรcntที่เริ่มตั้งเเต่0 ถูกเพิ่มขึ้นทีละ1 เเละเเสดงผลทุกๆ1วินาที หากกดปุ่มสีแดง โปรเเกรมจะresetโดยเริ่มนับ1ใหม่

## คำถามหลังการทดลอง
คำถาม:หากต้องการให้แสดงผลทุกๆ0.5วินาทีควรแก้ที่ใด
* ตอบ:แก้codeส่วนloop จากdelay(1000)เป็น delay(500)
