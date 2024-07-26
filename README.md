# Tree Planting Control System Using IoT

ระบบการควบคุมระยะไกลด้วย IoT (Internet of Things) ในการปลูกต้นไม้ การรดน้ำ การให้ปุ๋ย และการให้แสงจากหลอดไฟ โดยสามารถควบคุมการเปิดปิดการทำงานได้ทั้งในแอพพลิเคชั่นที่เชื่อมต่อ MQTT Broker ที่สามารถ remote ผ่านแอพได้ และสามารถควบคุมผ่านเว็บได้ โดยที่เว็บจะมีการเก็บข้อมูลค่าสถานะและสามารถอัพโหลดรูปภาพของต้นไม้ในแต่ละวันลง Database ได้

## Features

- ควบคุมการเปิดปิดการรดน้ำ การให้ปุ๋ย และการให้แสงจากหลอดไฟ
- ควบคุมการทำงานผ่านแอพพลิเคชั่นที่เชื่อมต่อกับ MQTT Broker
- ควบคุมการทำงานผ่านเว็บ
- เก็บข้อมูลค่าสถานะและอัพโหลดรูปภาพของต้นไม้ลง Database

## Technologies Used

- **VS Code:** สำหรับพัฒนา Web โดยใช้ JavaScript และ CSS
- **MongoDB:** สำหรับเก็บข้อมูล Database
- **MQTT:** สำหรับการสื่อสารระหว่างอุปกรณ์

## Hardware Used

- ปั๊มน้ำ
- ปั๊มปุ๋ย
- หลอดไฟ
- Relay 2 Module
- Relay 5V
- Raspberry Pi Zero 2W
- Adapter 12V
- Step Down 12V -> 5V

## Image

* Hardware
<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/79a1294a-23d0-4f56-ad29-f12c514d0965" style="width: 30%;">
</div>

* Tree
<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/f8db1427-01d8-49f1-bbdb-f7fda7b0903c" style="width: 30%;">
</div>
