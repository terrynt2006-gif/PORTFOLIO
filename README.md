# Terrence — Portfolio Website

A responsive, colourful, animated portfolio website for Terrence, a second-year Computer Science student at Midlands State University (MSU), Zimbabwe.

## Files
- `index.html` — page structure and portfolio content
- `style.css` — responsive styling, colour, animation and layout
- `script.js` — mobile navigation, reveal-on-scroll animations and current year
- `assets/profile-photo.jpg` — optional personal photo location (add your own image)

## Personalise the photo
Upload your chosen photo into `assets/` and name it `profile-photo.jpg`. Then replace the placeholder `<div class="photo-placeholder">...</div>` in `index.html` with:

```html
<img class="profile-photo" src="assets/profile-photo.jpg" alt="Portrait of Terrence">
```

Add this CSS rule to `style.css`:

```css
.profile-photo { width:100%; height:100%; object-fit:cover; border-radius:inherit; display:block; }
```

## Publish
This is a static site; no build step or package installation is required. It can be deployed from the repository root on Vercel or served with GitHub Pages.
