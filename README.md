# 🎨 Image Lab — AI Image Generator

A darkroom-themed AI image generator that turns text prompts into images 9 style presets, 4 frame sizes, and zero setup required. No API key, no backend, no sign-up.

**[🚀 Live Demo — try it here](https://aiimagegenerator-neon.vercel.app/)**

---

## How it works

Type a prompt, pick a style and frame size, and the app builds a request directly to the [Pollinations AI](https://pollinations.ai) image endpoint — a free, keyless image-generation API. There's no server, no database, and no secrets: the entire app is a single static HTML file that runs completely in the browser.

```
Your prompt + style + size
        │
        ▼
https://image.pollinations.ai/prompt/{encoded_prompt}?width=...&height=...&seed=...
        │
        ▼
   Image renders directly in the page
```

## Features

- **9 style presets** — Realistic, Digital Art, Oil Painting, Sketch, Anime, Minimalist, Cyberpunk, Watercolor, and Default
- **4 frame sizes** — Square, Landscape, Portrait, HD Square
- **Quick idea prompts** — one-click starting points if you're not sure what to generate
- **Download & print** generated images directly from the browser
- **No API key, no backend, no cost** — Pollinations AI is free and keyless

## Tech Stack

- HTML5, CSS3, vanilla JavaScript
- [Pollinations AI](https://pollinations.ai) — free text-to-image API

---

Built by [Sohaib Nadeem](https://github.com/sohaibnadeemcs) — [LinkedIn](https://linkedin.com/in/sohaib-nadeem-pk)
