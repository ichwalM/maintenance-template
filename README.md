# ICLABS — System Maintenance Page

A premium, production-ready maintenance page for the ICLABS digital infrastructure.

## Quick Start

Open `index.html` directly in any modern browser. No build step or local server required.

```
index.html
```

## Structure

```
/
├── index.html              # Complete maintenance page (HTML + CSS + JS)
├── assets/
│   ├── iclabs-logo.png     # ICLABS circuit chip logo
│   └── favicon.ico         # Browser tab icon
├── README.md               # This file
└── plant.md                # Original requirements
```

## Features

- **5-Phase Animation Loop** — System Online → Diagnostic → Maintenance Mode → Optimization → System Restored (~15s seamless cycle)
- **SVG Circuit Overlay** — Animated traces, nodes, and data pulses overlaid on the ICLABS logo
- **Responsive** — Optimized for all screen sizes from 360px to 1920px+
- **Performance** — GPU-friendly `transform`/`opacity` animations, minimal DOM elements, lightweight particles
- **Accessibility** — Semantic HTML, keyboard navigation, `aria-label`, `prefers-reduced-motion` support
- **Single File** — All CSS and JavaScript embedded in `index.html` for simple deployment

## External Dependencies

| Library | Version | CDN | Purpose |
|---------|---------|-----|---------|
| [GSAP](https://greensock.com/gsap/) | 3.12.5 | cdnjs | Complex timeline animations (phases, circuit effects) |
| [Inter](https://fonts.google.com/specimen/Inter) | Variable | Google Fonts | Primary UI typeface |
| [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) | 400 | Google Fonts | Monospace status text |

No frameworks (React, Vue, etc.) are used.

## Deployment

1. Upload the entire directory to your web server or static hosting.
2. Point your domain/subdomain to serve `index.html`.
3. Optionally configure your reverse proxy or CDN to serve this page during maintenance windows.

### Nginx Example

```nginx
server {
    listen 80;
    server_name yourdomain.com;

    root /path/to/maintenance-mode;
    index index.html;

    location / {
        try_files $uri /index.html =503;
    }
}
```

## Customization

Key CSS variables are defined at the top of the `<style>` block in `index.html`:

```css
:root {
  --color-bg: #0a0e14;
  --color-teal: #5ba4b5;
  --color-teal-bright: #6ec6d8;
  --logo-size: min(320px, 55vw);
  /* ... */
}
```

## Browser Support

Tested on modern evergreen browsers:
- Chrome / Edge 90+
- Firefox 90+
- Safari 15+
- Mobile Chrome / Safari

## License

Internal use — ICLABS.
