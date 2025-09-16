# 🚀 Learning Journey Tracker

Ứng dụng web full-stack (TypeScript) giúp **theo dõi tiến độ học tập**, **làm quiz kiểm tra kiến thức**, và **xem dashboard trực quan**.  
Dự án được xây dựng để showcase kỹ năng hiện đại: **SolidStart, Fastify, Prisma, Docker, CI/CD, Deploy**.

---

## ✨ Tính năng nổi bật
- 🔑 **Đăng ký / Đăng nhập** bằng email + mật khẩu (JWT auth).  
- 📊 **Dashboard** trực quan – biểu đồ tiến độ học theo thời gian & chủ đề.  
- 📝 **Quiz** – làm quiz nhanh, chấm điểm tự động, lưu kết quả.  
- 📚 **Resource Manager** *(tùy chọn)* – thêm tài nguyên học tập cá nhân.  
- 🐳 **Dockerized** – dễ dàng chạy trên mọi môi trường.  
- ⚡ **CI/CD** – GitHub Actions: test → build → deploy tự động.  

---

## 🛠️ Tech Stack

- **Frontend:** [SolidStart](https://start.solidjs.com/) + TypeScript + Vite  
- **Backend:** Node.js + Fastify + TypeScript  
- **Database:** PostgreSQL + Prisma ORM  
- **Testing:** Vitest + Playwright  
- **DevOps:** Docker + GitHub Actions  
- **Deploy:** Vercel (frontend) + Render/Railway (backend + DB)  

---

## 🏗️ Kiến trúc hệ thống

```mermaid
flowchart LR
  A[Frontend: SolidStart] -->|API calls| B[Backend: Fastify]
  B --> C[(PostgreSQL DB)]
  A <-->|Auth, Quiz, Progress| B
```

---

## 🚀 Cài đặt & Chạy Local

### 1. Clone repo
```bash
git clone https://github.com/your-username/learning-journey-tracker.git
cd learning-journey-tracker
```

### 2. Cấu hình môi trường
Tạo file `.env` trong thư mục `backend/` dựa trên `.env.example`:
```env
DATABASE_URL=postgresql://user:password@localhost:5432/mydb
JWT_SECRET=your_secret_key
```

### 3. Cài dependencies
```bash
cd backend && npm install
cd ../frontend && npm install
```

### 4. Khởi chạy bằng Docker
```bash
docker-compose up --build
```
👉 Ứng dụng chạy tại:  
- Frontend: http://localhost:3000  
- Backend API: http://localhost:4000  

---

## ⚡ CI/CD

- **GitHub Actions** (workflow trong `.github/workflows/ci-cd.yml`):  
  - ✅ Chạy lint + test  
  - 📦 Build Docker images  
  - 🚀 Deploy tự động (Vercel + Render/Railway)  

---

## 📌 Roadmap

- [ ] Thêm đăng nhập bằng Google/GitHub OAuth2  
- [ ] Chế độ multiplayer quiz  
- [ ] Dark mode UI  
- [ ] Xuất báo cáo tiến độ học ra PDF  

---

## 🤝 Đóng góp

1. Fork repo  
2. Tạo branch mới: `git checkout -b feature/my-feature`  
3. Commit thay đổi: `git commit -m 'Add my feature'`  
4. Push branch: `git push origin feature/my-feature`  
5. Mở Pull Request 🎉  

---

## 📄 License
MIT License © 2025 – Learning Journey Tracker
