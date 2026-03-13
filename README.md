<div align="center">
  <h1>🧠 Cortex Living</h1>
  <p><b>The brain behind the building. Your business. On autopilot. With receipts.</b></p>
  
  [![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
  [![FastAPI](https://img.shields.io/badge/FastAPI-0.109-009688?style=for-the-badge&logo=fastapi)](https://fastapi.tiangolo.com/)
  [![n8n](https://img.shields.io/badge/n8n-Workflow_Orchestration-FF6C37?style=for-the-badge&logo=n8n)](https://n8n.io/)
  [![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Supabase-4169E1?style=for-the-badge&logo=postgresql)](https://supabase.com/)
  [![AI](https://img.shields.io/badge/AI-GPT_4o__mini_%7C_DistilBERT-purple?style=for-the-badge)](https://openai.com/)
</div>

<br/>

## 📖 The Problem: Invisible Revenue Leaks
In India alone, 50,000+ PGs and hostels manage over 2 million tenants. Yet, the industry runs on manual chaos—endless WhatsApp messages, missed calls during peak seasons, and reactive maintenance. A typical PG misses up to 50 bookings a month and faces a 30% to 40% annual tenant turnover, bleeding an average of **₹15 lakhs a year** in preventable losses.

## 💡 The Solution: Cortex Living
**Cortex Living** is not just property management software; it is a multi-agent AI ecosystem. It acts as the central nervous system for hyperlocal real estate, autonomously handling everything from customer acquisition to conflict resolution and predictive maintenance.

We shift owners from a state of reactive panic to a fully organized, proactive life.

---

## ⚡ Key Features

### 🏢 Core Automation Engine
* **Intelligent Call Handling:** Multilingual AI Voice Agent (Vapi.ai) that negotiates, checks inventory, and closes leads in English, Hindi, and Hinglish.
* **Smart Onboarding Pipeline:** Zero-friction WhatsApp document collection, DigiLocker verification, and instant smart-lock code dispatch.
* **Maintenance Auto-Dispatch:** NLP-based categorization of tenant complaints that autonomously dispatches the right vendor via Google Maps integrations.
* **Rent Collection Automation:** Proactive WhatsApp nudges, AI voice escalations, and 1-click UPI generation.

### 🧠 The "Brain" Upgrades (DeFi & AI)
* **Ghost Manager Mode:** True autonomy. If Sentiment Analysis (DistilBERT) detects a highly frustrated tenant due to an SLA breach (e.g., 3-day Wi-Fi outage), the AI autonomously issues a micro-refund (₹500) to prevent churn.
* **Digital Twin Maintenance:** Uses smartphone LiDAR during onboarding to map rooms. Vendors receive exact 3D models of broken fixtures, eliminating diagnostic visits.
* **Pay-Per-Use Micro-Transactions:** Detects high weekend bandwidth usage and autonomously upsells 4K Netflix upgrades or Tiffin services via a single WhatsApp click.
* **Deadbeat Lockdown:** IoT integration with smart sub-meters. If a tenant is 7+ days late on rent, the system autonomously throttles Wi-Fi bandwidth.
* **Trustless Security Deposit:** Stakes tenant deposits in high-yield liquid funds, building credit for the tenant and generating compounding yield for the operator.

---

## 🛠️ Architecture & Tech Stack

Cortex Living operates on a highly decoupled, multi-agent architecture:

* **Frontend:** Next.js 14 (App Router), shadcn/ui, Tailwind CSS, Zustand, WebSockets.
* **Backend:** FastAPI (Python), n8n (Orchestration Engine), Redis (Caching), Tavily.
* **Database & Vector Storage:** PostgreSQL (Supabase), Qdrant (RAG & Chat Memory), AWS S3.
* **AI / ML Layer:** Vapi.ai (Voice), GPT-4o-mini (Reasoning), DistilBERT (Sentiment), XGBoost (Churn Prediction).
* **Integrations:** Twilio, WhatsApp Business API (WAHA), Razorpay/PhonePe, DigiLocker.

---

## 🚀 Quick Start (Local Development)

### Prerequisites
* Node.js (v18+)
* Python (3.10+)
* Docker & Docker Compose (for n8n, Redis, Qdrant)
* API Keys (OpenAI, Twilio, Supabase, Vapi.ai)

### 1. Clone the repository
```bash
git clone [https://github.com/your-org/cortex-living.git](https://github.com/your-org/cortex-living.git)
cd cortex-living
