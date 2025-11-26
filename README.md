OMDB Movie Explorer

A full-stack application that allows users to search movies, view details, and explore information from the OMDB API.
The project includes:

A Node.js REST API backend (with caching)

A React frontend UI

Runs fully locally

Follows REST & best practices

 Features
Backend (Web Service API)

Fetches movie data from the public OMDB API

Exposes simplified REST endpoints for the frontend

Implements in-memory caching (LRU / expiry)

Secure handling of OMDB API Key via environment variables

Clean folder structure: routes/, controllers/, utils/, cache/

Runs using Node.js & Express

Frontend (UI Layer)

Movie search dashboard

Results grid with posters, titles, and release year

Detailed movie info page:

Plot, Director, Actors, Ratings, etc.

Optional: Add/remove favorites (stored locally)

Fully responsive (mobile → desktop)

Built with React + Tailwind / CSS

Tech Stack
Backend

Node.js

Express.js

Axios

LRU / custom cache

dotenv

Frontend

React

Fetch API / Axios

Vanilla CSS or TailwindCSS
