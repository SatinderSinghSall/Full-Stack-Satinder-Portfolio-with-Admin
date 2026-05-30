# Full-Stack Portfolio App with an Admin Panel to manage Skills, Projects, Experiences, Blogs & more - Satinder Portfolio

---

# 🚀 Satinder Portfolio — Full-Stack App Portfolio with Admin CMS

Modern production-grade Full-Stack Portfolio Platform built using:

- React 19
- Vite
- Tailwind CSS v4
- Framer Motion
- Node.js
- Express.js
- MongoDB
- Cloudinary
- JWT Authentication

This project is not just a portfolio website — it is a complete scalable content management platform featuring:

- Dynamic Portfolio Management
- Admin Dashboard CMS
- Blog System
- Freelance Showcase
- YouTube Integration
- Contact Management
- Cloud Media Uploads
- Authentication System
- Rich Text Editor CMS

---

# 🌟 Live Features

## 🌐 Public Portfolio

- Modern animated landing page
- Dynamic projects showcase
- Freelance portfolio section
- AI / ML showcase
- Services section
- Responsive mobile sidebar
- Interactive animations
- Dynamic blog system
- YouTube content integration
- Contact system

---

## 🛠️ Admin CMS Dashboard

- Secure Admin Authentication
- Add/Edit/Delete Projects
- Blog Management System
- Freelance Project Management
- YouTube Content Management
- Contact Messages Dashboard
- Dynamic EditorJS content editor
- Cloudinary image upload system

---

# ⚡ Tech Stack

---

# 🎨 Frontend Stack

## Core

- React 19
- Vite 7

## Styling

- Tailwind CSS v4
- Tailwind Merge
- Class Variance Authority

## Animation

- Framer Motion

## Routing

- React Router DOM v7

## Rich Text Editor

- EditorJS
- EditorJS Plugins

## UI Libraries

- Radix UI
- Hero Icons
- Lucide React

## Charts

- Recharts

## API Communication

- Axios

---

# 🧠 Backend Stack

## Core

- Node.js
- Express.js 5

## Database

- MongoDB
- Mongoose

## Authentication

- JWT
- bcrypt

## File Uploads

- Multer
- Cloudinary
- Multer Storage Cloudinary

## Email Services

- Resend

## Utilities

- dotenv
- cors
- axios
- cross-env

---

# 📁 Full Project Structure

# File Tree: Satinder Portfolio

**Generated:** 5/30/2026, 8:23:39 PM
**Root Path:** `e:\My Projects\Full-Stack App Portfolio with Admin\Satinder Portfolio`

