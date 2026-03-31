# 🧬 Bioinformatics Signals

AI-assisted, human-curated signals across bioinformatics research, tools, and industry.

---

## 🚀 Setup

Install dependencies and start the dev server:

```bash
npm install
npm run dev
```

Open: http://localhost:4321

---

## ✍️ Creating a Post

Create a new Markdown file in:

```
src/content/posts/
```

Example:

```md
---
title: "Bioinformatics Signals — YYYY-MM-DD"
date: "YYYY-MM-DD"
summary: "Short description"
---

## 🔬 Key Signals

- Example signal  
  → Why it matters  

## 🧪 Research Highlights

- Paper / finding  

## 🏢 Industry

- News / funding  

## 🧠 Patterns Detected

- Trend or shift  

## 🧰 Tools & Resources

- Tool / repo  

## ⚙️ Notes

Generated through automated aggregation, machine-assisted categorization, and manual curation.
```

---

## 📦 Build

```bash
npm run build
```

Output is in:

```
dist/
```

---

## ☁️ Deploy

Deploy via Vercel:

* Push to GitHub
* Import project in Vercel
* Auto-deploy on every push

---

## 🔁 Workflow

1. Run data collection (RSS / scripts)
2. Filter + curate signals
3. Create new `.md` file
4. Commit & push

---

## 🧠 Notes

* No backend
* No database
* Content = Markdown files
* Fully static site

---



## Install and use version 22 (npm)

```
nvm install 22
nvm use 22
npm run dev
```