# GAMES Reborn Design System & Atomic Guide 🎨

Interactive component guide and design tokens architecture for all GAMES Reborn Network web portals, launcher interfaces, and administrative dashboards.

## 🏗️ Atomic Architecture Hierarchy
```
src/
├── tokens/       # Colors, Typography, Spacing, Shadows, Glows
├── atoms/        # Buttons, Badges, Inputs, Icons, Avatars
├── molecules/    # Search bars, Form fields, Player stat pills, Filter chips
├── organisms/    # Navigation headers, Server cards, Hero sections, Footers
├── templates/    # Portal layouts, Launcher modal frames, Dashboard shells
└── pages/        # Fully assembled production views & reference screens
```

## 🚀 Development & Build
```bash
npm install
npm run dev      # Local Vite dev server
npm run build    # Production build for GitHub Pages
```

## 🌐 Live GitHub Pages
Deployed automatically to **GitHub Pages** via GitHub Actions workflow (`.github/workflows/deploy.yml`).
