# Luffy Gear Second Landing Page

An interactive One Piece themed landing page featuring Luffy's Gear Second transformation. Built with React, Three.js, and GSAP for an immersive anime-style web experience.

## Features

- **3D Models** - Luffy's straw hat rendered with `@react-three/fiber` and `@react-three/drei`
- **Particle Effects** - Custom particle system with animated particles
- **Lightning & Smoke FX** - Dynamic lightning and smoke effects using OGL
- **Scroll-Triggered Animations** - GSAP-powered scroll experiences with timeline control
- **Ambient Thunder** - Atmospheric thunder sound and visual effects
- **Falling Kanji** - Japanese character animations
- **Glitch & Shiny Text Effects** - Custom React components for stylized typography
- **Splash Cursor** - Interactive cursor effects

## Tech Stack

- **React 19** + **Vite 8**
- **Three.js** (via `@react-three/fiber`, `@react-three/drei`)
- **GSAP** for animations
- **Framer Motion** / **Motion** for transitions
- **OGL** for WebGL effects
- **Oxlint** for linting

## Getting Started

### Prerequisites

- Node.js 18+
- npm

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Lint

```bash
npm run lint
```

## Project Structure

```
src/
├── components/          # Main React components
│   ├── Scene3D.jsx      # 3D scene with straw hat model
│   ├── LuffyCutout.jsx  # Luffy character cutout
│   ├── LightningSmokeFX.jsx
│   ├── FallingKanji.jsx
│   ├── AmbientThunder.jsx
│   └── ScrollExperience.jsx
├── reactbits/           # Reusable effect components
│   ├── Particles/
│   ├── Lightning/
│   ├── GlitchText/
│   ├── ShinyText/
│   ├── BlurText/
│   └── SplashCursor/
├── lib/                 # Utility functions
│   ├── timeline.js      # GSAP timeline helpers
│   ├── rng.js           # Random number generation
│   ├── math.js          # Math utilities
│   └── luffyLayout.js   # Layout calculations
├── App.jsx              # Main app component
├── main.jsx             # Entry point
└── index.css            # Global styles
```

## Assets

- `public/models/strawhat.glb` - Straw hat 3D model (GLB)
- `public/models/luffys_straw_hat/` - Alternative straw hat model (GLTF)
- `public/images/` - Background and character images

## License

MIT License - Feel free to use for learning or personal projects.

## Credits

- One Piece by Eiichiro Oda
- 3D models sourced from public repositories
- Built as a fan project for educational purposes