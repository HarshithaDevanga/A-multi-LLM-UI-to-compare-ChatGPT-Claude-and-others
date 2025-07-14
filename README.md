# A-multi-LLM-UI-to-compare-ChatGPT-Claude-and-others
LLM Comparison Tool is a full-stack web app that compares AI responses from ChatGPT (GPT-4o) and Claude AI side-by-side. Built with React, Tailwind CSS, Node.js, and Express.js, it enables real-time prompt testing and performance evaluation for developers and researchers.
# Multi-LLM Comparison Tool

This project is a full-stack web application that allows users to input a single prompt and compare the real-time responses from multiple Large Language Models (LLMs), specifically ChatGPT (GPT-4o) and Claude (simulated).

## Overview

The tool is designed for prompt testing, evaluation, and performance comparison of multiple AI models in a clean and responsive user interface. It highlights differences in tone, content, and speed between models, helping users determine which LLM is best suited for their use case.

## Features

- Accepts one prompt from the user
- Sends the prompt to two different LLMs (ChatGPT and Claude)
- Displays responses side by side
- Shows loading states for each model
- Responsive and clean UI built with Tailwind CSS
- Backend API routing using Node.js and Express
- Can be deployed using Vercel (frontend) and Railway (backend)

## Tech Stack

| Layer     | Technology                         |
|-----------|-------------------------------------|
| Frontend  | React.js, Vite, Tailwind CSS        |
| Backend   | Node.js, Express                    |
| APIs      | OpenAI (GPT-4o), Claude (simulated) |
| Deployment| GitHub, Vercel, Railway             |

## Folder Structure

llm-comparison-tool/
├── client/ # React frontend
│ ├── src/ # Frontend source files
│ │ ├── App.jsx # Main component
│ │ ├── main.jsx # App entry point
│ │ └── index.css # Global styles
│ └── public/ # Static assets
├── server/ # Express backend
│ ├── index.js # API logic
│ └── .env # Environment variables
├── README.md # Project documentation

## Getting Started

### Prerequisites

- Node.js and npm installed
- Git installed
- OpenAI API Key

### Local Setup Instructions

1. Clone the repository
   ```bash
   git clone https://github.com/HarshithaDevanga/A-multi-LLM-UI-to-compare-ChatGPT-Claude-and-others.git
   cd llm-comparison-tool
Install backend dependencies

bash
Copy
Edit
cd server
npm install
Add your OpenAI API key in server/.env

env
Copy
Edit
OPENAI_API_KEY=your_openai_key_here
Start the backend server

bash
Copy
Edit
node index.js
Install frontend dependencies

bash
Copy
Edit
cd ../client
npm install
Run the frontend development server

bash
Copy
Edit
npm run dev
Open the application in the browser at http://localhost:5173

Deployment
Frontend: Can be deployed using Vercel

Backend: Can be deployed using Railway

Future Improvements
Add support for Claude API and DeepSeek

Implement token usage tracking and model evaluation scores

Enhance UI/UX with additional customization options

Add logging and error handling in backend

Author
Harshitha D G
AI Software Engineer Intern | Full Stack Developer
https://github.com/HarshithaDevanga
