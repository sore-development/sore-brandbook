# Sore — Official Brand Book & Digital Asset Repository

<p align="center">
  <img src="logo/logo-hd-512.png" alt="Sore Brand Emblem" width="140" height="140" />
</p>

<p align="center">
  <strong>The Definitive Design System & Asset Repository for Sore Music</strong><br>
  High-fidelity audio streaming platform and Discord music bot.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Assets-43%20Production%20Files-F05789?style=flat-square" alt="Assets" />
  <img src="https://img.shields.io/badge/Format-Single%20HTML%20(Standalone)-E58B43?style=flat-square" alt="Format" />
  <img src="https://img.shields.io/badge/Resolution-Up%20to%204K%20%26%20Vector-16191E?style=flat-square" alt="Resolution" />
  <img src="https://img.shields.io/badge/Palette-Zero%20Blue%20%2F%20Purple-090A0D?style=flat-square" alt="Palette" />
</p>

---

## 🌅 Overview

**Sore** (Indonesian for *twilight*, *late afternoon*, or the *golden hour*) represents that relaxing transition period of the day when people unwind with their favorite songs. 

This repository contains the complete official brand guidelines, design tokens, typography specifications, and **43 production-ready digital assets** packaged into an interactive, self-contained documentation website ([index.html](index.html)).

---

## ✨ Design Principles

- **Acoustic Warmth:** Warm coral rose and dusk amber accents convey a relaxed, intimate listening experience.
- **Zero Blue / Purple Colorway:** Thoughtfully crafted without default tech blurple/indigo shades to maintain a distinctive and soothing visual identity.
- **Modern & Minimalist:** High contrast, distraction-free typography with ample negative space.
- **High Fidelity:** Pixel-perfect assets ranging from lossless SVGs to 4096×4096 Master PNGs and alpha-transparent WebM motion graphics.

---

## 🎨 Color Palette & Design Tokens

| Color Name | Token | HEX | RGB | Role |
| :--- | :--- | :--- | :--- | :--- |
| **Sore Sunset Rose** | `--sore-rose` | `#F05789` | `240, 87, 137` | Primary Brand Accent |
| **Dusk Amber** | `--sore-amber` | `#E58B43` | `229, 139, 67` | Warm Atmospheric Accent |
| **Obsidian Canvas** | `--bg-base` | `#090A0D` | `9, 10, 13` | Main App Background |
| **Carbon Surface** | `--bg-card` | `#16191E` | `22, 25, 30` | Cards & Module Containers |
| **Elevated Slate** | `--bg-elevated` | `#22262F` | `34, 38, 47` | Modals & Floating Tooltips |
| **Pure Light** | `--text-main` | `#FFFFFF` | `255, 255, 255` | Primary Headings & Marks |
| **Muted Silver** | `--text-muted` | `#9CA3AF` | `156, 163, 175` | Secondary Body Text |
| **Emerald Live** | `--status-live` | `#10B981` | `16, 185, 129` | Active Audio Streaming Status |

### CSS Variables Snippet
```css
:root {
  --sore-rose: #F05789;
  --sore-rose-hover: #FF6E9D;
  --sore-amber: #E58B43;
  --sore-gold: #F59E0B;
  --sore-bg-base: #090A0D;
  --sore-bg-surface: #111317;
  --sore-bg-card: #16191E;
  --sore-bg-elevated: #22262F;
  --sore-border: rgba(255, 255, 255, 0.08);
  --sore-border-active: #F05789;
  --sore-text-primary: #FFFFFF;
  --sore-text-muted: #9CA3AF;
  --sore-text-dim: #6B7280;
  --sore-status-live: #10B981;
}
```

---

## 🗂️ Asset Directory Structure

All 43 brand assets are systematically organized into 6 core directories:

