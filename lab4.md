# การทดลองที่4 การเขียนอินพุทสัญญาณดิจิทัล

## วัตถุประสงค์
1. เพื่อใช้platform io ในการเขียนโปรแกรม
2. เพื่อนำสัญญาณจากภายนอกเข้ามาในmicrocontroller

## อุปกรณ์
* microcontroller ESP-01
* USB
* adapter
* output port
* input port
* Led
* senserแสง
* ตัวทานต้าน

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

ซอสโค้ดการทดลองที่4 https://github.com/choompol-boonmee/lab63b/tree/master/examples/04_Input-Port

## วิธีทำการทดลอง
1. ต่อadapterเข้ากับUSB 2 serial และต่อกับmicrocontrollo
![GitHub Logo](/images/logo.png) Format: ![Alt Text](url)

2. upload โปรแกรมเข้าไปยังmicrocontrollerโดยคำสั่ง  pip run -t upload

3. กดปุ่มสีดำเเละแดง เพื่อให้รับโปรแกรมใหม่

4. รันคำสั่ง pio device monitor เพื่อดูผลลัพท์ที่แสดงผลออกมาจากคอมพิวเตอร์

5. นำport0 ต่อกับสายสีดำ บันทึกผลการทดลอง

6. นำขาของsenserแสงต่อกับสานสีแดง เเละขาที่senserที่ต่อกับตัวต้านทาน ต่อเข้าที่port 0 ขาของตัวต้านทานต่อกับสายสีดำ บันทึกผลการทดลอง

7. ต่อสายสีขาวเข้าport0 ใข้นิ้วปิดและเปิดบริเวณsenserแสง บันทึกผล

## บันทึกผลการทดลอง

![GitHub Logo](/images/logo.png) Format: ![Alt Text](url)

## อภิปรายผลการทดลอง


