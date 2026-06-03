# meetp2022.github.io

Personal portfolio site for Meet Patel — Developer Educator & Applied AI.

Built with plain HTML and CSS. No build step, no dependencies. Deploys directly to GitHub Pages.

## Structure

```
index.html       → Main page (hero, featured work, writing, portfolio, skills)
style.css        → Shared stylesheet
work/            → Case study subpages
  refract-ai-platform.html
  siemens-documentation-suite.html
  lti-data-platforms.html
```

## Local Preview

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Push to `main`. GitHub Pages serves `index.html` automatically.

## Updating Content

**Add a blog post:** Find `<!-- ADD NEW POSTS HERE -->` in `index.html` and copy the `<li>` template above it.

**Add a case study:** Copy an existing file in `work/`, update content and navigation links, then add a card to the Portfolio section of `index.html`.

## Links

- [Blog](https://meetp2022.hashnode.dev/)
- [GitHub](https://github.com/meetp2022)
- [LinkedIn](https://www.linkedin.com/in/meet-patel-1b8160ab)