```
├── 📁 backend
│   ├── 📁 config
│   │   └── 📄 cloudinary.js
│   ├── 📁 controllers
│   │   ├── 📄 authController.js
│   │   ├── 📄 dashboardController.js
│   │   └── 📄 freelanceController.js
│   ├── 📁 middleware
│   │   ├── 📄 auth.js
│   │   └── 📄 cloudinaryUpload.js
│   ├── 📁 models
│   │   ├── 📄 Blog.js
│   │   ├── 📄 ContactMessage.js
│   │   ├── 📄 FreelanceProject.js
│   │   ├── 📄 Project.js
│   │   ├── 📄 User.js
│   │   └── 📄 YouTubeVideo.js
│   ├── 📁 routes
│   │   ├── 📄 auth.js
│   │   ├── 📄 blog.js
│   │   ├── 📄 contact.js
│   │   ├── 📄 dashboard.js
│   │   ├── 📄 editorRoutes.js
│   │   ├── 📄 freelance.js
│   │   ├── 📄 project.js
│   │   ├── 📄 upload.js
│   │   └── 📄 youtube.js
│   ├── 📁 services
│   │   └── 📄 emailService.js
│   ├── 📁 templates
│   │   ├── 📄 adminNotificationTemplate.js
│   │   └── 📄 userAcknowledgementTemplate.js
│   ├── ⚙️ .gitignore
│   ├── 📝 README.md
│   ├── 📄 index.js
│   ├── ⚙️ package-lock.json
│   ├── ⚙️ package.json
│   └── 📄 seedAdmin.js
├── 📁 frontend
│   ├── 📁 Extra Codebase
│   │   ├── 📄 About.jsx
│   │   ├── 📄 ContactCTA_Button.jsx
│   │   ├── 📄 ContactMessages.jsx
│   │   ├── 📄 Experience.jsx
│   │   ├── 📄 Footer.jsx
│   │   ├── 📄 Home.jsx
│   │   ├── 📄 Home2.jsx
│   │   ├── 📄 Services.jsx
│   │   ├── 📄 Skills.jsx
│   │   ├── 📄 Skills2.jsx
│   │   └── 📄 adminNotificationTemplate.js
│   ├── 📁 public
│   │   ├── 📁 Gallery
│   │   │   └── 📁 Version 1.0.0
│   │   │       ├── 🖼️ Screenshot (1620).png
│   │   │       ├── 🖼️ Screenshot (1621).png
│   │   │       ├── 🖼️ Screenshot (1622).png
│   │   │       ├── 🖼️ Screenshot (1623).png
│   │   │       ├── 🖼️ Screenshot (1624).png
│   │   │       ├── 🖼️ Screenshot (1625).png
│   │   │       └── 🖼️ Screenshot (1626).png
│   │   ├── 🌐 googled50bc0bace67ba10.html
│   │   ├── 🖼️ icon.png
│   │   ├── 📄 robots.txt
│   │   ├── ⚙️ sitemap.xml
│   │   └── 🖼️ vite.svg
│   ├── 📁 src
│   │   ├── 📁 admin
│   │   │   ├── 📄 AddBlog.jsx
│   │   │   ├── 📄 AddFreelanceProject.jsx
│   │   │   ├── 📄 AddProject.jsx
│   │   │   ├── 📄 AddYouTube.jsx
│   │   │   ├── 📄 Blogs.jsx
│   │   │   ├── 📄 ContactMessages.jsx
│   │   │   ├── 📄 Dashboard.jsx
│   │   │   ├── 📄 ManageFreelanceProjects.jsx
│   │   │   ├── 📄 Projects.jsx
│   │   │   └── 📄 YouTube.jsx
│   │   ├── 📁 assets
│   │   │   ├── 📕 InternshipCompletionLetterSatinder.pdf
│   │   │   ├── 🖼️ Satinder_Image.jpg
│   │   │   ├── 📕 Satinder_Resume.pdf
│   │   │   └── 🖼️ react.svg
│   │   ├── 📁 components
│   │   │   ├── 📁 ai-ml
│   │   │   │   ├── 📄 AiMlHero.jsx
│   │   │   │   ├── 📄 AiMlProjects.jsx
│   │   │   │   └── 📄 AiMlSkills.jsx
│   │   │   ├── 📁 ui
│   │   │   │   ├── 📄 button.jsx
│   │   │   │   ├── 📄 card.jsx
│   │   │   │   └── 📄 dialog.jsx
│   │   │   ├── 📄 About.jsx
│   │   │   ├── 📄 AdminAuthLayout.jsx
│   │   │   ├── 📄 AdminLayout.jsx
│   │   │   ├── 📄 AdminRoute.jsx
│   │   │   ├── 📄 AppPromoModal.jsx
│   │   │   ├── 📄 AppStatusModal.jsx
│   │   │   ├── 📄 AppsShowcase.jsx
│   │   │   ├── 📄 ContactCTA_Button.jsx
│   │   │   ├── 📄 DeveloperCredit.jsx
│   │   │   ├── 📄 EditorBlocksRenderer.jsx
│   │   │   ├── 📄 EditorJSInput.jsx
│   │   │   ├── 📄 Experience.jsx
│   │   │   ├── 📄 FeatureYouTube.jsx
│   │   │   ├── 📄 FeaturedProjects.jsx
│   │   │   ├── 📄 Footer.jsx
│   │   │   ├── 📄 Hero.jsx
│   │   │   ├── 📄 Navbar.jsx
│   │   │   ├── 📄 PoetryPromoModal.jsx
│   │   │   ├── 📄 ScrollToTop.jsx
│   │   │   ├── 📄 ScrollTopButton.jsx
│   │   │   ├── 📄 SectionNavigator.jsx
│   │   │   ├── 📄 Sidebar.jsx
│   │   │   └── 📄 Skills.jsx
│   │   ├── 📁 lib
│   │   │   └── 📄 utils.js
│   │   ├── 📁 pages
│   │   │   ├── 📄 AiMl.jsx
│   │   │   ├── 📄 Blog.jsx
│   │   │   ├── 📄 BlogDetails.jsx
│   │   │   ├── 📄 Contact.jsx
│   │   │   ├── 📄 FreelanceDetails.jsx
│   │   │   ├── 📄 Home.jsx
│   │   │   ├── 📄 Login.jsx
│   │   │   ├── 📄 NotFound.jsx
│   │   │   ├── 📄 ProjectDetail.jsx
│   │   │   ├── 📄 Projects_User.jsx
│   │   │   ├── 📄 Services.jsx
│   │   │   ├── 📄 WatchMyFreelancing.jsx
│   │   │   ├── 📄 WatchMyYouTube.jsx
│   │   │   └── 📄 YouTubeDetails.jsx
│   │   ├── 📁 services
│   │   ├── 🎨 App.css
│   │   ├── 📄 App.jsx
│   │   ├── 🎨 index.css
│   │   └── 📄 main.jsx
│   ├── ⚙️ .gitignore
│   ├── 📝 README.md
│   ├── ⚙️ components.json
│   ├── 📄 eslint.config.js
│   ├── 🌐 index.html
│   ├── ⚙️ jsconfig.json
│   ├── ⚙️ package-lock.json
│   ├── ⚙️ package.json
│   ├── ⚙️ vercel.json
│   └── 📄 vite.config.js
├── ⚙️ .gitignore
└── 📝 README.md
```