```
sore-brand-book/
├── index.html                   # Interactive Brand Book website (100% standalone)
│
├── brand/                       # Master Brand Marks & Wallpapers
│   ├── brand-logo-hd-16x9.png   # 3840×2160 (4K 16:9 Presentation Format)
│   ├── brand-logo-hd-1x1.png    # 4096×4096 (Master 1:1 Square Format)
│   └── sore-brands.svg          # Infinite Scalable Vector Identity
│
├── logo/                        # Core Monograms & Vector Badges
│   ├── logo.png                 # Master Full-Color Logo with Sunset Halo
│   ├── logo-2.png               # High-Contrast Dark Surface Alternate
│   ├── logo-hd-512.png          # 512×512 Standard Avatar / Icon
│   ├── logo-hd-fullhd.png       # 1080×1080 Full HD Mark
│   ├── logo-hd-1920.png         # 1920×1920 Ultra Mark
│   └── sore-logo.svg            # Scalable Master Logo Vector
│
├── banner/                      # Headers, Banners & Social Cards
│   ├── hero-1920x1080.png       # Official 1080p Hero Wallpaper Banner
│   ├── home.png                 # Web Portal Panoramic Header
│   ├── banner-1.png .. -4.png   # Server Header Presets (2172×724)
│   ├── banner-music.png         # Compact Discord Music Player Card (854×215)
│   ├── community-guidelines.png # Rules & Community Announcement Banner
│   ├── welcome-to-sore-community.png # Onboarding Welcome Banner
│   ├── create-ticket.png        # Support Desk & Ticket Banner
│   ├── help-and-support.png     # Knowledge Base Center Header V1
│   ├── help-and-support1.png    # Knowledge Base Center Header V2
│   ├── help-menu.png            # Command Reference Banner
│   ├── req-song.png             # Song Request Queue Banner
│   ├── ticket-banner.png        # Dedicated Ticket Category Banner
│   ├── og-image.png             # OpenGraph Social Card (1983×793)
│   └── og-image-2.png           # OpenGraph Alternate Center Card
│
├── motion/                      # Video & Looping Animation Lab
│   ├── banner-motion-hd.mp4     # 1080p Looping Motion Video
│   ├── banner-motion-low.mp4    # Lightweight Fast-Loading Video
│   ├── banner-motion.gif        # Animated GIF Header Loop
│   ├── sore_transparent.webm    # Alpha Channel Transparent Video
│   ├── sore_transparent.mp4     # Motion Graphic Video (MP4)
│   ├── sore-green-screen.mp4    # Chroma Key Green Screen Footage
│   ├── sore_transparent_sticker.gif # 320×320 Transparent Sticker
│   └── sore_transparent_wide.gif    # Wide Animated Sticker Loop
│
├── bg/                          # Ambient Background Assets
│   ├── bg.png                   # High-Res Ambient Atmosphere (1672×941)
│   └── bg.svg                   # Scalable Vector Ambient Gradient Mesh
│
├── favicon/                     # Web & PWA App Icons
│   ├── favicon.ico              # Multi-Layer Desktop Favicon
│   ├── favicon-16x16.png        # 16×16 Tab Icon
│   ├── favicon-32x32.png        # 32×32 Retina Tab Icon
│   ├── apple-touch-icon.png     # 180×180 iOS Home Screen Icon
│   ├── android-chrome-192x192.png # 192×192 Android PWA Launcher
│   ├── android-chrome-512x512.png # 512×512 Android PWA Splash
│   └── site.webmanifest         # PWA Metadata Configuration
│
└── font/                        # Offline Local Font Fallbacks
    └── PlusJakartaSans/         # TrueType Variable Font Files
```

---

## ⚡ Quick Start & Deployment

### 1. Local Preview
Open the standalone documentation directly:
- **Direct file access:** Double-click [`index.html`](index.html) in your file explorer.
- **Local HTTP server:**
  ```bash
  # Python 3
  python -m http.server 8080
  ```
  Then navigate to `http://localhost:8080/index.html`.

### 2. Zero-Build Web Deployment
Because `index.html` is 100% self-contained with all metadata embedded, you can deploy the repository directly to:
- **GitHub Pages:** Set branch to `main` and root to `/`.
- **Vercel / Netlify / Cloudflare Pages:** Push and serve statically without any build command.

---

## 🛡️ Usage Standards (Do's & Don'ts)

- **✓ DO** maintain the default 1:1 aspect ratio for all logo instances.
- **✓ DO** preserve a minimum clear space of `0.5X` surrounding the emblem.
- **✓ DO** render the mark against dark carbon or high-contrast backgrounds.
- **✗ DON'T** recolor the brand into blue, purple, or indigo shades.
- **✗ DON'T** stretch, squash, or distort the logo proportions.
- **✗ DON'T** tilt or rotate the horizontal orientation of the mark.

---

<p align="center">
  <sub>© 2026 Sore App. All rights reserved. Crafted with Modern Minimalist Dark Aesthetics.</sub>
</p>
