# 💕 Valentine's Day Surprise for Nyasha

A beautiful, interactive website to ask Nyasha to be your Valentine!

## 🎵 Adding Music

To add the songs, you need to download MP3 files and add them to this repository:

### Option 1: Add MP3 Files (Recommended)

1. **Download the songs as MP3 files:**
   - "You're the One" by Elaine (background music)
   - "She's Mine" by J. Cole (celebration song)

2. **Rename the files:**
   - Rename Elaine's song to: `youre-the-one.mp3`
   - Rename J. Cole's song to: `shes-mine.mp3`

3. **Add them to this folder** (same location as index.html)

4. **Commit and push:**
   ```bash
   git add youre-the-one.mp3 shes-mine.mp3
   git commit -m "Add music files"
   git push
   ```

### Option 2: Use Online MP3 Links

If you have direct MP3 URLs from a hosting service:

1. Open `index.html`
2. Replace the `src` attributes:
   ```html
   <!-- Background Music -->
   <audio id="bgMusic" loop>
       <source src="YOUR_DIRECT_MP3_URL_HERE" type="audio/mpeg">
   </audio>

   <!-- Celebration Song -->
   <audio id="celebrationSong">
       <source src="YOUR_DIRECT_MP3_URL_HERE" type="audio/mpeg">
   </audio>
   ```

### Option 3: Use a Music Service

You can use services like:
- **SoundCloud**: Upload the songs and get embed links
- **Dropbox**: Upload and create direct download links
- **Google Drive**: Upload and create shareable links

## 🚀 Deployment

1. Push your code to GitHub
2. Enable GitHub Pages in Settings → Pages
3. Your site will be live at: `https://nokuudinge.github.io/Valentino-Cappuccinoo/`

## ✨ Features

- Modern glassmorphism design
- Animated gradient backgrounds
- Love meter that fills to 100%
- Floating hearts and rose petals
- Interactive "No" button that runs away
- Epic celebration with confetti when she says "Yes"
- Fully responsive for mobile and desktop
- Custom fonts and smooth animations

## 💡 Tips

- Test the website on your phone before sharing
- Make sure the music files are not too large (under 10MB each)
- The music only plays after user interaction (browser security)
- The "No" button is designed to be nearly impossible to click!

## 🎯 Made with love for Nyasha 💕
