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

### 2. Gantt Chart
```mermaid
gantt
    title Gantt Chart แผนผังการพัฒนาระบบยืม-คืนอุปกรณ์
    dateFormat  YYYY-MM-DD
    section 1. Planning & Requirements
    เก็บรวบรวมข้อมูล Stakeholders       :a1, 2026-10-01, 7d
    วิเคราะห์ Problem & Requirements      :a2, after a1, 7d
    section 2. System Design
    ออกแบบ DFD & ER-Diagram            :b1, after a2, 7d
    ออกแบบ UI/UX                      :b2, after b1, 7d
    section 3. System Development
    ระบบ Login & ยืนยันตัวตน              :c1, after b2, 7d
    ระบบค้นหาและยืมอุปกรณ์               :c2, after c1, 7d
    ระบบอนุมัติและคืนอุปกรณ์              :c3, after c2, 7d
    ระบบจัดการอุปกรณ์                     :c4, after c3, 7d
    section 4. Testing & Deploy
    System Testing                    :d1, after c4, 7d
    Deploy ขึ้น Server                 :e1, after d1, 4d
