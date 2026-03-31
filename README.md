# BioinStream - Compbio & Bioinformatics Blog

AI-assisted, human-curated news feed across bioinformatics research, tools, and industry.

Version deployed [here](https://compbio-blog-astro.vercel.app/).

## Setup

Install dependencies and start the dev server:

```bash
nvm install 22
nvm use 22

npm install
npm run dev
```

Open: http://localhost:4321

## Creating a Post

Create a new Markdown file in:

```
src/content/blog/
```

## Deploy

Deploy via Vercel:

* Push to GitHub
* Import project in Vercel
* Auto-deploy on every push


## Workflow

1. Run data collection (RSS / scripts)
2. Filter + curate news
3. Create new `.md` file
4. Commit & push


## Notes

* No backend
* No database
* Content = Markdown files
* Fully static site

