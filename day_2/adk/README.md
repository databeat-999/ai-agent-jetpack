## วิธีติดตั้งและใช้งาน

1. ติดตั้ง dependencies ด้วยคำสั่ง:
   ```
   pip install -r requirements.txt 
   ```

2. สร้างไฟล์ .env จาก make.env.example ด้วยคำสั่ง:
   ```
   make.env.example-->.env
   ```

3. หากพอร์ตถูกใช้งานอยู่ สามารถระบุพอร์ตใหม่ได้ เช่น:
   ```
   adk web --port 9999
   ```
