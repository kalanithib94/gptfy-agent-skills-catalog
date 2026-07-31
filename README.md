# GPTfy Agent Skills Catalog

Static multi-select skill download catalog for the GPTfy Dock Knowledge Base.

## Live site (GitHub Pages)

After Pages is enabled:

`https://kalanithib94.github.io/gptfy-agent-skills-catalog/`

## Update flow

1. Rebuild in the AGENT LIBRARY project:
   `python Deliverables/kb-catalog/build_kb_catalog.py`
2. Copy updated `index.html` + `zips/` into this repo
3. Commit and push to `main`
4. Dock iframe keeps the same URL — content refreshes automatically

## Dock embed

```html
<iframe
  src="https://kalanithib94.github.io/gptfy-agent-skills-catalog/"
  title="GPTfy Skills Catalog"
  width="100%"
  height="900"
  style="border:0;border-radius:8px;"
  loading="lazy"
></iframe>
```
