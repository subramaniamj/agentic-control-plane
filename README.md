# Stop counting agents

A short, visual perspective on agentic control planes: what they are, why they matter now, and how watsonx Orchestrate approaches them.

Open `index.html` in a browser to read it, or publish it with GitHub Pages.

## What's in the folder

| Path | What it is |
| --- | --- |
| `index.html` | The article. Carbon-style light theme, with a dark mode toggle. |
| `assets/css/article.css` | The page styles. |
| `assets/infographics/` | PNG exports of the quote and all five figures. Drop them straight into a LinkedIn article or post. |
| `assets/img/cover.png` | 1920 × 1080 cover image. |
| `assets/img/social-card.png` | 1200 × 627 link preview image. |

## Publish on GitHub

**GitHub Desktop:** File → Add Local Repository → pick this folder → choose "create a repository" → Publish repository.

**Command line:**

```bash
git init -b main
git add .
git commit -m "Add agentic control plane article"
gh repo create agentic-control-plane --public --source=. --push
```

**Turn on GitHub Pages:** Settings → Pages → Deploy from a branch → `main` / root. The article will be at `https://<your-username>.github.io/agentic-control-plane/`.

**Link previews:** LinkedIn needs a full URL for the preview image. Once Pages is live, change the `og:image` value in `index.html` to `https://<your-username>.github.io/agentic-control-plane/assets/img/social-card.png`.

## Notes

- No build step and no dependencies. Fonts (IBM Plex) load from Google Fonts.
- Views are my own. Product names are trademarks of their respective owners.
