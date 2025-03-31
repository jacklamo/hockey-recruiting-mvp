# Hockey Recruiting MVP

## Overview
This project is an **MVP (Minimum Viable Product)** for a **hockey recruiting platform**, allowing players to create profiles, upload game clips, and connect with scouts & coaches. The goal is to provide a streamlined system where athletes can showcase their skills and coaches can easily discover talent.

## Features (MVP Scope)
- **User Authentication** – Players, coaches, and scouts can sign up and log in.
- **Player Profiles** – Players can create a profile with basic info (name, age, position, etc.).
- **Video Upload System** – Players can upload game footage to showcase their skills.
- **Search & Filtering System** – Coaches/scouts can search for players by position, age, and location.
- **Coach/Scout Dashboard** – Allows coaches to view player profiles and videos.

## Tech Stack
### Frontend
- React.js (Next.js for SEO benefits)
- Tailwind CSS (for styling)

### Backend
- Node.js with Express.js (API & server)
- PostgreSQL (or Firebase for fast prototyping)
- JWT-based authentication (JSON Web Tokens)

### Storage & Deployment
- AWS S3 / Firebase Storage (for video uploads)
- Vercel (Frontend hosting)
- Render / Heroku (Backend hosting)
- Supabase (if using PostgreSQL)

## Project Structure
```
/hockey-recruiting-mvp
│── /backend  # Node.js API
│── /frontend  # React.js UI
│── /database  # PostgreSQL schema
│── README.md  # Project documentation
```

## Getting Started
### 1. Clone the Repository
```sh
git clone https://github.com/jacklamo/hockey-recruiting-mvp.git
cd hockey-recruiting-mvp
```

### 2. Install Dependencies
```sh
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
```

### 3. Run the Project
```sh
# Start backend server
cd backend
npm start

# Start frontend development server
cd ../frontend
npm run dev
```

## Future Enhancements
Once the MVP is solid, potential next steps:
- **AI-Generated Highlight Reels**
- **Advanced Performance Metrics & Analytics**
- **Direct Player-Coach Messaging**

## Contributing
Want to help? Feel free to fork this repository and submit pull requests.

## Contact
Reach out for collaboration: **jackwlamothe@gmail.com**
