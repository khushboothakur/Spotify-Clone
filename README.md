# 🎵 Spotify Clone – Web Player
 
A front-end clone of the **Spotify Web Player** built using HTML5 and CSS3, replicating Spotify's iconic dark-themed UI with a sidebar, music cards, and a bottom music player bar.
 
---
 
## 📌 About the Project
 
This project recreates the look and feel of Spotify's web player interface. It includes a fully structured layout with a navigation sidebar, browsable music card sections, and a functional-looking music player bar at the bottom — all built using pure HTML and CSS, without any JavaScript framework.
 
---
 
## 🖥️ Tech Stack
 
| Technology | Usage |
|------------|-------|
| HTML5 | Page structure and layout |
| CSS3 | Styling, Flexbox layout, responsiveness |
| Font Awesome 7 | Icons (home, search, player controls, etc.) |
| Google Fonts – Montserrat | Typography |
 
---
 
## ✨ Features
 
### 🗂️ Sidebar
- **Home** and **Search** navigation links
- **Your Library** section with:
  - "Create your first playlist" prompt card
  - "Browse podcasts" prompt card
  - Plus (+) and arrow icons for quick actions
### 🔝 Sticky Top Navigation
- Back/Forward chevron navigation arrows
- **Explore Premium** button (hidden on smaller screens)
- **Install App** button
- User profile icon
### 🎴 Music Card Sections
- **Recently Played** — 1 card
- **Trending Now Near You** — 4 cards
- **Featured Cards** — 3 cards
- Each card has: album art image, track title, and description text
### ▶️ Bottom Music Player (Fixed)
- **Left** — Album thumbnail, song title (*Daylight*), artist name (*David Kushner*), heart & wallet icons
- **Center** — 5 playback control icons (shuffle, previous, play/pause, next, repeat) + seekbar with current/total time
- **Right** — Queue, lyrics, microphone, volume icons + volume slider
### 📱 Responsive Design
- "Explore Premium" button hides on screens ≤ 990px
- Forward arrow hides on screens ≤ 1000px
---
 
## 📁 Project Structure
 
```
spotify-clone/
│
├── index.html              # Main HTML file
├── style.css               # CSS stylesheet
├── logo.png                # Favicon
├── library_icon.png        # Library section icon
├── player_icon1.png        # Shuffle icon
├── player_icon2.png        # Previous track icon
├── player_icon3.png        # Play/Pause icon (center, larger)
├── player_icon4.png        # Next track icon
├── player_icon5.png        # Repeat icon
├── card1img.jpeg           # Album art (Recently Played + Player)
├── card2img.jpeg           # Trending card
├── card3img.jpeg           # Trending card
├── card4img.jpeg           # Trending card
├── card5img.jpeg           # Trending + Featured card
└── card6img.jpeg           # Featured card
```
 
---
 
## 🎨 Design Highlights
 
- **Color Scheme:** Pure black (`#000`) background, dark panels (`#121212`), card backgrounds (`#232323`)
- **Font:** Montserrat (Google Fonts) throughout
- **Layout:** Flexbox used for sidebar, cards, player, and all inner components
- **Cards:** Wrap on smaller screens using `flex-wrap`
- **Music Player:** `position: fixed` at bottom, always visible
- **Sticky Navbar:** Stays at top of scrollable content using `position: sticky`
- **Hover Effects:** Opacity transitions on nav links, icons, and player controls
---
 
## 🚀 How to Run
 
No setup or installation needed!
 
1. Clone or download this repository
2. Make sure all image files are in the same folder as `index.html`
3. Open `index.html` in any browser
```bash
git clone https://github.com/your-username/spotify-clone.git
cd spotify-clone
open index.html
```
 
---
 
## 📸 Screenshots
 
> *(Add a screenshot of your project here)*
> `<img width="1920" height="1080" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/0394453c-67d5-43d2-9d1f-44bf7bcbe654" />
> <img width="1920" height="1080" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/bd4b60ce-2db6-4981-bf99-f2327f518046" />

`
 
---
 
## 🙋‍♀️ Author
 
**Khushboo**
- BTech Student | Frontend Developer in the making
- GitHub: [@khushboothakur](https://github.com/khushboothakur)
---
 
## 📝 Disclaimer
 
This project is built purely for **educational and learning purposes**.  
Spotify's name, logo, and design are trademarks of **Spotify AB** and are not affiliated with this project.
 
