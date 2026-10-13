# play-mate

> **Book courts. Find players. Play more.**  
> A sleek, high-performance sports venue discovery, court booking, and player matchmaking web application featuring an ultra-premium dark aesthetic, 3D interactive ticket decks, glassmorphism, and seamless client-side state management.

---

## 🌟 Overview

**PlayMate** bridges the gap between athletes, venues, and casual sports enthusiasts. Whether you need to book a 5-a-side football turf under floodlights, grab a badminton court for an evening drill, or find that crucial extra teammate for a Friday game, PlayMate makes it happen in seconds.

Built with a **"black stage, one red spotlight"** design philosophy, PlayMate draws inspiration from classic admission tickets and stadium passes—complete with perforated stubs, scannable barcodes, holographic gloss sheen, and smooth physics-based 3D tilt interactions.

---

## 🚀 Key Features

### 🏟️ 1. Venue Discovery & Smart Filtering
- **Dynamic Search & Filtering:** Instant real-time filtering across sports (Football, Basketball, Tennis, Badminton, Cricket).
- **Glassmorphic Venue Cards:** Skewed 3D glass cards with frosted backdrop filters that smoothly straighten, expand, and reveal real-time rates and amenities on hover.
- **Detailed Venue Profiles:** Interactive photo gallery, amenity badges (floodlights, parking, changing rooms, wooden/clay/turf courts), user ratings, and distance indicators.

### 🎟️ 2. Interactive 3D Ticket Deck
- **Physical Ticket Aesthetics:** Admission passes designed with authentic perforated divider lines, barcodes, ticket serials, and admission rates.
- **Physics-Based Gyroscopic 3D Tilt:** Real-time mouse tracking calculates tilt angles (`rotateX`, `rotateY`) and overlays dynamic holographic specular highlights.
- **Interactive Carousel Controls:** Smooth card swiping, drag gestures, navigation arrows, and paginated indicators.

### 📅 3. Real-Time Court Slot Booking
- **Flexible Time Picker:** Morning, afternoon, and evening hourly court slots with live conflict checking.
- **Split-the-Bill Calculator:** Built-in per-player cost division calculator that recalculates immediately as headcount adjusts.
- **Instant Booking Confirmation:** Generates unique booking IDs (e.g. `PM1042`) saved persistently in browser storage.

### 🤝 4. Community Matchmaking ("Find Players")
- **Open Pickup Games:** Browse games that need one more person—see sport, skill level (Casual, Intermediate, Competitive), host, venue, and per-head cost.
- **Post a Game:** Host your own game with customized headcount requirements, sport type, and slot timing.
- **One-Tap Join Requests:** Join games with a single tap and monitor request statuses.

### 🎫 5. Digital Passes & Booking Management
- **Perforated Ticket Stubs:** Every confirmed booking is rendered as a collectible ticket stub with barcodes, court times, and venue location.
- **Active & Past Tabs:** Switch between upcoming matches and completed bookings.
- **Cancellation Flow:** Cancel reservations with real-time slot release.

### 📊 6. Player Profile & Analytics
- **Activity Metrics:** Interactive tracking for total games played, courts booked, favourite venues, and current streak.
- **Monthly Activity Visualization:** Dynamic SVG bar chart illustrating monthly athletic sessions.
- **Sport Distribution:** Breakdown of hours spent per sport with responsive progress bars.
- **Local Storage Persistence:** All bookings, posted games, favorites, and profile changes persist seamlessly in browser `localStorage`.

---

## 🎨 Design System

| Element | Specification |
| :--- | :--- |
| **Theme** | Obsidian Dark Stage (`#0a0a0b`, `#16161a`) with Stadium Crimson (`#e5322d`, `#ff4f49`) accents |
| **Typography** | Marseille (Display), Archivo (Sans-Serif), DM Mono (Numbers, Barcodes & Metadata) |
| **Surfaces** | Translucent frosted glass with `backdrop-filter: blur(12px)`, fine hairline borders |
| **Lighting** | Dynamic radial cursor spotlight tracking cursor coordinates in real-time |

---

## 📁 Repository Structure

```
play-mate/
├── index.html              # Main single-page application entry point
├── css/
│   └── style.css           # Complete styling, design tokens, responsive grid & animations
├── js/
│   └── app.js              # Application logic, venue data, routing & state management
├── fonts/
│   ├── Marseille-subset.woff2
│   ├── MarseilleFreeRegular.otf
│   ├── MarseilleFreeRegular.ttf
│   └── LICENSE-info.txt
├── images/
│   └── football-hero.webp   # Hero poster asset
├── README.txt              # Quick asset notes & instructions
└── README.md               # Detailed project documentation
```

---

## 💻 Getting Started Locally

No complex build steps, package installations, or dependencies are required:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Anish02102004/play-mate.git
   cd play-mate
   ```

2. **Run the project:**
   - Simply double-click `index.html` to open it in any modern browser.
   - Or serve with a lightweight local web server (optional):
     ```bash
     # Using Python
     python -m http.server 3000

     # Using Node.js (npx)
     npx serve .
     ```

---

## 🌐 Deploy to GitHub Pages

1. Navigate to your repository on GitHub: `https://github.com/Anish02102004/play-mate`.
2. Go to **Settings** ➔ **Pages**.
3. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **`main`**
   - Folder: **`/ (root)`**
4. Click **Save**.
5. Your live app will be accessible at:
   `https://anish02102004.github.io/play-mate/`

---

## 👤 Author

**Anish Angural**  
- GitHub: [@Anish02102004](https://github.com/Anish02102004)  
- Email: anishangural987@gmail.com
