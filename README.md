# Image Host
Minimal static image sharing site based on hugo. Inspired by [ben brown](https://photos.benbrown.com/).

[View demo page here.](https://7omg.github.io/minimal-image-gallery/)

## Files
- `assets/`
    - `css/main.css`: main stylesheet
    - `photos/`: contains all photos in gallery
- `content/`
    - `_content.gotmpl`: content generator for individual photo pages, individual and album overview pages
    - `zoom/_index.md`: placeholder for `zoom` path
- `data/photos.yaml`: add metadata to photos
- `layouts/`: contains templates
    - `_partials`: reusable html parts
    - `robots.txt`
- `static/favicon.png`: set page favicon
