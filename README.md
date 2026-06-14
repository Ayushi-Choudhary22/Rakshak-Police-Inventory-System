# 🛡️ Rakshak – Police Inventory Management System

---

## 📌 Overview
Rakshak is a full-stack web application designed to digitize and streamline police inventory management. It helps manage police station resources, equipment, and departmental assets in a centralized and efficient system.

The project improves transparency, reduces manual errors, and enables faster and more reliable tracking of inventory across departments.

---

## 🌐 Live Demo
https://rakshak-police-inventory-system.vercel.app

---

## 🚀 Features
- Secure authentication system (Login / Signup)
- Police department management module
- Station-wise inventory tracking
- GPS/location-based module
- Centralized equipment management
- Responsive and modern UI
- Optimized performance with Next.js

---

## 🧰 Tech Stack

**Frontend**
- Next.js (App Router)
- React.js
- Tailwind CSS
- DaisyUI

**Backend / Services**
- Firebase Authentication
- Firebase Firestore Database

**Deployment**
- Vercel

---

## 📁 Project Structure

```bash
rakshak/
│
├── app/              # Next.js App Router pages
├── components/       # UI components
├── firebase/         # Firebase config
├── lib/              # Helper functions
├── public/           # Static assets
├── styles/           # Global styles
├── .env.local        # Environment variables (not pushed)
├── package.json      # Dependencies
└── next.config.js    # Next.js config

---

## ⚙️ Setup Instructions

### 1. Clone Repository
git clone https://github.com/Ayushi-Choudhary22/Rakshak-Police-Inventory-System.git
cd Rakshak-Police-Inventory-System

---

### 2. Install Dependencies
npm install

---

### 3. Create Environment File
Create a file named `.env.local` in the root folder and add:

NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id

---

## 🔥 Firebase Setup
1. Go to https://console.firebase.google.com
2. Create a new project
3. Enable Authentication (Email / Google)
4. Enable Firestore Database
5. Copy Firebase config into `.env.local`

---

## ▶️ Run Project (Development)
npm run dev

Open in browser:
http://localhost:3000

---

## 🚀 Build for Production
npm run build
npm start

---

## 🚀 Deployment (Vercel)
1. Push project to GitHub
2. Import repository in Vercel
3. Add environment variables in Vercel dashboard
4. Deploy automatically

---

## ⚠️ Common Issue

### Firebase Error: auth/invalid-api-key
Fix:
- Check `.env.local` values
- Ensure Firebase keys are correct
- Add same variables in Vercel environment settings

---

## 📌 Future Improvements
- Role-based access control (Admin / Officer)
- Real-time inventory tracking system
- AI-based prediction module
- Mobile application version
- Advanced analytics dashboard

---

## 🤝 Contributions
Contributions are welcome.
Fork the repo and submit pull requests for improvements.

---

## 👩‍💻 Author
Ayushi Choudhary
