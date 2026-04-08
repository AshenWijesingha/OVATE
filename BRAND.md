# OVATE Security — Brand Guidelines

This document defines the visual identity and brand standards for OVATE Security. All contributors, designers, and partners must adhere to these guidelines to maintain brand consistency.

---

## 📌 Table of Contents

1. [Brand Identity](#1-brand-identity)
2. [Logo Assets](#2-logo-assets)
3. [Colour Palette](#3-colour-palette)
4. [Typography](#4-typography)
5. [Spacing & Layout](#5-spacing--layout)
6. [Brand Voice & Tone](#6-brand-voice--tone)
7. [Usage Rules](#7-usage-rules)

---

## 1. Brand Identity

**OVATE Security** is a UK-based enterprise cybersecurity consultancy. The brand communicates:

- **Authority** — Deep technical expertise, CREST-accredited professionals
- **Precision** — Measured, data-driven language; clean, minimal design
- **Trust** — Understated confidence; no hype, no filler
- **Sophistication** — Premium enterprise positioning; monochromatic palette

---

## 2. Logo Assets

All official logos are hosted on Cloudinary and available in the `assets/logos/` directory.

### Available Variants

| Variant | Format | Usage |
|---|---|---|
| Gray Logo (5×) | `.webp` | Light backgrounds, print |
| White Logo (5×) | `.webp` | Dark backgrounds (primary use) |
| Gray Logo with TM symbol (5×) | `.webp` | Official documents, light bg |
| White Logo with TM symbol (5×) | `.webp` | Official documents, dark bg |
| Gray Logo with ® symbol (5×) | `.webp` | Registered trademark contexts, light bg |
| White Logo with TM symbol (alternate) | `.webp` | Dark background alternate |

### Cloudinary URLs

```
Gray Logo (5×):
https://res.cloudinary.com/dkj22lm1g/image/upload/v1775641128/gray_logo_5x_cwicxw.webp

White Logo (5×):
https://res.cloudinary.com/dkj22lm1g/image/upload/v1775641127/white_logo_5x_ggabv7.webp

Gray Logo TM Symbol (5×):
https://res.cloudinary.com/dkj22lm1g/image/upload/v1775641127/gray_logo_tm_symbol_5x_fdlitk.webp

White Logo TM Symbol (5×):
https://res.cloudinary.com/dkj22lm1g/image/upload/v1775641127/white_logo_r_symol_5x_ahnaxp.webp

Gray Logo ® Symbol (5×):
https://res.cloudinary.com/dkj22lm1g/image/upload/v1775641127/gray_logom_r_symbol_5x_q7rdac.webp

White Logo TM Symbol (alternate):
https://res.cloudinary.com/dkj22lm1g/image/upload/v1775641128/white_logo_tm_symbol_5x_e2ydzd.webp
```

### Logo Sizing

Minimum display sizes:
- **Digital**: 120px wide
- **Print**: 25mm wide
- **Favicon / App icon**: Use simplified mark at 32×32px or 180×180px

### Clear Space

Always maintain a minimum clear space equal to the height of the letter "O" in the wordmark around all sides of the logo.

---

## 3. Colour Palette

The OVATE palette is monochromatic, centred on dark greys, near-black, and silver tones.

### Primary Colours

| Name | Hex | Tailwind Token | Usage |
|---|---|---|---|
| **Midnight** | `#000000` | — | Page background, primary surfaces |
| **Storm** | `#262626` | `storm` | Card backgrounds, secondary surfaces |
| **Silver** | `#B1B1B1` | `silver` | Body text, subtle accents |
| **Light** | `#C7C9C8` | `light` | Secondary text, borders |
| **Thunder** | `#BDB8AD` | `thunder` | Tertiary labels, micro-copy |
| **White** | `#FFFFFF` | — | Headings, logo on dark bg |

### Gradient

The scroll progress bar and highlight accents use:
```
linear-gradient(90deg, #B1B1B1, #FFFFFF)
```

### Do Not Use

- Saturated colours (blues, greens, reds) outside of approved system status indicators
- Off-brand accent colours from third-party themes

---

## 4. Typography

### Typefaces

| Role | Family | Weights |
|---|---|---|
| **Headings & Body** | DM Sans | 400, 500, 600, 700, 800 |
| **Labels, Tags, UI** | Inter | 300, 400, 500, 600, 700 |

Both typefaces are loaded via Google Fonts:
```html
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:ital,opsz,wght@0,9..40,100..1000;1,9..40,100..1000&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

### Type Scale

| Element | Size | Weight | Tracking |
|---|---|---|---|
| Hero H1 (desktop) | 68px | 700 | −0.03em |
| Hero H1 (mobile) | 36px | 700 | −0.03em |
| Section H2 (desktop) | 40px | 700 | −0.02em |
| Section H2 (mobile) | 32px | 700 | −0.02em |
| Card H3 | 18–22px | 600 | Default |
| Body | 15–17px | 400 | Default |
| Labels / Tags | 9–11px | 500 | +0.2em (uppercase) |

---

## 5. Spacing & Layout

### Grid

- **Max content width**: `1280px` (`max-w-7xl`)
- **Horizontal padding**: `px-6` (mobile), `px-8` (tablet), `px-12` (desktop)
- **Section vertical padding**: `py-24 md:py-36`

### Border Radius

| Element | Radius |
|---|---|
| Cards | `16px` |
| Buttons | `8px` |
| Tags / Badges | `999px` (pill) |

### Border Style

Cards and containers use: `1px solid rgba(255,255,255,0.06)`  
On hover: `1px solid rgba(255,255,255,0.12)`

---

## 6. Brand Voice & Tone

### Characteristics

- **Authoritative** — Speak as experts. Use precise terminology. Avoid hedging.
- **Direct** — Short sentences. Active voice. No fluff.
- **Professional** — Enterprise-grade audience. Avoid slang and casual language.
- **Reassuring** — Convey competence and reliability without arrogance.

### Do

- "We protect your organisation's critical assets."
- "CREST-accredited penetration testing."
- "24/7 managed detection and response."

### Don't

- "We're the best in the biz!"
- "Cutting-edge synergistic security solutions"
- Excessive exclamation points or emoji in formal contexts

---

## 7. Usage Rules

### Approved Uses

- Official OVATE Security website and digital properties
- Marketing collateral approved by OVATE Security
- Partner co-branding (requires written approval)
- PR and media with editorial context

### Prohibited Uses

- Modifying logo colours, proportions, or layout
- Placing the logo on visually competing or cluttered backgrounds
- Combining the OVATE logo with other logos without approval
- Using the brand for parody, criticism, or misleading purposes

---

*For brand usage questions or approval requests, contact: brand@ovatesecurity.com*
