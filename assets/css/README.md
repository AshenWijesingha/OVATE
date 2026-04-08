# CSS Assets — OVATE Security

This directory is reserved for modular CSS stylesheets as the project evolves.

## Current Status

All styles are currently embedded within `index.html` in the `<style>` block for simplicity and to avoid an additional HTTP request.

## Future Structure

When the project scales, styles should be separated into:

```
assets/css/
├── base.css          # Reset, global box-model, scrollbar
├── animations.css    # Reveal system, hero word reveal, preloader
├── components.css    # Cards, buttons, section labels, nav
├── layout.css        # Grid, spacing, hero, section structure
└── utilities.css     # Helper classes
```

## Guidelines

- Use CSS custom properties (`--var`) for reusable values
- Maintain the existing naming conventions (`.rv`, `.card`, `.hero-*`)
- Follow mobile-first media query order
