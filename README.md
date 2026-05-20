# ☂️ Lumintu - Modern Insurance Solutions

Lumintu is a pixel-perfect, fully responsive corporate insurance landing page built as part of the Frontend Development Assignment. The project converts a premium Figma design into clean, semantic HTML5 and modular SASS (SCSS) architecture.

## 🌟 Key Features

- **Advanced SASS Architecture:** Organized codebase using partials (`_hero.scss`, `_service.scss`, `_why-lumintu.scss`, etc.).
- **Dynamic CSS Generation:** Used SASS variables, loops (`@each` for status alerts), and mathematical functions (`pxToRem`) for pixel-perfect typography.
- **Pixel-Perfect UI Replication:** Successfully handled complex CSS positioning bugs, including the overlapping floating rating cards on images.
- **100% Responsive Design:** Built using flexible flexbox layouts, CSS Grid, and custom SASS mixins for desktop, tablet, and mobile breakpoints.

---

## 📁 Project Structure

```text
Lumintu-Insurance/
│
├── index.html                  # Main Semantic HTML5 File
│
├── assets/
│   ├── css/
│   │   ├── style.min.css       # Compiled & Production-Ready CSS
│   │   └── style.min.css.map   # Source Map File for accurate debugging
│   │
│   ├── scss/                   # Modular SASS Structure
│   │   ├── style.scss          # Core SASS File (Imports all partials)
│   │   ├── _variables.scss     # Design System Tokens (Colors, Fonts)
│   │   ├── _mixin.scss         # Media Queries & Breakpoints
│   │   ├── _function.scss      # pxToRem Conversion Utilities
│   │   ├── _hero.scss          # Hero Section styles & animations
│   │   ├── _why-lumintu.scss   # Floating rating layout fixes
│   │   └── ...                 # Other Component Partials
│   │
│   ├── icon/                   # SVG Icons (Umbrella logo, etc.)
│   └── images/                 # Optimized Images used in design



Tech Stack Used-
HTML5: Semantic layouts (<header>, <section>, <span> instead of block structures for inline text alignment).
SASS (SCSS): Advanced modular layout properties, variables, nesting, maps, and functions.
Bootstrap Icons: Light-weight vector font iconography.
Google Fonts: DM Sans typography engine.
