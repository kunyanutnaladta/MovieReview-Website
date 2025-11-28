# 🎬 MovieReview Website

โปรเจกต์นี้เป็นเว็บไซต์รีวิวภาพยนตร์ที่พัฒนาด้วย **Node.js + Express + EJS + TailwindCSS** 
และใช้ **MongoDB Atlas** เป็นฐานข้อมูล

---

## 📂 Project Structure
```
MovieReview-Website/
│── controllers/      # Logic การทำงานของระบบ
│── middleware/       # Middleware เช่น Authentication, Flash Messages
│── models/           # Mongoose Models
│── public/           # Static files (CSS, JS, Images)
│── views/            # EJS Templates
│── .gitignore
│── README.md
│── index.js          # Main Entry Point
│── package.json
│── package-lock.json
```

---

## 🚀 Installation & Setup

### 1. Clone project
```bash
git clone <repository-url>
cd MovieReview-Website
```

### 2. Install dependencies
```bash
npm install
```

### 3. สร้างไฟล์ `.env` และใส่ค่าที่จำเป็น
```env
MONGODB_URI=your_mongodb_atlas_uri
SESSION_SECRET=your_session_secret
TMDB_KEY=your_tmdb_key
```

### 4. Run project
```bash
npm run start
```
หรือรันแบบ dev (ใช้ nodemon)
```bash
npm run dev
```

---

## 🛠 Tech Stack
- **Node.js + Express** → Backend
- **EJS** → Template Engine
- **TailwindCSS** → CSS Framework (CDN / Link based)
- **MongoDB Atlas** → Cloud Database

---

## 📌 Features
- สมัครสมาชิก / เข้าสู่ระบบ
- ค้นหาหนังจาก TMDB API
- เขียนรีวิว / ให้คะแนนหนัง
- ดูโปรไฟล์ผู้ใช้
- ระบบแจ้งเตือน (Flash Alert)

---

## 👥 Contributors
- Kunyanat Naladta และทีมผู้พัฒนาคนอื่นๆ

---

## Screenshot

<img width="1907" height="1016" alt="Screenshot 2025-11-28 132401" src="https://github.com/user-attachments/assets/3bdd0287-7f34-4fba-a12c-3c7a5fda13c9" />

<img width="1919" height="944" alt="Screenshot 2025-11-28 134930" src="https://github.com/user-attachments/assets/89f22412-7095-4bf5-952f-6d2309740c81" />

<img width="1895" height="1031" alt="Screenshot 2025-11-28 134950" src="https://github.com/user-attachments/assets/0d21dba4-38ac-475f-a55e-9191d446d4f5" />

<img width="1900" height="1026" alt="Screenshot 2025-11-28 135029" src="https://github.com/user-attachments/assets/96110b10-a4ba-42ff-afd0-64cb64d43c2e" />
