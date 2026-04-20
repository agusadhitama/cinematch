# 🎬 CineMatch - What Should I Watch?

> **Mood-based movie & series recommender powered by TMDB API**

![HTML](https://img.shields.io/badge/HTML-5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TMDB](https://img.shields.io/badge/API-TMDB-01B4E4?style=flat-square&logo=themoviedatabase&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-222?style=flat-square&logo=github&logoColor=white)

---

## ✨ About

**CineMatch** is a single-page web app that recommends movies and TV series based on your current mood and preferred genres. No sign-up, no clutter just pick your vibe and get your watchlist for tonight.

Built as a pure **HTML/CSS/JS** project with zero dependencies, fully responsive for both desktop and mobile.

---

## 🚀 Live Demo

👉 **[cinematch.agusadhitama.github.io](https://agusadhitama.github.io/cinematch)**

---

## 📸 Features

- 🎭 **Mood selector** 8 mood options that auto-map to relevant genres
- 🎬 **Genre filter** 12 genres to mix and match
- 📺 **Type toggle** choose Movie only, Series only, or Both
- ⭐ **Rich cards** poster, rating, year, genre tags & overview
- 💡 **"Why Tonight?"** personalized reason per recommendation
- 🌑 **Dark cinematic UI** animated background, grain texture, smooth transitions
- 📱 **Fully responsive** works great on PC and mobile

---

## 🛠️ Tech Stack

| Layer | Tech |
|-------|------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, animations, grid) |
| Logic | Vanilla JavaScript (ES6+) |
| Data | [TMDB API](https://www.themoviedb.org/documentation/api) |
| Font | Bebas Neue + DM Sans (Google Fonts) |
| Deploy | GitHub Pages |

---

## ⚙️ Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/agusadhitama/cinematch.git
cd cinematch
```

### 2. Get a free TMDB API Key
1. Sign up at [themoviedb.org](https://www.themoviedb.org/signup)
2. Go to **Settings → API → Request API Key**
3. Select **Developer** and fill in the form
4. Copy your API key

### 3. Add your API key
Open `index.html` and find this line:
```js
const TMDB_KEY = 'YOUR_TMDB_API_KEY';
```
Replace `YOUR_TMDB_API_KEY` with your actual key.

### 4. Open locally
Just open `index.html` in your browser - no build step, no npm, no config.

---

## 🌐 Deploy to GitHub Pages

```bash
# Initialize and push to GitHub
git init
git add .
git commit -m "🎬 Initial commit - CineMatch"
git remote add origin https://github.com/agusadhitama/cinematch.git
git push -u origin main
```

Then in your GitHub repo:
1. Go to **Settings → Pages**
2. Under **Source**, select **Branch: main**
3. Click **Save**
4. Your site will be live at `https://agusadhitama.github.io/cinematch` 🎉

---

## 📁 Project Structure

```
cinematch/
└── index.html       # Entire app  HTML, CSS, and JS in one file
└── README.md        # You are here
```

---

## 🎨 Design Highlights

- **Color palette** Deep dark background (`#0a0a0f`) with gold (`#e8c547`), coral (`#ff6b6b`), and cyan (`#6be5ff`) accents
- **Typography** Bebas Neue for headlines, DM Sans for body
- **Background** Animated ambient orbs with CSS blur + grain texture overlay
- **Cards** Staggered entrance animation with hover lift effect
- **Layout** CSS Grid, fully fluid from 320px to 4K

---

## 🗺️ Mood → Genre Mapping

| Mood | Mapped Genres |
|------|--------------|
| 😄 Happy | Comedy, Animation, Family |
| 😢 Sad | Drama, Romance |
| ⚡ Excited | Action, Adventure, Sci-Fi |
| 😌 Relaxed | Documentary, History, Music |
| 😐 Bored | Thriller, Mystery, Crime |
| 💕 Romantic | Romance, Comedy |
| 😰 Anxious | Horror, Thriller |
| 🌍 Adventurous | Adventure, Fantasy, Sci-Fi |

---

## 📌 Notes

- This app uses the **TMDB API** but is not endorsed or certified by TMDB.
- API key is used client-side. For production, consider proxying requests through a backend.
- No user data is collected or stored.

---

## 👤 Author

**Agus Satria Adhitama**  
Built with ❤️ - powered by [TMDB API](https://www.themoviedb.org/)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
