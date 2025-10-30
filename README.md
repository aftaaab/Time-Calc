# Time Zone Calculator PWA

A mobile-friendly Progressive Web App (PWA) for calculating time differences between Peru, UK, and other countries worldwide.

## Features

✨ **Current Time Display**
- Real-time clock showing time in two selected countries
- Support for 16+ countries including Peru, UK, USA, Spain, Japan, Australia, and more
- Live updating every second

🌍 **Time Difference Calculator**
- Instant calculation of time difference between any two countries
- Toggle between BST (British Summer Time) and GMT+0 for the UK
- Shows difference in hours and minutes

⏰ **Time Addition/Subtraction Calculator**
- Calculate what time it will be X hours from a given time
- Add or subtract any number of hours
- Results shown for both selected countries simultaneously
- Displays full date and time for results

🌐 **Bilingual Support**
- Switch between English and Spanish
- All interface elements translated
- Country names in both languages

📱 **Mobile-Friendly & PWA**
- Responsive design optimized for mobile devices
- Installable as a standalone app on phones and tablets
- Works offline after first load
- Fast and lightweight

## How to Use

### Online Hosting

1. Upload all files (`index.html`, `manifest.json`, `sw.js`) to any web server
2. Access via HTTPS (required for PWA features)
3. Install as app from browser menu

### Local Testing

1. Open `index.html` in a modern web browser
2. For PWA features, use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```
3. Visit `http://localhost:8000`

### Installing as PWA

**On Mobile (iOS/Android):**
- Open in Safari (iOS) or Chrome (Android)
- Tap share button → "Add to Home Screen"
- The app will appear as a standalone app icon

**On Desktop:**
- Open in Chrome/Edge
- Look for install icon in address bar
- Click "Install" to add to applications

## Usage Guide

### 1. Current Time Display
- Select Country 1 from the dropdown (defaults to Peru)
- Select Country 2 from the dropdown (defaults to UK)
- Times update automatically every second
- For UK: Toggle between BST and GMT+0 using the button

### 2. Time Calculator
- Enter a start time (e.g., 07:00)
- Enter number of hours to add or subtract (e.g., 14)
- Click "Add" or "Subtract" button
- View results for both countries simultaneously

### 3. Language Toggle
- Click "EN" for English
- Click "ES" for Spanish (Español)

## Supported Countries

- 🇵🇪 Peru (Lima)
- 🇬🇧 United Kingdom (London)
- 🇺🇸 USA (New York, Los Angeles, Chicago)
- 🇲🇽 Mexico (Mexico City)
- 🇨🇴 Colombia (Bogotá)
- 🇦🇷 Argentina (Buenos Aires)
- 🇧🇷 Brazil (São Paulo)
- 🇪🇸 Spain (Madrid)
- 🇫🇷 France (Paris)
- 🇩🇪 Germany (Berlin)
- 🇯🇵 Japan (Tokyo)
- 🇨🇳 China (Shanghai)
- 🇦🇪 UAE (Dubai)
- 🇦🇺 Australia (Sydney)

## Technical Details

**Built with:**
- React 18 (standalone, no build required)
- Tailwind CSS
- Lucide Icons
- JavaScript Intl API for timezone handling
- Service Worker for offline functionality

**Browser Requirements:**
- Modern browser (Chrome, Safari, Firefox, Edge)
- JavaScript enabled
- Intl API support (available in all modern browsers)

## File Structure

```
time-calculator/
├── index.html          # Main HTML file with React app
├── manifest.json       # PWA manifest
├── sw.js              # Service worker for offline support
└── README.md          # This file
```

## Deployment Options

### Option 1: GitHub Pages
1. Create a GitHub repository
2. Upload all files
3. Enable GitHub Pages in Settings
4. Access via `https://username.github.io/repo-name`

### Option 2: Netlify/Vercel
1. Drag and drop folder to Netlify/Vercel
2. Instant deployment with HTTPS
3. Free tier available

### Option 3: Any Web Host
1. Upload files via FTP/SFTP
2. Ensure HTTPS is enabled
3. Access via your domain

## Browser Compatibility

- ✅ Chrome/Edge 90+
- ✅ Safari 14+
- ✅ Firefox 88+
- ✅ Mobile browsers (iOS Safari, Chrome Android)

## Privacy

- No data collection
- No external analytics
- Runs entirely in browser
- No backend required

## License

Free to use and modify for personal or commercial projects.

## Support

For issues or questions, the app uses standard web technologies and should work in any modern browser with JavaScript enabled.

---

**Enjoy calculating times across the globe! 🌍⏰**
