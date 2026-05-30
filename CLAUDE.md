# Portfolio - jordibru.cloud

## Stack
- **Astro 5.x** -- static site generator
- Content lives in `src/content/*.md` (Markdown with frontmatter)
- Pages in `src/pages/*.astro` consume content via `import('../content/<name>.md')`
- Two layouts: `Layout.astro` (index) and `ChannelLayout.astro` (section pages)

## Design
- Editorial minimalist style inspired by Onomatopee / Inventory Press
- Font: Inter (400, 700, 900)
- Black on white. No colors, no shadows, no border-radius
- Typography does the heavy lifting: large bold titles, generous whitespace, clean lines
- Hover effects: subtle indent + arrow on index, underline on links

## Sections
1. About (`/about`)
2. Experience (`/experience`)
3. Projects (`/projects`)
4. Talks (`/talks`)
5. Hobbies (`/hobbies`)

## Content editing
Edit Markdown files in `src/content/`. Astro renders them automatically. To add a new section:
1. Create `src/content/<name>.md`
2. Create `src/pages/<name>.astro` importing the content and using `ChannelLayout`
3. Add entry to the `sections` array in `src/pages/index.astro`

## Commands
- `npm run dev` -- dev server on port 4321
- `npm run build` -- static build to `dist/`
- `npm run preview` -- preview built site

## Language
- Portfolio content in English
- Repo docs / commit messages in Spanish or English (Jordi's preference)
