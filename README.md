# AI Matrimony Platform — Matchmaker Network + AI Biodata Extraction

**Repository:** [mysathihelp/ai-matrimony-platform](https://github.com/mysathihelp/ai-matrimony-platform)

---

## 🌐 Project Overview
यह repository एक advanced AI-driven matrimony platform के लिए है, जो Shaadi.com और BharatMatrimony जैसी साइटों के सर्वोत्तम फीचर्स के साथ-साथ **गाँव-स्तर के matchmaker network** और **multi-tier commission system** को जोड़ता है।

**Core Features:**
- WhatsApp-first onboarding (image/PDF → AI biodata extract → auto profile)
- Matchmaker network with tier-based commission
- Franchise hierarchy (Taluka → District → State)
- AI biodata extraction (OCR + LLM)
- Wallet, payout, audit, and KYC verification
- Admin panel with commission control and dispute handling

---

## 🧩 Project Modules (Folders)

| Module | Description |
|---------|-------------|
| `01_blueprint` | Project architecture, summary, deliverables |
| `02_wp_mvp` | WordPress MVP build — roles, dashboards, and payment integration |
| `03_backend_api` | Laravel/Node backend APIs, commission engine, wallets, payouts |
| `04_ai_extractor` | AI biodata extraction microservice (OCR + GPT-5.1) |
| `05_whatsapp_integration` | WhatsApp BSP integration (Gupshup / Interakt) |
| `06_qa` | QA & UAT test cases |
| `07_deployment` | Hostinger setup, cron jobs, deployment instructions |

---

## 🧠 How to Use This Repository

1. Open any module folder → read the `.md` prompt.
2. Copy that prompt into ChatGPT (GPT-5 recommended) or share with your developer.
3. Generate code or technical output module-by-module.
4. Save each output back into the same folder as `.php`, `.js`, `.py`, etc.
5. Track progress via GitHub commits or Issues.

---

## ⚙️ Technology Stack

| Layer | Tools |
|-------|-------|
| Frontend | WordPress (Custom Plugin + Tailwind) |
| Backend | Laravel / PHP / MySQL |
| AI | Node.js or Python microservice with OpenAI GPT-5.1 |
| Messaging | WhatsApp BSP (Gupshup / Interakt) |
| Hosting | Hostinger (PHP 8.x + SSL + Cron) |

---

## 🚀 Development Flow
1. Define architecture → `01_blueprint`
2. Build MVP in WordPress → `02_wp_mvp`
3. Create backend APIs → `03_backend_api`
4. Add AI extraction → `04_ai_extractor`
5. Integrate WhatsApp flow → `05_whatsapp_integration`
6. Test and validate → `06_qa`
7. Deploy → `07_deployment`

---

## 📌 Ownership
**Project Owner:** [@mysathihelp](https://github.com/mysathihelp)  
**Status:** In Progress (MVP Planning Phase)

---
