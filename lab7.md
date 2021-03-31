# การทดลองที่ 7 เรื่อง การดัดแปลงการเขียนโปรแกรมค้นหาไวไฟ

## วัตถุประสงค์
1. เพื่อเข้าใจการต่อวงจรโดยใช้ไมโครคอนโทรลเลอร์
2. ฝึกการเขียนโปรแกรมด้วย platformio
3. ฝึกการเขียนโปรแกรมด้วยตนเอง

## อุปกรณ์ที่ใช้
1. ไมโครคอนโทรลเลอร์
2. สายUSB
3. USB2Serial converter

## ศึกษาข้อมูลเบื้องต้น
* https://www.youtube.com/watch?v=yBjab0UNuB8
* https://www.ioxhop.com/article/71/esp32
* https://www.arduinoall.net/arduino-tutor/lessons/9-loop-ok/
* https://www.youtube.com/watch?v=j0XMHydEOdM
* https://medium.com/@pattanapong.sriph
## Source Code
   > ![code12](https://user-images.githubusercontent.com/80879116/113142629-4f956b80-9255-11eb-8c09-b49059cda92c.png)

## คำอธิบาย
1. อ้างอิงไฟล์ Arduino.h และไฟล์ ESP8266WiFi.h
   > ![cd1](https://user-images.githubusercontent.com/80879116/113143368-435dde00-9256-11eb-9354-618b64340c94.png)
      
2. ประกาศตัวแปร cnt
   > ![cd2](https://user-images.githubusercontent.com/80879116/113143868-d8f96d80-9256-11eb-848d-6d7383478475.png)

3. code ในส่วนของ setup
   > ![cd4](https://user-images.githubusercontent.com/80879116/113147735-49a28900-925b-11eb-8922-b0e1c2b5c97e.png)

4. code ในส่วนของ loop
   > ![cd5](https://user-images.githubusercontent.com/80879116/113147956-853d5300-925b-11eb-9626-37afaa4e9db0.png)

## สรุปการแก้ไขในส่วนของ Code
  1. มีการใช้ \n \t เข้ามาใช้แทนที่ในส่วนของ println
  2. เพิ่มตัวแปร ในส่วนของดีเลย์
  3. ปรับการเขียน Serial.print ให้มีบรรทัดน้อยลง แต่การแสดงผลยังคงเดิม
  4. ปรับการเขียนด้วย For loop เป็น While loop

