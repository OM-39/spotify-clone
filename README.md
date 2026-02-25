# 🎵 Spotify Clone

A pixel-perfect **Spotify Web Player UI clone** built from scratch using pure **HTML** and **CSS**. This project replicates the core visual layout and design of Spotify's web player, including the sidebar, content area, music cards, and the bottom music player bar.

---

## 📸 Features

- **Sidebar Navigation** — Home and Search links with a "Your Library" section including playlist and podcast prompts
- **Sticky Top Navigation Bar** — Back/forward controls, "Explore Premium" and "Install App" buttons
- **Music Cards** — Responsive card grid layout for Recently Played, Trending, and Featured Charts sections
- **Bottom Music Player Bar** — Album art, song info, playback controls with progress bar, and volume slider
- **Responsive Design** — Hides certain elements on smaller screens using media queries
- **Google Fonts** — Uses the *Montserrat* typeface for clean, modern typography
- **Font Awesome Icons** — Integrated for UI icons throughout the app

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Page structure and layout |
| **CSS3** | Styling, flexbox layout, media queries |
| **Font Awesome 7** | Icons (nav, player, controls) |
| **Google Fonts** | Montserrat typeface |

---

## 📁 Project Structure

```
spotify-clone/
│
├── index.html          # Main HTML file
├── style.css           # All styles
│
└── assets/
    ├── logo.png
    ├── album-img-1.jpg
    ├── backward_icon.png
    ├── forward_icon.png
    ├── library_icon.png
    ├── tab-album-icon.png
    ├── play_musicbar.png
    ├── player_icon1.png
    ├── player_icon2.png
    ├── player_icon3.png
    ├── player_icon4.png
    ├── player_icon5.png
    ├── card1img.jpeg
    ├── card2img.jpeg
    ├── card3img.jpeg
    ├── card4img.jpeg
    ├── card5img.jpeg
    └── card6img.jpeg
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/OM-39/spotify-clone.git
```

### 2. Navigate into the project folder

```bash
cd spotify-clone
```

### 3. Open in browser

Simply open `index.html` in any modern web browser — no build tools or dependencies required!

```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

---

## 📱 Responsive Behavior

- On screens **wider than 1000px**: All navigation elements and forward button are visible
- On screens **narrower than 1000px**: Certain elements (like "Explore Premium" button and forward icon) are hidden using a `.hide` class

---

## 🎨 UI Sections

### Sidebar
- Nav links: Home, Search
- Your Library with "Create Playlist" and "Browse Podcasts" prompts

### Main Content
- **Recently Played** — Single featured card
- **Trending Now Near You** — Multi-card horizontal scroll section
- **Featured Charts** — Top Songs Global & India

### Music Player (Bottom Bar)
- Album art + song title + artist name
- Player controls: Shuffle, Previous, Play/Pause, Next, Repeat
- Playback progress bar with timestamps
- Volume control slider

---

## 🙌 Acknowledgements

- Inspired by [Spotify Web Player](https://open.spotify.com)
- Icons by [Font Awesome](https://fontawesome.com)
- Fonts by [Google Fonts](https://fonts.google.com)

---

## 📄 License

This project is for **educational purposes only** and is not affiliated with or endorsed by Spotify AB.

---

> Made with ❤️ as a front-end practice project
