# Lottie oEmbed Host

This repo hosts multiple Lottie animations with embeddable HTML pages and oEmbed JSON endpoints via GitHub Pages.

## 📁 Structure

Each subfolder (e.g., `wave/`) contains:
- A Lottie animation (`*.json`)
- A player page (`index.html`)
- A corresponding `oembed.json`

## 🎯 Usage

### Direct Embedding
Each animation can be embedded directly via iframe:
```html
<iframe src="https://bhipps.github.io/lottie-oembed/wave/" width="400" height="300"></iframe>
```

### oEmbed Support
Each animation provides an oEmbed endpoint for automatic embedding:
- oEmbed URL: `https://bhipps.github.io/lottie-oembed/wave/oembed.json`
- Player URL: `https://bhipps.github.io/lottie-oembed/wave/`

## 🚀 Available Animations

- [Wave Animation](wave/) - A smooth wave animation
- [Confetti Animation](confetti/) - Celebratory confetti burst
- [Logo Spin Animation](logo-spin/) - Rotating logo animation

## 📖 oEmbed Specification

This project follows the [oEmbed specification](https://oembed.com/) for rich content embedding.
