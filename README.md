# Spotify Clone

A **Spotify Clone** built using React.js, Tailwind CSS, and Node.js. This project allows users to stream music, create playlists, and explore songs with an interface similar to Spotify.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [Project Structure](#project-structure)
- [Setup Instructions](#setup-instructions)

## Features

- **User Authentication**: Secure sign-up and login system.
- **Music Streaming**: Play, pause, and skip songs seamlessly.
- **Search Functionality**: Search for songs, albums, and artists.
- **Playlist Management**: Create, edit, and manage playlists.
- **Responsive UI**: Fully optimized for both desktop and mobile devices.

## Technologies Used

- **Frontend**:
  - React.js - For building the user interface.
  - Tailwind CSS - For modern and responsive styling.
  - Vite - For fast front-end development.
  
- **Backend**:
  - Node.js & Express.js - For handling server-side logic.
  - MongoDB - For storing user and playlist data.
  - Spotify Web API - For fetching music data.

- **Authentication**:
  - JSON Web Tokens (JWT) - For secure user authentication.

## How to Use

1. **Sign Up / Log In**:
   - Create an account or log in with existing credentials.

2. **Browse Music**:
   - Discover new releases and trending playlists.

3. **Search Songs & Artists**:
   - Use the search bar to find specific tracks, albums, or artists.

4. **Play Music**:
   - Click on a song to start streaming. Use controls for play, pause, and skip.

5. **Create and Manage Playlists**:
   - Go to your library to create, edit, and organize your playlists.

## Project Structure

```plaintext
spotify-clone/
├── frontend/           # React-based frontend code
│   ├── src/
│   │   ├── components/ # Reusable UI components
│   │   ├── pages/      # Main pages of the app
│   │   ├── assets/     # Images and icons
│   │   ├── App.js      # Main React component
│   │   └── index.js    # Entry point for React
│   ├── package.json    # Dependencies for frontend
│   ├── tailwind.config.js # Tailwind CSS configuration
│   └── vite.config.js  # Vite configuration

├── backend/            # Node.js backend code
│   ├── models/         # Database models (User, Playlist)
│   ├── routes/         # API routes for authentication and music
│   ├── controllers/    # Business logic for handling requests
│   ├── server.js       # Main Express server setup
│   ├── package.json    # Dependencies for backend
│   └── .env            # Environment variables (API keys, database URI)

├── README.md           # This documentation file
└── .gitignore          # Files to be ignored by Git
```
Setup Instructions:
1.**Clone this repository:**
``git clone https://github.com/Mazussy/Spotify-Clone.git
``
2.**Navigate into the project directory:**
``cd Spotify-Clone
``
3.**Install dependencies for frontend & backend:**
``cd frontend && npm install
cd ../backend && npm install
``
4.**Set up environment variables:**
``SPOTIFY_CLIENT_ID=your_spotify_client_id
SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
``
5.**Run the project:**
``cd backend && npm start
cd frontend && npm run dev
``
