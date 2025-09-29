# Abu Hurerah — Portfolio (Static HTML)

Simple, responsive single-file portfolio built with plain HTML and CSS. Includes a dark/light theme toggle, skill progress bars, projects, experience, and contact sections.

## Features
- Single-file static site (index.html)
- Responsive layout with CSS grid and flexbox
- Dark / Light theme persisted in localStorage
- Skill progress bars (data-driven)
- Accessible header/nav and skip link
- Buttons for email, resume download and repo/demo links (placeholders)

## Tech
- HTML5, modern CSS
- Google Fonts (Inter)
- Font Awesome icons
- No build step required

## Usage

Quick preview (open directly)
- Double-click `index.html` or open in browser.

Serve locally (recommended for consistent behavior)
- Python 3:
  - `python -m http.server 8000`
  - Open http://localhost:8000
- Node (serve):
  - `npx serve .`

## Customize
- Edit `index.html` to change content:
  - Header: name, title, logo letters
  - Contact: phone, email, links
  - Skills: adjust `data-level` on `.skill` elements to change progress
  - Projects / Experience: update sections in the markup
- Fonts and icons loaded via external CDNs — update <head> if you want local assets.

Tip: update the resume download button (`#downloadBtn` / `#downloadResume`) to point to an actual PDF or implement a click handler to fetch one.

## Deploy
- GitHub Pages:
  - Commit `index.html` to a repository.
  - Enable Pages from the repository settings (branch: main / docs folder).
- Any static host (Netlify, Vercel, S3) can serve the file as-is.

## License
MIT — modify as needed.

## Contact
Email: abuhurerahfarooq@gmail.com
GitHub: https://github.com/abuhurerahfarooq