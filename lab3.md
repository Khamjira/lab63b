# การทดลองที่ 3 เรื่อง การเขียนโปรแกรมเอ้าพุทสัญญาณดิจิทัล

## วัตถุประสงค์ของการทดลอง
1.เพื่อเข้าใจการต่อวงจรโดยใช้ไมโครคอนโทรลเลอร์
2.ฝึกการเขียนโปรแกรมด้วย platformio

## อุปกรณ์ที่ใช้
1. ไมโครคอนโทรลเลอร์
2. สายUSB
3. USB2Serial converter
4. Input/Output Port 
5. adapter
6. หลอดไฟ LED

## ศึกษาข้อมูลเบื้องต้น
* https://www.youtube.com/watch?v=CCnN1WJsXQY

## วิธีทำการทดลอง
1. ต่อ adapter เข้ากับ USB2Serial converter
   * ![1](https://user-images.githubusercontent.com/80879116/112155144-98c33b00-8c17-11eb-837a-bca5621ba449.png)

2. ต่อ ไมโครตอนโทรลเลอร์ เข้ากับ adapter
   * ![2](https://user-images.githubusercontent.com/80879116/112155609-0bccb180-8c18-11eb-88a3-8f62f4b3758c.png)

3. ไปดูที่โปรแกรม อยู่ในโฟลเดอร์ที่ 03_Output-Port
   * ![3](https://user-images.githubusercontent.com/80879116/112162584-c495ef00-8c1e-11eb-8ae0-4daee6866961.png)

4. เขียนโปรแกรมโดยใช้ตามตัวอย่าง ที่เขียนด้วนภาษา C และ C++
  * ![4](https://user-images.githubusercontent.com/80879116/112163029-35d5a200-8c1f-11eb-981d-51bdd5a9dd76.png)

5. upload program โดยใช้คำสั่ง pio run -t upload
  *![5](https://user-images.githubusercontent.com/80879116/112163807-f22f6800-8c1f-11eb-846a-f249d46aca99.png)
