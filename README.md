# 🎬 ReelSync

**ReelSync** is a movie and TV discovery and streaming web application focused on a smooth viewing experience with **Burmese (Myanmar) AI-powered subtitles**, live subtitle synchronization, multiple streaming servers, and movie/TV metadata.

🌐 **Live Website:** https://reelsync.up.railway.app/

---

## ✨ Features

### 🎥 Movie & TV Discovery

* Trending movies
* Upcoming releases
* Top-rated movies
* Animation & Anime
* Popular TV series
* Search and discovery
* Genre filtering
* Year filtering
* Sorting options

### 🇲🇲 Burmese AI Subtitles

* Burmese subtitle support
* AI-powered subtitle translation
* Live audio/subtitle synchronization
* Subtitle timing adjustment
* Gemini AI integration
* Optional user-provided Google Gemini API key

### ▶️ Streaming Experience

* Multiple streaming servers
* Server switching when a source is slow or buffering
* Fullscreen playback
* Movie trailer support
* Streaming-focused interface

### 🎞️ Movie Information

Movie pages can provide:

* Release date
* Genre
* Cast
* Director
* Duration
* Country
* Language
* Production information
* Ratings and trailers

Movie and TV metadata are powered by **TMDB**.

### 🛠️ Live Diagnostics

ReelSync includes a live diagnostics and logging interface for monitoring:

* General application activity
* Subtitle operations
* Gemini AI operations
* Streaming activity
* Errors

---

## 🤖 Gemini AI Integration

ReelSync can use **Google Gemini API** for Burmese subtitle translation.

Users can enter their own Gemini API key through the subtitle settings interface.

> **Security:** Never hard-code private API keys into the frontend or commit API keys to a public GitHub repository. Use environment variables or another secure secret-management solution for production deployments.

---

## 🖥️ Main Sections

| Section      | Description                           |
| ------------ | ------------------------------------- |
| 🏠 Home      | Discover featured and popular content |
| 🔥 Trending  | Browse currently trending movies      |
| 📅 Upcoming  | Discover upcoming releases            |
| 🎨 Animation | Browse animation and anime content    |
| 📺 TV Series | Browse popular TV series              |
| ⭐ Top Rated  | Discover highly rated movies          |
| 🔎 Search    | Search and filter movies and TV shows |
| 🎬 Player    | Watch content with subtitle features  |

---

## 🌏 Burmese Subtitle Experience

One of the main goals of ReelSync is making international movies and TV series easier to enjoy for Burmese-speaking viewers.

The subtitle workflow is designed around:

```text
Movie / TV Episode
        ↓
Streaming Source
        ↓
Dialogue / Subtitle Processing
        ↓
Gemini AI Translation
        ↓
Burmese Subtitle
        ↓
Audio / Subtitle Synchronization
        ↓
Viewer
```

---

## 🚀 Project Highlights

* 🎬 Modern cinematic UI
* 🇲🇲 Burmese-first subtitle experience
* 🤖 Gemini AI integration
* ⚡ Multiple streaming sources
* 🔄 Live subtitle synchronization
* 🔎 Movie and TV discovery
* 📊 Live diagnostics and logs
* 🎞️ TMDB-powered metadata
* 📱 Smooth media-consumption experience

---

## ⚙️ Technology & Services

ReelSync integrates with several external services to provide its movie data, AI subtitle features, and streaming experience.

### 🎞️ TMDB

TMDB provides movie and TV metadata such as:

* Movie information
* TV series information
* Posters and backdrops
* Genres
* Cast information
* Ratings
* Release information
* Trailers

### 🤖 Google Gemini

Google Gemini is used for AI-powered Burmese subtitle translation.

### ▶️ Streaming Sources

ReelSync supports external streaming sources to provide video playback.

---

## 📸 Screenshots

Screenshots can be added to the repository under:

```text
screenshots/
├── home.png
├── movie-page.png
├── player.png
└── subtitles.png
```

Example:

```md
![ReelSync Home](screenshots/home.png)
```

---

## 🔮 Roadmap

* [ ] Improve Burmese subtitle translation quality
* [ ] Improve subtitle timing and synchronization
* [ ] Add user watch history
* [ ] Add favorites / watchlist
* [ ] Add continue watching
* [ ] Improve mobile experience
* [ ] Improve streaming-source management
* [ ] Improve TV-series episode navigation
* [ ] Add additional subtitle customization
* [ ] Improve performance and caching
* [ ] Add more subtitle languages

---

## ⚠️ Disclaimer

ReelSync does **not host video files on its own servers**.

Movie and TV metadata is provided through TMDB. Video playback may rely on external streaming sources, and availability can vary.

Users are responsible for ensuring that their use of external streaming sources and any content they access complies with applicable laws and the terms of the relevant services.

ReelSync is intended as a media discovery and playback interface and does not claim ownership of third-party content.

---

## 🔗 Links

* 🌐 **Live Website:** https://reelsync.up.railway.app/
* 🎞️ **TMDB:** https://www.themoviedb.org/
* 🤖 **Google AI Studio:** https://aistudio.google.com/

---

## ⭐ Support

If you find ReelSync useful, consider giving the repository a ⭐ on GitHub.

Your support helps the project continue to improve and makes it easier to add new features.

---

## 📄 License

This project is licensed under the **MIT License**.

You are free to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of this software, subject to the terms and conditions of the MIT License.

See the [LICENSE](LICENSE) file for the complete license text.
