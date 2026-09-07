# TikFinity Connector — คู่มือตั้งค่า IP / Port / Password

คู่มือภาษาไทยสำหรับต่อ TikFinity เข้ากับ Minecraft ผ่านมอด TikFinity Connector (Fabric, Minecraft 26.2)

**อ่านคู่มือ:** https://aotgtr.github.io/tikfinity-connector-guide/

## ในคู่มือมีอะไร

- มอดทำงานยังไง (TikTok → TikFinity → HTTP → เกม)
- ติดตั้ง 2 แบบ: เล่นคนเดียว (client) และเปิดเซิร์ฟเวอร์ Fabric
- 3 ช่องใน TikFinity (IP / Port / Password) คืออะไร และตรงกับค่าไหนในมอด
- ค่าที่ต้องใส่ใน 3 สถานการณ์: เครื่องเดียวกัน · ในวง LAN · เซิร์ฟเวอร์ IP นอก
- คำสั่ง `/tikfinity` สำหรับตั้งค่าในเกม
- เปิด firewall / port forward
- ความปลอดภัย และการแก้ปัญหา

## ไฟล์

- `index.html` — ตัวคู่มือ (หน้าเดียว ไม่มี dependency ภายนอกนอกจาก Google Fonts)
- `assets/` — ภาพประกอบ

หน้าเว็บ deploy ผ่าน GitHub Pages จาก branch `main`

## เครดิต

มอดต้นทาง: [jakob-kruse/tikfinity_mod](https://github.com/jakob-kruse/tikfinity_mod) (MIT)

หน้านี้เป็นคู่มือการตั้งค่าเท่านั้น ไม่ได้มีส่วนเกี่ยวข้องกับ TikFinity หรือ TikTok
