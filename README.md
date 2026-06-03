# AI Text Summarizer

A full-stack web application that uses AI to automatically summarize articles and text content. Users can submit articles, get AI-powered summaries, and maintain a history of their summarization requests.

## Features

- **User Authentication**: Secure sign-up and login functionality
- **Article Summarization**: AI-powered text summarization engine
- **History Tracking**: Keep track of all summarized articles
- **User Management**: Manage user profiles and preferences
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## Tech Stack

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB 
- **Authentication**: JWT-based authentication

### Frontend
- **Framework**: React with Vite
- **Build Tool**: Vite (fast and lightweight)
- **Styling**: CSS modules
- **Linting**: ESLint

## Project Structure

```
Ai-text-Summarizer/
├── Backend/
│   ├── controller/          # Route handlers
│   ├── middleware/          # Authentication middleware
│   ├── model/               # Database schemas
│   ├── route/               # API routes
│   ├── index.js             # Server entry point
│   └── package.json         # Backend dependencies
└── Frontend/
    ├── src/
    │   ├── components/      # React components
    │   ├── App.jsx          # Main app component
    │   └── main.jsx         # Entry point
    ├── public/              # Static assets
    └── package.json         # Frontend dependencies
```

## Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Backend Setup

1. Navigate to the Backend folder:
   ```bash
   cd Backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file with your configuration:
   ```
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. Start the server:
   ```bash
   npm start
   ```

### Frontend Setup

1. Navigate to the Frontend folder:
   ```bash
   cd Frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## API Endpoints

- **Auth**: `/user/*` - User authentication and management
- **Articles**: `/article/*` - Article submission and retrieval
- **Summaries**: `/summary/*` - Summarization endpoints
- **History**: `/history/*` - User history management

## Usage

1. Create an account or log in
2. Submit an article or text content
3. The AI will process and generate a summary
4. View your summarization history
5. Access previously summarized articles anytime

## Environment Variables

### Backend
- `PORT` - Server port (default: 5000)
- `MONGODB_URI` - MongoDB connection string
- `JWT_SECRET` - JWT secret key for authentication

### Frontend
- Configure API base URL in development/production environments
---
**⭐ If you like this project, consider giving it a star!**


