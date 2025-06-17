# 🎬 Movie Finder

Movie Finder is a modern React-based application built with Vite. It allows users to browse popular movies, search for specific titles, and save favourite movies. It uses clean, responsive design and organizes logic using components, contexts, and modular CSS.

---

## 🚀 Features

- 🔍 **Search Movies**: Instantly fetch movies based on your query.
- 🌟 **Popular Movies**: Loads trending movies on startup.
- ❤️ **Favourites**: Add and view your favourite movies.
- 🧠 **Context API**: Manage global favourite state.
- ⚡ **Fast & Responsive UI**: Built with Vite and modular CSS.

---


## 🖼️ Preview

<div align="center">
  <img src="https://github.com/user-attachments/assets/7f4aeab4-8f01-4842-b322-9fe06375ab08" alt="Preview 1" width="100%" />
  <br /><br />
  <img src="https://github.com/user-attachments/assets/42a44ad1-91d4-4ac7-bfa8-cad38af7ee8f" alt="Preview 2" width="100%" />
  <br /><br />
  <img src="https://github.com/user-attachments/assets/b4db70cb-fc6f-4fc9-bebf-6edbc22c37bf" alt="Preview 3" width="100%" />
</div>


---

## 🛠️ Project Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/movie-finder.git
cd movie-finder
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Add Environment Variable

Create a `.env` file in the root directory:

```env
VITE_API_KEY=your_api_key_here
```

> 💡 Replace `your_api_key_here` with your TMDB or OMDB API key.

### 4. Start the Development Server

```bash
npm run dev
```

---

## 📁 Folder Structure

```
movie-finder/
│
├── public/
├── src/
│   ├── assets/               # Images or logos
│   ├── components/           # Reusable components (MovieCard, NavBar)
│   ├── contexts/             # MovieContext for managing favourites
│   ├── css/                  # Modular CSS files
│   │   ├── App.css
│   │   ├── Favourites.css
│   │   ├── Home.css
│   │   └── index.css
│   ├── pages/                # Page components (Home, Favourites)
│   ├── services/             # API functions
│   ├── App.jsx               # Root component
│   ├── main.jsx              # Vite entry file
│
├── .env                      # API key (gitignored)
├── .gitignore
├── index.html
├── vite.config.js
├── package.json
└── README.md
```

---

## 🔧 API Setup

Make sure you’re using the correct API call format in `services/api.js` with the key accessed like this:

```js
const API_KEY = import.meta.env.VITE_API_KEY;
```

---

## 📌 Planned Improvements

- Add localStorage support for favourites
- Movie detail modal or page
- Improved error and loading states
- Pagination or infinite scroll

---

## 🧪 Tech Stack

- ⚛️ React (with Hooks & Context API)
- ⚡ Vite
- 🎨 CSS Modules
- 📦 Fetch for API calls

---

## 🙌 Acknowledgements

- Movie data provided by [TMDB](https://www.themoviedb.org/)
- Project inspired by modern movie apps and UIs

---

## 👨‍💻 Author

**Kaviselvan SJ**  
<a href="https://github.com/Kaviselvan-SJ" target="_blank">GitHub</a> • 
<a href="https://linkedin.com/in/kaviselvan-sj" target="_blank">LinkedIn</a>

