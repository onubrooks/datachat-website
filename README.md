# DataChat Website

Website + docs content hub for DataChat.

## Site map

- `index.html`: marketing homepage
- `features.html`: feature breakdown
- `use-cases.html`: practical usage scenarios
- `comparison.html`: positioning comparison (including DataChat, Vanna, LibreChat)
- `docs/`: documentation pages aligned to current shipped behavior

## Local preview

```bash
cd datachat-website
python -m http.server 8080
```

Then open:
- `http://localhost:8080/`
- `http://localhost:8080/docs/`

## Content policy

- Keep claims aligned to actual shipped behavior.
- Avoid roadmap hype in core marketing copy.
- Explicitly call out dependency/ops requirements when relevant.
