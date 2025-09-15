# Flashcard Web App

A React-based flashcard viewer that lets you upload a CSV (with **Question/Answer** or **A/B** columns) and flip between sides in an A5 landscape card style.

## Features
- Upload CSV with Question/Answer (or A/B)
- Alternating **A (odd pages)** and **B (even pages)** display
- Even pages have a 15% green background
- Centered text, adjustable font size
- Row numbers (top-left) and side label (top-right)
- Keyboard shortcuts (→, ←, Space)
- Shuffle & Reset order

---

## 🚀 One-Click Deploy

Click below to deploy instantly to **Vercel**:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Ffin-max%2Feflashcardsv3)

> Replace `yourusername/flashcard-app` with the actual path to your repository.

---

## Local Development

```bash
# Install dependencies
npm install

# Run dev server
npm run dev

# Build production bundle
npm run build
```

Visit `http://localhost:3000` to view the app.

---

## Hosting Options
- **Vercel** (recommended): 1‑click deploy above
- **Netlify**: Drag + drop the build folder or connect GitHub
- **GitHub Pages**: Push the `/out` or `/build` folder from `npm run build`
