# @realdonaldtrump • Instagram Profile Mock

A pixel-perfect, fully interactive single-file Instagram profile recreation for **President Donald J. Trump**.

![Preview](images/1.jpg)

## Overview

This project is a detailed, client-side recreation of Donald Trump's Instagram profile (@realdonaldtrump). It features **24 recent posts** with captions grounded in real presidential activities from his second term, powered by **26 unique AI-generated images**.

The demo includes realistic interactions, a working "Load more posts" feature, and is fully ready for deployment.

## Features

- **Profile stats** — 7,922 posts • 43.9M followers • 512 following
- **24 unique posts** in the grid (expandable via "Load more")
- **Story highlights** — Oval Office, Mar-a-Lago, Cabinet, America First, Florida, Champions
- **Post modal** — Full-screen viewer with:
  - Like / comment / save actions
  - Live comment posting
  - Double-click to like
- **Tabs** — Posts / Reels / Tagged views
- **Search** — Real-time filtering with clear button (`/` keyboard shortcut)
- **Interactive elements**:
  - Toggle follow state
  - Heart animation on like
  - Followers modal
- **Keyboard support** — `Esc`, `L` (like), `/` (search)
- **Mobile-friendly** responsive design
- **Vercel-ready** with `vercel.json`

## Tech Stack

- **HTML5** + vanilla JavaScript
- **Tailwind CSS** (via CDN)
- **Font Awesome 6** (via CDN)
- No build tools, no dependencies, no backend

## Getting Started

1. Clone the repository
2. Open `index.html` in any modern browser
3. Everything works offline

## Project Structure

```
grokdonaldtrump/
├── README.md
├── index.html
├── vercel.json
├── .gitignore
└── images/
    └── 1.jpg … 26.jpg   # 26 unique AI-generated presidential photos
```

## Deployment

This project is configured for easy deployment on Vercel:

- `vercel.json` included (clean URLs enabled)
- Pure static site — no build step required
- Simply connect the repository on Vercel and deploy

## Notes

- All 26 images were generated specifically for this project using AI.
- Post captions are inspired by real activities (Executive Orders, Mar-a-Lago working weekends, Cabinet meetings, White House events, military meetings, etc.).
- This is a frontend-only showcase — no real Instagram API or data is used.
- The profile is fictionalized for demonstration purposes.

## Keyboard Shortcuts

| Key     | Action                              |
|---------|-------------------------------------|
| `/`     | Focus search bar                    |
| `L`     | Like current post (when modal open) |
| `Esc`   | Close modals                        |
| `Enter` | Post comment (when input focused)   |

## Credits

Built as a self-contained web demo. Inspired by Instagram's current UI and President Trump's real public activities.

---

> Open `index.html` to explore. Ready for Vercel deployment.