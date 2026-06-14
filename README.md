# 🛡️ Rakshak – Police Inventory Management System

## 📌 Overview
Rakshak is a full-stack web application designed to digitize and streamline police inventory management. It helps manage police station resources, equipment, and departmental assets in a centralized system.

The goal is to improve transparency, reduce manual tracking errors, and enable efficient resource allocation across departments.

---

## 🌐 Live Demo
https://rakshak-police-inventory-system.vercel.app

---

# 🚀 How to Run This Project

This project can be run in TWO ways:

---

# 🟢 OPTION 1: Quick Start (Demo Mode)

Use this if you just want to run the project locally.

### Step 1: Clone Repository
git clone https://github.com/Ayushi-Choudhary22/Rakshak-Police-Inventory-System.git  
cd Rakshak-Police-Inventory-System  

---

### Step 2: Install Dependencies
npm install  

---

### Step 3: Run Project
npm run dev  

---

### Step 4: Open in Browser
http://localhost:3000  

---

✔ This will start the frontend instantly  
⚠ Some features may require Firebase setup

---

# 🛠 OPTION 2: Full Setup (Firebase Required)

Use this if you want full functionality (authentication + database).

---

## ⚙️ Step 1: Create Environment File

Create a file in the root folder:

.env.local

Add the following:

NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id

---

## 🔥 Step 2: Firebase Setup

1. Go to https://console.firebase.google.com
2. Create a new project
3. Enable:
   - Authentication (Email / Google)
   - Firestore Database
4. Copy Firebase config values
5. Paste them into `.env.local`

---

## ▶️ Step 3: Run Project

npm install  
npm run dev  

---

## 🚀 Step 4: Production Build

npm run build  
npm start  

---

# 📁 Project Structure

rakshak/
│── app/              # Pages (Next.js routing)
│── components/      # UI components
│── firebase/        # Firebase config
│── lib/             # Helper functions
│── public/          # Static assets
│── styles/          # Global styles
│── .env.local       # Environment variables (not pushed)
│── package.json     # Dependencies
│── next.config.js   # Next.js config

---

# 🚀 Deployment (Vercel)

1. Push project to GitHub  
2. Import repo in Vercel  
3. Add environment variables in Vercel dashboard  
4. Deploy automatically  

---

# ⚠️ Common Issue

## Firebase Error: auth/invalid-api-key

Fix:
- Check `.env.local`
- Ensure all Firebase keys are correct
- Add same environment variables in Vercel dashboard

---

# 📌 Future Improvements

- Role-based access control (Admin / Officer)
- Real-time inventory tracking
- AI-based resource prediction
- Mobile application version
- Advanced analytics dashboard

---

# 🤝 Contributions

Contributions are welcome.  
Feel free to fork the repository and improve the project.

---

# 👩‍💻 Author

Ayushi Choudhary
