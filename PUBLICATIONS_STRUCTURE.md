# Publications Content Structure

Use this structure for every publication:

- `content/publications/<publication-slug>/index.md`
- `content/publications/<publication-slug>/collage.svg`

## Replace workflow

1. Keep folder name and `index.md` unchanged.
2. Replace only `collage.svg` with your final collage image.
3. Run `hugo -D` to regenerate `docs/`.

Homepage publication cards are wired to:
- image: `/publications/<publication-slug>/collage.svg`
- page: `/publications/<publication-slug>/`
