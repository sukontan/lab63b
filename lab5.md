# การทดลองที่5 การเขียนโปรแกรมเชื่อมต่อไวไฟและเว็บเซอร์เวอร์

## วัตถุประสงค์
1. เพื่อใช้platform io ในการเขียนโปรแกรม
2. เพื่อสร้างเว็บเซอร์เวอร์ผ่านไวไฟ

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
  * run wifi https://youtu.be/VX-QNQcO-b4
### ซอสโค้ด
ซอสโค้ดของการทดลองที่5 https://github.com/choompol-boonmee/lab63b/tree/master/examples/05_Wifi-Web-Server

## วิธีทำการทดลอง
1. ต่อmicrocontrollerเข้าทางserial port

![Imgur](https://imgur.com/TVfw2Hb.jpg)


2. ใส่ชื่อwifi HI_BMFWIFI.24Gพร้อมรหัสในซอสโค้ด

upload โปรแกรมเข้าไปยังmicrocontrollerโดยคำสั่ง  pip run -t upload

3. กดปุ่มสีดำเเละแดง เพื่อให้รับโปรแกรมใหม่

4. รันคำสั่ง pio device monitor เพื่อดูผลลัพท์ที่แสดงผลออกมาจากคอมพิวเตอร์

5. ตรวจสอบIP addressที่เว็บเบราว์เซอร์
6. กดreset เพื่อทำงานใหม่
7. นำIP addressที่ได้มาทดสอบในเว็บเบราว์เซอร์


## บันทึกผลการทดลอง

Hello 1

Hello 2

Hello 3

## อภิรายผลการทดลอง

จะสังเกตได้ว่าเมื่ออัปโหลดเเล้วมีไฟกระพริบบ่งบอกถึงมีการรับส่งสัญญาณ เมื่อset upเว็บเบราว์เซอร์ โปรแกรมจะแสดงผลการค้นหาไวไฟ เชื่อมต่อไวไฟเเละเเสดงIP address เนื่องจากโปรแกรมนี้ทำหน้าที่เป็นเว็บเซอร์เวอร์จึงต้องใช้เว็บเบราว์เซอร์ในการทดสอบ ถ้ามีการเชื่อมต่อจะเเสดงผลHello cntโดยที่cntจะเพิ่มขึ้นทีละ1

## คำถามท้ายการทดลอง

คำถาม:ถ้าโปรเเกรมเเสดงHello 10เเล้วกดresetโปรแกรมจะเเสดงผลอย่างไร

ตอบ:เริ่มHello 1


