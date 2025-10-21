# 🌟 School Association of Matara (2005) Batch | Official Website

Welcome to the development repository for the Inter School Association of Matara (2005) Batch website! 🎉 This platform is designed to reconnect and engage our alumni, offering an easy and beautiful way to stay connected, share memories, and celebrate our journey. 💫

## Key Features

📅 Event Hub – Stay in the loop with all reunions, meetups, and exclusive gatherings. Easily register and share your experiences through this comprehensive event management system.

🎓 Programs & Initiatives – Get involved in batch-led programs and charitable events that make an impact while fostering a sense of community. 🤝

🌐 Alumni Network – Connect with batchmates through a dynamic directory that enhances both social and professional networking.

🖼️ Memory Vault – Relive and upload cherished photos from our school days and batch events, creating a digital time capsule to preserve our legacy. 📸

📰 News & Announcements – Stay updated with the latest news, stories, and important batch-related updates, all in one place.

💬 Community Forum – Engage in meaningful discussions, share ideas, and collaborate on events and initiatives that help keep our batch vision alive. 🗣️

## Why this project? 💡

This website is more than just a digital platform—it's a living, breathing community for the 2005 batch. Whether you're here to keep up with the latest events, contribute to charitable programs, or simply relive great memories, this space is designed to keep our alumni legacy alive and thriving. 🌟

## Technical Overview

### Project Structure
```
├── client/          # Main client-facing website
├── admin/           # Admin dashboard
└── api/            # Backend API server
```

### Technology Stack

#### Frontend (Client & Admin)
- ⚛️ React.js with Vite
- 🎨 TailwindCSS
- 🎭 Material-UI Components
- 🛣️ React Router DOM
- ✨ Framer Motion (animations)
- 🔄 Axios (API integration)

#### Backend
- 📡 Node.js & Express.js
- 🗄️ MongoDB with Mongoose
- 📧 Nodemailer
- 📁 Multer (file uploads)

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation & Setup

1. Clone the repository:
```bash
git clone [repository-url]
```

2. Install API dependencies and start the server:
```bash
cd api
npm install
npm run dev
```

3. Install and run the Client application:
```bash
cd ../client
npm install
npm run dev
```

4. Install and run the Admin panel:
```bash
cd ../admin
npm install
npm run dev
```

### Environment Setup

Create a `.env` file in the api directory:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5000
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
```

## Available Scripts

### API
- `npm run dev`: Development server with auto-reload
- `npm start`: Production server

### Client & Admin
- `npm run dev`: Start development server
- `npm run build`: Production build
- `npm run preview`: Preview production build
- `npm run lint`: Run ESLint
