# ENM Beamer Template

A LaTeX Beamer presentation template for the **Department of Engineering Management (ENM)** at the University of Antwerp.

## About

This is a custom Beamer theme designed for presentations by the Department of Engineering Management (ENM) at the University of Antwerp. The theme provides a professional and consistent look with ENM/University of Antwerp branding, including custom colors, logos, and layouts.

## Installation

1. Clone or download this repository
2. Place the `theme/` folder in your project directory
3. Ensure the `art/` folder is accessible for logo graphics

## How to Use

To use this theme in your presentation:

1. **Keep the folder structure intact:** Ensure both the `theme/` and `art/` folders are in the same directory as your main `.tex` file
2. **Add the path configuration** to your preamble (before `\usetheme`):
   ```latex
   \makeatletter
   \def\input@path{{theme/}}
   \makeatother
   ```
3. **Load the theme:**
   ```latex
   \usetheme{ENM}
   ```
4. **Compile** your document with pdfLaTeX or XeLaTeX

See `ENM-beamer.tex` for a complete working example.

## File Structure

```
.
├── theme/
│   ├── beamerthemeENM.sty            # Main theme file
│   ├── beamercolorthemeENM.sty       # Color definitions
│   ├── beamerfontthemeENM.sty        # Font settings
│   ├── beamerinnerthemeENM.sty       # Inner theme elements
│   └── beamerouterthemeENM.sty       # Outer theme elements
├── art/                               # Graphics and logos
│   ├── enm-logo.pdf
│   ├── enm-logo-text-white.pdf
│   ├── enm-logo-white.pdf
│   ├── enmBackground.pdf
│   └── ...
├── pictures/                          # Your presentation images
└── ENM-beamer.tex                     # Example presentation
```

