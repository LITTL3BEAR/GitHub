# DEV

## Create branch
1. git branch // ดู branch

2. git checkout -b {branch name} // สร้างและสลับ branch

3. git branch // ดูตำแหน่ง branch ตอนนี้

4. echo "your message" >> dev.md

5. git add .

6. git commit -m "your message"

7. git push origin {branch name} // อัพ branch ขึ้น server

up branch ขึ้น server เสร็จเรียบร้อย ... ตรวจสอบใน github


## Other branch command
$ git checkout {branch name} {file name} // ย้ายไฟล์จาก branch ต้นทาง **(สลับมาอยู่ใน branch ปลายทางก่อน)

$ git branch -d {branch name} // ลบ branch

$ git merge --no-ff {branch name} // รวมไฟล์จาก branch
