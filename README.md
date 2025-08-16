<h1 align="center">🚚 LogisticsApp</h1>
<p align="center">
  <b>A modern full-stack logistics platform built with TypeScript, Vite, TailwindCSS, and Drizzle ORM.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/hemavardhan252004-krishnapatnam/logisticsApp?style=for-the-badge" />
  <img src="https://img.shields.io/github/issues/hemavardhan252004-krishnapatnam/logisticsApp?style=for-the-badge&color=blue" />
  <img src="https://img.shields.io/github/stars/hemavardhan252004-krishnapatnam/logisticsApp?style=for-the-badge&color=yellow" />
  <img src="https://img.shields.io/github/forks/hemavardhan252004-krishnapatnam/logisticsApp?style=for-the-badge&color=green" />
</p>

---

## ✨ Features

✅ Full-stack architecture with **TypeScript**  
✅ Frontend powered by **Vite + TailwindCSS**  
✅ **Drizzle ORM** for type-safe database queries  
✅ Shared modules for **DRY and clean code**  
✅ Scalable, modular design for logistics workflows  

---

## 🛠 Tech Stack

| Layer       | Technology |
|-------------|------------|
| **Frontend** | ⚡ Vite, 🎨 TailwindCSS |
| **Backend**  | 🟢 Node.js |
| **ORM**      | 🗄️ Drizzle |
| **Language** | 🔷 TypeScript |
| **Build**    | 📦 Vite |

---

## 📂 Project Structure
/
├── client/ 🎨 Frontend app (Vite + Tailwind)
├── server/ ⚙️ Backend services (Node.js)
├── shared/ 📦 Shared TypeScript modules
├── drizzle.config.ts 🗄️ Drizzle ORM config
├── vite.config.ts ⚡ Vite config
├── tailwind.config.ts 🎨 TailwindCSS config
└── theme.json


---

## 🚀 Getting Started

### 🔑 Prerequisites
- Node.js `>=16`  
- NPM / Yarn  
- (Optional) Docker  

### ⚡ Installation

```bash
# Clone the repository
git clone https://github.com/hemavardhan252004-krishnapatnam/logisticsApp.git
cd logisticsApp

# Install dependencies
npm install   # or yarn install


# Start backend
npm run dev:server

# Start frontend
npm run dev:client

👉 Client will run on http://localhost:3000
👉 Server API will run on http://localhost:4000/api


# Backend
DATABASE_URL=postgresql://user:password@localhost:5432/logistics_db
JWT_SECRET=your_jwt_secret

# Frontend
VITE_API_URL=http://localhost:4000/api


📜 Scripts
Command	Description
npm run dev:client	Start Vite dev server
npm run dev:server	Start backend API
npm run build:client	Build frontend
npm run build:server	Build backend
npm run start	Run production build
npm run test	Run tests


🤝 Contributing

Contributions are welcome! 🎉

Fork the repo

Create your feature branch (git checkout -b feature/my-feature)

Commit (git commit -m "✨ Added new feature")

Push (git push origin feature/my-feature)

Open a PR 🚀
