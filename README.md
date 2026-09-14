# 🎬 ReelSync

**ReelSync** is a movie and TV discovery/streaming web application focused on a smooth viewing experience with **Burmese (Myanmar) AI-powered subtitles**, live subtitle synchronization, multiple streaming servers, and movie/TV metadata.

🌐 **Live Website:** https://reelsync.up.railway.app/

---

## ✨ Features

### 🎥 Movie & TV Discovery
- Trending movies
- Upcoming releases
- Top-rated movies
- Animation & Anime
- Popular TV series
- Search and discovery
- Genre filtering
- Year filtering
- Sorting options

### 🇲🇲 Burmese AI Subtitles
- Burmese subtitle support
- AI-powered subtitle translation
- Live audio/subtitle synchronization
- Subtitle timing adjustment
- Gemini AI integration
- Optional user-provided Google Gemini API key

### ▶️ Streaming Experience
- Multiple streaming servers
- Server switching when a source is slow or buffering
- Fullscreen playback
- Movie trailer support
- Streaming-focused interface

### 🎞️ Movie Information
Movie pages can provide:
- Release date
- Genre
- Cast
- Director
- Duration
- Country
- Language
- Production information
- Ratings and trailers

Movie and TV metadata are powered by **TMDB**.

### 🛠️ Live Diagnostics
ReelSync includes a live diagnostics/log interface for monitoring:
- General application activity
- Subtitle operations
- Gemini AI operations
- Streaming activity
- Errors

---

## 🤖 Gemini AI Integration

ReelSync can use **Google Gemini API** for Burmese subtitle translation.

Users can enter their own Gemini API key through the subtitle settings interface.

> **Security note:** Never hard-code a private Gemini API key into the frontend or commit API keys to a public GitHub repository. Use environment variables or another secure secret-management solution for production applications.

---

## 🖥️ Main Sections

| Section | Description |
|---|---|
| 🏠 Home | Discover featured and popular content |
| 🔥 Trending | Browse currently trending movies |
| 📅 Upcoming | Discover upcoming releases |
| 🎨 Animation | Animation and anime collection |
| 📺 TV Series | Browse popular TV series |
| ⭐ Top Rated | Discover highly rated movies |
| 🔎 Search | Search and filter movies and TV shows |
| 🎬 Player | Watch content with subtitle features |

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

- 🎬 Modern cinematic UI
- 🇲🇲 Burmese-first subtitle experience
- 🤖 Gemini AI integration
- ⚡ Multiple streaming sources
- 🔄 Live subtitle synchronization
- 🔎 Movie and TV discovery
- 📊 Live diagnostics and logs
- 🎞️ TMDB-powered metadata
- 📱 Designed for a smooth media-consumption experience

---

## ⚠️ Disclaimer

ReelSync does **not host video files on its own servers**.

Movie and TV metadata is provided through TMDB. Streaming content may be provided by external sources, and availability can vary.

Users are responsible for ensuring that their use of external streaming sources and any content they access complies with applicable laws and the terms of those services.

---

## 📚 Data & Services

- **TMDB** — movie, TV, rating, trailer, and cast metadata
- **Google Gemini / Google AI Studio** — AI-powered Burmese subtitle translation
- **External streaming servers** — video playback sources

---

## 📸 Screenshots

Add screenshots of your application here:

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

- [ ] Improved subtitle translation quality
- [ ] Better subtitle timing and synchronization
- [ ] User watch history
- [ ] Favorites / watchlist
- [ ] Continue watching
- [ ] Improved mobile experience
- [ ] More streaming-source management
- [ ] Enhanced TV-series episode navigation
- [ ] Additional subtitle customization
- [ ] Performance and caching improvements

---

## ⭐ Support the Project

If you find ReelSync useful, consider giving the repository a ⭐ on GitHub.

---

## 📄 License

Add your preferred open-source license here.

For example:

```text
MIT License
```

---

## 🔗 Links

- **Live Website:** https://reelsync.up.railway.app/
- **TMDB:** https://www.themoviedb.org/
- **Google AI Studio:** https://aistudio.google.com/
