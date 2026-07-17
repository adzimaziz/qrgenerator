# ✨ QR Studio — Beautiful QR Code Generator

> Generate stunning, customizable QR codes in six unique design styles — all from your browser, no server required.

![QR Studio Screenshot](screenshot.png)

---

## 🎨 Features

- **6 Unique QR Designs** — Choose from Classic, Gradient, Rounded, Neon Glow, Elegant, and Minimal styles
- **Instant Generation** — QR codes are generated entirely client-side with zero latency
- **High-Quality PNG Downloads** — Every design can be downloaded as a crisp 400×450 PNG image
- **Custom Titles** — Add a title that gets embedded directly into the QR code image
- **Dark Mode UI** — Premium dark theme with glassmorphism design and smooth animations
- **Fully Responsive** — Works beautifully on desktop, tablet, and mobile devices
- **No Dependencies** — Single HTML file with everything included (no build step required)
- **Privacy First** — All processing happens in-browser; no data is sent to any server

## 🖼️ Design Styles

| Style | Description |
|-------|-------------|
| **Classic** | Standard black-on-white QR code — clean and universally scannable |
| **Gradient** | Vibrant blue → purple → pink gradient fill |
| **Rounded** | Circular dot modules for a softer, modern look |
| **Neon Glow** | Cyan modules with glow effect on a dark background |
| **Elegant** | Navy modules on cream with decorative gold border and serif title |
| **Minimal** | Gray modules with generous whitespace and clean typography |

## 🚀 Getting Started

### Quick Start

1. **Download** or clone this repository
2. **Open** `index.html` in any modern web browser
3. **Paste** a URL and click **Generate QR Codes**
4. **Download** your favorite design as PNG

```bash
# Clone the repo
git clone <repository-url>

# Open in browser (macOS)
open index.html

# Open in browser (Windows)
start index.html

# Open in browser (Linux)
xdg-open index.html
```

### Requirements

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for loading Google Fonts and the QR library CDN on first visit)

## 🛠️ Technologies

| Technology | Purpose |
|------------|---------|
| **HTML5 Canvas** | QR code rendering with pixel-perfect control |
| **CSS3** | Glassmorphism, animations, responsive grid layout |
| **Vanilla JavaScript** | Application logic, canvas drawing, file downloads |
| [**qrcode-generator**](https://github.com/nichibashi/qrcode-generator) | QR code data encoding (v1.4.4 via CDN) |
| [**Google Fonts**](https://fonts.google.com/) | Inter + Space Grotesk typefaces |

## 📁 Project Structure

```
QR Generator/
├── index.html          # Complete application (HTML + CSS + JS)
└── README.md           # This file
```

## 🎯 Browser Support

| Browser | Version |
|---------|---------|
| Chrome | 80+ |
| Firefox | 78+ |
| Safari | 14+ |
| Edge | 80+ |

## 📝 License

This project is licensed under the **MIT License**.

```
MIT License

Copyright (c) 2025 QR Studio

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

<p align="center">Made with ♥ by QR Studio</p>
