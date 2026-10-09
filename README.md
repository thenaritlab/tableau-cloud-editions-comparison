# ☁️ เปรียบเทียบ Tableau Cloud Editions

> สรุป 4 Edition ของ Tableau Cloud ได้แก่ **Standard, Enterprise, Cloud+ และ Tableau+ Bundle** ทั้งราคา ฟีเจอร์ ประเภท License และวิธีเลือกให้เหมาะกับองค์กร

![Tableau Cloud](https://img.shields.io/badge/Tableau-Cloud-E97627?logo=tableau&logoColor=white)
![Editions](https://img.shields.io/badge/Editions-4-1F77B4)
![Updated](https://img.shields.io/badge/Updated-Oct%202026-2E7D32)

> [!IMPORTANT]
> ข้อมูลอ้างอิงจากหน้า Pricing และ Help ทางการของ Tableau ณ **ตุลาคม 2026** ราคาเป็น **List Price (USD)** ราคาจริงขึ้นกับสัญญา ส่วนลด และ Partner ในแต่ละประเทศ

---

## 🧭 สารบัญ

| | หัวข้อ |
|:---:|---|
| 1️⃣ | [ภาพรวม 4 Edition](#1️⃣-ภาพรวม-4-edition) |
| 2️⃣ | [ราคาต่อ User](#2️⃣-ราคาต่อ-user) |
| 3️⃣ | [ประเภท License: Creator / Explorer / Viewer](#3️⃣-ประเภท-license-creator--explorer--viewer) |
| 4️⃣ | [ตารางเปรียบเทียบฟีเจอร์](#4️⃣-ตารางเปรียบเทียบฟีเจอร์) |
| 5️⃣ | [รายละเอียดฟีเจอร์สำคัญ](#5️⃣-รายละเอียดฟีเจอร์สำคัญ) |
| 6️⃣ | [Site Capacity และข้อจำกัด](#6️⃣-site-capacity-และข้อจำกัด) |
| 7️⃣ | [รูปแบบการซื้อ License](#7️⃣-รูปแบบการซื้อ-license) |
| 8️⃣ | [เลือก Edition ไหนดี](#8️⃣-เลือก-edition-ไหนดี) |
| ❓ | [คำถามที่พบบ่อย](#-คำถามที่พบบ่อย) |
| 📚 | [แหล่งอ้างอิง](#-แหล่งอ้างอิง) |

---

## 1️⃣ ภาพรวม 4 Edition

แต่ละ Edition **ได้ทุกอย่างของ Edition ก่อนหน้า** แล้วเพิ่มความสามารถขึ้นไปทีละขั้น

```mermaid
flowchart LR
    A["🟢 Standard BI ครบชุด"] --> B["🔵 Enterprise + Governance & Security"]
    B --> C["🟣 Cloud+ + AI (Tableau Agent)"]
    C --> D["🟠 Tableau+ Bundle + Tableau Next / Agentic"]
```

| Edition | นิยามสั้น ๆ | เหมาะกับ |
|---|---|---|
| 🟢 **Standard** | ใช้ Tableau ได้ครบ: Web Authoring, Desktop, Prep, Pulse | ทีม/แผนกที่เริ่มใช้ BI |
| 🔵 **Enterprise** | + Data Management + Advanced Management | องค์กรที่ต้องการ Governance, Security และ Data Catalog |
| 🟣 **Cloud+** | + Tableau Agent (AI) + Tableau Knowledge + Premier Success | องค์กรที่อยากใช้ AI ช่วยสร้างและวิเคราะห์ |
| 🟠 **Tableau+ Bundle** | + Tableau Next + Data 360 + Tableau Semantics | องค์กรที่ใช้ Salesforce และต้องการ Agentic Analytics เต็มรูปแบบ |

> [!NOTE]
> ไม่มี Edition ชื่อ "Cloud Enterprise Plus" ตัวที่สูงที่สุดคือ **Tableau+ Bundle**

---

## 2️⃣ ราคาต่อ User

ราคาต่อ User ต่อเดือน (USD) **จ่ายรายปี**

| License | 🟢 Standard | 🔵 Enterprise | 🟣 Cloud+ | 🟠 Tableau+ Bundle |
|---|:---:|:---:|:---:|:---:|
| ✏️ **Creator** | $75 | $115 | ติดต่อ Sales | ติดต่อ Sales |
| 🔍 **Explorer** | $42 | $70 | ติดต่อ Sales | ติดต่อ Sales |
| 👁️ **Viewer** | $15 | $35 | ติดต่อ Sales | ติดต่อ Sales |

> [!WARNING]
> - **ไม่มีแพ็กเกจรายเดือน** ทุก Edition ต้องทำสัญญา **รายปี**
> - ทุก Deployment ต้องมี **Creator อย่างน้อย 1 License**

### 🧮 ตัวอย่างคำนวณ (Standard, List Price)

| License | จำนวน | ราคา/เดือน | รวม/ปี |
|---|:---:|:---:|---:|
| Creator | 2 | $75 | $1,800 |
| Explorer | 5 | $42 | $2,520 |
| Viewer | 50 | $15 | $9,000 |
| **รวม** | **57 users** | | **$13,320** |

---

## 3️⃣ ประเภท License: Creator / Explorer / Viewer

| ความสามารถ | ✏️ Creator | 🔍 Explorer | 👁️ Viewer |
|---|:---:|:---:|:---:|
| ดู Dashboard และ Interact (Filter, Drill) | ✅ | ✅ | ✅ |
| ดู Tableau Pulse Metrics | ✅ | ✅ | ✅ |
| Subscription / Data-driven Alerts | ✅ | ✅ | ✅ |
| ดาวน์โหลด Summary Data | ✅ | ✅ | ✅ |
| แก้ไข / สร้าง View บนเว็บจาก Data ที่ Publish ไว้แล้ว | ✅ | ✅ | ❌ |
| เป็น Site Admin จัดการ User | ✅ | ✅ | ❌ |
| เชื่อมต่อ Data Source ใหม่ | ✅ | ❌ | ❌ |
| ใช้ **Tableau Desktop** และ **Tableau Prep Builder** | ✅ | ❌ | ❌ |
| สร้าง Data Flow และ Knowledge Graph | ✅ | ❌ | ❌ |

> [!TIP]
> **จำง่าย ๆ:** Creator = **สร้างจาก Data ใหม่** · Explorer = **ต่อยอดจากของที่มีอยู่** · Viewer = **ดูอย่างเดียว**

---

## 4️⃣ ตารางเปรียบเทียบฟีเจอร์

| ฟีเจอร์ | 🟢 Standard | 🔵 Enterprise | 🟣 Cloud+ | 🟠 Bundle |
|---|:---:|:---:|:---:|:---:|
| **📊 Core Analytics** | | | | |
| Tableau Cloud | ✅ | ✅ | ✅ | ✅ |
| Tableau Desktop | ✅ | ✅ | ✅ | ✅ |
| Tableau Prep Builder | ✅ | ✅ | ✅ | ✅ |
| Tableau Pulse | ✅ | ✅ | ✅ | ✅ |
| Tableau MCP | ✅ | ✅ | ✅ | ✅ |
| จำนวน Site (Tableau Cloud Manager) | 3 | 10 | 50 | 50 |
| **🛡️ Governance & Management** | | | | |
| Data Management | ❌ | ✅ | ✅ | ✅ |
| Advanced Management | ❌ | ✅ | ✅ | ✅ |
| **🤖 AI** | | | | |
| Tableau Knowledge | ❌ | ❌ | ✅ | ✅ |
| Tableau Agent in Pulse | ❌ | ❌ | ✅ | ✅ |
| Tableau Agent in Authoring | ❌ | ❌ | ✅ | ✅ |
| Tableau Agent in Prep | ❌ | ❌ | ✅ | ✅ |
| Tableau Agent in Catalog | ❌ | ❌ | ✅ | ✅ |
| Release Preview Sites | ❌ | ❌ | ✅ | ✅ |
| **🧠 Salesforce Platform** | | | | |
| Data 360 | ❌ | ❌ | ⚪ ผ่าน Salesforce Foundations | ✅ |
| Tableau Semantics | ❌ | ❌ | ⚪ ผ่าน Salesforce Foundations | ✅ |
| Tableau Next Platform | ❌ | ❌ | ❌ | ✅ |
| Tableau Agent in Tableau Next | ❌ | ❌ | ❌ | ✅ |
| Tableau Next in Slack | ❌ | ❌ | ❌ | ✅ |
| Credits (สำหรับ AI บน Data 360) | ❌ | ❌ | ❌ | 250K |
| **🎓 Support & Learning** | | | | |
| Standard Success | ✅ | ✅ | ✅ | ✅ |
| eLearning | ❌ | ✅ | ✅ | ✅ |
| Premier Success | ❌ | ❌ | ✅ | ✅ |

---

## 5️⃣ รายละเอียดฟีเจอร์สำคัญ

### 🗂️ Data Management *(Enterprise ขึ้นไป)*

| ส่วนประกอบ | ทำอะไรได้ |
|---|---|
| **Tableau Catalog** | ค้นหา Data, Lineage และ Impact Analysis, Data Quality Warning, Certified Tables, คำอธิบาย Data |
| **Tableau Prep Conductor** | ตั้งเวลารัน Prep Flow อัตโนมัติ, Monitor และแจ้งเตือนเมื่อ Flow ล้มเหลว |
| **Virtual Connections & Data Policies** | แชร์ Connection กลาง, ทำ **Row-Level Security** ที่จุดเดียว, Preview as User |

### 🔐 Advanced Management *(Enterprise ขึ้นไป)*

| ด้าน | ฟีเจอร์ |
|---|---|
| **Security** | Customer-Managed Encryption Keys (เข้ารหัส Extract ด้วย Key ของเราเอง), Activity Log (Audit การใช้งาน) |
| **Management** | Content Migration Tool (ย้ายงานระหว่าง Project/Site), Admin Insights เก็บข้อมูลย้อนหลัง 365 วัน |
| **Scalability** | เพิ่ม Storage เป็น **5 TB ต่อ Site** (จากปกติ 1 TB) |

> [!NOTE]
> Data Management และ Advanced Management **ไม่ขายแยกเป็น Add-on แล้ว** ต้องได้มากับ Enterprise, Cloud+ หรือ Tableau+ Bundle (ยกเว้นลูกค้าเดิมที่เคยซื้อไว้)

### 🤖 Tableau Agent และ Tableau Knowledge *(Cloud+ ขึ้นไป)*

| ฟีเจอร์ | ทำอะไรได้ |
|---|---|
| **Tableau Agent in Authoring** | พิมพ์ถามเป็นภาษาคน แล้วให้ AI ช่วยสร้าง Viz และ Calculated Field |
| **Tableau Agent in Prep** | ให้ AI ช่วยเขียน Calculation และทำความสะอาดข้อมูลใน Prep |
| **Tableau Agent in Catalog** | ให้ AI ช่วยเขียนคำอธิบาย Data Source และ Field |
| **Tableau Agent in Pulse** | ถามต่อจาก Metric ใน Pulse และได้ Insight เพิ่ม |
| **Tableau Knowledge** | จัด Metadata และความหมายทางธุรกิจเป็น Knowledge Graph ที่ผ่าน Governance ให้ AI Agent ใช้ |

### 🚀 Tableau Next *(Tableau+ Bundle เท่านั้น)*

แพลตฟอร์ม **Agentic Analytics** บน Salesforce มาพร้อม **Data 360** (ชั้นข้อมูล), **Tableau Semantics** (ชั้นความหมายทางธุรกิจ), AI Agent และใช้งานใน **Slack** ได้

---

## 6️⃣ Site Capacity และข้อจำกัด

| รายการ | ค่า |
|---|---|
| 💾 Storage ต่อ Site | **1 TB** (Standard) · **5 TB** (Edition ที่มี Advanced Management) |
| 📦 ขนาดไฟล์ต่อ Workbook / Data Source / Flow | ไม่ควรเกิน **25 GB** |
| 🔄 เวลา Extract Refresh ต่อวัน | **8 ชั่วโมง × จำนวน Creator** (เช่น 10 Creator = 80 ชม./วัน) |
| ⏱️ เวลาสูงสุดต่อ Refresh Job | 2 ชั่วโมง |
| 🔁 Flow Runtime ต่อวัน | 24 ชม. ต่อ Resource Block (ซื้อเพิ่มได้) |
| ⏱️ เวลาสูงสุดต่อ Flow Job | 6 ชั่วโมง |
| 📧 Subscription | สูงสุด 30 นาที/Job, ขนาดอีเมลสูงสุด 2 MB |
| 🖥️ เวลาโหลด Viz สูงสุด | 5 นาที |
| 💤 Idle Timeout | 120 นาที |

> [!TIP]
> Extract ที่ใหญ่เกิน **10 GB** แนะนำให้ใช้ Live Connection, Aggregate ข้อมูล หรือ Incremental Refresh

---

## 7️⃣ รูปแบบการซื้อ License

| | 👤 Role-based (มาตรฐาน) | 📦 Capacity-based |
|---|---|---|
| วิธีคิดราคา | จ่ายตามจำนวน User แต่ละ Role | ซื้อ Creator/Explorer เป็นรายคน + **Viewer แบบเหมาเป็นก้อน (Viewer Blocks)** |
| ใช้ได้กับ | ทุก Edition | Standard, Enterprise, Cloud+ |
| เหมาะกับ | จำนวน User ชัดเจน | มี Viewer จำนวนมากหรือไม่แน่นอน |
| ราคา | ตามตารางด้านบน | ติดต่อ Sales |

> [!CAUTION]
> - **ใช้สองแบบปนกันใน Tenant เดียวกันไม่ได้** (Capacity-based กับ Role-based Viewer)
> - **ผสมหลาย Edition ใน Deployment เดียวกันไม่ได้** ยกเว้น Cloud+ กับ Tableau+ Bundle ที่อยู่ร่วมกันได้

---

## 8️⃣ เลือก Edition ไหนดี

```mermaid
flowchart TD
    Q1{"ต้องการ Row-Level Security กลาง, Data Catalog หรือ Audit Log?"}
    Q1 -- ไม่ --> S["🟢 Standard"]
    Q1 -- ใช่ --> Q2{"ต้องการ AI ช่วยสร้าง Viz และวิเคราะห์ (Tableau Agent)?"}
    Q2 -- ไม่ --> E["🔵 Enterprise"]
    Q2 -- ใช่ --> Q3{"ใช้ Salesforce และต้องการ Tableau Next / Data 360?"}
    Q3 -- ไม่ --> C["🟣 Cloud+"]
    Q3 -- ใช่ --> B["🟠 Tableau+ Bundle"]
```

| ถ้าองค์กร... | แนะนำ |
|---|---|
| เพิ่งเริ่มใช้ BI ไม่กี่ทีม ต้องการ Dashboard พื้นฐาน | 🟢 **Standard** |
| มีหลายแผนก ต้องการคุมสิทธิ์ข้อมูล, RLS, Audit, เข้ารหัสด้วย Key ตัวเอง | 🔵 **Enterprise** |
| อยากให้ User ถามข้อมูลด้วยภาษาคนและใช้ AI ช่วยสร้าง Dashboard | 🟣 **Cloud+** |
| ใช้ Salesforce เป็นแกนหลัก ต้องการ AI Agent ทำงานข้ามระบบและใน Slack | 🟠 **Tableau+ Bundle** |

---

## ❓ คำถามที่พบบ่อย

**Q: ต้องซื้อ Tableau Desktop แยกไหม?**
A: ไม่ต้อง License **Creator** ทุก Edition มี Tableau Desktop และ Prep Builder ให้แล้ว

**Q: Viewer ใช้ Tableau Pulse ได้ไหม?**
A: ได้ Pulse Metrics ใช้ได้ทั้ง Explorer และ Viewer แต่ **Tableau Agent in Pulse** ต้องเป็น Cloud+ ขึ้นไป

**Q: มีค่าใช้จ่ายตามการใช้งาน (Consumption) ไหม?**
A: โดยปกติไม่มี ยกเว้นฟีเจอร์ AI บางตัวที่ใช้ร่วมกับ Data 360 Audit Trail ซึ่งจะใช้ Credits (Tableau+ Bundle มีให้ 250K Credits)

**Q: อัปเกรดจาก Standard เป็น Enterprise ได้ไหม?**
A: ได้ ติดต่อ Account Team หรือ Partner แต่ต้องเปลี่ยนทั้ง Deployment เพราะผสมหลาย Edition ไม่ได้

**Q: มี Free Trial ไหม?**
A: มี Tableau Cloud Trial ให้ทดลองได้จากเว็บไซต์ Tableau

---

## 📚 แหล่งอ้างอิง

| แหล่ง | เนื้อหา |
|---|---|
| [Tableau Cloud Pricing](https://www.tableau.com/pricing/cloud) | ราคา, ตารางฟีเจอร์, FAQ |
| [Tableau Pricing – Teams & Organizations](https://www.tableau.com/pricing/teams-orgs) | ภาพรวมทุก Edition |
| [About Data Management](https://help.tableau.com/current/online/en-us/dm_overview.htm) | รายละเอียด Data Management |
| [About Tableau Advanced Management on Tableau Cloud](https://help.tableau.com/current/online/en-us/itm_intro.htm) | รายละเอียด Advanced Management |
| [Tableau Cloud Site Capacity](https://help.tableau.com/current/online/en-us/cloud_manager_capacity_site.htm) | Storage และข้อจำกัดของ Site |

---

[⬆️ กลับไปด้านบน](#️-เปรียบเทียบ-tableau-cloud-editions)

**Created by The Narit Lab**