---

_Generated by FileTree Pro Extension_

```bash id="m2wq7u"
Satinder Portfolio/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── templates/
│   ├── index.js
│   ├── seedAdmin.js
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── admin/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── lib/
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   ├── vite.config.js
│   └── package.json
│
├── .gitignore
└── README.md
```

---

# ✨ Key Features

---

# 🔐 Authentication System

- JWT-based Authentication
- Protected Admin Routes
- Token Validation Middleware
- Secure Login System
- Admin Authorization

---

# ☁️ Cloudinary Media System

Integrated Cloudinary upload pipeline:

- Image Uploads
- Cloud Storage
- Optimized Delivery
- Dynamic Image Rendering
- Multer Upload Middleware

---

# 📝 Dynamic Blog CMS

Rich content management powered by EditorJS:

- Headers
- Lists
- Quotes
- Tables
- Images
- Code Blocks
- Embeds
- Inline Styling

---

# 📧 Email System

Powered by Resend API:

- Admin Notification Emails
- User Acknowledgement Emails
- HTML Email Templates
- Dynamic Contact Form Workflow

---

# 📱 Responsive Design System

Fully optimized for:

- Mobile Devices
- Tablets
- Laptops
- Ultra-wide Displays

Includes:

- Mobile Drawer Navigation
- Smooth Scroll Management
- Responsive Layout Architecture
- Performance Optimizations

---

# 🎨 UI / UX Features

- Glassmorphism Design
- Dark Premium Interface
- Neon Glow Effects
- Smooth Hover Interactions
- Animated Route Transitions
- Framer Motion Animations
- Modern SaaS-style Layout

---

# 🚀 Installation Guide

---

# 1️⃣ Clone Repository

```bash id="v4wdl5"
git clone <your-repository-url>
```

---

# 2️⃣ Navigate to Project

```bash id="3syf2x"
cd Satinder-Portfolio
```

---

# 3️⃣ Install Frontend Dependencies

```bash id="aq9j9w"
cd frontend
npm install
```

---

# 4️⃣ Install Backend Dependencies

```bash id="o8pb7y"
cd ../backend
npm install
```

---

# 🔑 Environment Variables

---

# Frontend `.env.development`

```env id="9s5y0y"
VITE_API_URL=http://localhost:5000/api
```

---

# Frontend `.env.production`

```env id="z2e4v7"
VITE_API_URL=https://your-production-api.com/api
```

---

# Backend `.env.development`

```env id="gmdt1x"
PORT=5000

MONGO_URI=mongodb://127.0.0.1:27017/satinder_portfolio_db

JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

RESEND_API_KEY=your_resend_api_key
ADMIN_EMAIL=your_admin_email
```

---

# Backend `.env.production`

```env id="pdvm9d"
PORT=5000

MONGO_URI=your_production_mongodb_uri

JWT_SECRET=your_secure_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

RESEND_API_KEY=your_resend_api_key
ADMIN_EMAIL=your_admin_email
```

---

# ▶️ Running Development Servers

---

# Frontend

```bash id="l6a2dg"
cd frontend
npm run dev
```

Frontend runs on:

```bash id="1q1hgr"
http://localhost:5173
```

---

# Backend

```bash id="2rxhrk"
cd backend
npm run dev
```

Backend runs on:

```bash id="tvlrm1"
http://localhost:5000
```

---

# 🏗️ Production Build

---

# Frontend Build

```bash id="7vmbp5"
npm run build
```

---

# Backend Production

```bash id="3o2ul9"
npm start
```

---

# 📡 API Architecture

Base API URL:

```bash id="8v8cya"
/api
```

Example APIs:

```bash id="nqk6t7"
/api/projects
/api/blogs
/api/freelance
/api/youtube
/api/contact
/api/auth
```

