# The Dyslexia Parent Project — Website

A one-page website for The Dyslexia Parent Project, funded by The Sandra Dunagan Deal Center for Early Language and Literacy. Project awarded to Georgia State University.

## Folder Structure

```
dyslexia-parent-project/
├── index.html              ← the website
├── images/
│   ├── team/               ← project staff photos
│   │   ├── brennan-chandler.jpg
│   │   ├── isabel-vargas-bell.jpg
│   │   ├── elizabeth-hart.jpg
│   │   ├── erin-agyeman-duah.jpg
│   │   ├── erin-tankersley.jpg
│   │   ├── mallie-egan.jpg
│   │   └── abby-collins.jpg
│   └── pab/                ← Parent Advisory Board photos
│       ├── tina-engberg.jpg
│       ├── christen-miller.jpg
│       ├── missy-purcell.jpg
│       └── meagan-swingle.jpg
└── README.md
```

## Photo Specs

Before uploading, prep each photo:

- **Square crop** with face centered (the site displays them as circles)
- **600px–800px on each side** (enough for high-res displays without bloat)
- **Under 200KB each** — compress with [TinyPNG](https://tinypng.com) or [Squoosh](https://squoosh.app)
- **.jpg format** for photos with people
- **Exact filenames** as listed above (lowercase, hyphens, no spaces)

If a photo file is missing or named incorrectly, the site automatically falls back to showing the person's initials in a colored circle — so nothing ever looks broken.

## Deploy to Netlify via GitHub

**One-time setup:**
1. Create a free GitHub account if you don't have one
2. Create a new repository called `dyslexia-parent-project` (public or private, your choice)
3. Upload `index.html`, the `images/` folder, and this README via GitHub's web interface (drag-and-drop in the "Add file → Upload files" flow)
4. Go to [netlify.com](https://www.netlify.com), sign up with your GitHub
5. "Add new site" → "Import from Git" → pick your repo
6. Leave all build settings blank (this is a static site, nothing to build)
7. Click deploy — you get a URL like `random-name-12345.netlify.app`
8. Optional: rename the site under Site Settings → Domain → Change site name

**Future updates:**
- Edit `index.html` or add/replace photos directly in your GitHub repo
- Netlify rebuilds and redeploys automatically within ~30 seconds of any commit

## Updating Content

All copy lives inside `index.html`. Search for what you want to change (e.g., a bio, a module title) and edit in place. If you're unsure, ask Claude to help — paste the section you want to change and what you want it to say.

## Brand Quick Reference

- **Colors:**
  - Deep Navy `#0B2A6F` (headlines, primary)
  - Soft Purple `#8B6FC6`
  - Bright Blue `#3F7BE0`
  - Teal `#43B5AE`
  - Background `#F8F8F8`
- **Fonts:** DM Sans (headlines) + Inter (body) — loaded via Google Fonts
- **Brand standard:** Montserrat Bold (700) for print/PowerPoint
