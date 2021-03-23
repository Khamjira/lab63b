# การทดลองที่ 1 เรื่อง การเขียนโปรแกรมเพื่อรันบนไมโครคอนโทรลเลอร์

## วัตถุประสงค์ของการทดลอง
1. เข้าใจการต่อวงจรโดยใช้ไมโครคอนโทรลเลอร์
2. ฝึกการเขียนโปรแกรมด้วย platformio

## อุปกรณ์ที่ใช้
1. ไมโครคอนโทรลเลอร์
2. สายUSB
3. Serial converter

## ศึกษาข้อมูลเบื้องต้น
* https://learninginventions.org 
* https://www.youtube.com/watch?v=NLIUsWLEpmg

## วิธีทำการทดลอง
1. ต่อสายUSB เข้ากับ Serial Converter
   * ![IMG-3493](https://user-images.githubusercontent.com/80879116/112003626-a1ead400-8b53-11eb-8f3d-2993e1edc97c.jpg)

2. ต่อเข้ากับไมโครคอนโทรลเลอร์
   * ![IMG-3494](https://user-images.githubusercontent.com/80879116/112004142-1cb3ef00-8b54-11eb-9b21-b69a5eb8b125.jpg)
    
    
3. เขียนโปรแกรมโดยใช้ตามตัวอย่างที่ 1 ที่เขียนด้วนภาษา C และ C++
   * ![code1](https://user-images.githubusercontent.com/80879116/112017573-512da800-8b60-11eb-967e-137d91d3a469.jpg)

4. จากนั้นไปดูที่ configulation File ที่ชื่อว่า platformio.ini จะบอกว่าเป็นผลิตภันณ์ของบริษัทใด boardชื่ออะไร ใช้วีธีเขียนโปรแกรมแบบใด เป็นต้น
   * ![Untitled](https://user-images.githubusercontent.com/80879116/112145322-c787e400-8c0c-11eb-8a00-2f5724f848e9.png)

5. upload program 01_Serial-Monitor เข้าไปยังไมโครคอนโทรลเลอร์
   * ![Untitled1](https://user-images.githubusercontent.com/80879116/112145789-66144500-8c0d-11eb-9410-e1d7995becc2.png)

6. ในขณะที่ RUN เพื่อให้ไมโครคอนโทรลเลอร์ รับโปรแกรมใหม่ กดปุ่มเพื่อให้เซ็ต 
   * ![Untitled2](https://user-images.githubusercontent.com/80879116/112146326-07030000-8c0e-11eb-854d-25a6c2060e1e.png)

7. โปรแกรมโหลดสำเร็จ
   * ![Untitled3](https://user-images.githubusercontent.com/80879116/112146650-695c0080-8c0e-11eb-81e3-e1570c0226a1.png)

8. จากนั้นป้อนคำสั่ง pio device moniter เพื่อดูผลลัพธ์ที่แสดงผลออกมาจากคอมพิวเตอร์
   * ![Untitled4](https://user-images.githubusercontent.com/80879116/112147088-e12a2b00-8c0e-11eb-9302-464f756ea8d8.png)

## บันทึกผลการทดลอง


## อภิปรายผลการทดลอง

## คำถามหลังการทดลอง