---

# 🧠 Database Models

---

## User

Stores:

- Admin credentials
- Authentication data

---

## Blog

Stores:

- Blog content
- EditorJS blocks
- Cover images
- Metadata

---

## Project

Stores:

- Portfolio projects
- Technologies
- External links
- Images

---

## FreelanceProject

Stores:

- Freelance showcase projects
- Client information

---

## ContactMessage

Stores:

- Contact form submissions
- User inquiries

---

## YouTubeVideo

Stores:

- Featured YouTube videos
- Metadata

---

# 🔒 Security Features

- JWT Authentication
- Password Hashing
- Protected Routes
- Middleware Authorization
- Environment Variable Protection
- Secure Cloud Upload System

---

# ⚠️ Security Best Practices

Never expose:

- MongoDB URIs
- JWT Secrets
- Cloudinary Secrets
- API Keys
- `.env` files

Always use:

```bash id="d7kt8n"
.gitignore
```

for sensitive files.

---

# 🌍 Deployment Recommendations

---

# Frontend Hosting

- Vercel
- Netlify

---

# Backend Hosting

- Render
- Railway
- VPS
- DigitalOcean

---

# Database Hosting

- MongoDB Atlas

---

# ☁️ Media Storage

- Cloudinary

---

# 🎯 Future Improvements

Planned upgrades include:

- TypeScript Migration
- React Query Integration
- Role-Based Access Control (RBAC)
- Analytics Dashboard
- PWA Support
- Server-side Rendering
- Command Palette Search
- Advanced SEO Optimization
- API Rate Limiting
- Redis Caching
- WebSocket Features
- Advanced Dashboard Analytics

---

# 📈 Performance Optimizations

- Vite Fast Bundling
- Optimized React Rendering
- Lazy Loaded Components
- Dynamic Imports
- Optimized Animations
- Efficient API Calls
- Responsive Media Rendering

---

# 📄 License

This project is licensed under the ISC License.

---

# 👨‍💻 Author

# Satinder Singh Sall

Full-Stack Engineer specializing in:

- Frontend Engineering
- Backend Architecture
- Modern CMS Platforms
- AI/ML Interfaces
- Product Engineering
- Scalable Full-Stack Systems

---

# ⭐ Project Vision

This project was designed not just as a portfolio website, but as a scalable full-stack product platform demonstrating:

- Real-world frontend architecture
- Backend system design
- CMS development
- Authentication systems
- Cloud media management
- API architecture
- Modern UI/UX engineering
- Production-grade workflows

---

# Satinder Portfolio — Frontend

Modern Full-Stack Portfolio Frontend built with **React 19**, **Vite**, **Tailwind CSS v4**, **Framer Motion**, and a custom Admin CMS ecosystem.

This frontend powers the complete public-facing portfolio experience along with seamless integration to the backend admin system.

---

# ✨ Features

## 🌐 Public Portfolio

- Modern responsive landing page
- Animated hero sections
- AI / ML showcase
- Services section
- Dynamic projects showcase
- Freelancing showcase
- YouTube integration
- Blog system
- Contact system
- Smooth mobile sidebar navigation
- SEO optimized structure

---

## 🛠️ Admin Dashboard

- Secure Admin Login
- Add / Edit / Delete Projects
- Blog Management
- Freelance Project Management
- YouTube Content Management
- Dashboard Analytics Layout
- Dynamic EditorJS Blog Editor
- Cloudinary image upload integration

---

## 🎨 UI / UX

- Glassmorphism design system
- Mobile-first responsive layout
- Framer Motion animations
- Tailwind CSS v4 styling
- Radix UI components
- Custom reusable component architecture
- Smooth transitions & hover effects
- Premium dark theme interface

---

# ⚡ Tech Stack

## Frontend Framework

- React 19
- Vite 7

## Styling

- Tailwind CSS v4
- Tailwind Merge
- CVA (Class Variance Authority)

## Animations

- Framer Motion

## Routing

- React Router DOM v7

## Rich Text Editor

- EditorJS
- Multiple EditorJS plugins

## Drag & Drop

- @hello-pangea/dnd

## UI Components

- Radix UI
- Hero Icons
- Lucide React

## Charts & Visualization

- Recharts

## API Communication

- Axios

---

# 📁 Frontend Architecture

