# Changelog

All notable changes to the LUCA Free License project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [1.1.0] - 2026-02-28

### Added
- Mobile-first hamburger navigation menu for small screens (`docs/js/main.js`)
- Skip-to-content link for keyboard accessibility
- Open Graph and Twitter Card meta tags on all HTML pages
- `prefers-color-scheme` dark mode support via CSS custom properties
- `prefers-reduced-motion` media query to respect user preferences
- `IntersectionObserver`-based scroll-triggered animations for cards and features
- Active page highlighting in navigation via `aria-current="page"`
- Two extra responsive breakpoints: tablet (≤1024 px) and small-mobile (≤480 px)
- `loading="lazy"` attribute on all badge images
- `rel="noopener noreferrer"` on all `target="_blank"` links (security fix)

### Changed
- CSS rewritten with modern techniques: `clamp()` for fluid typography, CSS logical properties, `gap` tokens, and a consolidated `--transition` variable
- Navigation layout now uses a proper `height: var(--nav-height)` flex container
- Hard-coded `1fr 1fr` inline grid styles in `about.html` and `usage.html` replaced with responsive `.two-col-grid` class
- `<main id="main-content">` semantic wrapper added to every page
- All `<nav>` elements now carry `aria-label="Primary navigation"` and a linked `<ul id="nav-menu">`
- `font-family` updated to include `ui-monospace` and `SFMono-Regular` in monospace stacks
- Footer links deduplicated; each external link now carries `rel="noopener noreferrer"`
- Hamburger button uses pure CSS transform animation (no images, no icon font)

## [1.0.0] - 2026-02-03

### Added
- Initial release of LUCA Free License v1.0
- Comprehensive documentation:
  - README.md with overview and quick start
  - ABOUT.md with philosophy and background
  - FAQ.md with frequently asked questions
  - USAGE.md with detailed usage instructions
  - BADGES.md with all badge variations
  - CONTRIBUTING.md for contributors
- Full HTML website in /docs folder:
  - index.html - Landing page with license overview
  - about.html - Detailed information about LUCA
  - usage.html - Complete usage guide
  - faq.html - Frequently asked questions
  - 404.html - Custom 404 page
  - style.css - Professional styling
- Badge support for multiple colors and styles
- GitHub Pages support with .nojekyll
- License text (COPYING file)

### Core License Features
- Maximum freedom - "DO WHAT THE FUCK YOU WANT TO"
- No attribution required
- No copyleft restrictions
- Implicit patent grant
- Clear warranty disclaimer
- Severability clause for legal protection
- Self-modifiable license

---

**Licensed under LUCA v1.0 - DO WHAT THE FUCK YOU WANT TO.**
