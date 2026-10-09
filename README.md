# ☁️ เปรียบเทียบ Tableau Cloud Editions

> สรุป 4 Edition ของ Tableau Cloud ได้แก่ **Standard, Enterprise, Cloud+ และ Tableau+ Bundle** ทั้งราคา ฟีเจอร์ ประเภท License, Site Role และ AI จากข้อมูลทางการของ Tableau และ Salesforce

![Tableau Cloud](https://img.shields.io/badge/Tableau-Cloud-E97627?logo=tableau&logoColor=white)
![Editions](https://img.shields.io/badge/Editions-4-1F77B4)
![Updated](https://img.shields.io/badge/Updated-9%20Oct%202026-2E7D32)
![Source](https://img.shields.io/badge/Source-Tableau%20%7C%20Salesforce-00A1E0?logo=salesforce&logoColor=white)

> [!IMPORTANT]
> **อัปเดตล่าสุด: 9 ตุลาคม 2026** ข้อมูลและตัวเลขทั้งหมดมาจากหน้าเว็บทางการของ **Tableau** และ **Salesforce** โดยมีลิงก์อ้างอิงกำกับไว้ใต้แต่ละหัวข้อ
> ข้อมูลอาจเปลี่ยนแปลงได้ ควรตรวจสอบกับแหล่งอ้างอิงล่าสุดก่อนใช้งาน

> [!NOTE]
> **⚖️ ข้อจำกัดความรับผิดชอบ (Disclaimer)**
>
> เอกสารนี้จัดทำขึ้นจากการรวบรวมข้อมูลโดยส่วนตัวของผู้เขียน เพื่อวัตถุประสงค์ในการแบ่งปันความรู้เท่านั้น มิใช่เอกสารทางการของเจ้าของผลิตภัณฑ์ และไม่สามารถใช้เป็นเอกสารอ้างอิงทางการค้าได้ หากต้องการนำข้อมูลไปใช้อ้างอิง กรุณาตรวจสอบข้อมูลล่าสุดจากเว็บไซต์ทางการของเจ้าของผลิตภัณฑ์อีกครั้ง
>
> *This document is a personal compilation intended for knowledge-sharing purposes only. It is not official documentation from the product owner and shall not be used as a commercial reference. Please verify all information against the product owner's official website before use.*

---

## 🧭 สารบัญ

| | หัวข้อ |
|:---:|---|
| 1️⃣ | [ภาพรวม 4 Edition](#1️⃣-ภาพรวม-4-edition) |
| 2️⃣ | [ราคาต่อ User](#2️⃣-ราคาต่อ-user) |
| 3️⃣ | [ประเภท License และ Site Role](#3️⃣-ประเภท-license-และ-site-role) |
| 4️⃣ | [ตารางเปรียบเทียบฟีเจอร์](#4️⃣-ตารางเปรียบเทียบฟีเจอร์) |
| 5️⃣ | [รายละเอียดฟีเจอร์สำคัญ](#5️⃣-รายละเอียดฟีเจอร์สำคัญ) |
| 6️⃣ | [AI ใน Tableau (Tableau Agent)](#6️⃣-ai-ใน-tableau-tableau-agent) |
| 7️⃣ | [Site Capacity และข้อจำกัด](#7️⃣-site-capacity-และข้อจำกัด) |
| 8️⃣ | [รูปแบบ License](#8️⃣-รูปแบบ-license) |
| 9️⃣ | [Support / Success Plans](#9️⃣-support--success-plans) |
| 🔟 | [Tableau Cloud vs Tableau Server vs Tableau Next](#-tableau-cloud-vs-tableau-server-vs-tableau-next) |
| ❓ | [คำถามที่พบบ่อย](#-คำถามที่พบบ่อย) |
| 📚 | [แหล่งอ้างอิง](#-แหล่งอ้างอิง) |

---

## 1️⃣ ภาพรวม 4 Edition

แต่ละ Edition **ได้ทุกอย่างของ Edition ก่อนหน้า** แล้วเพิ่มความสามารถขึ้นไปทีละขั้น

```mermaid
flowchart LR
    A["🟢 Standard"] --> B["🔵 Enterprise"]
    B --> C["🟣 Cloud+"]
    C --> D["🟠 Tableau+ Bundle"]
```

| Edition | ได้อะไร |
|---|---|
| 🟢 **Standard** | Web Authoring, Tableau Desktop, Tableau Prep Builder, Tableau Pulse |
| 🔵 **Enterprise** | ทุกอย่างใน Standard + Advanced Management, Data Management, eLearning |
| 🟣 **Cloud+** | ทุกอย่างใน Enterprise + Tableau Knowledge, Tableau Agent, Premier Success, Release Preview |
| 🟠 **Tableau+ Bundle** | ทุกอย่างใน Cloud+ + Tableau Next |

> [!NOTE]
> ไม่มี Edition ชื่อ "Cloud Enterprise Plus" ตัวที่สูงที่สุดคือ **Tableau+ Bundle** (= Cloud+ + Tableau Next)

📎 อ้างอิง: [Tableau Pricing – Teams & Organizations](https://www.tableau.com/pricing/teams-orgs) · [Tableau Cloud Pricing](https://www.tableau.com/pricing/cloud)

---

## 2️⃣ ราคาต่อ User

ราคาต่อ User ต่อเดือน (USD) จ่ายรายปี ตามที่ประกาศบนเว็บไซต์ Tableau

| License | 🟢 Standard | 🔵 Enterprise | 🟣 Cloud+ | 🟠 Tableau+ Bundle |
|---|:---:|:---:|:---:|:---:|
| ✏️ **Creator** | $75 | $115 | Contact Sales | Contact Sales |
| 🔍 **Explorer** | $42 | $70 | Contact Sales | Contact Sales |
| 👁️ **Viewer** | $15 | $35 | Contact Sales | Contact Sales |

> [!WARNING]
> - ทุก Edition ต้องทำสัญญา **รายปี** (ไม่มีแพ็กเกจรายเดือน)
> - ทุก Deployment ต้องมี **Creator อย่างน้อย 1 License**
> - ราคา "เริ่มต้น" **$15 / $35** ที่แสดงบนหน้าแรกของ Tableau และ Salesforce คือราคา **Viewer**

📎 อ้างอิง: [Tableau Cloud Pricing](https://www.tableau.com/pricing/cloud) · [Tableau Pricing](https://www.tableau.com/pricing) · [Salesforce Analytics Pricing](https://www.salesforce.com/analytics/pricing/)

---

## 3️⃣ ประเภท License และ Site Role

### 🎫 License ทำอะไรได้บ้าง

| ความสามารถ | ✏️ Creator | 🔍 Explorer | 👁️ Viewer |
|---|:---:|:---:|:---:|
| ดู Dashboard และ Interact | ✅ | ✅ | ✅ |
| ดู Tableau Pulse Metrics | ✅ | ✅ | ✅ |
| Subscribe รับรายงาน | ✅ | ✅ | ✅ |
| ดาวน์โหลดรูป / Summary Data | ✅ | ✅ | ✅ |
| สร้าง Data-driven Alert เอง | ✅ | ✅ | ❌ |
| แก้ไข / สร้าง Workbook บนเว็บจาก Published Data Source | ✅ | ✅ *(Explorer (can publish) ขึ้นไป)* | ❌ |
| เป็น Site Admin จัดการ User | ✅ | ✅ | ❌ |
| เชื่อมต่อ Data Source ใหม่ / ภายนอก | ✅ | ❌ | ❌ |
| ใช้ Tableau Desktop และ Tableau Prep Builder | ✅ | ❌ | ❌ |
| สร้าง / Publish Prep Flow และ Data Source | ✅ | ❌ | ❌ |

### 👥 Site Role แต่ละแบบ

| Site Role | ใช้ License | ทำอะไรได้ |
|---|---|---|
| **Site Administrator Creator** | Creator | สิทธิ์สูงสุดใน Site: สร้าง/Publish ได้ทุกอย่าง + จัดการ User และ Site Role |
| **Creator** | Creator | เชื่อมต่อ Data, สร้างและ Publish Workbook, Data Source, Flow |
| **Site Administrator Explorer** | Explorer | จัดการ User/Site ได้ แต่เชื่อมต่อ Data ภายนอกไม่ได้ |
| **Explorer (can publish)** | Explorer | สร้าง/แก้ Workbook บนเว็บจาก Published Data Source แล้ว Save/Publish ได้ |
| **Explorer** | Explorer | Explore บนเว็บได้แต่ Save/Publish ไม่ได้, Subscribe และสร้าง Data-driven Alert ได้ |
| **Viewer** | Viewer | ดูและ Interact, Subscribe, ดาวน์โหลดรูป/Summary Data |
| **Unlicensed** | – | Sign in ไม่ได้ |

📎 อ้างอิง: [Set Users' Site Roles](https://help.tableau.com/current/online/en-us/users_site_roles.htm) · [Tableau Cloud Pricing – FAQ](https://www.tableau.com/pricing/cloud)

---

## 4️⃣ ตารางเปรียบเทียบฟีเจอร์

| ฟีเจอร์ | 🟢 Standard | 🔵 Enterprise | 🟣 Cloud+ | 🟠 Bundle |
|---|:---:|:---:|:---:|:---:|
| **📊 Core Analytics** | | | | |
| Tableau Cloud (Web Authoring) | ✅ | ✅ | ✅ | ✅ |
| Tableau Desktop | ✅ | ✅ | ✅ | ✅ |
| Tableau Prep Builder | ✅ | ✅ | ✅ | ✅ |
| Tableau Pulse | ✅ | ✅ | ✅ | ✅ |
| Tableau MCP | ✅ | ✅ | ✅ | ✅ |
| จำนวน Site (Tableau Cloud Manager) | สูงสุด 3 | สูงสุด 10 | สูงสุด 50 | สูงสุด 50 |
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
| Credits | ❌ | ❌ | ❌ | 250K |
| **🎓 Support & Learning** | | | | |
| Standard Success | ✅ | ✅ | ✅ | ✅ |
| eLearning | ❌ | ✅ | ✅ | ✅ |
| Premier Success | ❌ | ❌ | ✅ | ✅ |

📎 อ้างอิง: [Tableau Cloud Pricing – Compare Editions](https://www.tableau.com/pricing/cloud)

---

## 5️⃣ รายละเอียดฟีเจอร์สำคัญ

### 🗂️ Data Management *(Enterprise ขึ้นไป)*

| ส่วนประกอบ | ทำอะไรได้ |
|---|---|
| **Tableau Catalog** | ค้นหา Data, Lineage และ Impact Analysis, Data Quality Warning, Certified Database/Table, คำอธิบาย Data |
| **Tableau Prep Conductor** | ตั้งเวลารัน Prep Flow, Monitor และแจ้งเตือนเมื่อ Flow ล้มเหลว |
| **Virtual Connections & Data Policies** | แชร์ Connection กลาง, Row-Level Security Policy, Preview as User |

📎 อ้างอิง: [About Data Management](https://help.tableau.com/current/online/en-us/dm_overview.htm)

### 🔐 Advanced Management *(Enterprise ขึ้นไป)*

| ด้าน | ฟีเจอร์ |
|---|---|
| **Security** | Customer-Managed Encryption Keys, Activity Log |
| **Management** | Content Migration Tool, Admin Insights เก็บข้อมูลย้อนหลัง 365 วัน |
| **Scalability** | Storage **5 TB ต่อ Site** |

📎 อ้างอิง: [About Tableau Advanced Management on Tableau Cloud](https://help.tableau.com/current/online/en-us/itm_intro.htm)

> [!NOTE]
> Data Management และ Advanced Management **ไม่จำหน่ายแยกเป็น Add-on แล้ว** ได้มากับ Enterprise, Cloud+ หรือ Tableau+ Bundle (ยกเว้นลูกค้าที่เคยซื้อไว้ก่อน)

### 🧠 Tableau Knowledge *(Cloud+ ขึ้นไป)*

จัด Metadata และ Semantics เป็น **Knowledge Graph ที่ผ่าน Governance** สำหรับให้ AI Agent ใช้งาน

📎 อ้างอิง: [Tableau Cloud Pricing – FAQ](https://www.tableau.com/pricing/cloud)

### 🚀 Tableau Next *(Tableau+ Bundle หรือซื้อแยก)*

ประกอบด้วย Tableau Agent, Tableau Semantics และ Native Slack Integration

📎 อ้างอิง: [Tableau Pricing](https://www.tableau.com/pricing) · [Salesforce Analytics Pricing](https://www.salesforce.com/analytics/pricing/)

---

## 6️⃣ AI ใน Tableau (Tableau Agent)

| หัวข้อ | รายละเอียด |
|---|---|
| 🎫 **Edition ที่ใช้ได้** | Tableau Cloud ต้องเป็น **Cloud+ หรือ Tableau+** และเปิด **AI in Tableau** |
| 👤 **ใครใช้ได้** | Creator และ Explorer (ใน Web Authoring) · Viewer ใช้ **Tableau Agent in Dashboards** ได้ตั้งแต่เวอร์ชัน **2026.2.4** เมื่อมีสิทธิ์ AI Access และ Full Data Query |
| 🖥️ **Tableau Desktop** | ใช้ได้เมื่อ Sign in เข้า Site Tableau Cloud ที่เป็น Cloud+ / Tableau+ |
| 🔒 **ความปลอดภัยข้อมูล** | Zero Data Retention กับผู้ให้บริการ LLM, เคารพ Permissions เดิม, Mask ข้อมูล PII ได้ |
| 🌐 **ภาษา** | English และภาษาอื่นบางส่วน (ภาษาที่ไม่รองรับจะตอบเป็นภาษาอังกฤษ) |
| 🧪 **ทดลองใช้** | ใช้ได้กับ Tableau Cloud Trial (เฉพาะ Site ใหม่) อาจจำกัดจำนวน Request ต่อชั่วโมง |

📎 อ้างอิง: [Tableau Agent FAQ](https://help.tableau.com/current/online/en-us/web_author_einstein_faq.htm)

---

## 7️⃣ Site Capacity และข้อจำกัด

| รายการ | ค่า |
|---|---|
| 💾 Storage ต่อ Site | **1 TB** · **5 TB** สำหรับ Enterprise, Tableau+ หรือ Site ที่มี Advanced Management |
| 📦 ขนาดต่อ Workbook / Data Source / Flow | ไม่ควรเกิน **25 GB** |
| 🔄 เวลา Extract Refresh ต่อวัน | **8 ชั่วโมง ต่อ Creator License** (รีเซ็ต 24:00 UTC) |
| ⏱️ เวลาสูงสุดต่อ Refresh Job | 2 ชั่วโมง |
| 🔁 Flow Runtime ต่อวัน | 24 ชั่วโมง ต่อ Resource Block |
| ⏱️ เวลาสูงสุดต่อ Flow Job | 6 ชั่วโมง |
| 📧 Subscription | สูงสุด 30 นาที/Job, ขนาดอีเมลสูงสุด 2 MB |
| 🖥️ เวลาโหลด Viz สูงสุด | 5 นาที |
| 💤 Idle Timeout | 120 นาที |

> [!TIP]
> Extract ที่ใหญ่เกิน **10 GB** Tableau แนะนำให้ใช้ Live Connection, Aggregate ข้อมูล หรือ Incremental Extract

📎 อ้างอิง: [Tableau Cloud Site Capacity](https://help.tableau.com/current/online/en-us/cloud_manager_capacity_site.htm)

---

## 8️⃣ รูปแบบ License

| | 👤 Role-based | 📦 Capacity-based |
|---|---|---|
| วิธีคิด | ตามจำนวน User แต่ละ Role | Creator / Explorer รายคน + **Viewer Blocks** |
| ใช้ได้กับ | ทุก Edition | Standard, Enterprise, Cloud+ |
| Overage Charge | – | ไม่มี |
| การจัดสรร | ผูกกับ User | Admin กระจาย Capacity ข้าม Site ได้ |

> [!CAUTION]
> - ใช้ Capacity-based กับ Role-based Viewer **ปนกันใน Tenant เดียวกันไม่ได้**
> - **ผสมหลาย Edition ใน Deployment เดียวกันไม่ได้** ยกเว้น Cloud+ กับ Tableau+ Bundle

📎 อ้างอิง: [Tableau Cloud Pricing – FAQ](https://www.tableau.com/pricing/cloud) · [Tableau Pricing](https://www.tableau.com/pricing)

---

## 9️⃣ Support / Success Plans

| Plan | ได้มากับ |
|---|---|
| **Standard Success** | ทุก License |
| **eLearning** | Enterprise ขึ้นไป |
| **Premier Success** | Cloud+ และ Tableau+ Bundle · Edition อื่นซื้อเพิ่มได้ (30% ของ Net License Fees) |
| **Signature Success** | ติดต่อ Account Executive |

📎 อ้างอิง: [Tableau Cloud Pricing – FAQ](https://www.tableau.com/pricing/cloud) · [Salesforce Analytics Pricing – Success Plans](https://www.salesforce.com/analytics/pricing/)

---

## 🔟 Tableau Cloud vs Tableau Server vs Tableau Next

| | ☁️ Tableau Cloud | 🖥️ Tableau Server | 🚀 Tableau Next |
|---|---|---|---|
| **การติดตั้ง** | Fully hosted (SaaS) | ติดตั้งเอง: On-premises, Private / Public Cloud | บน Salesforce Platform |
| **Edition** | Standard · Enterprise · Cloud+ · Tableau+ Bundle | Tableau · Enterprise · Server+ | Tableau Next · Tableau+ Bundle |
| **ราคาเริ่มต้น** | $15/user/เดือน | $15/user/เดือน | $40/user/เดือน |
| **License** | Creator / Explorer / Viewer | Creator / Explorer / Viewer | Creator / Consumer |
| **ทางเลือกอื่น** | Capacity-based (Viewer Blocks) | Compute-based (หน่วยละ 8 Core) | – |
| **Tableau Agent** | Cloud+ ขึ้นไป | Authoring และ Prep ตั้งแต่ Edition เริ่มต้น (เวอร์ชัน 2025.3+, เชื่อม LLM ของตัวเอง) | ✅ |

> [!NOTE]
> - Tableau Next รวมอยู่ใน Edition Core, Advanced และ Max ของ Sales, Service และ Industry Clouds ด้วย
> - Tableau Agent บน Tableau Server **ไม่ผ่าน Einstein Trust Layer** ความปลอดภัยขึ้นกับผู้ให้บริการ LLM ที่เชื่อมต่อ

📎 อ้างอิง: [Tableau Pricing](https://www.tableau.com/pricing) · [Salesforce Analytics Pricing](https://www.salesforce.com/analytics/pricing/) · [Tableau Agent FAQ](https://help.tableau.com/current/online/en-us/web_author_einstein_faq.htm)

---

## ❓ คำถามที่พบบ่อย

**Q: ต้องซื้อ Tableau Desktop แยกไหม?**
A: ไม่ต้อง Tableau Desktop และ Prep Builder รวมอยู่ใน License Creator ทุก Edition

**Q: ยังไม่มี License อยากลองใช้ Tableau Desktop ได้ไหม?**
A: ได้ ใช้ **Tableau Desktop Free Edition** ทำงานกับ Excel, CSV และ Database ที่เก็บในเครื่องได้ แต่เชื่อมต่อ Published Data Source บน Cloud/Server, Publish ออนไลน์ และแชร์ Packaged Workbook ไม่ได้

**Q: Viewer ใช้ Tableau Pulse ได้ไหม?**
A: ได้ Pulse Metrics ใช้ได้ทั้ง Explorer และ Viewer ส่วน Tableau Agent in Pulse ต้องเป็น Cloud+ ขึ้นไป

**Q: Viewer ตั้ง Alert เองได้ไหม?**
A: ไม่ได้ Viewer Subscribe รับรายงานได้ แต่สร้าง Data-driven Alert เองต้องเป็น Explorer ขึ้นไป

**Q: มีค่าใช้จ่ายตามการใช้งาน (Consumption) ไหม?**
A: ไม่มี ยกเว้นฟีเจอร์ AI บางตัวที่ใช้ร่วมกับ Data 360 Audit Trail ซึ่งใช้ Credits (Tableau+ Bundle มี 250K Credits)

📎 อ้างอิง: [Tableau Pricing](https://www.tableau.com/pricing) · [Tableau Cloud Pricing – FAQ](https://www.tableau.com/pricing/cloud) · [Set Users' Site Roles](https://help.tableau.com/current/online/en-us/users_site_roles.htm)

---

## 📚 แหล่งอ้างอิง

ตรวจสอบเมื่อ **9 ตุลาคม 2026**

| แหล่ง | เนื้อหา |
|---|---|
| [Tableau Pricing](https://www.tableau.com/pricing) | ภาพรวมราคา Cloud / Server / Next / Free Edition |
| [Tableau Cloud Pricing](https://www.tableau.com/pricing/cloud) | ราคาต่อ License, ตารางฟีเจอร์, FAQ |
| [Tableau Pricing – Teams & Organizations](https://www.tableau.com/pricing/teams-orgs) | ภาพรวมทุก Edition |
| [Salesforce Analytics Pricing](https://www.salesforce.com/analytics/pricing/) | ราคา Tableau Cloud / Tableau Next และ Success Plans |
| [Set Users' Site Roles](https://help.tableau.com/current/online/en-us/users_site_roles.htm) | Site Role และสิทธิ์ของแต่ละ License |
| [Tableau Agent FAQ](https://help.tableau.com/current/online/en-us/web_author_einstein_faq.htm) | เงื่อนไขการใช้ Tableau Agent, ความปลอดภัยข้อมูล |
| [About Data Management](https://help.tableau.com/current/online/en-us/dm_overview.htm) | รายละเอียด Data Management |
| [About Tableau Advanced Management on Tableau Cloud](https://help.tableau.com/current/online/en-us/itm_intro.htm) | รายละเอียด Advanced Management |
| [Tableau Cloud Site Capacity](https://help.tableau.com/current/online/en-us/cloud_manager_capacity_site.htm) | Storage และข้อจำกัดของ Site |

---

[⬆️ กลับไปด้านบน](#️-เปรียบเทียบ-tableau-cloud-editions)

> [!NOTE]
> **⚖️ ข้อจำกัดความรับผิดชอบ (Disclaimer)**
>
> เอกสารนี้จัดทำขึ้นจากการรวบรวมข้อมูลโดยส่วนตัวของผู้เขียน เพื่อวัตถุประสงค์ในการแบ่งปันความรู้เท่านั้น มิใช่เอกสารทางการของเจ้าของผลิตภัณฑ์ และไม่สามารถใช้เป็นเอกสารอ้างอิงทางการค้าได้ หากต้องการนำข้อมูลไปใช้อ้างอิง กรุณาตรวจสอบข้อมูลล่าสุดจากเว็บไซต์ทางการของเจ้าของผลิตภัณฑ์อีกครั้ง
>
> *This document is a personal compilation intended for knowledge-sharing purposes only. It is not official documentation from the product owner and shall not be used as a commercial reference. Please verify all information against the product owner's official website before use.*

**Created by The Narit Lab**
