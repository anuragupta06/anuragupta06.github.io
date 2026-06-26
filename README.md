# Personal Site (anuragupta06)

This repository contains a minimal, responsive single-page personal website inspired by
`zhongxiaocong.com`, with sections for:

- About
- Projects
- Skills
- Background
- CV/PDF placeholder
- Contact

## Quick start

### 1. View locally

```bash
# from the project root
python -m http.server 4173
```

Open `http://localhost:4173/index.html`.

### 2. Deploy on GitHub Pages

If your repo is `anuragupta06.github.io`, enable GitHub Pages from Settings:

1. **Settings → Pages**
2. Source: `Deploy from a branch`
3. Branch: `main` (or your default branch), folder: `/ (root)`
4. Save

Your site will be published at:

- `https://anuragupta06.github.io`

### 3. Replace placeholder PDF

1. Put your real CV file at:

   - `assets/cv-placeholder.pdf`

2. Refresh the page.

The page already includes an embedded PDF block and a download link, so no code changes are required.

### 4. Edit profile content

Edit `index.html`:

- `anuragupta06` label in masthead and title
- Contact email / links
- About / projects / timeline entries
- Skills list

## Notes

- Navigation is responsive and supports mobile collapse.
- No build tool is required; this is plain HTML/CSS/JS.
