# Talks & Conferences Structure

Use one folder per event:

- `content/talks/<event-slug>/index.md`
- `content/talks/<event-slug>/collage.svg`
- `content/talks/<event-slug>/scene-01.svg`
- `content/talks/<event-slug>/scene-02.svg`
- `content/talks/<event-slug>/scene-03.svg`

## Two ways to use it

1. Collage reminder only
- Replace `collage.svg` only.
- Keep one or more scene files as placeholders.

2. Scrollable event photos
- Replace `scene-01.svg`, `scene-02.svg`, `scene-03.svg` with real photos (`.jpg`, `.png`, `.webp`, or `.svg`).
- Update `galleryImages` in `index.md` to match filenames.
- Add as many images as you want.

Example:

```yaml
galleryImages:
  - src: "scene-01.jpg"
  - src: "scene-02.jpg"
  - src: "scene-03.jpg"
  - src: "scene-04.jpg"
```

Homepage cards are wired to:
- image: `/talks/<event-slug>/collage.svg`
- page: `/talks/<event-slug>/`
