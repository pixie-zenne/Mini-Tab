# Tri Box (1.0.0)

**Tri Box** is a minimalist, single, static page that offers a clean and responsive three-box layout.

## Features

- **Responsive Grid Layout:** Three boxes arranged in a 2 by 1 grid that adapts to smaller screens by automatically stacking into a single column if the screen width is 768px and below.
- **Clean Design:** Minimalist UI with smooth shadows and rounded corners.

## Usage

Simply open `master.html` in a browser. The page displays three boxes:
- **Top Left:** Title display
- **Top Right:** Quick links
- **Bottom:** Random texts

## Customization

All colors, spacing, and dimensions are defined as CSS variables in the `:root` selector:
- `--primary-color`: Box color (#9381ff)
- `--secondary-color`: Page color (#b8b8ff)
- `--tertiary-color`: Text color (#f8f7ff)
- `--box-height`: Height of individual boxes (160px)
- `--gap`: Spacing between boxes (16px)
- `--radius`: Border radius for boxes (8px)
- `--container-width`: Maximum width of the grid container (768px)

## Responsive Breakpoints

- **Desktop (769px+):** The intended layout of the page will display
- **Mobile & Tablets (≤ 768px):** Single-column layout

## Browser Support

Works on all browsers that supports CSS Grid and Flexbox.

## License

Licensed under the MIT License. See LICENSE file for details.

