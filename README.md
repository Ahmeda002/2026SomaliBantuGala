# 2026 Somali Bantu Excellence Gala

Web-based presentation for the 2026 Somali Bantu Excellence Gala.

**Live presentation:** https://ahmeda002.github.io/2026SomaliBantuGala/

## Controls

- **→ / Space / click right side**: next slide
- **← / click left side**: previous slide
- **F**: full screen
- **Home / End**: first / last slide
- Add `#5` to the URL to jump to slide 5

## Structure

```
index.html        the whole presentation (slides, styles, navigation)
assets/images/    photos, logos and other images used in the slides
assets/video/     any video clips
```

## Editing

Each `<section class="slide">` in `index.html` is one slide. Text in `[brackets]` is a placeholder.
To add a photo, drop it in `assets/images/` and replace a `[Photo]` box with:

```html
<div class="photo"><img src="assets/images/your-photo.jpg" alt="Short description"></div>
```
