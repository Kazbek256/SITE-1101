# Personal Website

This is a small static personal website with pages: Home, About, Projects, Resume.

Project structure
- `index.html` — Home page
- `about.html` — About
- `projects.html` — Projects (Project 1 showcased)
- `resume.html` — Resume
- `css/styles.css` — Shared styles
- `js/main.js` — Small script to toggle mobile nav
- `assets/` — Put your images here (profile and project screenshots)

Replace placeholders
- Update the GitHub and Codecademy links in the pages with your real profile URLs.
- Update the repository link in the footer (`https://github.com/yourusername/your-repo`) to point to your public repository for the website.

Run locally
1. From the project folder run:

```powershell
python -m http.server 8000
```

2. Open `http://localhost:8000` in your browser.

Images
- Add your profile photo to `assets/` (example: `DSC04746.JPG`).
- Add project screenshots to `assets/` (example: `Screenshot_20251119_194232_YouTube(1).jpg`).

Accessibility and performance notes
- Images use `loading="lazy"` for better performance.
- Consider adding optimized WebP copies and `srcset` for responsive images.

License
- Add a license file if you intend to publish it publicly.
