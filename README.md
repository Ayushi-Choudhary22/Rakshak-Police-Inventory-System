# 🛡️ Rakshak – Police Inventory Management System

## 📌 Overview
Rakshak is a full-stack web application designed to modernize and streamline police inventory management. It provides a centralized digital system to track, manage, and monitor police resources such as equipment, stations, and departmental assets.

The goal of this project is to improve transparency, reduce manual errors, and make inventory management faster, more reliable, and more efficient for real-world administrative use.

---

## 🌐 Live Demo
https://rakshak-police-inventory-system.vercel.app

---

## ⚙️ Tech Stack

Frontend:
- Next.js (App Router)
- React.js
- Tailwind CSS
- DaisyUI

Backend / Services:
- Firebase Authentication
- Firebase Firestore Database

Deployment:
- Vercel

---

## 🚀 Features

- Secure Authentication System (Login/Signup)
- Police Department Management
- Station-wise Resource Tracking
- GPS Location Module
- Inventory Management System
- Clean and responsive dashboard UI
- Optimized performance using Next.js

---

## 📁 Project Structure

rakshak/
├── app/
├── components/
├── public/
├── styles/
├── lib/
├── firebase/
├── .env.local (not pushed to GitHub)
├── package.json
└── next.config.js

---

## 🛠️ Installation & Setup

### 1. Clone the Repository
git clone https://github.com/Ayushi-Choudhary22/Rakshak-Police-Inventory-System.git
cd Rakshak-Police-Inventory-System

---

### 2. Install Dependencies
npm install

---

### 3. Setup Environment Variables

Create a file named `.env.local` in the root folder and add:

NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key_here
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain_here
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id_here
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket_here
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id_here
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id_here

IMPORTANT:
- Do NOT share this file
- Do NOT push it to GitHub
- Get values from Firebase Console → Project Settings

---

### 4. Run the Project (Development Mode)
npm run dev

Open:
http://localhost:3000

---

### 5. Build for Production
npm run build
npm start

---

## 🔥 Firebase Setup

1. Go to Firebase Console
2. Create a new project
3. Enable:
   - Authentication (Email/Password or Google)
   - Firestore Database
4. Copy Firebase config keys into `.env.local`

---

## 🚀 Deployment (Vercel)

This project is deployed on Vercel.

To update deployment:
- Push changes to GitHub → auto deploys
OR
- Use Vercel Dashboard → manual deploy

---

## ⚠️ Common Issue

Firebase Error: auth/invalid-api-key

Fix:
- Check `.env.local`
- Ensure all Firebase keys are correct
- Add same variables in Vercel → Project Settings → Environment Variables

---

## 📌 Future Improvements

- Role-based access control (Admin / Officer)
- Real-time tracking system
- AI-based inventory prediction
- Mobile app version
- Advanced analytics dashboard

---

## 🤝 Contribution

Contributions are welcome.
Feel free to open issues or pull requests for improvements.

---

## 👩‍💻 Author

Ayushi Choudhary
