# การทดลองที่3 การเขียนโปรแกรมเอ้าพุทสัญญาณดิจิตอล

## วัตถุประสงค์
1. เพื่อใช้platform io ในการเขียนโปรแกรม
2. เพื่อoutputสัญญาณออกไปภายนอก

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
  * run example 3 https://youtu.be/CCnN1WJsXQY
### ซอสโค้ด
ซอสโค้ดของการทดลองที่3 https://github.com/choompol-boonmee/lab63b/tree/master/examples/03_Output-Port

## วิธีทำการทดลอง
1. ต่อadapterเข้ากับUSB 2 serial และต่อกับmicrocontrollor
![GitHub Logo](/images/logo.png) Format: ![Alt Text](url)

2. upload โปรแกรมoutput port เข้าไปยังmicrocontrollerโดยคำสั่ง  pip run -t upload

3. กดปุ่มสีดำเเละแดง เพื่อให้รับโปรแกรมใหม่

4.รันคำสั่ง pio device monitor เพื่อดูผลลัพท์ที่แสดงผลออกมาจากคอมพิวเตอร์

## บันทึกผลการทดลอง

![GitHub Logo](/images/logo.png) Format: ![Alt Text](url)

## อภิปรายผลการทดลอง

* ESP01 มีoutput port(port 0)และ input port(port 1) เมื่อใช้adapterต่อสายport0 เเละ port1 โดยมีสีขาวเเละสีเหลืองตามลำดับ เมื่อโปรแกรมส่งoutputออกมาที่port0 และเมื่อต่อกับled เปล่งเเสงเมื่อมีการส่ง1 led จะสว่าง
เนื่องจากโปรแกรมset port0เป็นoutput จากนั้นวนลูปทุกๆ500msเเละนับเพิ่มขึ้นทีละ1 ซึ่งเมื่อนับเป็นเลขคี่ จะเเสดงผลว่าon โดยส่งค่า1ไที่port0 เเต่ถ้าcntเป็นเลขคู่ เเสดงผลว่าoff

## คำถามท้ายการทดลอง
คำถาม:ถ้าoutputที่port0เป็น0 ledจะติดหรือไม่
* ไม่ติด
