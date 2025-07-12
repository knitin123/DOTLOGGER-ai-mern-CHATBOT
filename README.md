# 📘 DOTLOGGER – AI-Based Prompt Logger and Analyzer

DOTLOGGER is a full-stack MERN-based web application designed to **log, analyze, and interpret user prompts** using OpenAI’s API. It includes authentication, database logging, and a fast frontend built with Vite.

---

## 🚀 Features

  **Prompt Logger**: Users can input messages which are processed by OpenAI GPT.
  **AI Analysis**: Backend connects to OpenAI API to return intelligent responses.
  **Authentication**: Login/register functionality with JWT.
  **MongoDB Integration**: Prompts and users are securely stored.
   Built for fast local development with Vite + Tailwind.

---

## Tech Stack

| Layer       | Technology               |
|------------|---------------------------|
| Frontend   | React (Vite) + Tailwind CSS |
| Backend    | Node.js + Express         |
| AI         | OpenAI API (GPT)          |
| Database   | MongoDB Atlas             |
| Auth       | JWT (JSON Web Token)      |

---

##   Project Structure
DOTLOGGER-main/
├── backend/ # Express server
│ └── .env # MongoDB & API keys( file added )
├── vite-project-frontend/ # React frontend
│ └── .env # Frontend API URL
├── README.md
