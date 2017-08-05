# Billing Intelligent System (BIS)
Insurance accounting program

## Objective
ระบบรองรับการทำงานของระบบ การสร้าง Billing System จนกระทั่งออก File เพื่อส่งให้กับระบบ SAP ซึ่งทั้งหมดเป็นในรูปแบบ Automatically และเพื่อให้เข้าใจและมองภาพออกในรูปแบบอย่างง่าย ตาม Scope of Work 

## Feature 
1.  ระบบสามารถรองรับการ Create contract ได้อย่างสมบูรณ์
2.  Import Policy เข้าสู่ฐานข้อมูล
3.  Marketing สามารถทำการ Generate Invoice จาก Policy ที่ถึงกำหนดวางบิลตามที่กำหนดไว้ในแต่ละ Contract ได้โดยอัตโนมัติและถูกต้อง
4.  ระบบทำการ Amortize ยอดรายรับ (Income) เป็นราย Policy โดยทำการ Amortize หลังจากการ Confirm Generate Billing และสามารถทำการ Reverse ได้กรณีมีการยกเลิก Policy นั้น ๆ
5. 	ให้ระบบสามารถทำการบันทึกและยกเลิก Estimate Income ในกรณีที่ Policy นั้น ๆ ยังไม่มีการวางบิล ได้ถูกต้อง
6.	 เมื่อ Accounting ทำทำการ Generate Billing form  แล้วให้ระบบทำการ Generate SAP Template เพื่อทำการตั้ง AR 
7.	และเมื่อ Policy ถึงกำหนดรับรู้รายได้ (Earn Income) และ รับรู้ค่าคอมมิชชั่น (Commission Exp.) ให้ระบบทำการ Gen Amortize Income และ Gen Amortize Commission  ตามเงือนไขเวลาที่ผู้ใช้กำหนด 
8.	ให้ระบบมีรายงาน Amortization detail report check list ให้สามารถเรียกดูข้อมูลของ Income & Commission ได้ 
9.	หากมีการ Cancel Policy และมีการ Gen Amortize Income & Commission ไปแล้ว ให้ระบบแสดงค่าให้ถูกต้อง 
10.	ให้ระบบ สร้าง Report  Policy ที่ยังไม่ได้ทำการ Generate Billing 
11.	ให้ระบบการคำนวณ Commission และออกรายงานเพื่อตรวจสอบยอด Commission ได้
12.	ให้ระบบการสร้างและยกเลิกการสร้าง Batch เพื่อใช้สำหรับสร้างใบแจ้งหนี้ ได้
13.	ให้ระบบสามารถคำนวนตาราง Amortize Income และ Commission ได้


## Application Flow
![Alt text](https://github.com/jirayu88/BIS/blob/master/Project%20Scope.png)

## Platfrom
- Web Platfrom
- Window From Application (WPF)
- Window Console Application
- Web Service
![Alt text](https://github.com/jirayu88/BIS/blob/master/8-5-2017%2011-01-23%20PM.png)


## UI Design
![Alt text](https://github.com/jirayu88/BIS/blob/master/Generate%20Batch.png)
![Alt text](https://github.com/jirayu88/BIS/blob/master/Generate%20Billing%20form.png)


