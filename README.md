# MindMark 🧠

> Turn Markdown into Mind Maps — instantly.

**MindMark** is a lightweight, browser-based tool that converts your Markdown into beautiful mind maps in real time. No login, no server, no dependencies.

🌐 **Live Demo**: [https://hy834063-star.github.io/mindmark/](https://hy834063-star.github.io/mindmark/)

---

## Features

- ✍️ **Markdown Editor** — Dark-themed editor on the left
- 🗺️ **Real-time Mind Map** — Canvas-rendered mind map on the right
- 🎨 **Clean underline style** — Text sits on colored lines, no boxes
- 🖱️ **Pan & Zoom** — Scroll to zoom, drag to pan
- 💾 **Save as PNG** — Export your mind map as a high-res image
- 📋 **Local History** — Documents auto-saved to localStorage

## How to Use

```markdown
# Root Node (H1 becomes the root)

## Branch One (H2 becomes level-1 branches)
### Sub topic
- List item
  - Nested item

## Branch Two
### Another topic
```

## Local Development

Just open `index.html` in any browser — it's a single self-contained file.

```bash
npx serve .
# or
python -m http.server 8080
```

---

Made with ❤️ using vanilla HTML/CSS/JS + Canvas 2D
