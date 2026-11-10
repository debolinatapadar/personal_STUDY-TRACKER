# ✦ HAMSTERSTUDY ✦

A cute, retro-inspired personal study and creator tracker for GATE, college academics, extra study topics, YouTube, and Substack.

## Included

- GATE DA topic tracker with status stages and notes
- College academics tracker with 7 subjects and 5 units per subject
- Extra study topics for LeetCode, placements, projects, and revision
- YouTube workflow: idea → scripting → filming → editing → published
- Substack workflow: idea → drafting → editing → published
- Daily study updates with flexible blocks and learning notes
- Calendar view and progress charts
- Browser-local saving through `localStorage`
- Responsive design inspired by soft grey, pink, and purple retro web layouts

## Run locally

Open `dist/index.html` directly in a browser, or serve the `dist` folder with a small static server:

```bash
python -m http.server 4173 --directory dist
```

Then visit `http://localhost:4173`.

## Deploy with GitHub Pages

1. Create a GitHub repository.
2. Upload the project files.
3. In the repository, open **Settings → Pages**.
4. Use GitHub Actions for a static site deployment, or copy `dist/index.html` to the repository root and deploy the `main` branch.

The tracker is a static website, so no backend or environment variables are required.

## Project structure

```text
HAMSTERSTUDY/
├── dist/
│   └── index.html
├── .openai/
│   └── hosting.json
├── .gitignore
└── README.md
```

