# doudou.github.io

Personal academic website for **Yuling Xie** — Postdoctoral Research Fellow in
toxicology at the Institute for Global Food Security, Queen's University Belfast.

A static site (plain HTML + CSS, no build step) styled after a minimalist academic
homepage template.

## Structure

| File | Purpose |
|------|---------|
| `index.html` | Home — bio, research interests, current position, education |
| `research.html` | Research overview, projects, PhD thesis, methods, conferences |
| `experience.html` | Full experience, education, skills, languages (CV) |
| `style.css` | Shared styles |
| `assets/profile.svg` | Placeholder avatar — replace with a real photo |

## Customising

- **Photo:** drop a real image at `assets/profile.jpg` and change the `<img src="...">`
  in each page's hero (currently `assets/profile.svg`).
- **Social links:** edit the icons in the `.socials` block of `index.html`. Google
  Scholar and LinkedIn are included but commented out — add your URLs and uncomment.
- **Content:** all text lives directly in the HTML files.

## Preview locally

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy (GitHub Pages)

Push to `main`, then in the repo go to **Settings → Pages** and set the source to the
`main` branch (root). The site will be served at
`https://cher-dou.github.io/doudou.github.io/`.
