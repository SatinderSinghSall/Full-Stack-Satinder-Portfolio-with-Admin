# Full-Stack Portfolio App with an Admin Panel to manage Skills, Projects, Experiences, Blogs & more - Satinder Portfolio

# File Tree: Satinder Portfolio

Generated on: 8/12/2025, 6:17:08 AM
Root path: `e:\My Projects\Full-Stack App Portfolio with Admin\Satinder Portfolio`

```
├── 📁 backend/
│   ├── 📁 .git/ 🚫 (auto-hidden)
│   ├── 📁 config/
│   │   └── 📄 cloudinary.js
│   ├── 📁 controllers/
│   │   ├── 📄 authController.js
│   │   └── 📄 dashboardController.js
│   ├── 📁 middleware/
│   │   ├── 📄 auth.js
│   │   └── 📄 cloudinaryUpload.js
│   ├── 📁 models/
│   │   ├── 📄 Blog.js
│   │   ├── 📄 ContactMessage.js
│   │   ├── 📄 Project.js
│   │   ├── 📄 User.js
│   │   └── 📄 YouTubeVideo.js
│   ├── 📁 node_modules/ 🚫 (auto-hidden)
│   ├── 📁 routes/
│   │   ├── 📄 auth.js
│   │   ├── 📄 blog.js
│   │   ├── 📄 contact.js
│   │   ├── 📄 dashboard.js
│   │   ├── 📄 project.js
│   │   └── 📄 youtube.js
│   ├── 📄 .env.development 🚫 (auto-hidden)
│   ├── 📄 .env.production 🚫 (auto-hidden)
│   ├── 🚫 .gitignore
│   ├── 📖 README.md
│   ├── 📄 index.js
│   ├── 📄 package-lock.json
│   ├── 📄 package.json
│   └── 📄 seedAdmin.js
└── 📁 frontend/
    ├── 📁 .git/ 🚫 (auto-hidden)
    ├── 📁 dist/ 🚫 (auto-hidden)
    ├── 📁 node_modules/ 🚫 (auto-hidden)
    ├── 📁 public/
    │   ├── 🖼️ icon.png
    │   └── 🖼️ vite.svg
    ├── 📁 src/
    │   ├── 📁 admin/
    │   │   ├── 📄 AddBlog.jsx
    │   │   ├── 📄 AddProject.jsx
    │   │   ├── 📄 AddYouTube.jsx
    │   │   ├── 📄 Blogs.jsx
    │   │   ├── 📄 ContactMessages.jsx
    │   │   ├── 📄 Dashboard.jsx
    │   │   ├── 📄 Projects.jsx
    │   │   └── 📄 YouTube.jsx
    │   ├── 📁 assets/
    │   │   ├── 🖼️ Satinder_Image.jpg
    │   │   ├── 📕 Satinder_Resume.pdf
    │   │   └── 🖼️ react.svg
    │   ├── 📁 components/
    │   │   ├── 📄 About.jsx
    │   │   ├── 📄 AdminLayout.jsx
    │   │   ├── 📄 AdminRoute.jsx
    │   │   ├── 📄 ContactCTA_Button.jsx
    │   │   ├── 📄 Experience.jsx
    │   │   ├── 📄 Footer.jsx
    │   │   ├── 📄 Navbar.jsx
    │   │   ├── 📄 Sidebar.jsx
    │   │   └── 📄 Skills.jsx
    │   ├── 📁 pages/
    │   │   ├── 📄 Blog.jsx
    │   │   ├── 📄 BlogDetails.jsx
    │   │   ├── 📄 Contact.jsx
    │   │   ├── 📄 Home.jsx
    │   │   ├── 📄 Login.jsx
    │   │   ├── 📄 NotFound.jsx
    │   │   ├── 📄 ProjectDetail.jsx
    │   │   ├── 📄 Projects_User.jsx
    │   │   ├── 📄 Services.jsx
    │   │   ├── 📄 WatchMyYouTube.jsx
    │   │   └── 📄 YouTubeDetails.jsx
    │   ├── 📁 services/
    │   ├── 🎨 App.css
    │   ├── 📄 App.jsx
    │   ├── 🎨 index.css
    │   └── 📄 main.jsx
    ├── 📄 .env.development 🚫 (auto-hidden)
    ├── 📄 .env.production 🚫 (auto-hidden)
    ├── 🚫 .gitignore
    ├── 📖 README.md
    ├── 📄 eslint.config.js
    ├── 🌐 index.html
    ├── 📄 package-lock.json
    ├── 📄 package.json
    ├── 📄 vercel.json
    └── 📄 vite.config.js
```

---

## View the app Live: https://satinder-portfolio.vercel.app/

Absolutely! Here’s a clean, professional README structure for your **Full-Stack Portfolio App with Admin Panel** project. It’s polished and ready to present on GitHub or any documentation platform:

---

# Satinder Portfolio — Full-Stack Portfolio App with Admin Panel

[Live Demo](https://satinder-portfolio.vercel.app/)

---

## Overview

**Satinder Portfolio** is a comprehensive full-stack web application featuring a personal portfolio with an admin panel. The admin panel allows managing various sections including Skills, Projects, Experiences, Blogs, and more. This project is designed to showcase web development skills, both on the frontend and backend, with a strong emphasis on real-world use cases such as content management, authentication, and file uploads.

---

## Features

- **Admin Panel** to add, update, and delete portfolio content.
- Authentication system for secure admin access.
- Manage Skills, Projects, Experiences, Blogs, and YouTube videos.
- Contact form with message management.
- Responsive UI for seamless experience on all devices.
- Cloudinary integration for media uploads.
- Modern tech stack with React (frontend) and Node.js/Express (backend).

---

## Tech Stack

### Frontend

- React.js (with JSX and Hooks)
- Vite as build tool
- CSS for styling

### Backend

- Node.js with Express.js
- MongoDB (via Mongoose) for database
- Cloudinary for image and media storage
- JWT for authentication

---

## Project Structure

```
Satinder Portfolio/
├── backend/
│   ├── config/                 # Config files (e.g., Cloudinary)
│   ├── controllers/            # API logic controllers
│   ├── middleware/             # Auth and file upload middleware
│   ├── models/                 # Mongoose models (User, Blog, Project, etc.)
│   ├── routes/                 # Express route handlers
│   ├── index.js                # Entry point for backend server
│   ├── seedAdmin.js            # Script to create admin user
│   └── .env                   # Environment variables (hidden)
│
└── frontend/
    ├── public/                 # Static assets
    ├── src/
    │   ├── admin/              # Admin panel pages and forms
    │   ├── assets/             # Images, resume PDFs, etc.
    │   ├── components/         # Reusable React components
    │   ├── pages/              # Main frontend pages
    │   ├── services/           # API calls and services (optional)
    │   ├── App.jsx             # Main React app component
    │   └── main.jsx            # ReactDOM render and app initialization
    ├── vite.config.js          # Vite config
    └── .env                   # Frontend environment variables (hidden)
```

---
