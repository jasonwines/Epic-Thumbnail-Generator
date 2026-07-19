# Epic Thumbnail Generator

A lightweight, single-file HTML5 Canvas utility designed to create crisp, highly customizable thumbnails directly in your web browser. Built entirely with HTML, CSS, and vanilla JavaScript, this tool requires no backend server or external dependencies to run.

---

## 🚀 Quick Start

1. Download or clone the `index.html` file.
2. Double-click the file to open it in any modern web browser (Safari, Edge, Chrome, etc.).
3. Start designing!

---

## 🛠️ Features

### Canvas Controls
* **Multiple Aspect Ratios:** Quickly switch between standard formats (16:9, 21:9, 16:10, 4:3).
* **Local Export:** Render and download your composition instantly as a high-quality `.png` with custom file naming.
* **UI Themes:** Toggle between Dark Mode (default) and Light Mode to suit your workspace preferences.

### Layer 1: Background
* **Solid Colors:** Choose any hex color using the native browser color picker.
* **Linear Gradients:** Build custom two-color gradients with fine-tuned control over the angle (0-360°) and center offset (0-100%).

### Layer 2: Image Overlay
* **Smart Auto-Fit:** Uploaded images automatically calculate scale to fit the canvas with a safe 150px padding.
* **Center Anchoring:** Scale and transform images symmetrically from their true center.
* **Soft Edge Masking:** Toggle a dynamic vignette effect with a configurable percentage slider to seamlessly blend images into the background.
* **Full Canvas Positioning:** X and Y axis sliders allow you to drag images completely off-screen if needed.

### Layer 3: Text Overlay
* **Typography:** Select from 5 classic, high-impact fonts (Impact, Arial, Courier New, Georgia, Trebuchet MS).
* **Dynamic Scaling:** Font sizes up to 500px, anchored perfectly to the center for predictable layout adjustments.
* **Custom Outlines:** Add a colored stroke around your text with adjustable thickness to prevent background bleed.
* **Advanced Drop Shadows:** Configure shadow color, opacity (alpha), blur radius (hard to soft edges), and independent X/Y offsets.

---

## 💻 Technical Details

* **Language:** HTML5, CSS3, JavaScript (ES6)
* **Rendering Engine:** `<canvas>` API (`2d` context)
* **Architecture:** Zero-dependency, single-file deployment. All image processing and compositing is handled client-side to ensure privacy and speed. 
* **Compositing:** Utilizes `globalCompositeOperation = 'source-in'` for advanced masking techniques (Soft Edges).

---

## 👨‍💻 Author & Support

**Version 1.0** 
Created by Jason Wines in July 2026.

If you find this project helpful, please consider making a donation to support its continued development and the creation of other niche projects. While I'm happy to provide these resources for free, your contributions help offset the time and costs associated with maintaining them. Thank you for your support!

[Buy me a coffee! ☕](https://buymeacoffee.com/jasonwines)
