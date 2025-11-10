# Apocalypse Radio - Mobile Web App

A post-apocalyptic radio station simulator optimized for mobile devices. Experience immersive audio with realistic station switching, track progression, and off-air periods between episodes.

## Features

- 📱 **Mobile-Optimized**: Responsive design that works perfectly on phones
- 🎵 **Multiple Stations**: 9 different radio stations with unique content
- ⏸️ **Pause/Resume**: Click stations to pause/resume exactly where you left off
- 📻 **Realistic Experience**: 20-minute gaps between episodes like real radio
- 🎮 **Gaming Controls**: Keyboard shortcuts and touch-friendly interface
- 💾 **State Persistence**: Automatically saves your progress
- 🔋 **PWA Ready**: Install as a native app on your phone

## Installation as Phone App

### Method 1: Direct Installation from Browser
1. Open `radio_mobile.html` in your phone's browser
2. Look for "Add to Home Screen" option in browser menu
3. Follow prompts to install as app

### Method 2: Deploy on GitHub Pages
1. Create a new repository on GitHub
2. Upload these files:
   - `radio_mobile.html` (rename to `index.html`)
   - `manifest.json`
3. Go to repository Settings → Pages
4. Enable GitHub Pages from main branch
5. Visit your GitHub Pages URL on mobile
6. Install as web app using browser menu

## Audio File Structure

Create folders for your radio stations with this structure:
```
88.5-Channel 7/
├── 1.ogg (or 1.mp3)
├── 2.ogg (or 2.mp3)
└── ...

89.6-Lady Luck/
├── 1.ogg (or 1.mp3)
├── 2.ogg (or 2.mp3)
└── ...
```

## Controls

### Touch/Mouse:
- **Power Button**: Turn radio on/off
- **Station Buttons**: Select/pause stations
- **Volume Slider**: Adjust volume
- **Reset Button**: Reset all stations to track 1

### Keyboard Shortcuts:
- **1-9**: Select station number
- **P**: Toggle power
- **M**: Mute/unmute
- **↑/↓**: Volume up/down

## How It Works

1. **Station Selection**: Click any station to start playing from where you left off
2. **Automatic Progression**: When a track ends, station goes off-air for 20 minutes
3. **Track Looping**: After all tracks play, station loops back to track 1
4. **Persistent State**: Your position is saved automatically

## Mobile Optimization Features

- Touch-friendly 48px+ button targets
- Responsive grid layout for station buttons
- Optimized text sizes for mobile screens
- Proper viewport settings for mobile browsers
- PWA manifest for app-like experience
- Battery-friendly design

## Browser Compatibility

- ✅ Chrome/Safari on iOS
- ✅ Chrome on Android
- ✅ Firefox Mobile
- ✅ Edge Mobile

## File Formats Supported

- **OGG Vorbis** (preferred)
- **MP3** (fallback)

The app automatically tries OGG first, then falls back to MP3 if needed.

---

*Built for immersive post-apocalyptic radio experience. Tune in, survivor.*