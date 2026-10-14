# AlphaPaws — Illustrated Edition

A preschool alphabet and sticker game for ages 3–5. This update replaces the CSS-drawn puppy with an illustrated Biscuit cutout and adds a garden illustration to the sticker board. The puppy bobs and celebrates, while clouds, butterflies, and flowers animate independently. Existing voice selection, parental controls, alphabet lessons and progress storage remain intact.

## Upload to GitHub Pages
Upload `index.html` and the complete `assets` folder to the **root** of your existing repository. Keep the exact names and capitalization. Your repository should contain:

```
index.html
README.md
assets/
  biscuit.png
  garden.jpg
```

Commit changes and refresh your GitHub Pages URL. On iPhone, close/reopen Safari or refresh if the old art is cached.

## Artwork and animation notes
The puppy art is cropped from the illustrated AlphaPaws concept and gently feathered; it is **not** a fully rigged walking character. The current motion is CSS-based idle bobbing and jumping. True walking, blinking and independent tail motion will need separate pose/layer assets or sprite frames. The background and flowers are separate elements, allowing independent motion. Voice options depend on browser/OS.
