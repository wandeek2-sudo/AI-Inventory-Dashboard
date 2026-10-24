# AI Inventory Dashboard — ติดตั้งเป็นเว็บไซต์

## วิธีเผยแพร่ผ่าน Render (ไม่ต้องรัน Colab)

1. แตกไฟล์ ZIP นี้
2. อัปโหลดไฟล์ทั้งหมด (`app.py`, `requirements.txt`, `render.yaml`, `README_TH.md`) ไปยัง GitHub repository ใหม่
3. เข้า https://render.com แล้วสมัคร/เข้าสู่ระบบ
4. เลือก **New → Blueprint** และเชื่อมต่อ GitHub repository ที่อัปโหลดไว้ (หรือเลือก New → Web Service แล้วใช้ Build Command `pip install -r requirements.txt` และ Start Command `python app.py`)
5. เลือกแผน Free หากมีให้เลือก แล้วกด deploy
6. เมื่อ deploy สำเร็จ Render จะให้ URL ของเว็บลงท้ายด้วย `onrender.com`

## ข้อจำกัด
- ต้องมีบัญชี Render และ GitHub; ฉันไม่สามารถสร้าง/เผยแพร่ URL ในนามบัญชีของคุณจากในแชทนี้ได้
- บริการฟรีอาจพักเมื่อไม่มีการใช้งาน และต้องรอให้เริ่มใหม่เมื่อเปิดลิงก์
- ไฟล์ที่ผู้ใช้ upload ในเว็บไม่ได้เก็บถาวรบนระบบโฮสต์ฟรี ดังนั้นควรดาวน์โหลดรายงานก่อนออกจากระบบ
- ห้ามอัปโหลดข้อมูลสต็อกที่เป็นความลับหรือข้อมูลลูกค้าที่อ่อนไหวลงในเว็บสาธารณะ
