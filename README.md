# Water Operation KM Dashboard

ระบบจัดการองค์ความรู้งานสูบส่งและสูบจ่ายน้ำ (Prototype)

🌐 **เปิดใช้งาน:** https://tigerswp818-star.github.io/water-km-dashboard/

- Dashboard ไฟล์เดียว (self-contained) — Overview, System Map (จำลองจากจอ SCADA จริง), Main Transmission, Pumping Stations, Flow & Pressure Analytics (ข้อมูลรายชั่วโมงจริง มี.ค.–พ.ค. 2025/2026), RTU Monitoring (ทะเบียน 236 จุด), Shift Handover (รับ–ส่งเวร Real-time), KM Library (42 เรื่อง), Data Upload
- **Shift Handover** — บอร์ดผู้บริหารดูสถานะเวรทั้ง 10 สถานีแบบสด (ลิงก์ `#shift`), เจ้าหน้าที่ลงชื่อรับเวร/บันทึกเหตุการณ์/ส่งเวรพร้อมยกยอดงานค้างอัตโนมัติ, ประวัติย้อนหลัง + Export/Import JSON — โหมดสาธิตเก็บในเครื่อง (สดข้ามแท็บ) และสลับเป็น Firebase Realtime Database ได้จากแท็บ "การเชื่อมต่อ Real-time" เพื่อให้ทุกเครื่องเห็นพร้อมกันทั้งองค์กร
- ข้อมูลต้นทางและประวัติการพัฒนาอยู่ที่ repo [TOEIC_GAME](https://github.com/tigerswp818-star/TOEIC_GAME) branch `claude/water-operation-km-dashboard-b08042` โฟลเดอร์ `water-km-dashboard/`
- Deploy อัตโนมัติผ่าน GitHub Actions ทุกครั้งที่ push ไฟล์ใหม่เข้า `main`