```bash
frontend/
│
├── public/                  # Static assets
├── src/
│
│   ├── admin/               # Admin dashboard pages
│   ├── assets/              # Images, PDFs, static assets
│   ├── components/          # Reusable UI components
│   │
│   │   ├── ai-ml/           # AI/ML section components
│   │   ├── ui/              # Shared UI primitives
│   │   └── ...
│   │
│   ├── lib/                 # Utility functions
│   ├── pages/               # Route pages
│   ├── services/            # API services
│   │
│   ├── App.jsx              # Main app component
│   ├── main.jsx             # Application entry point
│   ├── App.css
│   └── index.css
│
├── vite.config.js
├── package.json
└── README.md
```

---

# 🚀 Installation

## 1. Clone Repository

```bash
git clone <your-repository-url>
```

---

## 2. Navigate to Frontend

```bash
cd frontend
```

---

## 3. Install Dependencies

```bash
npm install
```

---

# 🔑 Environment Variables

Create:

```bash
.env.development
```

and

```bash
.env.production
```

---

## Development

```env
VITE_API_URL=http://localhost:5000/api
```

---

## Production

```env
VITE_API_URL=https://your-production-api-url.com/api
```

---

# ▶️ Running Development Server

```bash
npm run dev
```

Frontend runs on:

```bash
http://localhost:5173
```

---

# 🏗️ Production Build

```bash
npm run build
```

---

# 👀 Preview Production Build

```bash
npm run preview
```

---

# 📦 Major Dependencies

## Core

- react
- react-dom
- vite

## Styling

- tailwindcss
- tailwind-merge
- class-variance-authority

## Animation

- framer-motion

## Editor

- @editorjs/editorjs
- @editorjs/header
- @editorjs/image
- @editorjs/list
- @editorjs/table
- @editorjs/quote
- @editorjs/code

## Routing

- react-router-dom

## UI

- lucide-react
- @heroicons/react
- radix-ui

---

# 🔒 Authentication Flow

Frontend communicates with backend authentication APIs using:

- JWT Authentication
- Protected Admin Routes
- Local Storage Token Management
- Route Guards

---

# 🌩️ Cloudinary Integration

Images uploaded through Admin Dashboard are processed via backend and stored on Cloudinary.

Frontend handles:

- Preview rendering
- Upload state management
- Dynamic asset rendering

---

# 📱 Responsive Design

The entire frontend is optimized for:

- Mobile Devices
- Tablets
- Laptops
- Large Displays

Special attention has been given to:

- Mobile navigation
- Scroll behavior
- Drawer systems
- Performance
- Accessibility

---

# 🎯 Performance Optimizations

- Vite fast bundling
- Lazy loading routes
- Optimized animations
- Reusable component system
- Efficient API calls
- Dynamic rendering
- Responsive image handling

---

# 🧠 Future Improvements

Planned upgrades include:

- TypeScript migration
- React Query integration
- Advanced analytics dashboard
- Theme customization
- Multi-admin RBAC system
- PWA support
- Server-side rendering
- Command palette search
- Advanced SEO optimization

---

# 🛡️ Security Notes

Never expose:

- API Keys
- JWT Secrets
- Cloudinary Secrets
- Database URIs

Use `.env` files properly and keep secrets outside version control.

---

# 📄 License

This project is licensed under the ISC License.

---

# 👨‍💻 Author

## Satinder Singh Sall

Full-Stack Engineer specializing in:

- Modern React Applications
- Backend Systems
- AI/ML Interfaces
- Product Engineering
- Full-Stack Architecture

---

# ⭐ Project Vision

This portfolio is designed not just as a personal website, but as a scalable full-stack product platform demonstrating:

- Modern frontend engineering
- Backend architecture
- CMS systems
- UI/UX systems
- Production-grade workflows
- Real-world application development

---

# Satinder Portfolio — Backend

Scalable Express.js backend powering the full-stack Satinder Portfolio platform with Admin CMS, authentication system, dynamic content management, image uploads, and email integrations.

This backend provides REST APIs for:

- Portfolio management
- Blog CMS
- Freelance showcase
- YouTube content system
- Contact management
- Admin authentication
- Cloudinary media uploads

---

# ✨ Features

## 🔐 Authentication System

- JWT Authentication
- Protected Admin Routes
- Middleware-based authorization
- Secure login system

---

## 📝 Content Management APIs

- Blog CRUD APIs
- Project CRUD APIs
- Freelance Project APIs
- YouTube Content APIs
- Contact Form APIs

---

## ☁️ Cloudinary Upload System

- Cloudinary integration
- Image upload handling
- Multer middleware
- Dynamic media storage

---

## 📧 Email System

- Resend Email Integration
- Admin Notifications
- User Acknowledgement Emails
- Custom email templates

---

# ⚡ Tech Stack

