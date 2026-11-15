# AGENTS.md

This repository serves https://elliotchong.github.io through GitHub Pages, deployed from `main`. It holds only generated files that a publish script copies from a private source repository: `index.html`, the resume PDF, `og.png` (link-preview card), and `.nojekyll`.

- Don't edit those files here; the next publish overwrites them. Make content and layout changes in the source repository and republish from there.
- The page is intentionally excluded from search engines (`noindex`). Keep it that way unless the owner asks.
- A Pages build takes about a minute after a push; confirm with `curl -sI https://elliotchong.github.io/`.
