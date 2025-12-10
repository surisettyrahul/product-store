# Product-store

Simple full-stack product store app (frontend + backend) to manage products.

## 📄 What is this  
Product-store lets you add, view, update and delete products via a UI + backend API.  
It can serve as a basic product catalog / admin-store boilerplate or learning project.

## ✅ Features  
- 🌟 Tech stack: PERN + TailwindCSS + Daisy UI
- 🚀 Rate Limiting & Bot Detection
- 👌 Global state management with Zustand
- 🐞 Error handling both on the server and client

## 🛠️ Tech Stack (assumed)  
- Frontend: React (JavaScript)
- Backend: Node.js, Express
- Database: PostgreSQL

 
## 🚀 Setup .env file 
```bash
- PORT=3000
- PGUSER=...
- PGPASSWORD=...
- PGHOST=...
- PGDATABASE=...

ARCJET_KEY=...
ARCJET_ENV=development
```

## 🚀 Setup & Run Locally  

```bash
git clone https://github.com/surisettyrahul/product-store.git
cd product-store

# If repo has separate backend & frontend
cd backend
npm install
npm run dev

# In new terminal tab: start frontend (if separate)
cd ../frontend
npm install
npm run dev
