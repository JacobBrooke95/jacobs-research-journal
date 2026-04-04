# Jacob's Research Journal

A personal research blog built with plain HTML/CSS, hosted on GitHub Pages.

**Live site:** https://jacobbrooke95.github.io/jacobs-research-journal/
**RSS feed:** https://jacobbrooke95.github.io/jacobs-research-journal/feed.xml

## Adding a new post

1. Copy `templates/post-template.html` to `posts/YYYY-MM-DD-slug.html`
2. Fill in all `<!-- TEMPLATE FIELD -->` sections
3. Add the post to the `<ul class="post-list">` in `index.html`
4. Add the post to `feed.xml` (copy an existing `<item>` block)
5. Commit and push — GitHub Pages deploys automatically

## Structure

```
research-journal/
├── index.html          # Homepage post list
├── about.html          # About page
├── style.css           # All styles
├── feed.xml            # RSS feed
├── .nojekyll           # Disables Jekyll processing
├── posts/              # Individual post files
│   └── YYYY-MM-DD-slug.html
└── templates/
    └── post-template.html   # Copy this for new posts
```

## Design

- Font: Inter (body) + Lora (post body text)
- Palette: warm cream (#FAF8F5), brown accent (#8B5E3C)
- No build step, no dependencies, no JavaScript
