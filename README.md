## 🚀 Live Demo

🔗 **Live Demo:** [https://lithish-s.github.io/CodeAlpha_MusicPlayer/](https://lithish-s.github.io/CodeAlpha_Musicplayer/)

## 📋 Task Requirements Met

# 🎵 CodeAlpha Music Player

![Music Player](https://img.shields.io/badge/CodeAlpha-Music%20Player-blueviolet)
![HTML5](https://img.shields.io/badge/HTML5-Orange)
![CSS3](https://img.shields.io/badge/CSS3-Blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![Font Awesome](https://img.shields.io/badge/Font%20Awesome-6-teal)
![Audio API](https://img.shields.io/badge/Audio-API-green)

A feature-rich, beautifully designed music player with interactive playlist, volume control, progress bar drag support, keyboard shortcuts, and autoplay functionality. Built with pure HTML, CSS, and JavaScript as part of the CodeAlpha Frontend Development Internship (Task 4).

### ✅ Core Features (100% Complete)
| Feature | Implementation |
|---------|----------------|
| **Music Player Interface** | Clean, modern UI with album art and song info |
| **Audio Controls** | Play, pause, next, previous functionality |
| **Song Metadata** | Title, artist, duration display |
| **Progress Bar** | Visual progress tracking with time display |
| **Volume Control** | Adjustable volume with visual feedback |
| **Responsive Design** | Desktop, tablet, and mobile optimized |

### ✅ Bonus Features (100% Complete)
| Bonus Feature | Implementation |
|---------------|----------------|
| **Interactive Playlist** | Click any song to play, active track highlighting |
| **Drag Support** | Click and drag on progress bar AND volume bar |
| **Keyboard Shortcuts** | Space, Arrow Left/Right, Arrow Up/Down |
| **Autoplay Mode** | Automatically play next song when enabled |
| **Now Playing Indicator** | Visual icon showing currently playing track |
| **Pulse Animation** | Animated album art while playing |
| **Smooth Transitions** | Hover effects, scale animations, transform effects |

## ✨ Key Features

### 🎯 Playback Controls
- **Play/Pause** – Toggle music playback with central button
- **Navigation** – Previous/Next buttons with playlist looping
- **Current Time** – Real-time progress tracking
- **Duration Display** – Total song length shown

### 🎚️ Advanced Progress Bar
- **Click to Seek** – Jump to any position in the song
- **Drag to Scrub** – Click and drag for precise positioning
- **Smooth Updates** – 0.1s linear transition for fluid movement
- **Visual Handle** – Shows draggable indicator on hover

### 🔊 Volume Management
- **Click to Set** – Click anywhere on volume bar
- **Drag to Adjust** – Fine-tune volume with drag support
- **Percentage Display** – Shows current volume level
- **Dynamic Icons** – Changes icon based on volume level:
  - 🔇 Volume mute (0%)
  - 🔉 Volume down (1-49%)
  - 🔊 Volume up (50-100%)

### 📑 Interactive Playlist
| Song | Artist | Duration |
|------|--------|----------|
| Blinding Lights | The Weeknd | 3:20 |
| Shape of You | Ed Sheeran | 3:54 |
| Dance Monkey | Tones and I | 3:29 |
| Someone Like You | Adele | 4:45 |
| Uptown Funk | Bruno Mars | 4:30 |
| Perfect | Ed Sheeran | 4:23 |

**Playlist Features:**
- Click any song to play immediately
- Active song highlighted with gradient background
- "Now Playing" volume icon indicator
- Hover animation with translateX effect
- Smooth scrolling for many songs

### ⌨️ Full Keyboard Support
| Key | Action |
|-----|--------|
| `Space` | Play/Pause |
| `←` | Previous song |
| `→` | Next song |
| `↑` | Volume up (+10%) |
| `↓` | Volume down (-10%) |

### 🔄 Autoplay Mode
- Toggle switch in player interface
- When enabled: automatically plays next song
- When disabled: stops at end of current song
- Visual checkbox with smooth styling

## 💻 Technologies Used

| Technology | Purpose | Key Features |
|------------|---------|--------------|
| **HTML5** | Structure | Audio element, semantic layout |
| **CSS3** | Styling | Grid, Flexbox, animations, keyframes |
| **JavaScript ES6+** | Logic | Audio API, event listeners, DOM manipulation |
| **Font Awesome 6** | Icons | Playback controls, volume, playlist |

## 📱 Responsive Breakpoints

| Device | Layout | Album Art | Controls |
|--------|--------|-----------|----------|
| Desktop (>900px) | 2-column (player + playlist) | 200px | Full size |
| Tablet (480-900px) | 1-column | 180px | Compact |
| Mobile (<480px) | 1-column stacked | 150px | Smaller buttons |

## 🎮 How to Use

### 📖 Basic Usage
```javascript
// Play a song
1. Click any song in the playlist
2. OR click Play button to start current song
3. Use Previous/Next to navigate

// Control playback
Click Play/Pause button OR press Space bar
Click Previous/Next OR press ←/→ arrows

// Adjust volume
Click volume bar OR press ↑/↓ arrows
Drag volume handle for precise control

// Seek in song
Click progress bar OR drag handle
Watch current time update in real-time
