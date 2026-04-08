# Contributing to OVATE Security

Thank you for your interest in contributing to the OVATE Security website! This document outlines the process for contributing and the standards we follow.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Development Setup](#development-setup)
- [Coding Standards](#coding-standards)
- [Submitting Changes](#submitting-changes)
- [Reporting Issues](#reporting-issues)

---

## 🤝 Code of Conduct

This project follows a professional standard of conduct. All contributors are expected to:

- Be respectful and constructive in all communications
- Focus feedback on code and ideas, not individuals
- Welcome newcomers and help them get started
- Uphold the professional reputation of OVATE Security

---

## 🛠️ How to Contribute

### Types of Contributions Welcome

- **Bug fixes** — Broken layouts, animation glitches, JavaScript errors
- **Accessibility improvements** — ARIA labels, keyboard navigation, screen reader support
- **SEO enhancements** — Structured data, meta tag improvements
- **Performance optimisations** — Reduce render-blocking resources, improve load time
- **Content updates** — Corrections to copy, service descriptions, or contact information
- **Feature additions** — New sections, interactive elements (with prior discussion)

### What Requires Prior Discussion

Before starting work on significant changes, please open an issue to discuss:

- New sections or major layout changes
- Changes to the brand identity, colours, or typography
- Third-party library additions
- Structural changes to the HTML

---

## 💻 Development Setup

The website requires **no build process**. To work locally:

1. **Fork** the repository on GitHub
2. **Clone** your fork:
   ```bash
   git clone https://github.com/YOUR_USERNAME/OVATE.git
   cd OVATE
   ```
3. **Open** a local development server:
   ```bash
   python3 -m http.server 8080
   # or
   npx serve .
   ```
4. **Open** `http://localhost:8080` in your browser

---

## 📐 Coding Standards

### HTML

- Use semantic HTML5 elements (`<section>`, `<nav>`, `<article>`, `<aside>`)
- All images must have descriptive `alt` attributes
- Maintain consistent indentation (2 spaces)
- Keep inline styles minimal — prefer Tailwind utility classes

### CSS / Tailwind

- Utility classes follow the existing Tailwind configuration in `index.html`
- Custom CSS is written in the `<style>` block within `index.html`
- Follow the existing naming conventions: `.rv`, `.card`, `.hero-*`, `.section-label`
- Prefer CSS transitions over JavaScript animations where possible

### JavaScript

- Use vanilla JavaScript (no jQuery, no external JS libraries unless essential)
- Use `const` and `let` — avoid `var`
- Functions should be named descriptively
- Add comments for non-obvious logic
- Avoid blocking the main thread — use `requestAnimationFrame` for animations

### Brand Consistency

- Maintain the established colour palette (see [BRAND.md](BRAND.md))
- Use **DM Sans** for headings and body, **Inter** for labels and micro-copy
- All new sections should follow the `.rv` scroll-reveal pattern

---

## 📬 Submitting Changes

1. **Create a branch** from `main`:
   ```bash
   git checkout -b fix/description-of-fix
   # or
   git checkout -b feat/description-of-feature
   ```

2. **Make your changes** following the coding standards above

3. **Test your changes** across:
   - Chrome, Firefox, Safari (latest versions)
   - Mobile viewports (375px, 390px, 414px)
   - Tablet viewport (768px)
   - Desktop viewports (1280px, 1440px, 1920px)

4. **Commit** with a clear, conventional commit message:
   ```
   fix: correct mobile nav overlay z-index
   feat: add testimonials section with scroll reveal
   docs: update README setup instructions
   style: align service card heights on tablet
   ```

5. **Push** your branch and open a **Pull Request**

6. In the PR description, include:
   - What was changed and why
   - Screenshots or recordings of UI changes
   - Browser/device testing completed

---

## 🐛 Reporting Issues

Use the issue templates provided:

- **[Bug Report](.github/ISSUE_TEMPLATE/bug_report.md)** — For broken functionality
- **[Feature Request](.github/ISSUE_TEMPLATE/feature_request.md)** — For new functionality

When reporting a bug, always include:
- Browser and version
- Operating system
- Steps to reproduce
- Expected vs actual behaviour
- Screenshots if applicable

---

## 📄 Licence

By contributing, you agree that your contributions will be covered under the OVATE Security proprietary licence. All intellectual property remains the property of OVATE Security Ltd.

---

*Questions? Open an issue or contact the maintainers via [ovatesecurity.com](https://ovatesecurity.com).*
