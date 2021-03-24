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
  * run example 4 https://youtu.be/nFqoZT26U5k
### ซอสโค้ด

ซอสโค้ดการทดลองที่4 https://github.com/choompol-boonmee/lab63b/tree/master/examples/04_Input-Port

## วิธีทำการทดลอง
1. ต่อadapterเข้ากับUSB 2 serial และต่อกับmicrocontrollo


2. upload โปรแกรมเข้าไปยังmicrocontrollerโดยคำสั่ง  pip run -t upload

3. กดปุ่มสีดำเเละแดง เพื่อให้รับโปรแกรมใหม่

4. รันคำสั่ง pio device monitor เพื่อดูผลลัพท์ที่แสดงผลออกมาจากคอมพิวเตอร์

![Imgur](https://imgur.com/mSkHF8d.jpg)

5. นำport0 ต่อกับสายสีดำ บันทึกผลการทดลอง

6. นำขาของsenserแสงต่อกับสานสีแดง เเละขาที่senserที่ต่อกับตัวต้านทาน ต่อเข้าที่port 0 ขาของตัวต้านทานต่อกับสายสีดำ 

![Imgur](https://imgur.com/SuD4BLX.jpg)

7. ต่อสายสีขาวเข้าport0 ใข้นิ้วปิดและเปิดบริเวณsenserแสง บันทึกผล

## บันทึกผลการทดลอง

port0ต่อกับสายดำ

![Imgur](https://imgur.com/yYyoLuK.jpg)

ใช้นิ้วปิดบริเวณsensorแสง

![Imgur](https://imgur.com/BZCaGtb.jpg)

## อภิปรายผลการทดลอง

* จากซอสโค้ดจะเห็นได้ว่า ให้port0 เป็นinput เเละport2 เป็นoutput เมื่อเป็น1ให้ส่งLowไปที่port2 Ledจะดับ เเต่ถ้าเป็น0ส่งHighไปที่port2 Ledจะติด ดังนั้นสัญญาณinputเป็นตัวควบคุม Led หากนำสายสีขาวหรือport0ต่อกับสายสีดำให้inputเป็น0 เมื่อต่อsenserแสง ถ้ามีเเสงสว่างจะเเสดงผล0 ไม่มีเเสงสว่าง จะเเสดงผล1

## คำถามท้ายการทดลอง
คำถาม:เมื่อต่อsenserเเสงเเละเเสดงผลคือ0 ส่งผลต่อled หรือไม่

ตอบ:ส่งผลให้ledติด

