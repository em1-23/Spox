# 🎵 Spox — Music Web Application

Spox is a feature-rich, web-based music streaming client inspired by modern audio platforms. Built using **React.js** and **LocalStorage**, it provides a smooth music browsing and listening experience with lightweight client-side data persistence.

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![LocalStorage](https://img.shields.io/badge/LocalStorage-FF6B6B?style=for-the-badge&logo=indexeddb&logoColor=white)

---

## 🚀 Features

- 🎨 **Modern UI** — Clean, modern, and fully responsive layout inspired by top music apps.
- 🎧 **Interactive Audio Player** — Play, pause, skip tracks, adjust volume, and control playback seamlessly.
- 💾 **LocalStorage Persistence**
  - Save and manage your favorite tracks in **Liked Songs**.
  - Create, edit, and organize custom user **Playlists**.
  - Persist player settings and user preferences across browser sessions.
- 🔍 **Smart Search** — Quickly filter through tracks, artists, and playlists.
- 📱 **Cross-Device Responsive** — Styled to look great on desktop, tablet, and mobile browsers.

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| **Frontend Framework** | React.js (Hooks & Context API) |
| **Styling** | CSS3 / Tailwind CSS |
| **Icons** | Lucide React / React Icons |
| **Data Persistence** | Web LocalStorage API |

---

## 🤖 Clone & Run

```bash
# Clone the repository
git clone https://github.com/em1-23/Spox.git
```
# Navigate into the project directory
cd spox

# Install dependencies
npm install

# Start the development server
npm start
Note: Make sure you have Node.js installed on your machine.
<h1 align="center">📁 Project Structure</h1>

```bash
plain
 src/
 ├── assets/           # Audio files, icons, and cover artwork
 ├── components/       # UI elements (Player, Sidebar, Header, SongCard, PlaylistModal)
 ├── context/          # React Context API for player state & LocalStorage logic
 ├── data/             # Mock track lists and metadata
 ├── pages/            # Main views (Home, Search, Library, PlaylistView)
 ├── App.js            # Core layout & application routing logic
 └── index.js          # React DOM entry point
```

📄 License & Disclaimer
This project is open-source and created strictly for educational and portfolio purposes.
<p align="center">Made with ❤️ and 🎵</p>
