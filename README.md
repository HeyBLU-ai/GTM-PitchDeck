# HeyBLU Interactive Investor Pitch Deck

## Project Overview
This is an interactive HTML-based pitch deck for HeyBLU, an AI-powered umpire assistant for amateur baseball. The presentation is designed as a single-page, vertical-scrolling experience that mimics the flow of a traditional presentation while adding interactive elements.

## HeyBLU Product Description
HeyBLU is a smartphone-based AI platform that provides tools to run smoother, fairer, and more enjoyable baseball games. The solution addresses critical issues in amateur baseball:

- **Critical Umpire Shortage**: Games played without qualified officials
- **Inconsistent Strike Zones**: Variable officiating that frustrates players and hinders development
- **Rising On-Field Hostility**: Umpires facing increasing verbal abuse leading to high turnover

### Key Features
- AI-Powered Rulebook with voice-activated access to league-specific rules
- Automated Incident Reporting with audio evidence
- Ball-Strike Assist delivered discreetly to earbuds
- Player Development Tools with heatmaps and performance metrics
- On-device processing for privacy and zero latency

## Technical Environment
- **Operating System**: Windows 10 (Build 10.0.26100)
- **Shell**: PowerShell
- **Project Location**: `C:\Users\rbreg\Documents\GitHub_Projects\pitchdeck JP\`

## File Structure
```
pitchdeck JP/
├── pitchdeck2.html          # Main presentation file
├── README.md               # This documentation
├── images/                 # Local image assets
│   ├── adjustable-k-zone.jpg
│   ├── BLU-K-call.jpg
│   ├── BLU-Platform.jpg
│   ├── ipad-coach-kid1.jpg
│   ├── ipad-coach-kids.jpg
│   ├── ipad-masked-coach.jpg
│   ├── kid-coach.jpg
│   ├── landscape-ipad-coach.jpg
│   ├── MPH-coach-kid.jpg
│   ├── umpire-catcher.jpg
│   └── Visual-K-zone.jpg
└── assets/                 # External dependencies (when offline)
    ├── css/
    │   └── tailwind.min.css
    ├── js/
    │   └── chart.min.js
    └── fonts/
        └── inter.css
```

## Dependencies
The pitch deck currently uses external CDN resources:
- **Tailwind CSS**: For styling and responsive design
- **Chart.js**: For interactive data visualizations (market charts, financial projections)
- **Google Fonts (Inter)**: For typography

## Making the Presentation Offline
To make this presentation fully self-contained for local hard drive use:

1. **Download Dependencies** (Windows PowerShell commands):
   ```powershell
   Invoke-WebRequest -Uri "https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.min.js" -OutFile "assets/js/chart.min.js"
   Invoke-WebRequest -Uri "https://cdn.tailwindcss.com/3.4.0/tailwind.min.css" -OutFile "assets/css/tailwind.min.css"
   Invoke-WebRequest -Uri "https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" -OutFile "assets/fonts/inter.css"
   ```

2. **Update HTML References** in `pitchdeck2.html`:
   - Replace CDN links with local file paths
   - Update external image URLs to local image references

## Interactive Features
- **Sticky Navigation**: Jump between sections
- **Tabbed Interface**: Switch between technology and features
- **Interactive Timeline**: 3-phase go-to-market strategy
- **Dynamic Charts**: Market penetration, financial projections, use of funds
- **Product Preview**: Toggle between ball/strike outcomes
- **Smooth Scrolling**: Enhanced user experience

## Investment Details
- **Seeking**: $4.5M Series A
- **Target Market**: ~4.5M youth baseball players in organized leagues
- **Revenue Goal**: $25M ARR by Year 3
- **Market Penetration Needed**: ~2.8% of SAM

## Contact Information
- **Rob Regan**: Co-Founder, CEO & President
- **Email**: robr@bigleagueballpark.com
- **Phone**: 415-652-3780

## Usage Instructions
1. Open `pitchdeck2.html` in any modern web browser
2. Use the navigation menu to jump between sections
3. Interact with charts, tabs, and preview elements
4. Scroll vertically to experience the full presentation flow

## Development Notes
- Built as a single-page application
- Uses modern CSS (Flexbox, Grid) and JavaScript (ES6+)
- Responsive design for desktop and mobile viewing
- No server-side dependencies required
- Optimized for presentation environments (projectors, large screens)

