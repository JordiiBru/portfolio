# Portfolio - jordibru.cloud

## Stack
- **Astro 5.x**, static site generator
- Content in `src/content/*.md` (Markdown with frontmatter)
- Pages in `src/pages/*.astro` consume content via `import('../content/<name>.md')`
- Two layouts: `Layout.astro` (index), `ChannelLayout.astro` (section pages)

## Design
- Editorial minimalist, inspired by Onomatopee / Inventory Press
- Font: Inter (400, 700, 900)
- Black on white with **lila (#7c3aed)** as accent: borders, arrows, link color, hover states
- **Yellow (#fde68a)** for text selection highlight
- No shadows, no border-radius, no decorative elements. Typography and whitespace only.

## Sections
1. About (`/about`)
2. Experience (`/experience`)
3. Projects (`/projects`)
4. Talks (`/talks`)
5. Hobbies (`/hobbies`)
6. Life (`/life`)

## Content editing
Edit Markdown files in `src/content/`. Astro renders them automatically. To add a new section:
1. Create `src/content/<name>.md`
2. Create `src/pages/<name>.astro` importing content with `ChannelLayout`
3. Add entry to `sections` array in `src/pages/index.astro`

## Dates in Experience
Use `<span class="date">2024 – Present</span>` after `## heading` for grey subtitle dates.

## Writing style
- No em dashes. Use commas, periods, or colons.
- Concise. Cut verbosity.
- English content.

## Commands
- `npm run dev` -- dev server on port 4321
- `npm run build` -- static build to `dist/`
- `npm run preview` -- preview built site

## i18n
Not yet implemented. Structure ready for future translations. Do not translate until content is finalized.
