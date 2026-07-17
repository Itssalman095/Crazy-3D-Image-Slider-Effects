# 3D CSS Carousel Gallery

A visually immersive image gallery built with pure HTML, CSS, and vanilla JavaScript — no libraries or frameworks. Features a rotating 3D carousel banner and a scroll-triggered showcase section.


## 🚀 Demo
[Live Demo](https://itssalman095.github.io/Crazy-3D-Image-Slider-Effects/)
## Features

- **3D Rotating Carousel** — A CSS `transform-style: preserve-3d` carousel that continuously auto-rotates 10 images in 3D space using `rotateY` and `translateZ`.
- **Animated Scroll Progress Bar** — A fixed top progress indicator powered by the CSS `animation-timeline: scroll()` property (no JavaScript required).
- **Scroll-Reveal Showcase Section** — 10 detailed image entries that fade and slide into view as you scroll, using the `IntersectionObserver` API.
- **Alternating Layout** — Showcase items alternate between left-aligned and right-aligned (reversed) layouts for visual rhythm.
- **Smooth Back-to-Top Navigation** — A button that smoothly scrolls back to the top of the page.
- **Fully Responsive** — Layout adapts for tablet (≤900px) and mobile (≤600px) screen sizes.

## Tech Stack

- HTML5
- CSS3 (3D transforms, custom properties, `backdrop-filter`, scroll-driven animations)
- Vanilla JavaScript (`IntersectionObserver`, smooth scrolling)

## Project Structure

```
.
├── index.html   # Page markup and inline JS
└── style.css    # All styling and animations
```

## Getting Started

No build tools or dependencies are required.

1. Clone the repository:
   ```bash
   git clone https://github.com/Itssalman095/Crazy-3D-Image-Slider-Effects.git
   ```
2. Open `index.html` directly in your browser, or serve it with a local dev server (e.g. the VS Code "Live Server" extension) for the best experience.

## Browser Support

This project relies on modern CSS features (`animation-timeline: scroll()`, `backdrop-filter`, 3D transforms). For the best experience, use a recent version of Chrome or Edge — scroll-driven animations are not yet supported in all browsers.

## Credits

- Fonts: [ICA Rubik](https://fonts.cdnfonts.com/css/ica-rubik-black) & [Poppins](https://fonts.cdnfonts.com/css/poppins) via CDN Fonts
- Images: Sourced from Pinterest for demo purposes — replace with your own or licensed images before deploying publicly

## Author

**Salman**
Web Design — immersive web experiences using pure CSS, HTML, and JavaScript.

## License

This project is open source and available under the [MIT License](LICENSE).
