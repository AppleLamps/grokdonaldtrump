# @miahper • Instagram Profile

A pixel-perfect, fully interactive single-file Instagram profile mock built as a standalone demo.

![Instagram Profile Mock](images/2.jpg)

## Overview

This project recreates the Instagram profile experience for **Mia Harper** (@miahper), an 18-year-old UCLA student living in Malibu, California. It includes realistic posts, story highlights, comments, likes, and smooth interactions — all in a single HTML file.

## Features

- **Profile header** — Bio, stats (187 posts, 52.4k followers, 743 following), verified badge, follow/message buttons
- **Story highlights** — Horizontally scrollable with animated gradient rings
- **Posts grid** — 3-column responsive layout with hover overlays showing likes & comments
- **Tabs** — Posts / Reels / Tagged views (Reels show fake play counts, Tagged shows attribution)
- **Post modal** — Full-screen viewer with:
  - Like / comment / save actions
  - Live comment posting
  - Double-click to like on desktop
- **Search** — Real-time filtering of posts by caption or comment text (`/` keyboard shortcut)
- **Interactive elements**:
  - Toggle follow state
  - Like posts (heart animation + count updates)
  - Save to collection
  - Followers modal
- **Keyboard support** — `Esc` closes modals, `L` likes current post, `/` focuses search
- **Mobile-friendly** — Responsive layout using Tailwind

## Tech Stack

- **HTML5** + vanilla JavaScript
- **Tailwind CSS 3.4** (via CDN)
- **Font Awesome 6.5** (via CDN)
- No build tools, no dependencies, no backend

## Getting Started

1. Clone or download this repository
2. Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge)
3. Enjoy the demo — everything works offline

No server or installation required.

## Project Structure

```
grok-web-3/
├── README.md
├── index.html
└── images/
    ├── 1.jpg … 14.jpg   # 14 AI-generated photos for the demo
```

## Notes

- All 14 images were generated specifically for this demo using AI.
- The profile data, captions, and comments are fictional.
- This is a frontend-only showcase — no real Instagram API or data is used.

## Keyboard Shortcuts

| Key       | Action                     |
|-----------|----------------------------|
| `/`       | Focus search bar           |
| `L`       | Like current post (in modal) |
| `Esc`     | Close post / followers modals |
| `Enter`   | Post comment (when input focused) |

## Credits

Built as a quick, self-contained web demo. Inspired by Instagram's 2024–2025 UI.

---

> Open `index.html` and start exploring. Perfect for portfolios, UI practice, or quick demos.