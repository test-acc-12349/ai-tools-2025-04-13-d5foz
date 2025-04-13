# AI Tools Directory 🤖

> The ultimate directory of AI tools and resources for enhancing productivity and creativity.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Demo](#demo)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Customization](#customization)
- [Deployment](#deployment)
- [Custom Domain Setup](#custom-domain-setup)
- [Troubleshooting](#troubleshooting)
- [Resources](#resources)
- [Support](#support)

## Overview
AI Tools Directory is a curated collection of artificial intelligence tools organized in a clean, responsive 3-column grid layout. The directory showcases various AI-powered solutions including writers, SEO tools, chrome extensions, and more.

## Features
- Responsive 3-column grid layout
- Category filtering system
- Search functionality
- Tool cards with descriptions
- Category labels (ai, new, sale)
- Mobile-friendly design
- SEO optimized
- Fast loading performance

## Demo
Visit the live demo: [https://ai-tools-directory.com](https://ai-tools-directory.com)

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- Basic knowledge of HTML/CSS

### Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/ai-tools-directory.git

# Navigate to project directory
cd ai-tools-directory

# Install dependencies
npm install

# Start development server
npm run dev
```

## Directory Structure
```
ai-tools-directory/
├── src/
│   ├── components/
│   │   ├── Header.js
│   │   ├── ToolCard.js
│   │   └── CategoryFilter.js
│   ├── data/
│   │   └── tools.json
│   └── styles/
│       └── main.css
├── public/
│   └── images/
├── package.json
└── README.md
```

## Customization

### Adding/Editing Directory Items
Edit the `src/data/tools.json` file:
```json
{
  "tools": [
    {
      "id": "1",
      "name": "AI Writer Pro",
      "description": "Advanced AI writing assistant",
      "category": ["ai", "new"],
      "url": "https://example.com",
      "image": "/images/ai-writer.png"
    }
  ]
}
```

### Modifying Category Labels
Update categories in `src/components/CategoryFilter.js`:
```javascript
const categories = ['ai', 'new', 'sale'];
```

### Updating Hero Section
Modify the hero section in `src/components/Header.js`:
```html
<div class="hero">
  <h1>Your New Title</h1>
  <p>Your new description text</p>
</div>
```

### Customizing Colors
Edit the CSS variables in `src/styles/main.css`:
```css
:root {
  --primary-color: #3498db;
  --secondary-color: #2ecc71;
  --background-color: #f5f6fa;
}
```

## Deployment

### Build for Production
```bash
# Create production build
npm run build

# Test production build locally
npm run serve
```

### Deploy to Hosting
```bash
# Deploy to Netlify
netlify deploy --prod

# Deploy to Vercel
vercel --prod
```

## Custom Domain Setup

1. Purchase domain from preferred registrar
2. Add DNS records:
```
A     @     76.76.21.21
CNAME www   yourdomain.com
```
3. Configure hosting platform:
   - Navigate to domain settings
   - Add custom domain
   - Wait for DNS propagation (24-48 hours)

## Troubleshooting

### Common Issues

#### Build Errors
```bash
# Clear cache and node modules
rm -rf node_modules
rm -rf .cache
npm install
```

#### Image Loading Issues
- Ensure images are in the correct format (PNG/JPG/WebP)
- Check file paths in tools.json
- Verify public directory structure

## Resources
- [Documentation](https://docs.ai-tools-directory.com)
- [Component Library](https://components.ai-tools-directory.com)
- [API Reference](https://api.ai-tools-directory.com)

## Support
- [Submit an Issue](https://github.com/yourusername/ai-tools-directory/issues)
- [Email Support](mailto:support@ai-tools-directory.com)
- [Join Discord Community](https://discord.gg/ai-tools)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
Contributions are welcome! Please read our [Contributing Guide](CONTRIBUTING.md) for details.

---

Made with ❤️ by [Your Name](https://github.com/yourusername)