# FUNCH x Slip2Go

## Assignment
Build a Car Rental System with the following features:
- View all available cars, with the ability to filter by destination country
- Clicking on a car opens its detail page, which must display all car information including available options and pricing rates
- Users can make a booking. When booking, the system has 2 flows: 1. Already logged in — book immediately 2. Book and register a new account at the same time
- Booking approval is done by an admin through the back-office system only
- Pricing Rules
  - A feature for customers to select pick-up and return dates/times, with automatic pricing calculation and display
  - Pricing has 2 rates: 1. Hourly rate — xx THB per hour 2. Daily rate — xx THB per day
  - If total usage exceeds 8 hours, it is counted as 1 full day
  - If the car is returned after 14:00, the entire day is counted as 1 full day — e.g. 10:00–12:00 = 2 hours, but 10:00–15:00 = 1 full day
  - Once usage exceeds 8 hours (counted as 1 day), the hourly rate starts over again from the pick-up time the next day — e.g. renting from 10:00 and returning at 11:00 the next day = 1 day + 1 hour

Back-Office System
- Car management
- Booking approval management
- Member management
- Booking summary reports

Additional Notes
- The requirements above cover only ~70% of the full scope. If you see any areas that can be fleshed out further, feel free to add features, UI elements, or flows to make it more complete
- The system supports bookings worldwide — be mindful of things that may behave differently across countries (e.g. timezones, currencies)
- The back-office system can also be extended and improved further
- The full scope of work covers everything from design, frontend development, backend (API) development, and database design

### Tech Stack
##### Frontend
- Must use one of: React.js, Vue.js, Next.js, or Nuxt.js + Tailwind CSS
##### Backend
- Must use Node.js or Golang + a framework. Primary database must be a Relational DB (Postgres recommended), but additional databases can be used as needed

## Scoring Criteria
Total score: 24 points, divided into 8 topics at 3 points each, based on the following scale:\
1 = Below expectations\
2 = Meets expectations\
3 = Exceeds expectations
###### Frontend Scoring Topics
1. Overall code structure — e.g. file organization and code quality (Efficiency, Readability, Maintainability)
2. UI design quality and UX (ease of use)
3. Security — both in terms of usage and code
4. Feature correctness and completeness
###### Backend Scoring Topics
1. Overall code structure — e.g. file organization and code quality (Efficiency, Readability, Maintainability)
2. API design — including endpoint naming and appropriateness of each endpoint's usage
3. Security — both in terms of usage and code
4. Database management (schema design, data modeling, data storage approach)

-----

## โจทย์
จัดทำระบบเช่ารถยนต์ โดยมีฟีเจอร์ดังต่อไปนี้
- ดูรายการรถทั้งหมด โดยสามารถแยกตาม ประเทศที่จะเดินทางไปได้
- เมื่อกดเลือกรถ จะเข้าสู่หน้ารายละเอียดรถ โดยต้องแสดงข้อมูลของรถคนนั้นทั้งหมด ตั้งแต่ option ไปจนถึงอัตราค่าบริการ
- สามารถกดจองรถได้ ซึ่งเมื่อกดจอง ระบบจะแบ่งเป็น 2 โฟลวคือ 1. เข้าสู่ระบบอยู่แล้วจองรถได้ทันที 2. จองรถพร้อมสมัครสมาชิกทันที
- การอนุมัติ จะเกิดจากแอดมิน ทำการอนุมัติผ่านระบบหลังบ้านเท่านั้น
- Pricing Rules
  - มีฟีเจอร์ให้ลูกค้าเลือกวันรับรถ - คืนรถ และคำนวนอัตราค่าบริการและแสดงอัตโนมัติ
  - อัตราการค่าบริการ จะแบ่งเป็น 2 อัตรา 1. เป็นรายชั่วโมงๆละ xx บาท 2. เป็นรายวันๆละ xx บาท
  - อัตราการค่าบริการ หากมีการนับเวลาการใช้งานแล้วเกิน 8 ชั่วโมงจะนับเป็น 1 วัน
  - อัตราการค่าบริการ หากเวลาในการนำส่งรถคืนเกินเวลา 14.00 น. จะนับค่าบริการของวันนั้นเท่ากับ 1 วันทันที เช่น 10.00 - 12.00 จะเท่ากับ 2 ชั่วโมง แต่ถ้า 10.00 - 15.00 ค่าบริการจะเท่ากับ 1 วัน
  - อัตราการค่าบริการ เมื่อใช้งานเกิน 8 ชั่วโมง แล้วอัตราค่าบริการนับเป็น 1 วันแล้วจะเริ่มนับรายชั่วโมงอีกครั้ง เมื่อถึงเวลารับรถของอีกวัน เช่น เช่ารถ 10 โมง คืน 11 โมง ของอีกวัน ค่าบริการจะเท่ากับ 1 วัน 1 ชั่วโมง

ระบบหลังบ้าน
- ระบบจัดการข้อมูลรถยนต์
- ระบบอนุมัติการจอง
- ระบบจัดการสมาชิก
- รายงานสรุปยอดจองรถ

