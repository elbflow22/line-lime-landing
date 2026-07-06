# Line Lime — landing page

A standalone, static demand-validation landing page for **Line Lime** — the home for a professional short-form creator's scripts.

- Single self-contained `index.html` (inline CSS/JS, Google Fonts via CDN).
- Two-step waitlist: email + 5 qualifying questions, submitted to **Formspree** via AJAX.
- Deployed via **GitHub Pages**.

## Configure the form

Open `index.html`, find `const FORMSPREE_ID = "YOUR_FORM_ID";` near the bottom, and replace it with your Formspree form id (the part after `formspree.io/f/`). Commit and push — Pages redeploys automatically.

## Local preview

```bash
python3 -m http.server 8080
# open http://localhost:8080
```
