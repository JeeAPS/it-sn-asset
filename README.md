# 💻 IT-SN Asset Management (Cloud Web App)

ระบบจัดการทรัพย์สินไอที (IT Asset Management) ที่ถูกยกระดับจากการทำงานแบบ Offline (Local Script) ขึ้นสู่สถาปัตยกรรมแบบ Cloud-Native Web Application เพื่อช่วยลดเวลาการทำงาน (1-Click Automation) และเพิ่มความแม่นยำในการออกรายงาน

## 🚀 Features (ความสามารถหลัก)
- **Real-time Data Sync:** เชื่อมต่อและอ่านข้อมูลอุปกรณ์ไอทีโดยตรงจาก Google Sheets
- **Automated Document Generation:** ประมวลผลข้อมูลและสร้างไฟล์รายงาน Word (`.docx`) ตาม Template ที่กำหนดไว้อัตโนมัติในคลิกเดียว
- **Cloud Accessibility:** ใช้งานผ่าน Web Browser ได้จากทุกอุปกรณ์ (PC, Mac, Mobile) 
- **Zero Downtime Deployment:** อัปเดตเวอร์ชันใหม่ผ่านระบบ CI/CD อัตโนมัติบน Streamlit Cloud

## 🛠️ Tech Stack (เครื่องมือที่ใช้พัฒนา)
- **Language:** Python 3.9+
- **Frontend & Logic:** Streamlit
- **Document Engine:** `python-docx`
- **Data Manipulation:** `pandas`
- **Infrastructure:** Streamlit Community Cloud & GitHub

## 📂 Project Structure (โครงสร้างไฟล์)
```text
it-sn-asset/
├── import.py             # Main Script: โค้ดหลักสำหรับ UI และ Logic ของระบบ
├── template.docx         # Word Template: ไฟล์แม่แบบที่มีการฝัง Placeholder ตัวแปรไว้
├── requirements.txt      # Dependencies: รายชื่อไลบรารีที่จำเป็นสำหรับติดตั้งบนเซิร์ฟเวอร์
└── README.md             # Documentation: เอกสารแนะนำโปรเจกต์
