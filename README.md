# Gogrify 🎧 | A Spotify-Inspired Personal Portfolio

Welcome to **Gogrify**, a highly interactive, custom-built personal portfolio designed to mimic the aesthetic, UI, and functionality of the Spotify Web Player. 

Instead of a standard grid layout, my projects, skills, and background are presented as "Playlists," "Tracks," and "Albums," complete with a working custom audio player and native app micro-interactions.

### 🌐 Live Demo
**[Experience the live portfolio here](https://shivam-2811.github.io/personal-portfolio/)**

---

## ✨ Key Features

*   🎵 **Custom Audio Player:** A fully functional bottom player bar with custom tracks for different pages (`ipl_song.mp3`, `markov_song.mp3`). Features include Play/Pause toggling, a scrubbable progress bar, volume control, and Spacebar keybind support.
*   🗂️ **Playlist-Style Project Routing:** Projects are listed as "tracks" on the main profile. Clicking a project navigates to a dedicated "Album" page (e.g., *IPL Analytics*, *Musical Markov Chain*) featuring detailed tech stacks, custom skill icons, and GitHub repository links.
*   🖱️ **Native App Micro-Interactions:** 
    *   Interactive **Heart (♡ to ♥)** toggle buttons.
    *   Working **Three-dots (•••)** dropdown menus with a functional "Share" button that copies the live page URL to the clipboard.
    *   "Follow" button toggles.
    *   Interactive skill/hobby pill tags.
*   🕒 **Dynamic Time-Based Greeting:** The header automatically updates to say "Good morning," "Good afternoon," or "Good evening" based on the user's local system time.
*   📱 **Fully Responsive Layout:** Custom CSS Flexbox rules ensure the UI scales perfectly from ultra-wide desktop monitors down to mobile phone screens without horizontal scrolling issues, dynamically hiding/showing columns just like the native mobile app.

---

## 🛠️ Tech Stack

This project was built entirely from scratch without the use of external front-end frameworks or libraries. 

*   **HTML5:** Semantic structure and layout.
*   **CSS3:** Advanced Flexbox/Grid layouts, custom Spotify-themed scrollbars, gradients, absolute positioning, and responsive media queries.
*   **Vanilla JavaScript (ES6+):** Audio element manipulation, DOM manipulation, event listeners, clipboard API integration, and dynamic logic.
*   **Hosting:** GitHub Pages

---

## 📁 Repository Structure

```text
📂 personal-portfolio/
├── 📄 index.html                  # Main profile page (The "Artist" profile)
├── 📄 ipl-project.html            # Dedicated project page for IPL Analytics
├── 📄 markov-project.html         # Dedicated project page for Musical Markov Chain
├── 📄 style.css                   # Global stylesheet containing all custom UI/UX styling
│
├── 🎵 Audio Assets/
│   ├── song.mp3 / song1-3.mp3     # Main portfolio background tracks
│   ├── ipl_song.mp3               # Theme track for IPL Analytics project
│   └── markov_song.mp3            # Theme track for Markov Chain project
│
└── 🖼️ Visual Assets/
    ├── SHIVAM.jpg                 # Profile picture / Artist Avatar
    ├── ipl_profile.jpg            # IPL Project Album Art
    ├── music_markov.jpg           # Markov Project Album Art
    └── (Various custom icons)     # sql_emoji, python, chains, data_cleaning, model, etc.
