# JavaScript Assets — OVATE Security

This directory is reserved for modular JavaScript files as the project evolves.

## Current Status

All scripts are currently embedded within `index.html` in the `<script>` block for simplicity and to avoid additional HTTP requests.

## Future Structure

When the project scales, scripts should be separated into:

```
assets/js/
├── preloader.js      # Preloader animation and progress bar
├── particles.js      # Particle canvas background
├── nav.js            # Navigation scroll-spy, mobile menu
├── animations.js     # Scroll-triggered reveal (Intersection Observer)
├── cards.js          # Cursor spotlight effect on cards
├── form.js           # Contact form validation and submission
└── main.js           # Entry point, initialises all modules
```

## Guidelines

- Use ES6+ syntax (`const`, `let`, arrow functions, template literals)
- No external JavaScript libraries unless strictly necessary
- Use `requestAnimationFrame` for smooth animations
- Initialise scripts after DOM content is loaded (`DOMContentLoaded`)
- Add JSDoc comments to exported functions
