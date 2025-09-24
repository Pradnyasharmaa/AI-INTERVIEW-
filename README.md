🚀 Seekie – AI Mock Interview App

Welcome to Seekie!
Seekie is a full-stack AI-powered mock interview platform designed to help developers and job seekers practice interviews. It provides AI-driven questions, real-time feedback, and interview history tracking to simulate a realistic hiring experience.

📑 Table of Contents

Overview
Features
Tech Stack
Getting Started
Installation
Usage
Contributing

🔎 Overview

Seekie helps users practice both technical and behavioral interviews in an interactive environment.
Using Gemini AI, it generates custom questions based on user preferences and provides instant feedback. With Clerk authentication and Drizzle ORM, users can securely log in and track their past interviews.

✨ Features

🤖 AI-Generated Questions – Tailored technical and HR questions based on profile and skill set.

🔐 User Authentication – Secure login & signup using Clerk.

⚡ Real-Time Feedback – Get instant AI-powered feedback on your answers.

🎨 Modern UI – Responsive, user-friendly interface built with React + Next.js.

📊 Interview History – Save and revisit your past mock interviews with Drizzle ORM.

🛠 Tech Stack

Next.js
 – Full-stack React framework

React
 – Component-based frontend

Drizzle ORM
 – Database ORM for persistence

Clerk
 – Authentication and user management

Gemini AI
 – AI API for interview Q&A and feedback

Tailwind CSS
 + Shadcn UI – Styling and modern UI components

🚀 Getting Started
Installation

Clone the repository

git clone https://github.com/Pradnyasharmaa/seekie-ai-interview.git
cd seekie-ai-interview


Install dependencies

npm install


Create a .env file in the root with the following variables:

DATABASE_URL=your_database_url

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=your_gemini_api_key


Start development server

npm run dev


The app will run at http://localhost:3000
.

🤝 Contributing

Contributions are welcome!

Fork the repo

Create a feature branch

Make your changes

Submit a pull request 🚀
