# Changelog

All notable changes to the OVATE Security website are documented here.

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html) and follows the [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) format.

---

## [Unreleased]

### Planned
- Cookie consent banner
- Blog / Insights section
- Case studies section
- Multi-language support

---

## [1.1.0] — 2025-04-08

### Added
- `README.md` — Comprehensive project documentation with setup instructions and project structure
- `CONTRIBUTING.md` — Contribution guidelines for developers
- `BRAND.md` — Brand guidelines covering logo usage, colour palette, and typography
- `CHANGELOG.md` — Version history (this file)
- `.github/ISSUE_TEMPLATE/bug_report.md` — Structured bug report template
- `.github/ISSUE_TEMPLATE/feature_request.md` — Feature request template
- `sitemap.xml` — XML sitemap referencing all website sections for search engine indexing
- `robots.txt` — Crawler directives allowing all search engines; references sitemap
- `manifest.json` — Web App Manifest enabling PWA installability
- `.gitignore` — Proper Git ignore rules for web projects
- `assets/logos/` — Directory for brand logo assets with usage documentation
- `assets/images/` — Directory for website imagery
- `assets/css/` — Placeholder directory for future modular stylesheets
- `assets/js/` — Placeholder directory for future modular scripts
- Open Graph meta tags (`og:title`, `og:description`, `og:type`, `og:url`, `og:image`)
- Twitter Card meta tags for rich social media previews
- Canonical URL `<link>` tag
- `<link rel="manifest">` pointing to `manifest.json`
- Theme colour meta tag (`#000000`)

### Changed
- `index.html` — Enhanced `<head>` with comprehensive SEO and social sharing meta tags

---

## [1.0.0] — 2025-01-01

### Added
- Initial website launch
- Hero section with animated word reveal and particle canvas background
- Navigation with scroll-spy active state and mobile hamburger menu
- Preloader animation with progress bar and curtain exit
- About section featuring company mission, vision, and founder profile
- "Why OVATE" section with five key differentiators
- Services section covering MDR, Penetration Testing, GRC, vCISO, and Security Awareness Training
- Industries section (Financial Services, Healthcare, Technology, Government, Retail)
- Contact form with client-side validation
- Footer with social links
- Scroll-triggered reveal animations using Intersection Observer API
- Cursor spotlight effect on service cards
- Scroll progress indicator bar
- Noise overlay texture
- Tailwind CSS (CDN) with custom colour theme configuration
- DM Sans and Inter typefaces via Google Fonts

---

[Unreleased]: https://github.com/AshenWijesingha/OVATE/compare/v1.1.0...HEAD
[1.1.0]: https://github.com/AshenWijesingha/OVATE/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/AshenWijesingha/OVATE/releases/tag/v1.0.0
