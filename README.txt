ชุดไฟล์แอป ระบบบันทึกรอบเดือนสตรี (สร้างเมื่อ 20261028-122102)

วิธีติดตั้งบน GitHub Pages (ฟรี)
1. สมัคร/เข้าสู่ระบบ github.com แล้วกด New repository ตั้งชื่อ เช่น period-app เลือก Public แล้วกด Create repository
2. กด uploading an existing file (หรือ Add file > Upload files) ลากไฟล์ทั้งหมดในชุดนี้ (ไม่ใช่ไฟล์ zip) ไปวาง แล้วกด Commit changes
3. ไปที่ Settings > Pages > Build and deployment > Source เลือก Deploy from a branch เลือก main และ /(root) แล้วกด Save
4. รอประมาณ 1-10 นาที ลิงก์แอปจะเป็น https://ชื่อบัญชี.github.io/period-app/
5. นำลิงก์นั้นไปใส่ในระบบ: หน้าผู้ดูแล > แอปบนมือถือ (PWA) > ลิงก์ของแอป แล้วกดบันทึก (ขั้นนี้จำเป็น ระบบจะยอมให้แอปเปิดได้)
6. ถ้าใช้ปุ่มเข้าสู่ระบบด้วย Google ให้เพิ่มลิงก์แอปเป็น Authorized redirect URI ใน Google Cloud Console ด้วย

อัปเดตแอปภายหลัง: สร้างชุดไฟล์ใหม่ แล้วอัปโหลดทับไฟล์เดิมทั้งหมดในที่เก็บเดิม (ลิงก์แอปไม่เปลี่ยน)
ห้ามแก้ไฟล์ด้วยมือ ยกเว้นต้องการเปลี่ยนรูปไอคอน (ใช้ชื่อไฟล์และขนาดเดิม)
