# 🎵 Spotify Web Player Clone

A responsive **Spotify-inspired Web Player UI** built using **HTML5 and CSS3**.
This project recreates the visual layout of Spotify's web player, including the sidebar, music library, playlists, content cards, navigation bar, and bottom music player.

> **Note:** This is a frontend UI project for learning and practice. It does not currently include real music playback, authentication, or Spotify API integration.

---

## 📸 Project Overview

The project includes a dark-themed music streaming interface inspired by Spotify's Web Player.

### Main Sections

* 🏠 Home & Search navigation
* 📚 Your Library section
* 🎵 Playlist creation cards
* 🎙️ Podcast discovery section
* 🔥 Recently Played
* 📈 Trending music cards
* 📊 Featured Charts
* 🎧 Bottom music player
* ⏯️ Player controls
* 🔊 Volume/control section
* 📱 Basic responsive behavior

---

## 🛠️ Technologies Used

* **HTML5** — Structure and semantic content
* **CSS3** — Layout, styling, responsiveness, and UI design
* **Flexbox** — Page and component layouts
* **CSS Media Queries** — Responsive behavior
* **Font Awesome** — Navigation and interface icons
* **Google Fonts** — Montserrat, Inter, Lato, and Roboto

---

## 📂 Project Structure

```text
Spotify-Web-Player/
│
├── index.html
├── style.css
│
├── assets/
│   ├── album_picture.jpeg
│   ├── album_icon1.png
│   ├── album_icon2.png
│   ├── backward_icon.png
│   ├── forward_icon.png
│   ├── library_icon.png
│   ├── player_icon1.png
│   ├── player_icon2.png
│   ├── player_icon3.png
│   ├── player_icon4.png
│   ├── player_icon5.png
│   ├── controls_icon1.png
│   └── ...
│
└── README.md
```

---

## ✨ Features

### Sidebar

The sidebar contains:

* Home
* Search
* Library
* Create Playlist
* Browse Podcasts

### Main Content

The main content area contains different music sections:

* Recently Played
* Trending Now Near You
* Featured Charts

Music cards contain:

* Album artwork
* Playlist title
* Description

### Music Player

The bottom player contains:

* Current song information
* Album artwork
* Artist name
* Previous/next controls
* Play/pause control
* Progress bar
* Volume and additional controls

---

## 📱 Responsive Design

The project uses CSS media queries to adjust certain navigation elements on smaller screens.

For example:

```css
@media(max-width:1000px){
    .hide{
        display: none;
    }
}
```

This hides selected navigation elements when the viewport becomes smaller.

---

## 🎨 UI Design

The project follows a dark Spotify-inspired color scheme:

* Black background
* Dark gray content areas
* White typography
* Green progress indicator
* Rounded cards and buttons

The layout primarily uses **CSS Flexbox** for positioning and alignment.

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Open the project

Navigate into the project folder:

```bash
cd YOUR-REPOSITORY
```

### 3. Run the project

Open `index.html` in your browser.

You can also use **VS Code with Live Server** for easier development.

---

## 🎯 Learning Objectives

This project was created to practice:

* HTML page structure
* CSS Flexbox
* Responsive layouts
* CSS positioning
* Sticky navigation
* Fixed elements
* Custom range sliders
* Card-based layouts
* Dark UI design
* Using external fonts
* Using Font Awesome icons
* Organizing frontend assets

---

## 🔮 Future Improvements

Possible future upgrades include:

* [ ] Add JavaScript functionality
* [ ] Implement actual music playback
* [ ] Make the progress bar functional
* [ ] Add volume control functionality
* [ ] Add working navigation
* [ ] Add playlist creation
* [ ] Add search functionality
* [ ] Add responsive mobile sidebar
* [ ] Add song data dynamically
* [ ] Connect a backend
* [ ] Integrate a music API

---

## ⚠️ Disclaimer

This project is an **educational frontend recreation inspired by Spotify's user interface**.

It is not affiliated with or endorsed by Spotify.

All trademarks and original assets belong to their respective owners.

---

## 👨‍💻 Author

**Irbaz Abid**

BS Computer Science Student | Aspiring Full-Stack Developer

Interested in:

* 🌐 Full-Stack Web Development
* 💻 Software Engineering
* 🐍 Python
* ⚛️ React
* 🗄️ Databases
* 🧠 Data Structures & Algorithms

---

## ⭐ Support

If you found this project useful for learning frontend development, consider giving the repository a ⭐.
