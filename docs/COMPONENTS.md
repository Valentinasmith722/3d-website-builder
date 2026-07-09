# 3D Components Library

## Available Components

### Hero Section
- `Hero3D` - Full-screen 3D hero with camera controls
- `HeroParticles` - Particle background with text overlay

### Product Showcase
- `ProductViewer` - 360° product rotation
- `ProductConfigurator` - Color/material selector

### Interactive Elements
- `AnimatedButton` - 3D button with hover effects
- `FloatingCard` - Card with parallax effect

## Usage

```tsx
import { Hero3D } from '@3d-builder/components';

<Hero3D
  model="./models/product.glb"
  autoRotate={true}
  background="gradient"
/>
```
