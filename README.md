# 🍳 Grok Recipes

**Battle-tested prompt recipes for Grok (text) & Grok Imagine (images/videos).**  
Track what actually works, share iterations, and build the ultimate prompt cookbook.

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://rosekrans.github.io/grok-recipes)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/rosekrans/grok-recipes/pulls)

## ✨ Features

- **Visual Recipe Cards** — See real example outputs (especially images)
- **Full Prompt + Variations** — Copy-paste ready with smart tweaks
- **Effectiveness Tracking** — Star ratings, notes, success metrics, and iteration history
- **Search & Filters** — Instantly find recipes by category, tag, or keyword
- **Community Powered** — Submit via PRs. Every recipe has its own feedback thread

## 🚀 Quick Start (for users)

1. Visit the live site (GitHub Pages)
2. Browse or search recipes
3. Click any card → view full prompt, variations, examples
4. Copy the prompt and try it in Grok!

## 🛠️ Local Development

```bash
# Clone and open
git clone https://github.com/rosekrans/grok-recipes.git
cd grok-recipes
# Open index.html in your browser (or use Live Server)
```

No build step required — pure HTML + Tailwind + vanilla JS.

## 📁 Project Structure

```
grok-recipes/
├── index.html              # The beautiful self-contained site
├── recipes.json            # All recipe data (easy to edit)
├── README.md
├── assets/
│   └── images/recipes/     # Your Grok-generated example images go here
└── .github/
    ├── ISSUE_TEMPLATE/
    └── PULL_REQUEST_TEMPLATE/
```

## 🤝 Contributing a New Recipe

We love high-quality, **proven** recipes!

1. Fork the repo
2. Add your recipe to `recipes.json` (follow the schema)
3. Add 1–3 example images to `assets/images/recipes/`
4. Update `index.html` if you want a custom card (optional — JS auto-renders)
5. Open a Pull Request with:
   - Clear title
   - Why this recipe is effective (test results, use cases)
   - Example outputs

### Recipe Schema (recipes.json)

```json
{
  "id": "unique-kebab-case-id",
  "title": "Short Catchy Title",
  "category": "text" | "image",
  "tags": ["tag1", "tag2"],
  "prompt": "Full prompt text here...",
  "variations": ["Variation 1...", "Variation 2..."],
  "rating": 9.2,
  "notes": "Why it works, testing notes, tips...",
  "examples": [
    {"url": "assets/images/recipes/your-image.jpg", "caption": "Description"}
  ],
  "date": "2026-04-21",
  "author": "YourName"
}
```

## 📜 License

MIT — share freely, credit appreciated.

## 💬 Feedback & Ideas

Open an Issue or start a Discussion. Let's make Grok even more powerful together!

---

*Built with ❤️ for the Grok community. Powered by xAI.*
# grok-recipes-pvt
