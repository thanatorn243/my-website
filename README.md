# ระบบบันทึกรายรับ-รายจ่าย

ระบบบันทึกรายรับ-รายจ่ายออนไลน์ พร้อมสรุปข้อมูลอัตโนมัติ

## คุณสมบัติ

- บันทึกรายรับและรายจ่าย
- แสดงสรุปรายรับ-รายจ่ายรวม
- แสดงกราฟวงกลมแสดงสัดส่วนรายจ่ายตามหมวดหมู่
- แสดงประวัติรายการทั้งหมด
- ระบบจัดการข้อมูลแบบ Real-time

## การติดตั้ง

1. ติดตั้ง MongoDB บนเครื่องของคุณ
2. ติดตั้ง Node.js และ npm
3. Clone โปรเจคนี้
4. ติดตั้ง dependencies:

```bash
# ติดตั้ง dependencies สำหรับ backend
npm install

# ติดตั้ง dependencies สำหรับ frontend
cd client
npm install
```

## การใช้งาน

1. เริ่มต้น MongoDB service
2. รัน backend server:

```bash
npm run dev
```

3. รัน frontend development server:

```bash
cd client
npm start
```

4. เปิดเบราว์เซอร์และไปที่ http://localhost:3000

## เทคโนโลยีที่ใช้

- Frontend: React, Material-UI, Recharts
- Backend: Node.js, Express
- Database: MongoDB 