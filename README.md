# Blackroad Dashboard

[![Build Status](https://img.shields.io/github/actions/workflow/status/blackboxprogramming/blackroad-dashboard/deploy.yml?branch=main)](https://github.com/blackboxprogramming/blackroad-dashboard/actions) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Brand Compliant](https://img.shields.io/badge/Brand-Compliant-success)](https://brand.blackroad.io)

## 🌟 Features

- ✨ 

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/BlackRoad-OS/blackroad-dashboard.git

# Navigate to the directory
cd blackroad-dashboard

# Open in browser
open index.html
```

## 📦 Deployment

### Cloudflare Pages

This project is configured for automatic deployment via Cloudflare Pages:

1. Connected to GitHub repository
2. Auto-deploys on push to `main` branch
3. Preview deployments for all branches
4. Custom domain: blackroad-dashboard.pages.dev

**Live URL:** https://blackroad-dashboard.pages.dev

## 🎨 Brand Compliance

This project follows the official [BlackRoad Brand System](https://brand.blackroad.io):

- ✅ **Colors:** Amber (#F5A623), Hot Pink (#FF1D6C), Electric Blue (#2979FF), Violet (#9C27B0)
- ✅ **Spacing:** Golden Ratio (φ = 1.618)
- ✅ **Typography:** SF Pro Display, line-height: 1.618
- ✅ **Gradients:** 135° with stops at 38.2% & 61.8%
- ❌ **No forbidden colors** from old system

## 🛠️ Technology Stack

- **Frontend:** HTML5, CSS3 (Custom Properties)
- **Design System:** BlackRoad Brand System
- **Hosting:** Cloudflare Pages
- **CI/CD:** GitHub Actions
- **Version Control:** Git & GitHub

## 📂 Project Structure

```
blackroad-dashboard/
├── index.html          # Main page
├── README.md           # This file
├── CONTRIBUTING.md     # Contribution guidelines
├── LICENSE             # MIT License
└── .github/
    └── workflows/
        └── deploy.yml  # CI/CD workflow
```

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.

### Quick Contribution Guide

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m '✨ Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📋 Development

### Prerequisites

- Modern web browser
- Git
- Text editor (VS Code recommended)

### Local Development

Simply open `index.html` in your browser. No build process required!

### Brand Compliance Check

Ensure your changes follow the brand system:

```bash
# Check colors
grep -r "#FF1D6C\|#F5A623\|#2979FF\|#9C27B0" .

# Verify no forbidden colors
grep -r "#FF9D00\|#FF6B00\|#FF0066" . && echo "⚠️ Forbidden colors found!"
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌐 Part of BlackRoad OS

This repository is part of the [BlackRoad OS](https://blackroad.io) ecosystem.

### Related Projects

- [blackroad-os-web](https://github.com/BlackRoad-OS/blackroad-os-web) - Main platform
- [blackroad-os-docs](https://github.com/BlackRoad-OS/blackroad-os-docs) - Documentation
- [blackroad-os-brand](https://github.com/BlackRoad-OS/blackroad-os-brand) - Brand system

## 📞 Support

- **Documentation:** https://docs.blackroad.io
- **Issues:** https://github.com/BlackRoad-OS/blackroad-dashboard/issues
- **Email:** blackroad.systems@gmail.com

## 🙏 Acknowledgments

- Built with [Claude Code](https://claude.com/claude-code)
- Deployed on [Cloudflare Pages](https://pages.cloudflare.com)
- Part of the BlackRoad OS ecosystem

---

**Status:** 🟢 Active
**Last Updated:** 2026-01-07
**Maintained by:** BlackRoad OS Team
