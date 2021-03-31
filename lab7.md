# การทดลองที่7 การเขียนโปรเเกรมสำหรับสัญญาณทางม้าลายอัตโนมัติ

## วัตถุประสงค์
1. เพื่อใช้platform io ในการเขียนโปรแกรม
2. เพื่อสร้างสัญญาณทางม้าลายอัตโนมัติ

## อุปกรณ์
* microcontroller ESP-01
* USB
* adapter
* output port
* input port
* Led

## ศึกษาข้อมูลเบื้องต้น
  * digital https://youtu.be/8ErQEAMUAlQ 
  * voltage https://youtu.be/ZsGuyLhPhbM
  * computer https://youtu.be/9s2qB71o3Xc
  * internet https://youtu.be/pSAqgVDv8xU
  * program lang https://youtu.be/TrZzCv0kVUM
  * platformio https://youtu.be/APdBR37Ukxg
  * iotset1 https://youtu.be/9aF0upI9Gic
  
### ซอสโค้ด
ซอสโค้ดของการทดลองที่7 ![Imgur](https://imgur.com/NZaWt7d.jpg)

## วิธีทำการทดลอง
1. ต่อmicrocontrollerเข้าทางserial port

![Imgur](https://imgur.com/TVfw2Hb.jpg)


2. upload โปรแกรมเข้าไปยังmicrocontrollerโดยคำสั่ง  pip run -t upload

3. กดปุ่มสีดำเเละแดง เพื่อให้รับโปรแกรมใหม่

4. รันคำสั่ง pio device monitor เพื่อดูผลลัพท์ที่แสดงผลออกมาจากคอมพิวเตอร์

## บันทึกผลการทดลอง

![Imgur](https://imgur.com/NZaWt7d.jpg)

## อภิปรายผลการทดลอง
* จากการทดลองเมื่อกดปุ่มเพื่อreset cntจะนับเพิ่มทีละ1 ถ้าcnt=30 โปรแกรมส่งoutputออกมาที่port0เเละเมื่อต่อกับledเปล่งเเสง เมื่อมีการส่งHIGH ledจะสว่างเนื่องจากโปรแกรมset port0เป็นoutput โดยสว่างเป็นเวลา30วินาที 
กรณีที่cntไม่ใช่30 โปรแกรมจะส่งLOWมาที่port0 ledจะไม่สว่าง จากนั้นวนลูปทุกๆ30วินาที

