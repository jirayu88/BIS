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














![Alt text](https://raw.githubusercontent.com/ETDA/e-TaxInvoice-PDFgen/master/eTaxInvoicePdfGenerator/icon_AppETax.png)


## e-Tax Invoice by TeDA - PDF Generator on PC 

  e-Tax Invoice by TeDA - PDF Generator on PC  มิติใหม่ของการสร้างใบกำกับภาษีอิเล็กทรอนิกส์ โดยอำนวยความสะดวกให้ผู้ประกอบการ สามารถสร้างใบกำกับภาษีอิเล็กทรอนิกส์ เพื่อสนับสนุนโครงการ e-Tax Invoice by Email ที่เป็นความร่วมมือระหว่าง สพธอ.และกรมสรรพากร 

สพธอ.ได้ พัฒนาโปรแกรมสร้างใบกํากับภาษีในรูปแบบ [PDF/A-3](https://en.wikipedia.org/wiki/PDF/A) ให้มีข้อมูล XML ตามเอกสารข้อเสนอแนะมาตรฐานด้านเทคโนโลยีสารสนเทศ และการสื่อสารที่จําเป็นต่อธุรกรรม ทางอิเล็กทรอนิกส์ (ขมธอ. 3-2560 เวอร์ชั่น 2.0) โดยตัวโปรแกรมนี้จะทํางานบน Stand-alone PC

**คุณลักษณะสำคัญของ e-Tax Invoice by TeDA - PDF Generator on PC  :**
* บันทึกข้อมูลผู้ประกอบการ ทั้งผู้ขายและผู้ซื้อ
* บันทึกข้อมูลสินค้า/บริการ
* สร้างใบกำกับภาษีอิเล็กทรอนิกส์
* สร้างใบเพิ่มหนี้อิเล็กทรอนิกส์
* สร้างใบลดหนี้อิเล็กทรอนิกส์

## Latest Release
Windows x64 : [โปรแกรมจัดเตรียมใบกำกับภาษีอิเล็กทรอนิกส์ในรูปแบบ PDF/A-3 สำหรับติดตั้งที่เครื่อง PC](https://github.com/ETDA/e-TaxInvoice-PDFgen/releases/download/1.0.0/eTaxInvoice_v1.0.0.zip)

หรือตรวจสอบ version ทั้งหมดได้จากหน้า [release page](https://github.com/ETDA/e-TaxInvoice-PDFgen/releases)

## Changelog 

[Read full changelog](https://github.com/ETDA/e-TaxInvoice-PDFgen/blob/master/CHANGELOG.md)

[1.0.0] - 2017-06-30

**Added** 
- e-Tax Invoice by TeDA - PDF Generator on PC baseline version 

## Contact Us
สามารถติดต่อเราได้ที่  eservice@etda.or.th

## Document
สามารถ download ได้จาก [ คู่มือโปรแกรมจัดเตรียมใบกำกับภาษีอิเล็กทรอนิกส์ในรูปแบบ PDF/A-3 (PC) ](http://teda.th/files/etaxdocuments/eTaxInvoice_PDF_A3_pc.pdf)  

## Dependency 
iTextSharp5.5.9.0 
 * itextsharp.dll
 * itextsharp.pdfa.dll
 * itextsharp.xtra.dll

## Font
 สามารถ download ได้จาก [THSarabun-PSK](https://github.com/ETDA/e-TaxInvoice-PDFgen/blob/master/Font/th-sarabun-psk.zip)
 
 > รายละเอียดการลง font สามารถอ่านได้จาก[ คู่มือโปรแกรมจัดเตรียมใบกำกับภาษีอิเล็กทรอนิกส์ในรูปแบบ PDF/A-3 (PC) ](http://teda.th/files/etaxdocuments/eTaxInvoice_PDF_A3_pc.pdf)  

## License 
[GNU Affero General Public License v3.0](https://github.com/ETDA/e-TaxInvoice-PDFgen/blob/master/LICENSE)

Permissions of this strongest copyleft license are conditioned on making available complete source code of licensed works and modifications, which include larger works using a licensed work, under the same license. Copyright and license notices must be preserved. Contributors provide an express grant of patent rights. When a modified version is used to provide a service over a network, the complete source code of the modified version must be made available.



