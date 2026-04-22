# Bio Page
Your personal link-in-bio page — fully editable, no backend, no signup.
Just open, customize, and share.

---

## Live Demo
https://bio-page-hazel.vercel.app/

---

## Features
- **Editable profile** — name, handle, bio, avatar color, and photo upload
- **Sections & links** — create multiple sections, add unlimited links to each
- **Reorder everything** — move sections and links up/down with one click
- **Icon picker** — 14 built-in icons (GitHub, Instagram, TikTok, Medium, YouTube, and more)
- **Photo upload** — set a custom avatar image, falls back to a colored initial
- **Share button** — copies the page URL to clipboard instantly
- **Persistent storage** — all edits saved automatically to localStorage
- **Reset to default** — one click to restore the original profile
- Fully responsive (mobile-friendly)
- Full keyboard accessibility
- No authentication
- No ads
- No watermarks

---

## Icons
| Icon | Use Case |
|---|---|
| Globe | Website / Portfolio |
| GitHub | GitHub profile |
| Instagram | Instagram profile |
| TikTok | TikTok profile |
| Twitter/X | Twitter / X profile |
| LinkedIn | LinkedIn profile |
| YouTube | YouTube channel |
| Medium | Blog / Medium |
| Book | Blog / Reading list |
| Briefcase | Work / Hire Me |
| Mail | Email |
| Phone | Phone number |
| Link | Generic link |
| Star | Featured |

---

## Tech Stack
- React 18 (Vite)
- CSS custom properties (Apple-inspired dark UI, no framework)
- localStorage (client-side persistence)
- Vercel (static deploy)

---

## How It Works
1. Open the page — your profile loads from localStorage (or defaults on first visit)
2. Click **Edit** in the top bar to enter edit mode
3. Tap the pencil on your avatar to update profile info or upload a photo
4. Add sections and links, pick icons, set URLs
5. Reorder with the arrow buttons
6. Click **Done** — everything saves automatically
7. Hit **Share** to copy your page link

> All data lives in your browser's localStorage. Nothing is sent to any server.

---

## Customization
The entire design is driven by CSS custom properties in `src/styles.css`:

```css
--bg        /* page background     */
--accent    /* primary color       */
--radius-lg /* card corner radius  */
--shadow    /* card shadow         */
```

Swap `--accent` to change the highlight color across the whole UI.

---

## Installation
```bash
# Clone the repo
git clone https://github.com/berkinyilmaz/bio-page.git

# Install dependencies
cd bio-page
npm install

# Run locally
npm run dev
```
