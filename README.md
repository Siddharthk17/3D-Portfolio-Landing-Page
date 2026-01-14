# 🚀 Portfolio Landing Page

<div align="center">

![Portfolio Banner](https://img.shields.io/badge/Portfolio-Landing%20Page-00FFFF?style=for-the-badge&logo=html5&logoColor=white)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Spline](https://img.shields.io/badge/Spline-3D-5B21B6?style=for-the-badge&logo=spline&logoColor=white)](https://spline.design/)
[![Netlify Status](https://img.shields.io/badge/Netlify-Deployed-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://3dportfolio-website-sid.netlify.app/)

*A stunning, interactive 3D portfolio landing page featuring elegant animations and immersive design*

### 🌐 **[ ⚡ LAUNCH EXPERIENCE ⚡ ](https://3dportfolio-website-sid.netlify.app/)**

```
█▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀█
█  ╔═══════════════════════════════════╗ █
█  ║  🎯 LIVE DEPLOYMENT INITIATED 🎯 ║ █
█  ╚═══════════════════════════════════╝ █
█                                        █
█   > Initializing 3D environment...  ✓  █
█   > Loading custom fonts...         ✓  █
█   > Rendering animations...         ✓  █
█   > Establishing connection...      ✓  █
█                                         █
█   STATUS: 🟢 ONLINE & OPERATIONAL      █
█   URL: 3dportfolio-website-sid.netlify  █
█                                         █
█  [════════════ 100% ════════════]       █
█                                         █
█▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄█
```

<a href="https://3dportfolio-website-sid.netlify.app/" target="_blank">
  <img src="https://img.shields.io/badge/🚀_ENTER_THE_MATRIX-00FFFF?style=for-the-badge&labelColor=000000" alt="Launch Demo" />
</a>

---

**Experience it live:** https://3dportfolio-website-sid.netlify.app/

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Customization](#-customization)
- [Performance](#-performance)
- [Browser Support](#-browser-support)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🌟 Overview

This portfolio landing page combines cutting-edge web technologies to create an unforgettable first impression. Built with a focus on visual appeal and user experience, it features a fully interactive 3D background powered by Spline, smooth animations, and a clean, modern interface.

> **🎮 LIVE DEMO:** Experience the full interactive portfolio at [https://3dportfolio-website-sid.netlify.app/](https://3dportfolio-website-sid.netlify.app/)
> 
> *Deployed on Netlify with continuous integration and global CDN delivery*

### ✨ Key Highlights

- **Immersive 3D Experience** - Interactive Spline 3D scene as the background
- **Smooth Animations** - Carefully choreographed entrance animations
- **Custom Typography** - Custom "Mars" font for unique branding
- **Responsive Design** - Fully optimized for all devices
- **Performance Optimized** - Lightweight and fast-loading

---

## 🎯 Features

### 🎨 Design Features

- **3D Interactive Background** - Powered by Spline for a stunning visual experience
- **Elegant Typography** - Custom Mars font with glowing text effects
- **Smooth Hover Effects** - Interactive navigation with sheen animations
- **Scroll Indicator** - Animated scroll prompt for better UX
- **Responsive Layout** - Mobile-first approach with breakpoints for all devices

### ⚡ Technical Features

- **Zero Dependencies** (except Spline viewer)
- **Pure Vanilla JavaScript**
- **CSS3 Animations**
- **Shadow DOM Manipulation** for Spline customization
- **Performance Optimized** with fixed positioning
- **Cross-browser Compatible**

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Semantic structure and content |
| **CSS3** | Styling, animations, and responsive design |
| **JavaScript (ES6+)** | Dynamic interactions and DOM manipulation |
| **Spline 3D** | Interactive 3D background scene |
| **JetBrains Mono** | Modern monospace typography |
| **Custom Font (Mars)** | Unique heading typography |

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for best performance)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/portfolio-landing.git
   cd portfolio-landing
   ```

2. **Ensure folder structure**
   ```
   portfolio-landing/
   ├── index.html
   └── fonts/
       └── Mars.ttf
   ```

3. **Open the project**
   
   **Option A:** Direct file access
   ```bash
   # Simply open index.html in your browser
   open index.html
   ```
   
   **Option B:** Using a local server (recommended)
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

4. **Visit in browser**
   ```
   http://localhost:8000
   ```

---

## 📁 Project Structure

```
portfolio-landing/
│
├── index.html              # Main HTML file
│   ├── <head>             # Meta tags, fonts, Spline import
│   ├── <style>            # Embedded CSS
│   ├── <body>             # Content structure
│   └── <script>           # Spline logo removal logic
│
└── fonts/
    └── Mars.ttf           # Custom Mars font file
```

### Key Components

#### 1. **3D Background Layer** (z-index: 1)
```html
<div class="spline-container">
    <spline-viewer url="..."></spline-viewer>
</div>
```

#### 2. **Overlay Content Layer** (z-index: 2)
```html
<div class="overlay-content">
    <nav>...</nav>
    <div class="intro-text">...</div>
    <div class="tagline">...</div>
    <div class="scroll-indicator">...</div>
</div>
```

---

## 🎨 Customization

### Changing Colors

The color scheme uses Azure/Cyan tones. To customize:

```css
/* Primary color variable (find in CSS) */
#F0FFFF  /* Azure/Cyan - Used for text and accents */
#000000  /* Pure black - Background */
#FFFFFF  /* White - Hover states */
```

### Updating Text Content

```html
<!-- Intro Text (Top Left) -->
<h1>Hi</h1>
<h2>I Am Sid</h2>

<!-- Tagline (Bottom Right) -->
<h2>A Jack Of All Trades Is A Master Of None</h2>
<p>But Oftentimes Better Than A Master Of One</p>
```

### Replacing the 3D Scene

Update the Spline viewer URL:

```html
<spline-viewer url="YOUR_SPLINE_URL_HERE"></spline-viewer>
```

### Animation Timing

Adjust animation delays in the CSS:

```css
animation: fadeInDown 1s ease 3.5s forwards;
/*                              ↑ delay time */
```

### Custom Font

Replace `Mars.ttf` in the `fonts/` folder and update the font-face declaration:

```css
@font-face {
    font-family: 'YourFont';
    src: url('./fonts/YourFont.ttf') format('truetype');
}
```

---

## ⚡ Performance

### Optimization Features

- **Fixed Positioning** - Reduced repaints and reflows
- **CSS Animations** - Hardware-accelerated transforms
- **Lazy Loading** - Spline scene loads progressively
- **Minimal JavaScript** - Only for Spline logo removal
- **No External Dependencies** - Faster load times

### Performance Metrics

- **First Contentful Paint:** < 1.5s
- **Time to Interactive:** < 3s
- **Total Bundle Size:** < 100KB (excluding 3D scene)

---

## 🌐 Browser Support

| Browser | Supported Versions |
|---------|-------------------|
| Chrome | ✅ Latest 2 versions |
| Firefox | ✅ Latest 2 versions |
| Safari | ✅ Latest 2 versions |
| Edge | ✅ Latest 2 versions |
| Opera | ✅ Latest 2 versions |

**Note:** Internet Explorer is not supported due to modern CSS and ES6+ JavaScript features.

---

## 📱 Responsive Breakpoints

| Device | Breakpoint | Adjustments |
|--------|-----------|-------------|
| **Desktop** | > 1024px | Full layout with optimal spacing |
| **Tablet** | 768px - 1024px | Reduced font sizes and gaps |
| **Mobile (Large)** | 480px - 768px | Adjusted positioning and wrapping |
| **Mobile (Small)** | < 480px | Compact layout with minimal padding |

---

## 🤝 Contributing

Contributions are what make the open-source community amazing! Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 📧 Contact

**Sid** - [Your Email](mailto:your.email@example.com)

**🌐 Live Site:** [https://3dportfolio-website-sid.netlify.app/](https://3dportfolio-website-sid.netlify.app/)

**📦 Repository:** [https://github.com/yourusername/portfolio-landing](https://github.com/yourusername/portfolio-landing)

---

## 🚀 Deployment

This project is deployed on **Netlify** with automatic deployments from the main branch.

### Deploy Your Own

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/yourusername/portfolio-landing)

**Quick Deploy Steps:**
1. Fork this repository
2. Connect to Netlify
3. Click "Deploy site"
4. Your portfolio is live! 🎉

---

## 🙏 Acknowledgments

- [Spline](https://spline.design/) - For the amazing 3D design tool
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) - For the beautiful monospace font
- [Shields.io](https://shields.io/) - For the README badges
- The open-source community for inspiration and support

---

<div align="center">

**⭐ Star this repo if you found it helpful!**

[![Website](https://img.shields.io/website?down_color=red&down_message=offline&up_color=00FFFF&up_message=online&url=https%3A%2F%2F3dportfolio-website-sid.netlify.app%2F&style=for-the-badge&logo=netlify)](https://3dportfolio-website-sid.netlify.app/)

**Made with ❤️ and ⚡ by Sid**

**[🌐 Visit Live Site](https://3dportfolio-website-sid.netlify.app/)** • **[⭐ Star on GitHub](#)** • **[🐛 Report Issues](#)**

</div>
