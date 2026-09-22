# รายงานวิชาวิศวกรรมซอฟต์แวร์ 
**ชื่อ-นามสกุล**: [นาย ติรคุณ นพกาศ]
**รหัสนักศึกษา**: [3674021360068]

---

## ส่วนที่ 2: WBS และ Gantt Chart

### 1. Work Breakdown Structure (WBS)
```mermaid
mindmap
  root((ระบบยืม-คืนอุปกรณ์ห้องปฏิบัติการ))
    1. การวางแผนและวิเคราะห์
      1.1 เก็บรวบรวมข้อมูล Stakeholders
      1.2 วิเคราะห์ Problem Statement และ Requirements
    2. การออกแบบระบบ
      2.1 ออกแบบ Context Diagram และ DFD Level 1, 2
      2.2 ออกแบบ UI/UX หน้าจอผู้ใช้และเจ้าหน้าที่
    3. การพัฒนาระบบ
      3.1 ระบบยืนยันตัวตน Authenticate
      3.2 ระบบค้นหาและส่งคำขอยืมอุปกรณ์
      3.3 ระบบอนุมัติคำขอและบันทึกการรับคืน
      3.4 ระบบจัดการข้อมูลอุปกรณ์
    4. การทดสอบระบบ
      4.1 Unit Testing & Integration Testing
      4.2 User Acceptance Testing (UAT)
    5. การติดตั้งและส่งมอบ
      5.1 Deploy ขึ้น Production Server

## ส่วนที่ 2: Work Breakdown Structure (WBS) และ Gantt Chart

### 1. Work Breakdown Structure (WBS)
```mermaid
mindmap
  root((ระบบยืม-คืนอุปกรณ์ห้องปฏิบัติการ))
    1. การวางแผนและวิเคราะห์
      1.1 เก็บรวบรวมข้อมูล Stakeholders
      1.2 วิเคราะห์ Problem Statement และ Requirements
    2. การออกแบบระบบ
      2.1 ออกแบบ Context Diagram และ DFD Level 1, 2
      2.2 ออกแบบ UI/UX หน้าจอผู้ใช้และเจ้าหน้าที่
    3. การพัฒนาระบบ
      3.1 ระบบยืนยันตัวตน Authenticate
      3.2 ระบบค้นหาและส่งคำขอยืมอุปกรณ์
      3.3 ระบบอนุมัติคำขอและบันทึกการรับคืน
      3.4 ระบบจัดการข้อมูลอุปกรณ์
    4. การทดสอบระบบ
      4.1 Unit Testing & Integration Testing
      4.2 User Acceptance Testing (UAT)
    5. การติดตั้งและส่งมอบ
      5.1 Deploy ขึ้น Production Server
    System Testing                    :d1, after c4, 7d
    Deploy ขึ้น Server                 :e1, after d1, 4d
