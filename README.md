# Smart Notes

Smart Notes is a full-stack collaborative note-taking application built with React, TypeScript, Node.js, Express, and Firebase. It allows users to create rich-text notes, collaborate in real time, share notes with permissions, and get AI-assisted writing suggestions.

## Features

- Rich-text note editing
- Real-time collaboration with Socket.io
- Secure Google sign-in with Firebase Authentication
- Note sharing with role-based permissions:
  - read
  - write
  - admin
- AI-powered suggestions, completions, title generation, and content analysis using Google Gemini
- Firestore-based storage
- Email notifications for shared notes and welcome messages
- Responsive UI built with Material UI

## Tech Stack

### Frontend
- React 19
- TypeScript
- Material UI
- Draft.js / React Quill
- Firebase Client SDK
- Socket.io Client
- React Router

### Backend
- Node.js
- Express.js
- Firebase Admin SDK
- Firestore
- Socket.io
- JWT-based authentication
- Nodemailer for email notifications

## Project Structure

```text
Smart Notes/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── .env
│   ├── package.json
│   ├── server.js
│   └── serviceAccountKey.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── .env
│   ├── package.json
│   └── tsconfig.json
│
├── README.md
└── .gitignore
