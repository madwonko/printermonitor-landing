# PrinterMonitor Pro — Landing Page

Static marketing site for [PrinterMonitor Pro](https://prntr.org).

- Single `index.html`, Tailwind (CDN) + Inter font — no build step.
- Brand: `blue-600`, hero gradient `#667eea→#764ba2`, CTA gradient `#f093fb→#f5576c`.
- Assets in `assets/` (logo + favicon).

## Local preview
```bash
python -m http.server 8080   # then open http://localhost:8080
```

## Deploy (Vercel)
Framework preset **Other**, output dir `.` (root). Attach domains `www.prntr.org` and apex `prntr.org`.
