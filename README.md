# Institute of Digital Risk (IDR) Website

A modern, responsive website for the Institute of Digital Risk, featuring a professional design with orange, white, and black branding.

## Features

- **Responsive Design**: Fully optimized for mobile, tablet, and desktop viewing
- **Sticky Navigation**: Smooth scrolling navigation bar with mobile menu
- **Hero Section**: Engaging landing area with clear call-to-action buttons
- **About Section**: Comprehensive overview of IDR's mission and partnerships
- **Service Pillars**: Showcasing Academy, Innovation & Incubation, and Advisory Services
- **Community Section**: Highlighting target audiences and professional network
- **Contact Form**: Interactive form for inquiries and registration
- **Professional Footer**: Complete site navigation and information

## Design Elements

### Logo
The IDR logo features a 3D cube in isometric perspective, symbolizing:
- Structure and stability in digital risk management
- Multi-faceted approach to risk mitigation
- Resilience and interconnected systems

See `LOGO_DESIGN.md` for detailed design rationale.

### Color Palette
- Primary: Orange (#FF6B35)
- Secondary: Black (#000000)
- Background: White (#FFFFFF) with subtle gradients

## Technology Stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- Lucide React (icons)

## Getting Started

### Prerequisites
- Node.js 18+ and npm

### Installation

1. Install dependencies:
```bash
npm install
```

2. Run development server:
```bash
npm run dev
```

3. Build for production:
```bash
npm run build
```

4. Preview production build:
```bash
npm run preview
```

## Project Structure

```
src/
├── components/
│   ├── Logo.tsx           # IDR logo component (icon and full variants)
│   ├── Navigation.tsx     # Sticky navigation with smooth scrolling
│   ├── Hero.tsx          # Landing section with CTA
│   ├── About.tsx         # About IDR section
│   ├── Services.tsx      # Service pillars and pipeline
│   ├── Community.tsx     # Target audience information
│   ├── Contact.tsx       # Contact form
│   └── Footer.tsx        # Site footer
├── App.tsx               # Main application component
├── main.tsx             # Application entry point
└── index.css            # Global styles and Tailwind imports
```

## Deployment

The `dist/` folder contains the production-ready files after running `npm run build`. Deploy this folder to any static hosting service:

- Netlify
- Vercel
- GitHub Pages
- AWS S3
- Any web server

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

All rights reserved - Institute of Digital Risk
