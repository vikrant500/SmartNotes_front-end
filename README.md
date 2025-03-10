# About the Project

Smart Notes was born out of necessity when Samsung and Apple released AI-powered updates to their native note-taking applications, which weren't supported on the Samsung Tab S6 Lite. Instead of missing out on these innovative features, I decided to build a complete solution from scratch. This project demonstrates that cutting-edge AI note-taking capabilities can be implemented on any device through a web application.

## Smart Notes Frontend

This repository contains the frontend for the Smart Notes application, a project inspired by the AI-powered note-taking features introduced by Samsung and Apple. The backend can be found at [SmartNotes_backend](https://github.com/vikrant500/SmartNotes_api?tab=readme-ov-file).

## Local Setup

### Prerequisites
- Node.js and npm
- Git
- Backend repository set up and running

### Installation Steps

1. Clone both repositories in the same parent directory:
   ```bash
   git clone [https://github.com/vikrant500/SmartNotes_front-end.git]
   git clone [https://github.com/vikrant500/SmartNotes_api.git]
   ```
   
   Your directory structure should look like this:
   ```
   parent-directory/
   ├── SmartNotes_frontend/
   └── SmartNotes_backend/
   ```

2. Navigate to the frontend directory:
   ```bash
   cd SmartNotes_frontend
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

## Running the Application

1. Start the frontend:
   ```bash
   npm run dev
   ```

2. Start the backend server (in its directory):
   ```bash
   python3 main.py
   ```

The frontend application will start running on `http://localhost:3000`.

## Features
- Modern, responsive user interface
- Real-time AI-powered note enhancements
- Seamless integration with backend API
- Rich text editing capabilities

## Note
Ensure the backend server is running before starting the frontend application for full functionality.