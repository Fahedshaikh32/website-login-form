<div align="center">

# 🌐 Website Login Form

**A clean, modern login page UI built with pure HTML5 and CSS3.**

No frameworks, no dependencies — just a glassmorphism-style form with animated gradient shapes and a fully responsive layout.

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

- 🎨 **Glassmorphism design** — frosted-glass form with `backdrop-filter: blur()` over a dark background
- 🟠🔵 **Animated gradient shapes** — floating blurred circles for visual depth
- 📱 **Responsive layout** — centers and scales cleanly across screen sizes
- 🧩 **Minimal, semantic markup** — a single form with labeled username/password fields
- ⚡ **Zero dependencies** — plain HTML and CSS, no build step required

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

> **Note:** The stylesheet is linked as `style.css` (lowercase) in `index.html`, while the file in this repo is named `Style.css`. On case-sensitive file systems (Linux, and GitHub Pages) this mismatch will break the styling — rename the file to `style.css` or update the `<link>` tag to match. See [Design Details](#design-details) below.

## Project Structure

```
.
├── index.html    # Page markup: background shapes + login form
├── Style.css     # Glassmorphism styling, gradients, layout
└── README.md
```

## Design Details

| Element | Styling approach |
|---|---|
| Page background | Solid dark navy (`#080710`) |
| Decorative shapes | Two absolutely-positioned circles with linear gradients (blue and orange), placed behind the form |
| Form container | Semi-transparent white background, blurred backdrop, subtle border and shadow — the "frosted glass" effect |
| Inputs | Full-width, softly tinted fields with rounded corners and light placeholder text |
| Submit button | Solid white button with bold text for strong contrast against the dark theme |

## Roadmap

- [ ] Fix `style.css` / `Style.css` filename casing to prevent broken styling on case-sensitive hosts
- [ ] Add client-side form validation
- [ ] Add a "Remember me" checkbox and "Forgot password?" link
- [ ] Add social login buttons (styles already scaffolded in CSS)
- [ ] Wire up actual authentication (backend integration)
- [ ] Add dark/light theme toggle

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
