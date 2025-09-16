# 🚀 Learning Journey Tracker

[![CI/CD](https://github.com/longduong0910/learning-journey-tracker/actions/workflows/ci-cd.yml/badge.svg)](https://github.com/your-username/learning-journey-tracker/actions) 
[![Deploy Frontend](https://img.shields.io/badge/Vercel-Deployed-black?logo=vercel)](https://vercel.com) 
[![Deploy Backend](https://img.shields.io/badge/Render/Railway-Deployed-blue?logo=render)](https://render.com) 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Ứng dụng web full-stack (TypeScript) giúp **theo dõi tiến độ học tập**, **làm quiz kiểm tra kiến thức** và **xem dashboard trực quan**.  
Dự án showcase kỹ năng hiện đại: **SolidStart, Fastify, Prisma, Docker, CI/CD, Deploy**.

---

## ✨ Tính năng
- 🔑 Đăng ký / Đăng nhập (JWT auth)  
- 📊 Dashboard trực quan theo tiến độ học  
- 📝 Quiz chấm điểm tự động, lưu kết quả  
- 📚 Quản lý tài nguyên học tập (tùy chọn)  
- 🐳 Dockerized + ⚡ CI/CD với GitHub Actions  

---

## 🛠️ Tech Stack
- **Frontend:** SolidStart (TypeScript + Vite)  
- **Backend:** Node.js + Fastify  
- **Database:** PostgreSQL + Prisma  
- **Testing:** Vitest + Playwright  
- **Deploy:** Vercel (frontend), Render/Railway (backend + DB)  

---

## 🚀 Cài đặt & Chạy Local
```bash
# Clone repo
git clone https://github.com/your-username/learning-journey-tracker.git
cd learning-journey-tracker

# Cài dependencies
cd backend && npm install
cd ../frontend && npm install

# Chạy bằng Docker
docker-compose up --build
```
👉 App chạy tại: Frontend `http://localhost:3000`, Backend `http://localhost:4000`

---

## ⚡ CI/CD & Deploy
- **CI/CD:** GitHub Actions (lint → test → build → deploy)  
- **Deploy:** Vercel (frontend) + Render/Railway (backend & DB)  

---

## 📄 License
MIT License © 2025 – Learning Journey Tracker
