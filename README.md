# 🎬 MyApp1 - Movie Finder

MyApp1 is a **React-based web application** that allows users to search for movies, view trending movies, and explore detailed movie information. It integrates with **The Movie Database (TMDb) API** and **Appwrite** for backend services.

---

## 🚀 Features

✅ **Search Movies**: Find movies by title using the TMDb API.  
🔥 **Trending Movies**: Explore the most popular movies.  
📌 **Movie Details**: Get ratings, release year, language, and poster.  
📱 **Responsive Design**: Works on both desktop and mobile.  
⏳ **Loading Spinner**: Shows a spinner while fetching data.  
⌛ **Debounced Search**: Reduces API calls by debouncing input.  

---

## 🛠 Tech Stack

- **Frontend**: React, TailwindCSS 🎨
- **Backend**: Appwrite 🛠️
- **Build Tool**: Vite ⚡
- **Linting**: ESLint 📏
- **API**: TMDb API 🎥

---

## 📦 Installation & Setup

### 🔧 Setup Locally

   1. **Clone the repository**:
   git clone https://github.com/anshul-rohilla4/movieDesk.git

   2.cd myapp1

   3.npm i

   4.create .env in root dir
   
    VITE_TMDB_KEY=your_tmdb_api_key
    VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
    VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
    VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
   
   5.npm run dev

   6.Open your browser and navigate to http://localhost:5173
