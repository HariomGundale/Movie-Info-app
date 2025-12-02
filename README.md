# 🎬 Movie Info App

A clean and simple React application that allows users to search for movies and view detailed information using the OMDb API.

---

## 🚀 Features

- 🔍 Search movies by title

- 🎞️ View poster, title, year, and type

- 📄 Click a movie card to open detailed info

- ⚡ Fast and responsive UI

- 🧩 Component-based architecture

- 🔐 API key security using .env file

---

## 🛠️ Tech Stack

- React JS

- Axios / Fetch API

- OMDb API

- HTML / CSS / JavaScript

---

## 📦 Install & Run Locally

```bash
# Clone the repository
git clone https://github.com/HariomGundale/Movie-Info-app.git

# Navigate into project 
cd Movie-Info-app

#Install dependencies
npm install

```

## 🔐 Setting Up the API Key (VERY IMPORTANT)

This app requires an OMDb API key.

Step 1 — Get your free API key

Visit: https://www.omdbapi.com/apikey.aspx

Choose "Free Key", enter your email, and get your API KEY.

Step 2 — Create .env file in project root

Movie-Info-app/.env

Add your key:
REACT_APP_API_KEY=your_api_key_here

Step 3 — Restart the React server

React does not auto-load .env, so run:

npm start

---

## ▶️ Run the Project

```bash

npm start

```

Your app opens at:

👉 http://localhost:3000

---

## 📁 Project Structure

```plaintext

Movie-Info-app/
│
├── public/
│   ├── index.html
│   ├── movie-icon.svg
│   ├── search-icon.svg
│   └── ...
│
├── src/
│   ├── Components/
│   │   ├── MovieComponent.js
│   │   └── MovieInfoComponent.js
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── index.css
│
├── .gitignore
├── package.json
├── README.md
└── .env (ignored)


```

##  🧑‍💻 Author

Hariom Gundale