## Backend Framework

- Node.js
- Express.js 5

## Database

- MongoDB
- Mongoose ODM

## Authentication

- JWT (jsonwebtoken)
- bcrypt

## File Upload

- Multer
- Cloudinary
- multer-storage-cloudinary

## Email Services

- Resend

## Utilities

- dotenv
- cors
- axios
- cross-env

---

# 📁 Backend Architecture

```bash id="wzj99o"
backend/
│
├── config/                     # Configuration files
│   └── cloudinary.js
│
├── controllers/                # Route controllers
│   ├── authController.js
│   ├── dashboardController.js
│   └── freelanceController.js
│
├── middleware/                 # Custom middlewares
│   ├── auth.js
│   └── cloudinaryUpload.js
│
├── models/                     # Mongoose schemas
│   ├── Blog.js
│   ├── ContactMessage.js
│   ├── FreelanceProject.js
│   ├── Project.js
│   ├── User.js
│   └── YouTubeVideo.js
│
├── routes/                     # API routes
│   ├── auth.js
│   ├── blog.js
│   ├── contact.js
│   ├── dashboard.js
│   ├── editorRoutes.js
│   ├── freelance.js
│   ├── project.js
│   ├── upload.js
│   └── youtube.js
│
├── services/                   # Business logic services
│   └── emailService.js
│
├── templates/                  # Email templates
│   ├── adminNotificationTemplate.js
│   └── userAcknowledgementTemplate.js
│
├── index.js                    # Main server entry point
├── seedAdmin.js                # Admin seeding script
├── package.json
└── README.md
```

---

# 🚀 Installation

## 1. Clone Repository

```bash id="6j4wr7"
git clone <your-repository-url>
```

---

## 2. Navigate to Backend

```bash id="jlwm24"
cd backend
```

---

## 3. Install Dependencies

```bash id="wnr9qx"
npm install
```

---

# 🔑 Environment Variables

Create:

```bash id="b6h5rz"
.env.development
```

and

```bash id="vl1x0m"
.env.production
```

---

# ⚙️ Development Environment

```env id="w23n2g"
PORT=5000

MONGO_URI=mongodb://127.0.0.1:27017/satinder_portfolio_db

JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

RESEND_API_KEY=your_resend_api_key
ADMIN_EMAIL=your_admin_email
```

---

# 🌍 Production Environment

```env id="y9rv0g"
PORT=5000

MONGO_URI=your_production_mongodb_uri

JWT_SECRET=your_secure_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

RESEND_API_KEY=your_resend_api_key
ADMIN_EMAIL=your_admin_email
```

---

# ▶️ Running Development Server

```bash id="n9v69z"
npm run dev
```

Server runs on:

```bash id="0mych4"
http://localhost:5000
```

---

# 🚀 Production Server

```bash id="wfj2k5"
npm start
```

---

# 📡 API Base URL

```bash id="4jv9h5"
/api
```

Example:

```bash id="vz7smq"
http://localhost:5000/api/projects
```

---

# 🛡️ Authentication System

Protected routes use:

- JWT tokens
- Authorization middleware
- Token validation
- Admin-only access control

Authentication flow:

1. User logs in
2. JWT token generated
3. Token stored on frontend
4. Protected APIs validated using middleware

---

# ☁️ Cloudinary Upload Flow

Image uploads are handled using:

- Multer
- Cloudinary Storage Engine
- Upload Middleware

Features:

- Automatic cloud storage
- Optimized asset delivery
- Dynamic URL generation
- Secure upload handling

---

# 📧 Email Notification System

The backend sends:

- Admin notification emails
- User acknowledgement emails

Powered by:

- Resend API
- HTML email templates

---

# 📦 Major Dependencies

## Core

- express
- mongoose
- dotenv

## Authentication

- bcrypt
- jsonwebtoken

## Uploads

- multer
- cloudinary
- multer-storage-cloudinary

## Utilities

- cors
- axios
- cross-env

## Email

- resend

---

# 🧠 Database Models

## User

Stores:

- Admin credentials
- Authentication data

---

## Blog

Stores:

- Blog content
- EditorJS blocks
- Metadata
- Cover images

---

## Project

Stores:

- Portfolio projects
- Technologies
- Project links
- Images

---

## FreelanceProject

Stores:

- Freelance showcase projects
- Client/project information

---

## ContactMessage

Stores:

- User contact form submissions
- Inquiry information

---

## YouTubeVideo

Stores:

- Featured YouTube content
- Video metadata

---

# 🔒 Security Features