เพิ่มเติม
- requirement เบื้องต้นเป็นเพียง 70% ของ scope ทั้งหมดเท่านั้น หากคิดว่าส่วนไหนสามารถเพิ่มเติมรายละเอียดให้สมบูรณ์ได้ อยากให้ใส่ฟีเจอร์ UI หรือ โฟลว มาให้สมบูรณ์ได้เลย
- ระบบสามารถจองได้ทั่วโลก ดังนั้นระวังบางเรื่องที่จะส่งผลแตกต่างกันหากอยู่คนละประเทศด้วย
- ระบบหลังบ้านสามารถ เพิ่มเติมให้่สมบูรณ์ได้มากยิ่งขึ้นเช่นกัน
- ขอบเขตงานทั้งหมดรวมตั้งแต่ การออกแบบ การพัฒนา frontend + backend(API) รวมถึงการออกแบบฐานข้อมูลด้วย

### Tech Stack
##### Frontend
- เลือกใช้ React.js, Vue.js, Next.js, Nuxt.js + Tailwind CSS เท่านั้น
##### Backend
- เลือกใช้ Node.js หรือ Golang + Framework ฐานข้อมูลเป็น Relational DB (แนะนำ Postgres) เป็นหลัก แต่สามารถเสริมฐานข้อมูลตัวอื่นๆได้ตามความจำเป็น

## เกณฑ์การให้คะแนน
คะแนนเต็ม 24 คะแนนโดยแบ่งเป็น 8 หัวข้อๆละ 3 คะแนน โดยมีหลักการให้คะแนน ดังต่อไปนี้\
1 = ทำได้ต่ำกว่าความคาดหวัง\
2 = ทำได้ตามความคาดหวัง\
3 = ทำได้เกินความคาดหวัง
###### หัวข้อการให้คะแนน Frontend มีดังต่อไปนี้
1. โครงสร้างการเขียน code ทั้งหมด เช่น รูปแบบการจัดวางไฟล์ และ คุณภาพการเขียนโค้ด (Efficiancy, Readability, Maintainability)
2. ความสวยงามระบบ (UI) และ ความสะดวกสบายในการใช้งาน (UX)
3. ความปลอดภัยทั้งในแง่การใช้งาน และ การเขียนโค้ด
4. ความถูกต้องและสมบูรณ์ทางด้านฟีเจอร์
###### หัวข้อการให้คะแนน Backend มีดังต่อไปนี้
1. โครงสร้างการเขียน code ทั้งหทด เช่น รูปแบบการจัดวางไฟล์ และ คุณภาพการเขียนโค้ด (Efficiancy, Readability, Maintainability)
2. การออกแบบ และ รูปแบบของ API ทั้งชื่อ Endpoint และ ความเหมาะสมในการใช้งานแต่ละ Endpoint
3. ความปลอดภัยทั้งในแง่การใช้งาน และ การเขียนโค้ด
4. การจัดการ Database (การออกแบบฐานข้อมูล, รูปแบบการเก็บข้อมูล, วิธีการเก็บข้อมูล)
---
## ข้อมูลอื่นๆเพิ่มเติม / Additional Information
- แจ้งสมัครงานโดยส่ง CV มาที่ อีเมล์ **wisarut.ph@funch.tech** จากนั้นทางบริษัทจะติดต่อกลับและแจ้งกำหนดส่งโปรเจค (ระยะเวลา 2 อาทิตย์)
- จัดทำระบบแบ่งเป็น 2 Project คือ Frontend และ Backend โดยพัฒนาตามเทคโนโลยีที่กำหนดให้เท่านั้น
- เมื่อทำงานเสร็จแล้ว เอาขึ้น Github ส่วนตัว โดยแยกเป็น 2 Repository ตามโปรเจค แล้วส่งลิงค์ Repository มาที่ **wisarut.ph@funch.tech**
- ระยะเวลาในการทำงานไม่มีผลต่อคะแนน บริษัทเราโฟกัสที่คุณภาพของงาน ดังนั้นใช้เวลาให้มากที่สุดเพื่อให้งานออกมาดีที่สุด
- เมื่อส่งงานแล้ว ทางบริษัทจะมีการนัดสัมภาษณ์อีกภายใน 3 วันหลังส่งงาน และแจ้งผลอีกครั้งภายใน 7 วันหลังการสัมภาษณ์
- หรือหากมีข้อสงสัยเพิ่มเติมให้สอบถามผ่านทางอีเมล์
---
- To apply, send your CV to **wisarut.ph@funch.tech** — the company will follow up and provide a project submission deadline (2-week timeframe)
- The system must be split into 2 separate projects: Frontend and Backend, developed using only the specified tech stack
- Once completed, upload both projects to your personal GitHub as 2 separate repositories, then send the repository links to **wisarut.ph@funch.tech**
- Time taken has no impact on your score — we focus on the quality of work, so take as much time as you need to deliver your best
- After submission, the company will schedule an interview within 3 days, and notify you of the result within 7 days after the interview
- For any questions, feel free to reach out via email


