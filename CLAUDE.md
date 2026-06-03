# Portfolio Site — meetp2022.github.io

## Project Context

GitHub Pages portfolio for Meet Patel — Developer Educator & Applied AI, based in Dresden, Germany. Plain HTML + CSS, no build step. Deploys by pushing to `main`.

## Site Structure

```
/
├── index.html          ← Main single-page site (hero, work, writing, portfolio, skills)
├── style.css           ← Shared styles (all pages use this)
├── work/
│   ├── refract-ai-platform.html         ← Case study: Fosfor/LTIMindtree AI platform docs
│   ├── siemens-documentation-suite.html ← Case study: Siemens Rulestream product docs
│   └── lti-data-platforms.html          ← Case study: LTIMindtree data/ML platform docs
├── CLAUDE.md           ← This file (project context for Claude Code)
└── README.md
```

## Positioning (use for all copy)

- **Headline:** Developer Educator & Applied AI
- **Honest scope:** 7+ years in enterprise technical roles, 2+ years hands-on production RAG/LLM systems
- **NEVER claim:** "7+ years in AI" — the honest framing is "7+ years enterprise technical roles"
- **Target audience:** Hiring managers at AI/developer-tool companies for DevRel, API docs, developer education roles

## Design System

- **Theme:** Dark (#0a0a12 bg), teal accent (#14b8a6)
- **Fonts:** Outfit (headings), DM Sans (body) — loaded from Google Fonts
- **All styles in style.css** — subpages link to `../style.css`
- **CSS variables:** All colors, fonts, spacing use :root vars
- **Cards:** .card class with hover glow effect
- **Tags/pills:** .tag (small, accent bg) and .pill (border, hover effect)
- **Scroll reveal:** .reveal class + IntersectionObserver JS on index.html

## How to Add Content

### New blog post
In index.html, find `<!-- ADD NEW POSTS HERE -->` in the Writing section. Copy the `<li>` block above it and update title, description, URL.

### New featured work card
Copy an existing `.card` in the Featured Work section. Update h3, p, tags, and href.

### New case study subpage
1. Copy an existing file in `work/`
2. Update content, breadcrumb, case-nav links
3. Add a card in the Portfolio section of index.html linking to the new page
4. CSS path: `../style.css`

## Links

- Blog: https://meetp2022.hashnode.dev/
- GitHub: https://github.com/meetp2022
- LinkedIn: https://www.linkedin.com/in/meet-patel-1b8160ab
- CareerIndex: https://www.careerindex.tech/blog
- Email: meet.mvp74@gmail.com
