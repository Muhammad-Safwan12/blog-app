# 📝 Blog-App

A modern **React.js + Appwrite** powered blogging platform built using **Vite**.  
It features full **authentication**, **CRUD operations**, and a clean responsive UI.

---

## 🚀 Features

- 🔐 **User Authentication** (Sign up, Login, Logout) via Appwrite Auth
- 📝 **Create, Read, Update, Delete** blog posts
- 🔍 Clean & responsive UI (built with TailwindCSS)
- ☁️ Appwrite Backend Integration (Database, Storage, Users)
- ⚡️ Fast build using **Vite**

---

## 🛠️ Tech Stack

| Frontend | Backend (BaaS) | Styling       | Build Tool |
|----------|----------------|----------------|-------------|
| React.js | Appwrite       | Tailwind CSS   | Vite        |

---

## 📁 Project Structure
```
blog-app/
├── public/
├── src/
│ ├── components/
│ ├── pages/
│ ├── appwrite/ # Appwrite config and API calls
│ ├── App.jsx
│ └── main.jsx
├── .env # Appwrite credentials
├── .gitignore
├── index.html
├── vite.config.js
└── package.json
```

# 🔐 Authentication Logic (Brief)

Users register/login using Appwrite's built-in auth service.

On success, a session is stored and accessed via Appwrite SDK.

Protected routes check for user session before rendering.

# 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first
to discuss what you would like to change.

# 💬 Contact

Connect with me on:

- [GitHub](https://github.com/Muhammad-Safwan12)

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
