📸 PicPrompt – AI Image Prompt Generator
PicPrompt is a simple full-stack web application where users can upload an image and generate an AI-based prompt or description.
The project contains a React (Vite) frontend and a Node.js + Express backend.

🚀 Features
Upload an image
Generate AI prompt/description
Clean and minimal interface
Organized full-stack folder structure
Easy to run locally

📂 Project Structure
PicPrompt/
│
├── client/                     # React Frontend
│   ├── public/
│   └── src/
│       ├── assets/             # Images, icons
│       ├── components/         # Reusable UI components
│       ├── pages/              # Home, Result, BuyCredit pages
│       ├── App.jsx
│       └── main.jsx
│
├── server/                     # Node.js Backend
│   ├── controllers/
│   ├── routes/
│   ├── utils/
│   └── index.js
│
└── README.md


🛠️ How to Run the Project

▶️ Start the Frontend
cd client
npm install
npm run dev

▶️ Start the Backend
cd server
npm install
npm start

Frontend default URL:
http://localhost:5173
Backend default URL:
http://localhost:5000

🧰 Tech Stack
Frontend: React, Vite, TailwindCSS
Backend: Node.js, Express
Others: Axios, File Upload Handling

📘 Overview
PicPrompt lets users upload an image and instantly receive useful prompts/descriptions powered by AI.
It is easy to extend with additional AI features like captions, tags, or summaries.