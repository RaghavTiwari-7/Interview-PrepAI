AI-Powered Interview Prep App
Overview
This project is a full-stack single-page application (SPA) that simulates job interview preparation using AI. Users can sign up/login, upload their resumes and job descriptions (PDFs), and chat with an AI interviewer that generates relevant questions and evaluates responses against user documents using a Retrieval-Augmented Generation (RAG) approach.

Features
User Authentication with JWT (signup/login).

Secure file upload for resumes and job descriptions with progress bar.

Automatic PDF text extraction, chunking, and vector embedding storage.

AI-powered chat interface that generates interview questions and scores user answers using semantic search.

Responsive, accessible UI developed with React and Tailwind CSS.

Robust backend APIs built with Node.js, Express, and MongoDB Atlas.

File storage integrated with AWS S3 or Cloudinary.

Deployed frontend on Vercel, backend on Render.

Tech Stack
Frontend: React, Tailwind CSS, Axios

Backend: Node.js, Express, JWT Authentication, MongoDB Atlas

AI & NLP: OpenAI API, Embeddings, RAG

File Storage: AWS S3 or Cloudinary

Deployment: Vercel (frontend), Render (backend)
