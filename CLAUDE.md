# Portfolio - jordibru.cloud

## Stack
- **Astro 5.x**, static site generator
- Content in `src/content/*.md` (Markdown with frontmatter)
- Pages in `src/pages/*.astro` consume content via `import('../content/<name>.md')`
- Two layouts: `Layout.astro` (index), `ChannelLayout.astro` (section pages)

## Design
Editorial minimalist aesthetic, inspired by Onomatopee / Inventory Press. The visual language is built entirely on typography and whitespace. No shadows, no border-radius, no decorative elements.

- **Base:** Black (`#111`) on white. High contrast, flat, no noise.
- **Font:** Inter (400, 700, 900). Weight and size carry all hierarchy.
- **Lila (`#7c3aed`):** Used sparingly as accent only. Structural dividers (top/bottom `border`), hover underlines on links, arrow color on section rows, and active/flipped states on the avatar ring. Not for body text or backgrounds.
- **Yellow (`#fde68a`):** Text selection highlight only.
- When adding new UI elements, default to black/grey. Reach for lila only for interactive affordances or key structural lines.

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
