# @realdonaldtrump • Instagram Profile Mock

A high-fidelity, fully interactive single-file recreation of President Donald J. Trump's Instagram profile (@realdonaldtrump).

![Preview](images/1.jpg)

## Overview

This project is a detailed client-side recreation of the @realdonaldtrump Instagram profile. It features **24 posts** (expandable via "Load more") with captions inspired by real presidential activities from his second term, powered by **26 unique AI-generated images**.

The experience includes realistic interactions, tabbed views, real-time search, and strong mobile support. It is fully self-contained and ready for static deployment.

## Features

- **Profile header** — 7,922 posts • 43.9M followers • 512 following, editable follow state, and bio
- **24 posts initially** — expandable to 36 via "Load more" (only on Posts tab)
- **Story highlights** — Six scrollable rings: Oval Office, Mar-a-Lago, Cabinet, America First, Florida, Champions
- **Post viewer** — Detailed modal (bottom sheet on mobile) with:
  - Like, comment, save, and double-tap-to-like with classic heart burst animation
  - Live comment posting
  - Caption and comment display
- **Tabbed views** — Posts (grid), Reels (demo), and Tagged (demo). Non-Posts tabs show illustrative content and open photos in the viewer
- **Search** — Real-time filtering across captions and comments with desktop (`/`) and mobile support
- **Interactive elements**:
  - Follow / unfollow toggle with toast feedback
  - Followers modal with sample accounts
  - Mobile search bar (tap icon or bottom nav)
- **Mobile experience** — Fully responsive with:
  - Smaller profile photo on phones
  - Clean 3-column grid (no hover overlays)
  - Instagram-style bottom tab bar (Home, Search, Create, Reels, Profile)
  - Bottom-sheet post modal for better thumb reach and keyboard behavior
  - Touch-optimized tap feedback and double-tap to like
  - Safe area support for notched devices
- **Vercel-ready** — `vercel.json` with clean URLs enabled

## Tech Stack

- **HTML5** + vanilla JavaScript
- **Tailwind CSS** (via CDN)
- **Font Awesome 6** (via CDN)
- No build tools, no dependencies, no backend

## Getting Started

1. Clone the repository
2. Open `index.html` directly in any modern browser (no build step required)
3. The experience works fully offline and is optimized for both desktop and mobile devices

All interactions (likes, comments, search, modals, load more) are handled client-side.

## Project Structure

```
grokdonaldtrump/
├── README.md
├── index.html
├── vercel.json
├── .gitignore
└── images/
    └── 1.jpg … 26.jpg   # 26 unique AI-generated images (square, 1:1)
```

## Deployment

Ready for instant static hosting:

- `vercel.json` included (`cleanUrls: true`)
- No build step or dependencies
- Deploy to Vercel, Netlify, GitHub Pages, or any static host by serving the root directory

## Notes

- All 26 images were generated specifically for this project using AI.
- Post captions and activities are fictionalized but inspired by real second-term presidential events and themes.
- This is a pure frontend demo — no Instagram API, backend, or real data is used.
- The profile and content are created for demonstration and educational purposes only.

## Keyboard Shortcuts

| Key     | Action                              |
|---------|-------------------------------------|
| `/`     | Focus search bar                    |
| `L`     | Like current post (when modal open) |
| `Esc`   | Close modals                        |
| `Enter` | Post comment (when input focused)   |

## Credits

Built as a self-contained web demo. Inspired by Instagram's interface patterns and real-world public activities of the 45th and 47th President.

---

Open `index.html` in a browser to explore. The project is ready for static deployment on Vercel or similar platforms.