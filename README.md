# NodeNest — Prototype (static)

This is a minimal static prototype for the NodeNest marketing site (dark, minimal). It contains:

- `index.html` — homepage / product overview
- `pricing.html` — pricing page
- `styles.css` — shared styles (dark theme)

How to preview locally

Open `index.html` in a browser, or run a simple HTTP server in PowerShell:

```powershell
# from the repository root (C:\Users\<you>\Desktop\NodeNest)
python -m http.server 8000

# then open http://localhost:8000 in your browser
```

Next steps

- Add `legal/terms.html` and `legal/privacy.html` (links exist in footer).
- Add `features.html` and `contact.html` if you want more pages.
- Replace the Discord invite placeholder in the header/CTAs.
- If you want a Tailwind/Next.js version, I can scaffold that next.