- JWT-based authentication
- Password hashing using bcrypt
- Environment variable protection
- Protected admin APIs
- Middleware authorization
- Secure cloud upload system

---

# ⚠️ Important Security Notes

Never commit:

- `.env` files
- JWT secrets
- MongoDB credentials
- Cloudinary secrets
- Resend API keys

Always add sensitive files to:

```bash id="6vctvq"
.gitignore
```

---

# 🌐 Deployment Recommendations

## Frontend

- Vercel
- Netlify

## Backend

- Render
- Railway
- VPS
- DigitalOcean

## Database

- MongoDB Atlas

---

# 🎯 Future Improvements

Planned upgrades:

- TypeScript migration
- RBAC (Role-Based Access Control)
- API rate limiting
- Request validation
- Swagger API docs
- Redis caching
- WebSocket notifications
- Microservice architecture
- Advanced analytics APIs

---

# 📄 License

This project is licensed under the ISC License.

---

# 👨‍💻 Author

## Satinder Singh Sall

Full-Stack Engineer focused on:

- Backend architecture
- Modern web systems
- CMS platforms
- Scalable APIs
- Product engineering

---

# ⭐ Project Vision

This backend is designed as a production-ready content platform supporting:

- Dynamic portfolio systems
- Admin CMS workflows
- Secure authentication
- Cloud media management
- Real-world application architecture

---

# Full-Stack Portfolio App with an Admin Panel to manage Skills, Projects, Experiences, Blogs & more - Satinder Portfolio

# File Tree: Satinder Portfolio

**Generated:** 5/30/2026, 8:12:05 PM
**Root Path:** `e:\My Projects\Full-Stack App Portfolio with Admin\Satinder Portfolio`

