# 3D Website Builder 🌐

> Create stunning, interactive 3D websites without writing code. Drag-and-drop interface, pre-built 3D components, and real-time preview. Perfect for portfolios, product showcases, landing pages, and immersive experiences.

## ✨ Features

- **No-Code 3D Editor**: Drag, drop, and customize 3D elements visually
- **Pre-Built 3D Components**: 50+ ready-to-use 3D objects (products, characters, environments)
- **Real-Time Preview**: See changes instantly as you build
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Animations & Interactions**: Scroll-triggered, hover, click, and timeline animations
- **Lighting & Materials**: PBR materials, HDR lighting, shadows, reflections
- **Export Options**: Static HTML, React component, or embeddable iframe
- **SEO Optimized**: Automatic meta tags, structured data, and performance optimization
- **Analytics Integration**: Track user engagement with 3D elements
- **Collaboration**: Multi-user editing with comments and version history
- **Custom Code**: Add custom Three.js/React Three Fiber code for advanced users
- **Hosting**: One-click deploy to Vercel, Netlify, or GitHub Pages

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/valentinasmith722/3d-website-builder.git
cd 3d-website-builder

# Install dependencies
npm install

# Start the editor
npm run dev

# Open http://localhost:3000 in your browser
```

## 🎨 Editor Preview

```
┌─────────────────────────────────────────────────────────────┐
│  3D Website Builder v2.0                    [Export] [Preview]│
├──────────────────┬────────────────────────────────────────────┤
│  🧩 Components   │                                          │
│  ┌──────────────┐ │     ☀️                                    │
│  │ 3D Product   │ │    /│\                                  │
│  │ Showcase     │ │   / │ \    🏢 Building                  │
│  └──────────────┘ │  /  │  \                                 │
│  ┌──────────────┐ │     │      🌳 🌳                         │
│  │ Hero Section │ │    ═╧═                                  │
│  │ with 3D      │ │  ┌─────────┐                            │
│  │ Character    │ │  │  🚗    │  Product Card               │
│  └──────────────┘ │  └─────────┘                            │
│  ┌──────────────┐ │                                          │
│  │ 3D Gallery   │ │  [Drag components here]                  │
│  │ Carousel     │ │                                          │
│  └──────────────┘ │                                          │
│  ┌──────────────┐ │                                          │
│  │ Interactive  │ │  ⚙️ Properties                           │
│  │ 3D Map       │ │  Position: X: 0 Y: 1 Z: -2              │
│  └──────────────┘ │  Rotation: X: 0 Y: 45 Z: 0              │
│  ┌──────────────┐ │  Scale: 1.5x                             │
│  │ Particle     │ │  Material: Metal / Roughness: 0.3      │
│  │ Effects      │ │  Animation: Rotate Y (loop)              │
│  └──────────────┘ │                                          │
└──────────────────┴────────────────────────────────────────────┘
```

## 🛠️ Tech Stack

- **3D Engine**: Three.js + React Three Fiber
- **Physics**: Cannon.js / Rapier (optional)
- **Editor**: React 18 + Zustand (state management)
- **UI**: Radix UI + Tailwind CSS
- **Animations**: Framer Motion + GSAP
- **Export**: Next.js / Vite templates
- **Hosting**: Vercel API + GitHub Pages
- **Storage**: Supabase (projects) + AWS S3 (assets)

## 🎯 Use Cases

- **Product Showcases**: 3D product configurators for e-commerce
- **Portfolio Sites**: Interactive 3D portfolios for designers/developers
- **Landing Pages**: Eye-catching 3D hero sections that convert
- **Real Estate**: 3D virtual tours and property visualizations
- **Education**: Interactive 3D models for learning
- **Events**: Immersive event pages and virtual exhibitions
- **Gaming**: Simple 3D games and interactive experiences
- **Architecture**: 3D building visualizations and walkthroughs

## 🎨 3D Components Library

### Product Showcase
- 360° product viewer
- Color/material configurator
- AR preview (WebXR)
- Hotspots with product info

### Hero Sections
- 3D text animations
- Floating objects
- Particle backgrounds
- Morphing shapes

### Interactive Elements
- 3D buttons and cards
- Scroll-triggered animations
- Mouse-following objects
- Click interactions

### Environment
- 3D rooms and spaces
- Nature scenes (trees, water, sky)
- Urban environments
- Abstract backgrounds

## 🔧 Configuration

Create a `.env.local` file:

```env
# Database (Supabase)
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_anon_key
SUPABASE_SERVICE_ROLE_KEY=your_service_role_key

# Storage (AWS S3 or Cloudflare R2)
AWS_ACCESS_KEY_ID=your_key
AWS_SECRET_ACCESS_KEY=your_secret
AWS_REGION=us-east-1
AWS_S3_BUCKET=your_bucket

# Optional: AI features
OPENAI_API_KEY=your_openai_key

# Optional: Analytics
GOOGLE_ANALYTICS_ID=G-XXXXXXXXXX
```

## 📦 Export Options

### 1. Static HTML
```bash
npm run export:static
# Generates optimized HTML + JS + assets
# Host anywhere: GitHub Pages, Netlify, Vercel
```

### 2. React Component
```bash
npm run export:react
# Generates a reusable React component
# Import into any React/Next.js project
```

### 3. Embed (iframe)
```bash
npm run export:embed
# Generates embeddable iframe code
# Paste into any website, WordPress, Wix, etc.
```

## 🎓 Tutorials

- [Build Your First 3D Portfolio](docs/tutorial-portfolio.md)
- [Create a Product Configurator](docs/tutorial-product.md)
- [Add Scroll Animations](docs/tutorial-scroll.md)
- [Optimize for Mobile](docs/tutorial-mobile.md)
- [Custom Three.js Code](docs/tutorial-advanced.md)

## 🤝 Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

### Ways to Contribute

- 🐛 Report bugs via GitHub Issues
- 💡 Suggest features via GitHub Discussions
- 🎨 Submit new 3D components
- 🔧 Improve performance and optimization
- 📖 Write tutorials and documentation
- 🌍 Translate the interface

## ☕ Support This Project

This tool is **100% free and open source**. We believe everyone should be able to create stunning 3D websites, not just developers with years of Three.js experience.

If 3D Website Builder helped you land a client, impress your boss, or bring your creative vision to life, consider supporting its continued development:

**Solana (USDT)**: `BKjS4agVRowFGqUuWHEKZerk3dCS52V1n4NdWaeNTo8E`

Your support helps us:
- Add more 3D components and templates
- Develop mobile AR features (WebXR)
- Create video tutorials and courses
- Improve performance and loading times
- Build a marketplace for community components
- Keep the tool free for everyone

*Every contribution helps us democratize 3D web design. Thank you for being part of this mission.* 🙏

## 📄 License

MIT License — free to use, modify, and distribute.

## 🌟 Star History

If this project helped you create something amazing, please give it a star ⭐ on GitHub!

---

*Built with ❤️ for creators everywhere | 2026*
