# Nikhil Blog Portfolio (Astro + Tailwind)

### Quick start — no local tooling needed

1. **Create a repo** on GitHub (public or private).
2. **Upload** every file/folder in this ZIP via *Add file → Upload files*.
3. Commit to **main**, wait for the GitHub Actions run.
4. Enable **Pages** in Settings (Source = GitHub Actions). Your site is live!

### Adding a post (in the browser)

1. Go to `src/posts/` → *Add file → Create new file*.
2. Name it `YYYY-MM-DD-my-title.md`.
3. Paste your Markdown from Notion.
4. Add front‑matter:

```yaml
---
title: "Title here"
pubDate: 2025-06-05
description: "One‑liner"
tags: ["product", "ux"]
---
```

5. Commit — done! The new post appears after the deploy finishes.

### Dark / light mode

Click the sun/moon icon in the navbar. Default follows OS preference.

### Customizing styles

Edit `tailwind.config.cjs` (accent color, fonts) or `src/styles/global.css`.

---

Enjoy! ✨
