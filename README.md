<div align="center">

# BossZY27

**Automation Engineer · Bot Developer · System Integration**

พัฒนาระบบที่เชื่อมข้อมูล ลดงานซ้ำ และทำให้ขั้นตอนทำงานตรวจสอบย้อนหลังได้

[Portfolio](https://bosszy-portfolio.vercel.app/) · [Repositories](https://github.com/BossZY27?tab=repositories) · [Classroom Automation](https://github.com/BossZY27/webscraping-classroom-ai) · [Secretary Bot](https://github.com/BossZY27/secretary-bot)

<picture>
  <source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/BossZY27/BossZY27/main/assets/automation-core-static.svg" />
  <img src="https://raw.githubusercontent.com/BossZY27/BossZY27/main/assets/automation-core.svg" alt="ขั้นตอนงานอัตโนมัติจาก Input ไปสู่ Process, Automate และ Deliver" width="100%" />
</picture>

</div>

## เกี่ยวกับฉัน

ผมพัฒนาโปรเจกต์ในโปรไฟล์นี้ด้วยตนเอง โดยเริ่มจากทำความเข้าใจขั้นตอนงาน ออกแบบข้อมูล เชื่อม API หรือบริการภายนอก และทำ workflow ให้มีจุดตรวจสอบก่อนส่งผลลัพธ์ต่อ

กำลังมองหาโอกาสในสาย **Automation Engineer** ที่ได้ทำงานเกี่ยวกับ bot, internal tools, scheduled jobs, data workflow และการเชื่อมระบบ โดยใช้ AI เฉพาะจุดที่เหมาะกับงาน

## ผลงานหลัก

### [Classroom Automation & AI Assistant](https://github.com/BossZY27/webscraping-classroom-ai)

เชื่อม Google Classroom และ Drive เพื่อเลือกติดตามรายวิชา ซิงค์ไฟล์ ตรวจซ้ำด้วย SHA-256 เก็บ metadata ตั้ง scheduled sync และส่งออกไฟล์หรือข้อความสำหรับนำไปใช้งานต่อ

`Python` `FastAPI` `Google APIs` `SQLite` `APScheduler`

**หลักฐาน:** [คู่มือติดตั้ง, workflow และ API](https://github.com/BossZY27/webscraping-classroom-ai#readme)

### [Secretary Bot](https://github.com/BossZY27/secretary-bot)

Telegram bot ที่รับข้อความหรือภาพตาราง ใช้ Gemini ช่วยแปลงเป็นนัดหมาย ขอคำยืนยันก่อนบันทึก ตรวจเวลาว่าง และแจ้งเตือนตามเวลา

`Python` `Telegram Bot` `Gemini Vision` `SQLite`

**หลักฐาน:** [คำสั่ง, workflow และข้อจำกัด](https://github.com/BossZY27/secretary-bot#readme)

### [TikTok Analytics Dashboard](https://github.com/BossZY27/tiktok-analytics)

Dashboard หลายบัญชีที่นำเข้า CSV/XLSX เก็บสถิติรายวันใน PostgreSQL แยกสิทธิ์ผู้ใช้ และมี local Playwright workflow สำหรับดึง export จาก TikTok Studio

`Next.js` `TypeScript` `Prisma` `PostgreSQL` `Playwright`

**หลักฐาน:** [data workflow, environment variables และตัวอย่างข้อมูล](https://github.com/BossZY27/tiktok-analytics#readme)

### [Thai RAG API](https://github.com/BossZY27/thai-rag-api)

FastAPI prototype สำหรับค้นฐานความรู้ภาษาไทยด้วย hybrid ranking บน embeddings จาก Ollama รองรับคำตอบแบบ rule-based หรือ local LLM พร้อม source metadata, logs และ feedback

`Python` `FastAPI` `Ollama` `SQLite` `RAG`

**หลักฐาน:** [สถาปัตยกรรม, API และตัวอย่างแบบสังเคราะห์](https://github.com/BossZY27/thai-rag-api#readme)

### [Loongmordek Auto Sheets](https://github.com/BossZY27/loongmordek-auto-sheets)

Google Apps Script workflow ที่แยกคอนเทนต์หนึ่งชุดเป็นแถวสำหรับ 4 แพลตฟอร์ม พร้อมสถานะตรวจทาน การคำนวณเวลาคิว และ parser test ที่รันแบบ offline ได้

`Google Apps Script` `Google Sheets` `Workflow Automation` `Node.js Test`

**หลักฐาน:** [คู่มือติดตั้ง, รูปแบบข้อมูล และคำสั่งทดสอบ](https://github.com/BossZY27/loongmordek-auto-sheets#readme)

## วิธีที่ผมออกแบบ Automation

```text
Input → Validate → Transform → Store → Review → Deliver → Log
```

- แยก credential และข้อมูลจริงออกจาก source code
- เพิ่ม confirmation หรือ review state ก่อน action ที่มีผลจริง
- ทำให้ workflow ตรวจสอบย้อนหลังได้ด้วย status, log หรือ stored metadata
- แยก static test ออกจาก integration test ที่ต้องใช้บัญชีหรือบริการภายนอก

## เทคโนโลยีที่ใช้ในผลงาน

- **ภาษา:** Python, TypeScript, JavaScript, SQL, Google Apps Script
- **Backend & Data:** FastAPI, Next.js, PostgreSQL, SQLite, Prisma
- **Automation:** REST APIs, scheduled jobs, Google APIs, Playwright, notifications
- **Bot & AI:** Telegram Bot, Gemini, Ollama, RAG, AI Vision

<details>
<summary><b>English summary</b></summary>

I build automation, bots, and internal tools that connect data, reduce repetitive work, and keep workflow states traceable. The projects above are solo builds covering process analysis, API integration, backend development, scheduling, validation, and documentation.

I am looking for an **Automation Engineer** role focused on bots, system integration, data workflows, and practical AI.

</details>

## Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/BossZY27/BossZY27/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/BossZY27/BossZY27/output/github-contribution-grid-snake.svg" />
  <img alt="งูวิ่งตามกราฟ GitHub contribution ของ BossZY27" src="https://raw.githubusercontent.com/BossZY27/BossZY27/output/github-contribution-grid-snake.svg" />
</picture>

<sub>อัปเดตจาก GitHub Actions ทุกวัน</sub>
