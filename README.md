# การทดสอบนักพัฒนาระบบ

Tech Stack ที่จำเป็น

• PHP

• CSS

• HTML

• (JavaScript), (TypeScript), (Sweetalert2)

ให้ทำการสร้างโปรเจคขึ้นมาและทำการเพิ่มคุณสมบัติโดยแบ่งออกเป็นส่วนๆดังนี้

• ลงทะเบียน

POST /register

• เข้าสู่ระบบ

POST /auth/signin

• สร้างสิ่งที่ต้องทำ (ต้องมีการรับรองความถูกต้อง)

POST /todos

• รับสิ่งที่ต้องทำ (ต้องมีการรับรองความถูกต้อง)

GET /todos?[page=1]&[perPage=5]

• ค้นหาสิ่งที่ต้องทำ (จำเป็นต้องตรวจสอบสิทธิ์)

GET /todos/{todoId}

• อัปเดตสิ่งที่ต้องทำ (จำเป็นต้องมีการตรวจสอบสิทธิ์)

PATCH /todos/{todoId}

• ลบสิ่งที่ต้องทำ (จำเป็นต้องตรวจสอบสิทธิ์)

DELETE /todos/{todoId}
