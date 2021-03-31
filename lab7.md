# การทดลองที่ 2 เรื่อง การเขียนโปรแกรมค้นหาไวไฟ

## วัตถูประสงค์
1. เพื่อเข้าใจการต่อวงจรโดยใช้ไมโครคอนโทรลเลอร์
2. ฝึกการเขียนโปรแกรมด้วย platformio

## อุปกรณ์ที่ใช้
1. ไมโครคอนโทรลเลอร์
2. สายUSB
3. USB2Serial converter

## ศึกษาข้อมูลเบื้องต้น
* https://www.youtube.com/watch?v=yBjab0UNuB8

## Source Code
   > #include <Arduino.h>
   > #include <ESP8266WiFi.h>

   > int cnt = 0;

   > void setup()
     > {
	>Serial.begin(115200);
	>WiFi.mode(WIFI_STA);
	>WiFi.disconnect();
	>int d = 500;
	>delay(d);
	>Serial.println("\n\n\n");
     >}

   > void loop()
    > {
	>Serial.print("========== เริ่มต้นแสกนหา Wifi ===========\n");
	>int n = WiFi.scanNetworks();
	>int i = 0;
	>if(n == 0) {
		>Serial.println("NO NETWORK FOUND");
	>} else {
		>while(i<n) {
			>Serial.print(i + 1 ,": ", WiFi.SSID(i)\t);
			>Serial.println(" (", WiFi.RSSI(i),")");
			>Serial.print(WiFi.channel(i));
			>delay(10);
			>i++;
		>}
	>}
	>Serial.println("\n\n");
	>delay(10 * 1000);
      >}
      
