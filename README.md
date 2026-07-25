# Happy First Anniversary, My Madam Jee ❤️

A single-file, interactive anniversary website — built to feel like opening a
luxury love story rather than reading a page. Soft pink, rose gold, cream,
glassmorphism, floating hearts, and a lot of little surprises.

Live in one file: **`index.html`** — no build tools, no dependencies to install.

---

## ✨ What's inside

- Cinematic opening sequence (typed lines + photo reveal + falling petals)
- Live "together since" love timer (days / hours / minutes / seconds)
- Scroll-animated love story timeline
- Photo memory gallery with lightbox
- Envelope → love letter with sparkling words
- 25 flip cards — "Why I Love You"
- "100 Reasons" random generator
- Memory jar (click a heart, get a memory)
- Floating love notes
- Compliment machine
- Hug button (heart burst + screen shake)
- Gift box reveal
- Love quiz (rigged in her favor 😉)
- Runaway "NO" button + confetti "YES" button
- Scratch card
- Overflowing love meter
- Daily promises
- Final message + rising hearts ending
- A tiny hidden heart secret somewhere on the page 🤫

---

## 🚀 How to host it (GitHub Pages)

1. Create a new GitHub repository (public).
2. Upload `index.html` to the repo (root folder).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`,
   branch `main`, folder `/ (root)`.
5. Save. GitHub will give you a live link like:
   `https://your-username.github.io/your-repo-name/`
6. Share that link with her 💌

No servers, no npm install, no backend — it just works.

---

## 🖊️ How to personalize it

You only need to edit **one place** in the whole file: the `CONFIG` block,
found inside a `<script id="love-data">` tag near the bottom of `index.html`.
Search for `CONFIG` and you'll land right on it.

Everything below is inside that block:

| What you want to change   | Field in CONFIG      |
|----------------------------|----------------------|
| Your anniversary start date | `startDate`         |
| The hero photo (opening reveal) | `heroPhoto`      |
| Background music (optional) | `backgroundMusic`   |
| Timeline events (met, first "I love you", etc.) | `timeline` |
| Gallery photos + captions   | `gallery`            |
| The love letter text        | `letter`             |
| The 25 "Why I Love You" flip cards | `whyCards`    |
| The 100 reasons list         | `reasons`            |
| Memory jar memories          | `memories`           |
| Floating love notes          | `notes`              |
| Compliment machine lines     | `compliments`        |
| Daily promises                | `promises`           |

**Tips:**
- Photos can be image URLs, or upload your own images into the repo (e.g. a
  `photos/` folder) and point to them like `"photos/us1.jpg"`.
- Background music works the same way — add an `.mp3` file to the repo and
  set `backgroundMusic: "music.mp3"`.
- In the love letter, wrap any word in double asterisks like `**My Home**`
  and it will automatically sparkle ✨.
- You don't need to touch any HTML, CSS, or other JavaScript — just this one
  config block.

---

## 🛠️ Tech

- Plain HTML, CSS, and JavaScript — no frameworks, no build step
- Fully responsive (mobile + desktop)
- Respects `prefers-reduced-motion` for accessibility
- Works great on GitHub Pages, Netlify, Vercel, or literally any static host

---

Made with ❤️, one year in.
