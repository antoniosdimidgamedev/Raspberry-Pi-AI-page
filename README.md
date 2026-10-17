# 🍓 Raspberry Pi AI Products Showcase

An interactive, single-page web application showcasing the complete Raspberry Pi lineup with **AI-powered products**, localized pricing from official resellers worldwide, and a memory picker for multi-variant models.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-Ready-brightgreen)

---

## 🌐 Live Demo

> 🔗 **[View Live Demo](https://antoniosdimidgamedev.github.io/Raspberry-Pi-AI-page/)**

*(Replace with your actual GitHub Pages URL after deployment)*

---

## ✨ Features

### 🛍️ Product Catalog
- **Complete Raspberry Pi lineup**: Pi 1, Pi 2, Pi 3, Pi 4, Pi 5, Pi 500
- **Memory variants**: Pi 5 (1GB–16GB), Pi 4 (1GB–8GB), Pi 500 (8GB/16GB)
- **AI accessories**: AI Kit (Hailo-8L), AI Camera (IMX500), M.2 HAT+
- **Legacy models**: Zero, Zero 2 W, and older generations

### 🌍 Localization
- **IP-based country detection** using `ipapi.co` (with fallback)
- **50+ countries** supported with official Raspberry Pi resellers
- **Localized pricing** in native currencies (€, £, $, ¥, ₹, etc.)
- **Manual country picker** for users who want to override detection

### 🎨 User Experience
- **Interactive memory picker** — select RAM size to update prices live
- **Category filters** — All / Current / AI Accessories / Legacy
- **Detailed product modals** with tabs for Features, Specs, and Compatibility
- **Responsive design** — works on mobile, tablet, and desktop
- **Dark theme** with Raspberry Pi brand colors (red & green)

### 🔗 Integrations
- **Direct links** to official Raspberry Pi product pages
- **Buy buttons** redirecting to local official resellers
- **Documentation links** to raspberrypi.com

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic structure |
| **Tailwind CSS** (CDN) | Utility-first styling |
| **Vanilla JavaScript** | All interactivity (no frameworks) |
| **Fontsource** | Inter font family |
| **SVG** | Custom product illustrations |
| **IP API** | Geolocation detection |

---

## 📂 Project Structure

```
raspberry-pi-ai-shop/
├── index.html      # Main application (single file)
├── LICENSE         # MIT License
└── README.md       # This file
```

The entire application is contained in a single `index.html` file — no build step required!

---

## 🚀 Deployment

### Option 1: GitHub Pages (Recommended)

1. **Create a new repository** on GitHub
2. **Upload `index.html`** to the root of the repository
3. Go to **Settings → Pages**
4. Set source to **Deploy from branch** → `main` → `/ (root)`
5. Save — your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO/`

### Option 2: Netlify / Vercel

1. Drag and drop the folder containing `index.html`
2. Instant deployment with automatic HTTPS

### Option 3: Local Development

Simply open `index.html` in any modern browser. No server required!

---

## 🎯 Supported Countries & Resellers

| Region | Reseller | Currency |
|---|---|---|
| 🇬🇧 United Kingdom | Pimoroni | GBP (£) |
| 🇬🇷 Greece | NettOp | EUR (€) |
| 🇺🇸 United States | CanaKit | USD ($) |
| 🇩🇪 Germany | Berrybase | EUR (€) |
| 🇫🇷 France | Kubii | EUR (€) |
| 🇨🇦 Canada | CanaKit | CAD (C$) |
| 🇦🇺 Australia | Core Electronics | AUD (A$) |
| 🇯🇵 Japan | KSY | JPY (¥) |
| 🇮🇳 India | Robu.in | INR (₹) |
| ...and 40+ more | | |

*Full list available in the source code*

---

## 🖼️ Screenshots

> *Add screenshots here after deploying*

```
screenshots/
├── desktop-view.png
├── mobile-view.png
└── product-modal.png
```

---

## ⚙️ Configuration

### Changing Default Country
Edit the `detectLocation()` function in `index.html`:
```javascript
// Change fallback from 'GB' to your preferred country code
setReseller('GB'); // e.g., 'US', 'DE', 'GR'
```

### Adding a New Reseller
Add an entry to the `resellers` object:
```javascript
'XX': { 
    name: 'Reseller Name', 
    url: 'https://reseller.com', 
    currency: 'XXX', 
    symbol: '$', 
    flag: '🏳️', 
    country: 'Country Name' 
}
```

### Updating Exchange Rates
Edit the `exchangeRates` object with current rates (relative to USD).

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- 🐛 Report bugs
- 💡 Suggest new features
- 🔧 Submit pull requests
- 🌍 Add more resellers for your country

---

## ⚠️ Disclaimer

This is an **unofficial project** and is not affiliated with, endorsed by, or connected to **Raspberry Pi Ltd**.

- **Raspberry Pi** is a registered trademark of Raspberry Pi Ltd.
- All product names, logos, and brands are property of their respective owners.
- Prices shown are **approximate conversions** from official USD RRPs and may differ from actual reseller prices.
- Exchange rates are static and may be outdated.
- Reseller information is provided for convenience; always verify on the reseller's website.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

```
MIT License — Copyright (c) 2026 [Your Name]
```

---

## 🙏 Acknowledgments

- 🍓 **[Raspberry Pi Foundation](https://www.raspberrypi.com/)** — for creating the amazing Raspberry Pi ecosystem
- 🎨 **[Tailwind CSS](https://tailwindcss.com/)** — for the utility-first CSS framework
- 🌍 **[IP-API](https://ip-api.com/)** & **[ipapi.co](https://ipapi.co/)** — for geolocation services
- 🤖 Built with assistance from **Qwen 3.7 Plus**

---

## 📬 Contact

Have questions or suggestions? Open an [issue](../../issues) on GitHub!

---

<div align="center">

**Made with ❤️ for the Raspberry Pi community**

[⬆ Back to Top](#-raspberry-pi-ai-products-showcase)

</div>
