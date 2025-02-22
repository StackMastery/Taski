<a href="https://github.com/StackMastery/Taski">
    <img style="width: 100%" src="https://ik.imagekit.io/1xu2irsp6/github/task.webp?updatedAt=1740211917320" alt="Task Managment">
</a>
<br />
<br />

<div align="center">
    <img width="200" src="https://ik.imagekit.io/1xu2irsp6/github/Logo.svg?updatedAt=1740212694249">
</div>

## 🚨 Introduction

Welcome to the Taski Full-Stack Project

**Taski** is a comprehensive task management system developed using the MERN stack, which combines MongoDB, Express.js, React, and Node.js. This platform is designed to help individuals and teams efficiently organize, prioritize, and track their tasks and projects in real-time. With its user-friendly interface and powerful functionalities, Taski streamlines workflow, enhances collaboration, and boosts productivity. Whether you’re managing simple to-do lists or more complex projects, Taski provides the necessary tools to ensure that every task is accounted for and completed on time.

## ✨ Features

1. All apis protected
2. Code Readable And Strutered
3. User Verification Using Jose
4. Mongoose Schema Models
5. CRUD Operation
6. Middlewares
7. Responsive design
8. Dark mode Light Mode
9. Data Caching

## 📦 Main Dependencies

### Frontend

1. @hello-pangea/dnd (^18.0.1)
2. @radix-ui/react-avatar (^1.1.3)
3. @radix-ui/react-popover (^1.1.6)
4. @radix-ui/react-select (^2.1.6)
5. @react-three/fiber (^9.0.0-alpha.8)
6. @tailwindcss/vite (^4.0.7)
7. @tanstack/react-query (^5.66.8)
8. @tsparticles/engine (^3.8.1)
9. @tsparticles/react (^3.0.0)
10. @tsparticles/slim (^3.8.1)
11. axios (^1.7.9)
12. class-variance-authority (^0.7.1)
13. clsx (^2.1.1)
14. firebase (^11.3.1)
15. framer-motion (^12.4.7)
16. lucide-react (^0.475.0)
17. moment (^2.30.1)
18. motion (^12.4.7)
19. notistack (^3.0.2)
20. react (^19.0.0)
21. react-dom (^19.0.0)
22. react-icons (^5.5.0)
23. react-router-dom (^7.2.0)
24. tailwind-merge (^3.0.1)
25. tailwindcss (^4.0.7)
26. tailwindcss-animate (^1.0.7)
27. three (^0.173.0)

### Backend

1. cookie-parser (^1.4.7)
2. cors (^2.8.5)
3. dotenv (^16.4.7)
4. express (^4.21.2)
5. jose (^5.10.0)
6. mongoose (^8.9.2)

## Project Diagram

```
├─ backend
│  ├─ .env.example
│  ├─ .gitignore
│  ├─ app.server.js
│  ├─ backend.zip
│  ├─ config
│  │  └─ joseSecret.js
│  ├─ controllers
│  │  ├─ Auth
│  │  │  └─ createToken.js
│  │  └─ Task
│  │     ├─ createNewTask.js
│  │     ├─ deleteTask.js
│  │     ├─ getAllTasks.js
│  │     ├─ getTaskById.js
│  │     ├─ updateTask.js
│  │     └─ updateTasksMany.js
│  ├─ db
│  │  └─ dbConnect.js
│  ├─ middlewares
│  │  └─ verifyAccessToke.js
│  ├─ models
│  │  └─ task.model.js
│  ├─ package-lock.json
│  ├─ package.json
│  ├─ routes
│  │  └─ router.js
│  └─ vercel.json
└─ frontend
   ├─ .env.example
   ├─ .gitignore
   ├─ components.json
   ├─ eslint.config.js
   ├─ firebase.config.js
   ├─ frontend.zip
   ├─ index.html
   ├─ jsconfig.json
   ├─ package-lock.json
   ├─ package.json
   ├─ public
   │  ├─ _redirects
   │  ├─ favicon.svg
   │  └─ notfound.svg
   ├─ src
   │  ├─ Layout
   │  │  └─ Layout.jsx
   │  ├─ components
   │  │  ├─ Header.jsx
   │  │  ├─ TaskAdd.jsx
   │  │  ├─ magicui
   │  │  │  └─ scroll-progress.jsx
   │  │  └─ ui
   │  │     ├─ Br.jsx
   │  │     ├─ Button.jsx
   │  │     ├─ DarkMode.jsx
   │  │     ├─ Logo.jsx
   │  │     ├─ MarkLink.jsx
   │  │     ├─ Overlay.jsx
   │  │     ├─ avatar.jsx
   │  │     ├─ canvas-reveal-effect.jsx
   │  │     ├─ cover.jsx
   │  │     ├─ evervault-card.jsx
   │  │     ├─ popover.jsx
   │  │     ├─ select.jsx
   │  │     ├─ skeleton.jsx
   │  │     └─ sparkles.jsx
   │  ├─ context
   │  │  └─ AuthContext.jsx
   │  ├─ hooks
   │  │  └─ axiosSecure.js
   │  ├─ lib
   │  │  └─ utils.js
   │  ├─ main.jsx
   │  ├─ pages
   │  │  ├─ 404.jsx
   │  │  ├─ Dashboard
   │  │  │  ├─ Dashboard.jsx
   │  │  │  └─ DashboardSkeleton.jsx
   │  │  ├─ Home
   │  │  │  └─ Home.jsx
   │  │  └─ Tasks
   │  │     ├─ Tasks.jsx
   │  │     └─ update
   │  │        ├─ Skeleton.jsx
   │  │        └─ Update.jsx
   │  ├─ router
   │  │  ├─ Private.routes.jsx
   │  │  └─ Routes.jsx
   │  └─ style.css
   └─ vite.config.js
```

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/StackMastery/Taski
cd taski
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Configure Frontend Env**

Rename the .env.example file to .env.local and fill all env

```bash
# Firebase Config

VITE_FIREBASE_API_KEY=YOUR_API_KEY
VITE_FIREBASE_AUTH_DOMAIN=YOUR_AUTH_DOMAIN
VITE_FIREBASE_PROJECT_ID=YOUR_PROJECT_ID
VITE_FIREBASE_STORAGE_BUCKET=YOUR_STORAGE_BUCKET
VITE_FIREBASE_MESSAGING_SENDER_ID=YOUR_MESSAGING_SENDER_ID
VITE_FIREBASE_APP_ID=YOUR_APP_ID
VITE_FIREBASE_MEASUREMENT_ID=YOUR_MEASUREMENT_ID

# Github Profile
VITE_GITHUB_PROFILE=YOUR_GITHUB_PROFILE_LINK

# Backend Url
VITE_BASE_URL=SERVER_ENDPOINT

```

**Configure Backend Env**

Rename the .env.example file to .env and fill all env

```bash
#Port
PORT=YOUR_PORT
JOSE_SECRET=YOUR_BASE_64_SECRET # Ex- hK6g/zwgbekCwn651TB3ljbr7u4KpTc=
MONGODB_CONN_URI=YOUR_MONGODB_CONNECTION_URI
CORD_ORIGIN=YOUR_WHITE_LISTED_ORIGINS

```

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:PORT](http://localhost:3000) in your browser to view the project.
