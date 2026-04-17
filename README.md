# Hi, I'm Samuel Nikolas 👋

**Backend Developer | Evolving Full Stack | Java • Python • TypeScript**

Passionate about APIs, Clean Architecture, and Engineering Best Practices

---

## 📚 Education & Focus

🎓 **Systems Analysis and Development** – UNIFOR (2024 – 2026)
💻 **Backend:** Java (Spring Boot) and Python (FastAPI)
🎨 **Frontend:** React with TypeScript
📱 **Mobile:** React Native with Expo (iOS & Android)
🏗️ **Specialty:** Layered Architecture, REST APIs, and Secure Authentication
📜 **Current focus:** DevOps, Docker, IaC (Terraform + Ansible), Microservices Architecture

---

## 🔗 Links

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samuel-nikolas)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:samucanikolas3@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/samuca2k18)

---

## 🛠️ Tech Stack

### Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Backend & APIs
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=socket.io&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### Mobile
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)

### Databases & DevOps
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🚀 Featured Projects

### 🛡️ Albion Market API

**Professional REST API for real-time Albion Online market price monitoring**

![Python](https://img.shields.io/badge/Python-3.12+-blue?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-0.121-green?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Supabase-blue?style=flat-square)

**Highlights:**
- 🔐 JWT authentication with PBKDF2-SHA256 hashing + mandatory email verification (Resend API, 24h token TTL)
- 🔔 Intelligent price alerts: manual target price or AI-based expected price (median/mean over configurable history window)
- 🌍 Multi-region support (Europe / America / Asia); TTL cache (5 min prices, 10 min history)
- 🔍 Local item index (~100k items) in PT-BR & EN-US with exact + fuzzy search
- 🏗️ Layered architecture (Router → Service → Repository) following SOLID; Alembic versioned migrations
- ⚙️ GitHub Actions CI/CD; Swagger/OpenAPI auto-docs; deployed on Vercel via Render

[→ Repository](https://github.com/samuca2k18/Market_Albion_Online) | [🌐 Live API](https://market-albion-online.vercel.app)

---

### 🟦 Market Albion — Intelligent Price Dashboard

**Full-stack web platform for Albion Online market analysis**

![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript)
![Tailwind](https://img.shields.io/badge/Tailwind-CSS-06B6D4?style=flat-square)

**Highlights:**
- 📊 Profit-opportunity dashboard with interactive price history charts (Recharts)
- 🔍 Advanced filters by quality, enchantment, and city
- 🌍 Full internationalization (PT-BR / EN-US) with i18next
- ⚡ Optimized data fetching with TanStack Query

[→ Repository](https://github.com/samuca2k18/Front_Market_Albion) | [🌐 Live Demo](https://front-market-albion.vercel.app)

---

### 🌊 Soul Surf — Social Network for Surfers (Full Stack)

**Complete social platform with real-time features and full Infrastructure as Code**

![Java](https://img.shields.io/badge/Java-Spring_Boot-6DB33F?style=flat-square)
![WebSocket](https://img.shields.io/badge/WebSocket-STOMP-010101?style=flat-square)
![React](https://img.shields.io/badge/React-TypeScript-61DAFB?style=flat-square)
![Terraform](https://img.shields.io/badge/IaC-Terraform+Ansible-844FBA?style=flat-square)

**Highlights:**
- 📰 Social feed (public/private posts with photo upload), nested comments, @mention system with smart autocomplete
- 💬 Real-time direct messaging via WebSocket/STOMP; real-time notifications for mentions and comments
- 🏖️ Beach catalog with location-based posts and community wall (mural)
- ☀️ OpenWeather API integration for live surf conditions per beach
- 👮 Admin panel: platform metrics, audit logs, content moderation (ban/unban), role management
- 🚀 Full IaC: Terraform (cloud provisioning) + Ansible (deploy automation) + Docker Compose; GitHub Actions CI/CD; deployed on Oracle Cloud

[→ Repository](https://github.com/valentimdev/Soul_Surf_PA2) | [🌐 Live Demo](https://soul-surf-pa-2.vercel.app)

---

### 🎹 IAssis Pianos — CRM & WhatsApp Bot

**Commercial CRM, digital secretary, and WhatsApp chatbot for a real piano business client**

![Python](https://img.shields.io/badge/Python-3.12+-blue?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-latest-green?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-Oracle_Cloud-2496ED?style=flat-square)

**Highlights:**
- 📋 Full sales pipeline: lead management with temperature scoring, deal tracking (quote → negotiation → closed/lost)
- 📄 Automated PDF generation (ReportLab): quotes, receipts, and rental contracts with company branding
- 🤖 Interactive WhatsApp bot via Evolution API v2: state-machine menu, collects customer data, generates & sends PDFs in-chat
- 📅 Appointment scheduling module; KPI dashboard endpoint; daily summary scheduler
- 🔒 Deployed on Oracle Cloud VM with Docker Compose; Alembic migrations; API key & webhook token security hardening

[→ Repository](https://github.com/samuca2k18/Aissis_back)

---

### 🏄 Soul Surf Mobile

**Cross-platform mobile app (iOS/Android) for the Soul Surf social platform**

![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo)

**Highlights:**
- 📱 Complete mobile experience: feed, posts, comments, real-time DM chat, JWT auth
- 🗺️ File-based navigation with Expo Router; EAS Build configuration
- ✅ Jest unit tests; TypeScript strict mode; Oracle Cloud backend

[→ Repository](https://github.com/valentimdev/Soul-Surf-Mobile)

---

### 📊 ETL Project

**Python ETL pipeline for Data Engineering**

![Python](https://img.shields.io/badge/Python-Data_Engineering-3776AB?style=flat-square)

**Highlights:**
- 🔄 Automated extraction, transformation, and loading of structured data
- 📁 Modular pipeline architecture — scalable and easy to extend

[→ Repository](https://github.com/samuca2k18/ETL_project)

---

## 📊 GitHub Stats

<div align="center">

[![Samuel Nikolas GitHub Stats](https://github-readme-stats.vercel.app/api?username=samuca2k18&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true)](https://github.com/samuca2k18)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=samuca2k18&layout=compact&langs_count=8&theme=tokyonight)](https://github.com/samuca2k18)

</div>

---

## 🎯 What I'm Working On

- 🔭 Expanding the **Albion Market** ecosystem (API + Frontend)
- 🎹 Maintaining and evolving **IAssis Pianos** CRM for production use
- 🌱 Deepening knowledge in **Software Architecture** and **Design Patterns**
- 📚 Studying **DevOps**, **Kubernetes**, and **Microservices**
- 💡 Applying clean code and best practices across all projects
- 🚀 Exploring **Event-Driven Architecture**

---

## 💡 Mindset

I believe good code is code that solves real problems, is easy to understand, and easy to maintain. I always strive for:

✅ Clean and scalable architecture
✅ Quality tests and documentation
✅ Security from day one
✅ Optimized performance
✅ Collaboration and knowledge sharing

---

## 💬 Let's Connect!

I'm always open to new opportunities, challenges, and collaborations.

- 📧 **Email:** samucanikolas3@gmail.com
- 🔗 **LinkedIn:** [samuel-nikolas](https://www.linkedin.com/in/samuel-nikolas)
- 💻 **GitHub:** [@samuca2k18](https://github.com/samuca2k18)

⭐ **If you found my projects interesting, consider leaving a star!**

---

<div align="center">

![Visitors](https://komarev.com/ghpvc/?username=samuca2k18&color=1A56DB&style=flat-square&label=Visitors)

</div>
