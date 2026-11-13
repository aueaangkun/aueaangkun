# backend-api-w1

- ชื่อ-นามสกุล: <ใส่ชื่อของคุณ>
- รหัสนักศึกษา: <ใส่รหัส>
- วิชา: 31901-2005 การพัฒนาซอฟต์แวร์ด้วยเทคโนโลยี Back-End (หน่วยที่ 1 สัปดาห์ที่ 1)

## คำอธิบายระบบ
ระบบแจ้งซ่อมคอมพิวเตอร์และอุปกรณ์ของวิทยาลัย (Back-End API) ผู้แจ้ง (นักศึกษา/ครู) แจ้งเครื่องที่เสียพร้อมอาการและติดตามสถานะได้
ช่างเทคนิครับงานและอัปเดตสถานะการซ่อม หัวหน้างานดูสรุปงาน มอบหมายงาน และจัดการข้อมูลห้อง/เครื่อง
รายละเอียดดูที่ [docs/scenario.md](docs/scenario.md)

## โครงสร้างโปรเจกต์
```
backend-api-w1/
├── docs/
│   ├── scenario.md      ใบสถานการณ์จำลอง
│   └── uml/             usecase.png, class-diagram.png, ไฟล์ .drawio
├── src/
│   ├── routes/          เส้นทาง API
│   ├── controllers/     ตรรกะการทำงาน
│   ├── models/          โครงสร้างข้อมูล
│   └── config/          ค่าตั้งค่า
├── .env.example
├── .gitignore
├── package.json
└── README.md
```

## วิธีติดตั้ง
```bash
git clone https://github.com/aueaangkun/backend-api-w1.git
cd backend-api-w1
npm install
cp .env.example .env
```
