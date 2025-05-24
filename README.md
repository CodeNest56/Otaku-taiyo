# Otaku-taiyo

**Otaku-taiyo** is a fan-driven, anime-themed web platform designed to bring together anime lovers through an immersive and interactive experience. Built with HTML, CSS, and JavaScript, it features a fully static yet dynamic-feeling user interface inspired by platforms like Crunchyroll and Anime World.

---

## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Future Plans](#future-plans)
- [Contributing](#contributing)
- [License](#license)

---

## About the Project

**Otaku-taiyo** is built for anime fans who want a clean, responsive, and engaging place to explore anime, manga, music, and chat with friends. The platform operates entirely in the browser using local storage for user data and requires no server or database.

---

## Features

- **User Authentication**
  - Local signup and login with email/username and password
  - 4-digit PIN verification system for additional security

- **Anime & Manga Browsing**
  - Explore different titles with visuals and details
  - Future updates may include ratings, reviews, and bookmarking

- **Anime Music Streaming**
  - Play anime soundtracks in-browser with themed UI

- **Chat System**
  - Local chat interface to interact with other users (peer-to-peer)

- **Search Bar**
  - Search for anime, manga, songs, and user profiles across all pages

- **Modern Design**
  - Inspired by popular anime platforms
  - Responsive layout for mobile and desktop

---

## Getting Started

1. **Download or Clone the Repository**2. **Open the Project Locally**  
Simply open `index.html` in any modern browser — no server or installation required.

---

## Project Structure

```plaintext
Otaku-taiyo/
│
├── index.html            # Landing page
├── login.html            # Login interface
├── signup.html           # Signup with PIN verification
├── dashboard.html        # Main user area after login
├── anime.html            # Anime listings
├── manga.html            # Manga listings
├── songs.html            # Music player page
├── chat.html             # Chat interface
│
├── css/
│   └── style.css         # Main stylesheet
│
├── js/
│   ├── auth.js           # Handles login/signup logic
│   ├── search.js         # Search functionality
│   └── ui.js             # UI interactions and events
│
└── assets/
 ├── images/           # Anime/manga thumbnails and icons
 └── music/            # Audio files for streaming
