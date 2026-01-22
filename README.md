# Scanner App 📄🔍

A web-based document scanning application built using modern frontend tooling and Firebase services.
The app allows users to scan, crop, process, and manage documents efficiently through a clean and responsive UI.

---

## 🚀 Features

* 📸 Document scanning and image processing
* ✂️ Manual crop editor for fine adjustments
* 🔐 Authentication flow (Login module)
* ☁️ Firebase integration for backend services
* ⚡ Fast frontend powered by Vite + React
* 🧪 Unit testing with Vitest

---

## 🛠 Tech Stack

### Frontend

* React (TypeScript)
* Vite
* CSS / Custom styles
* ESLint for linting
* Vitest for testing

### Backend / Cloud

* Firebase (Hosting, Firestore rules)
* CORS configuration for secure access

---

## 📁 Project Structure

```
Scanner-App/
│
├── frontend/
│   ├── index.html
│   ├── package.json
│   ├── vite.config.ts
│   ├── tsconfig*.json
│   ├── public/
│   └── src/
│       ├── components/
│       ├── hooks/
│       ├── utils/
│       └── main.tsx
│
├── firebase/
│   ├── firebase.json
│   ├── firestore.rules
│   ├── cors.json
│   └── .firebaserc
│
├── docs/
│   └── HOW_THE_APP_WORKS.md
│
├── .gitignore
└── README.md
```

---

## ⚙️ Setup & Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Aaru607/scanner-app.git
cd scanner-app
```

### 2️⃣ Install dependencies

```bash
cd frontend
npm install
```

### 3️⃣ Run the application

```bash
npm run dev
```

The app will be available at:

```
http://localhost:5173
```

---

## 🔥 Firebase Configuration

Firebase-related configuration files are located inside the `firebase/` directory.

* `firebase.json` – Firebase project configuration
* `firestore.rules` – Firestore security rules
* `cors.json` – CORS policy configuration

> ⚠️ The `.firebase/` cache directory is ignored using `.gitignore`.

---

## 📄 Documentation

Detailed working and flow of the application can be found here:

```
docs/HOW_THE_APP_WORKS.md
```

---

## 🧠 Design Decisions

* Frontend and Firebase configs are separated for better maintainability
* Folder structure follows industry best practices
* Configuration and cache files are excluded from version control
* Clean commit history maintained for clarity

---

## 🤝 Contribution

Feel free to fork the repository and raise a pull request for improvements or bug fixes.

---

## 📌 Author

Developed as part of a learning and project implementation exercise focused on frontend architecture and cloud integration.

---

## 📜 License

This project is open-source and available for educational and demonstration purposes.
