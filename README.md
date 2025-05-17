# Simple Site - SCSS Learning Project

A responsive web project built using SCSS/Sass for educational purposes. This project demonstrates the implementation of modern CSS preprocessing techniques and responsive design principles.

## Project Overview

This project is a single-page website that includes:
- Responsive navigation
- Hero section
- About section
- Experience showcase
- Work process description
- Video integration
- Footer

## Technical Stack

- HTML5
- SCSS/Sass
- Gulp build system
- BEM methodology
- Mobile-first approach

## Project Structure

```
simple-site-figma-project-nr1/
├── src/
│   └── scss/
│       ├── base/
│       ├── components/
│       ├── mixins/
│       └── presets/
├── assets/
│   ├── css/
│   ├── images/
│   └── js/
└── index.html
```

## SCSS Architecture

The project follows the 7-1 pattern for SCSS organization:
- `presets/`: Variables, colors, and base configurations
- `base/`: Typography and normalize
- `components/`: Individual component styles
- `mixins/`: Reusable SCSS mixins

## Features

- Responsive design with multiple breakpoints (1200px, 992px, 576px, 375px)
- BEM naming convention
- CSS custom properties
- Flexbox layouts
- Media queries optimization
- Cross-browser compatibility
- Performance optimization

## Development

1. Install dependencies:
```bash
npm install
```

2. Run development server:
```bash
gulp watch
```

3. Build for production:
```bash
gulp scss
```

## CSS Features

- Mobile-first approach
- Modular SCSS architecture
- Custom utility classes
- Responsive containers
- Flexible grid system

## Author

- Bohdan Horobets. Created as an educational project

## License

MIT License