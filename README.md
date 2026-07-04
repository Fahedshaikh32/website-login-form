<div align="center">

# 🌐 Website Login Form

**A clean, modern login page UI built with pure HTML5 and CSS3.**

A warm, editorial-style login card with a serif/sans type pairing, a soft teal accent, and a single self-contained file — no build tools, no dependencies.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](#)
[![License](https://img.shields.io/badge/license-MIT-green)](#license)
[![Status](https://img.shields.io/badge/status-complete-brightgreen)](#)

[Preview](#preview) •
[Features](#features) •
[Getting Started](#getting-started) •
[Project Structure](#project-structure) •
[Design Details](#design-details) •
[Roadmap](#roadmap)

</div>

---

## Preview

<div align="center">
<img width="900" alt="Login page preview" src="https://github.com/user-attachments/assets/504e64f7-9df7-4e14-865b-b1e3a6eeffe6" />
</div>

## Features

- 🎨 **Warm, editorial design** — cream background, italic serif heading, and a single deep-teal accent color
- 🧩 **Self-contained single file** — all CSS lives inside `<style>` in `index.html`, so there's nothing to misconfigure or lose track of
- ⌨️ **Accessible form markup** — every `<label>` is properly linked to its `<input>` via `for`/`id`, with `autocomplete` hints
- 🎯 **Interactive focus states** — inputs highlight with a soft teal glow on focus
- 📱 **Responsive layout** — scales cleanly down to mobile widths
- ⚡ **Zero dependencies** — no frameworks, no build step, just HTML and CSS (plus a Google Fonts link for typography)

## Getting Started

### Prerequisites

Just a web browser. No build tools, package managers, or servers required.

### Run locally

```bash
git clone https://github.com/Fahedshaikh32/website-login-form.git
cd website-login-form
```

Then open `index.html` directly in your browser:

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

Or simply double-click `index.html` in your file explorer — every style is embedded in the file itself, so it will always render fully styled, with no separate stylesheet to keep track of.

## Project Structure

```
.
├── index.html    # Markup + embedded styles (single self-contained file)
└── README.md
```

## Design Details

| Element | Styling approach |
|---|---|
| Page background | Warm paper cream (`#f6f1e9`) |
| Accent color | Deep teal (`#1e5f5a`), used for the eyebrow label, input focus ring, button, and link |
| Typography | *Fraunces* (italic serif) for the heading, *Inter* (sans-serif) for labels, inputs, and body text |
| Signature shape | A single soft, low-opacity teal circle in the top-left corner for subtle depth |
| Card | White card with a soft shadow and rounded corners — no glass/blur effects, kept simple |
| Inputs | Cream-tinted fields with a teal border and glow on focus |
| Button | Solid teal, full-width, with a subtle hover fade |

## Roadmap

- [ ] Add client-side form validation
- [ ] Add a "Remember me" checkbox and "Forgot password?" link
- [ ] Add social login buttons
- [ ] Wire up actual authentication (backend integration)
- [ ] Add a dark theme toggle

## Contributing

Contributions are welcome. If you'd like to improve the design or add functionality:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes
4. Open a pull request

## License

This project is available under the MIT License. See the `LICENSE` file for details.

## Author

**Fahed Shaikh**

<div align="center">

If you find this project useful, consider giving it a ⭐

</div>
