# Qurtoba Translation Services website

Static homepage (Direction A, "Ink & Brass"). No build step: `index.html` plus the `images` folder.

## Publish with GitHub Pages
1. Upload `index.html`, the `images` folder and this README to the root of a repository (keep the folder name and file names as they are).
2. In the repository, open Settings, then Pages.
3. Under Source choose "Deploy from a branch", pick `main` and `/ (root)`, then Save.
4. The site appears at `https://<username>.github.io/<repository>/` after about a minute.

## Notes
- Colors and the logo are placeholders. Replace them when the client supplies the real ones (colors are the `--a-*` variables at the top of the `<style>` block).
- The quotation form is not connected to anything yet and sends nothing.
- Page text comes from the client's requirements document.
- Fonts load from Google Fonts (Newsreader and Public Sans).
- Hero image: `images/hero-desktop.jpg` (wide screens) and `images/hero-mobile.jpg` (phones). To change it, replace these two files with the same names, or edit the `url(...)` lines of `.a-hero` in `index.html`.
