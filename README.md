# ENGSE203 LAB 01 — Developer Environment & GitHub Repository Setup

## ผู้จัดทำ

- ชื่อ-นามสกุล: นายสันติ ปัญญาหน้อย
- รหัสนักศึกษา: 68543210077-2
- ระบบปฏิบัติการที่ใช้: macOS

## วัตถุประสงค์ของงาน

เมื่อทำ LAB นี้เสร็จ นักศึกษาจะสามารถ

- ตรวจสอบและใช้ Node.js, npm, Visual Studio Code และ Git จาก Terminal ได้
- สร้างโครงงาน JavaScript ขนาดย่อม พร้อม package.json และ npm script
- รันโปรแกรม Node.js ที่แสดงชื่อ รหัสนักศึกษา OS และ Node.js version ได้
- สร้าง GitHub repository, commit, push และจัดทำ README เพื่อเป็นหลักฐานการเรียนรู้ได้

## เครื่องมือที่ใช้

- Visual Studio Code
- Node.js รุ่น LTS และ npm
- Git
- บัญชี GitHub ที่ใช้งานได้
- อินเทอร์เน็ต

## วิธีติดตั้งและรัน

เปิด **Visual Studio Code → Terminal → New Terminal** แล้วรันคำสั่งต่อไปนี้

```bash
node -v
npm -v
git --version
```

ผลลัพธ์ควรเป็นหมายเลขเวอร์ชันทั้ง 3 รายการ หากคำสั่งใดแสดงข้อความว่าไม่พบคำสั่ง ให้แจ้งผู้สอน/ผู้ช่วยสอนก่อนดำเนินการต่อ

## ขั้นตอนที่ 2 — สร้างโครงสร้างโครงงาน

สร้างพื้นที่ทำงานของรายวิชา แล้วสร้างโครงงาน LAB 1

**macOS / iMac M1**

```bash
mkdir -p ~/Documents/ENGSE203
cd ~/Documents/ENGSE203
```

**Windows 11 + Ubuntu WSL**

```bash
mkdir -p ~/workspace/engse203
cd ~/workspace/engse203
```

จากนั้น ใช้คำสั่งร่วมกันทั้งสองระบบ

```bash
mkdir engse203-lab01
cd engse203-lab01
npm init -y
mkdir src
code .
```

## โครงสร้างไฟล์

```text
.
├── src/
├── package.json
└── README.md
```

## หลักฐานผลลัพธ์

อธิบายผลลัพธ์ พร้อมแนบภาพหน้าจอหรือข้อความผลลัพธ์ตามที่ใบงานกำหนด

## ปัญหาที่พบและวิธีแก้ไข

- ปัญหา:
- วิธีแก้:

## References & AI Assistance

- Source / Documentation:
- AI tool used:
- Used for:
- My adaptation:
