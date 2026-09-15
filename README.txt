
ESP32 EGG PAM - BLE Controller

คำสั่งที่แอปส่ง:
F = เดินหน้า
B = ถอยหลัง
L = ซ้าย
R = ขวา
S = หยุด

BLE:
Device name: ESP32
Service UUID:
6E400001-B5A3-F393-E0A9-E50E24DCCA9E
Characteristic UUID:
6E400002-B5A3-F393-E0A9-E50E24DCCA9E

วิธีใช้งาน:
1. สร้างโปรเจกต์ Flutter หรือใช้โฟลเดอร์นี้
2. flutter pub get
3. flutter run
4. เปิด Bluetooth ของโทรศัพท์
5. เปิดแอป แล้วกด "ค้นหา ESP32"
6. ต้องอัปโหลดโค้ด BLE ที่ใช้ UUID และชื่อ ESP32 ตรงกับแอป

ตอนนี้แอปยังควบคุมเฉพาะ BLE ไม่ได้ควบคุมมอเตอร์โดยตรง
