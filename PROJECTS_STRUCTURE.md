# Research Projects Content Structure

Use this structure for every collaborative project:

- `content/research-projects/<project-slug>/index.md`
- `content/research-projects/<project-slug>/collage.svg`

Current slugs:
- `eu-scores`
- `wiser`
- `dfs`

## Replace workflow

1. Keep the folder names and `index.md` files.
2. Replace only `collage.svg` with your final project collage image.
3. Update `index.md` text with final summary, role, outcomes, and links.
4. Run `hugo -D` to regenerate `docs/`.

Homepage Projects cards are wired to:
- image: `/research-projects/<project-slug>/collage.svg`
- page: `/research-projects/<project-slug>/`
