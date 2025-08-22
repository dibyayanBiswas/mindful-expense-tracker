# Mindful Expense Tracker

A **SaaS-style personal finance app** that helps users track their expenses and analyze **needs vs. wants vs. impulse spending**.  
The goal is to encourage mindful financial habits with clear insights, visualizations, and gamified streaks.  

---

## 🛠 Tech Stack
- **Frontend:** React + TypeScript + Vite + TailwindCSS + shadcn/ui  
- **Backend:** Node.js + Express + TypeScript + Prisma + PostgreSQL  
- **Database:** Supabase (Postgres managed DB)  
- **Monorepo:** Turborepo (apps & shared packages)  
- **CI/CD:** GitHub Actions (lint + build)  
- **Deployment:** Vercel (frontend), Render/Railway (backend)  
- **Testing:** Jest + React Testing Library (frontend), Supertest (backend)  

---

## Features
- **User Authentication** (signup, login, logout)  
- **Expense Management**: add, update, delete expenses  
- **Categorization**: classify as *Need*, *Want*, or *Impulse*  
- **Dashboard Analytics**: monthly spending trends, pie charts  
- **Insights**: impulse streak tracking, weekly highlights  
- **UI/UX**: modern design system with shadcn/ui, dark mode support  
- **Responsive Design**: works across desktop, tablet, and mobile  

---

## Getting Started

### 1. Clone repository
```bash
git clone https://github.com/dibyayanBiswas/mindful-expense-tracker.git
cd mindful-expense-tracker

### 2. Install dependencies
npm install

### 3. Run frontend (React)
cd apps/frontend
npm run dev

### 4. Run backend (Express API)
cd apps/backend
npm run dev

### 5. Running Tests
cd apps/frontend
npm test

cd apps/backend
npm test


## Roadmap
- Production deployment (Vercel + Railway)  
- Expense export (CSV, PDF reports)  
- Budget goals & progress tracking  
- Gamification: badges for impulse-free streaks  
- AI-driven spending insights (personalized tips)  
- Mobile-first PWA (offline support)  


## Engineering Notes
- Project structured as a **Turborepo monorepo** (apps & shared packages).  
- **Shared TypeScript types** in `packages/types` → ensures backend & frontend stay consistent.  
- **ESLint + Prettier + Husky** enforce code quality before commits.  
- **GitHub Actions CI** runs lint + build checks on every push/PR.  
- Scalable structure → ready for SaaS-style features (multi-tenant, APIs, etc).  


## Badges

![CI](https://github.com/dibyayanBiswas/mindful-expense-tracker/actions/workflows/ci.yml/badge.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)


## License
This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute it with attribution.  

