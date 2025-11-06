# 📧 Email Summary Assistant (MVP)

> An automated AI SaaS that summarizes your daily client emails and sends a neat digest — no apps, no dashboard, just results in your inbox.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)
[![Made with Node.js](https://img.shields.io/badge/Node.js-18.x-green)](#)
[![Next.js](https://img.shields.io/badge/Next.js-Latest-black)](#)
[![OpenAI API](https://img.shields.io/badge/OpenAI-API-blue)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## ⚙️ Overview

The **Email Summary Assistant** automatically connects to your Gmail or Outlook inbox, summarizes your client and project emails using AI, and delivers a concise daily report.  

It runs quietly in the background — no dashboards, no branding, no social media.

**Key features:**
- 📬 AI-powered email summarization  
- 🧠 Task and deadline extraction  
- 💳 Stripe subscriptions  
- 🔄 Automated daily cron summaries  
- ☁️ Fully serverless (Vercel-ready)

---

## 🧩 Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | Next.js (Vercel) |
| Backend | Node.js + Serverless API Routes |
| Database | Supabase (PostgreSQL) |
| Auth | Gmail/Outlook OAuth2 |
| AI | OpenAI GPT-4o-mini |
| Emails | SendGrid |
| Billing | Stripe Subscriptions |

---

## 🚀 Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/YOUR-USERNAME/email-summary-assistant.git
cd email-summary-assistant

# 2. Install dependencies
npm install

# 3. Set up environment variables
cp .env.local.example .env.local
# Then edit .env.local with your API keys

# 4. Run the dev server
npm run dev