```
├── 📁 backend
│   ├── 📁 config
│   │   └── 📄 cloudinary.js
│   ├── 📁 controllers
│   │   ├── 📄 authController.js
│   │   ├── 📄 dashboardController.js
│   │   └── 📄 freelanceController.js
│   ├── 📁 middleware
│   │   ├── 📄 auth.js
│   │   └── 📄 cloudinaryUpload.js
│   ├── 📁 models
│   │   ├── 📄 Blog.js
│   │   ├── 📄 ContactMessage.js
│   │   ├── 📄 FreelanceProject.js
│   │   ├── 📄 Project.js
│   │   ├── 📄 User.js
│   │   └── 📄 YouTubeVideo.js
│   ├── 📁 routes
│   │   ├── 📄 auth.js
│   │   ├── 📄 blog.js
│   │   ├── 📄 contact.js
│   │   ├── 📄 dashboard.js
│   │   ├── 📄 editorRoutes.js
│   │   ├── 📄 freelance.js
│   │   ├── 📄 project.js
│   │   ├── 📄 upload.js
│   │   └── 📄 youtube.js
│   ├── 📁 services
│   │   └── 📄 emailService.js
│   ├── 📁 templates
│   │   ├── 📄 adminNotificationTemplate.js
│   │   └── 📄 userAcknowledgementTemplate.js
│   ├── ⚙️ .gitignore
│   ├── 📝 README.md
│   ├── 📄 index.js
│   ├── ⚙️ package-lock.json
│   ├── ⚙️ package.json
│   └── 📄 seedAdmin.js
├── 📁 frontend
│   ├── 📁 Extra Codebase
│   │   ├── 📄 About.jsx
│   │   ├── 📄 ContactCTA_Button.jsx
│   │   ├── 📄 ContactMessages.jsx
│   │   ├── 📄 Experience.jsx
│   │   ├── 📄 Footer.jsx
│   │   ├── 📄 Home.jsx
│   │   ├── 📄 Home2.jsx
│   │   ├── 📄 Services.jsx
│   │   ├── 📄 Skills.jsx
│   │   ├── 📄 Skills2.jsx
│   │   └── 📄 adminNotificationTemplate.js
│   ├── 📁 public
│   │   ├── 📁 Gallery
│   │   │   └── 📁 Version 1.0.0
│   │   │       ├── 🖼️ Screenshot (1620).png
│   │   │       ├── 🖼️ Screenshot (1621).png
│   │   │       ├── 🖼️ Screenshot (1622).png
│   │   │       ├── 🖼️ Screenshot (1623).png
│   │   │       ├── 🖼️ Screenshot (1624).png
│   │   │       ├── 🖼️ Screenshot (1625).png
│   │   │       └── 🖼️ Screenshot (1626).png
│   │   ├── 🌐 googled50bc0bace67ba10.html
│   │   ├── 🖼️ icon.png
│   │   ├── 📄 robots.txt
│   │   ├── ⚙️ sitemap.xml
│   │   └── 🖼️ vite.svg
│   ├── 📁 src
│   │   ├── 📁 admin
│   │   │   ├── 📄 AddBlog.jsx
│   │   │   ├── 📄 AddFreelanceProject.jsx
│   │   │   ├── 📄 AddProject.jsx
│   │   │   ├── 📄 AddYouTube.jsx
│   │   │   ├── 📄 Blogs.jsx
│   │   │   ├── 📄 ContactMessages.jsx
│   │   │   ├── 📄 Dashboard.jsx
│   │   │   ├── 📄 ManageFreelanceProjects.jsx
│   │   │   ├── 📄 Projects.jsx
│   │   │   └── 📄 YouTube.jsx
│   │   ├── 📁 assets
│   │   │   ├── 📕 InternshipCompletionLetterSatinder.pdf
│   │   │   ├── 🖼️ Satinder_Image.jpg
│   │   │   ├── 📕 Satinder_Resume.pdf
│   │   │   └── 🖼️ react.svg
│   │   ├── 📁 components
│   │   │   ├── 📁 ai-ml
│   │   │   │   ├── 📄 AiMlHero.jsx
│   │   │   │   ├── 📄 AiMlProjects.jsx
│   │   │   │   └── 📄 AiMlSkills.jsx
│   │   │   ├── 📁 ui
│   │   │   │   ├── 📄 button.jsx
│   │   │   │   ├── 📄 card.jsx
│   │   │   │   └── 📄 dialog.jsx
│   │   │   ├── 📄 About.jsx
│   │   │   ├── 📄 AdminAuthLayout.jsx
│   │   │   ├── 📄 AdminLayout.jsx
│   │   │   ├── 📄 AdminRoute.jsx
│   │   │   ├── 📄 AppPromoModal.jsx
│   │   │   ├── 📄 AppStatusModal.jsx
│   │   │   ├── 📄 AppsShowcase.jsx
│   │   │   ├── 📄 ContactCTA_Button.jsx
│   │   │   ├── 📄 DeveloperCredit.jsx
│   │   │   ├── 📄 EditorBlocksRenderer.jsx
│   │   │   ├── 📄 EditorJSInput.jsx
│   │   │   ├── 📄 Experience.jsx
│   │   │   ├── 📄 FeatureYouTube.jsx
│   │   │   ├── 📄 FeaturedProjects.jsx
│   │   │   ├── 📄 Footer.jsx
│   │   │   ├── 📄 Hero.jsx
│   │   │   ├── 📄 Navbar.jsx
│   │   │   ├── 📄 PoetryPromoModal.jsx
│   │   │   ├── 📄 ScrollToTop.jsx
│   │   │   ├── 📄 ScrollTopButton.jsx
│   │   │   ├── 📄 SectionNavigator.jsx
│   │   │   ├── 📄 Sidebar.jsx
│   │   │   └── 📄 Skills.jsx
│   │   ├── 📁 lib
│   │   │   └── 📄 utils.js
│   │   ├── 📁 pages
│   │   │   ├── 📄 AiMl.jsx
│   │   │   ├── 📄 Blog.jsx
│   │   │   ├── 📄 BlogDetails.jsx
│   │   │   ├── 📄 Contact.jsx
│   │   │   ├── 📄 FreelanceDetails.jsx
│   │   │   ├── 📄 Home.jsx
│   │   │   ├── 📄 Login.jsx
│   │   │   ├── 📄 NotFound.jsx
│   │   │   ├── 📄 ProjectDetail.jsx
│   │   │   ├── 📄 Projects_User.jsx
│   │   │   ├── 📄 Services.jsx
│   │   │   ├── 📄 WatchMyFreelancing.jsx
│   │   │   ├── 📄 WatchMyYouTube.jsx
│   │   │   └── 📄 YouTubeDetails.jsx
│   │   ├── 📁 services
│   │   ├── 🎨 App.css
│   │   ├── 📄 App.jsx
│   │   ├── 🎨 index.css
│   │   └── 📄 main.jsx
│   ├── ⚙️ .gitignore
│   ├── 📝 README.md
│   ├── ⚙️ components.json
│   ├── 📄 eslint.config.js
│   ├── 🌐 index.html
│   ├── ⚙️ jsconfig.json
│   ├── ⚙️ package-lock.json
│   ├── ⚙️ package.json
│   ├── ⚙️ vercel.json
│   └── 📄 vite.config.js
├── ⚙️ .gitignore
└── 📝 README.md
```

---

_Generated by FileTree Pro Extension_

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
