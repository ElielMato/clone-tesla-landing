# Tesla Landing - Website

![Astro](https://img.shields.io/badge/Astro-2.6.2-orange?logo=astro)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.3.2-teal?logo=tailwindcss)

A modern, responsive Tesla landing page clone built with **Astro**, featuring sleek design and smooth user experience. This project showcases Tesla's vehicle lineup including Model S, Model 3, Model X, Model Y, and energy products like Solar Panels, Solar Roof, and Powerwall.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly across desktop, tablet, and mobile devices
- **Static Site Generation**: Powered by Astro for lightning-fast performance and SEO optimization
- **Vehicle Showcase**: Interactive sections displaying Tesla's complete vehicle lineup
- **Energy Products**: Dedicated sections for Tesla's energy solutions
- **Modern UI/UX**: Clean, minimalist design inspired by Tesla's official website
- **Optimized Images**: High-quality AVIF format images for better performance
- **Type Safety**: Full TypeScript implementation for robust development
- **Component-Based Architecture**: Modular Astro components for maintainable code

## �️ Tech Stack

| Technology       | Purpose                            | Version |
| ---------------- | ---------------------------------- | ------- |
| **Astro**        | Static Site Generator              | 2.6.2   |
| **TypeScript**   | Type Safety & Developer Experience | 5.0     |
| **Tailwind CSS** | Utility-First CSS Framework        | 3.3.2   |

## 📁 Project Structure

```
src/
├── components/           # Astro components
│   ├── Header/          # Navigation components
│   │   └── LandingHeader.astro
│   ├── Home/            # Homepage components
│   │   ├── HeroSection.astro
│   │   ├── Logo.astro
│   │   ├── Model3.astro
│   │   ├── ModelS.astro
│   │   ├── ModelX.astro
│   │   ├── ModelY.astro
│   │   ├── Powerwall.astro
│   │   ├── SolarPanels.astro
│   │   └── SolarRoof.astro
│   └── ModelS/          # Model S specific components
│       ├── HeaderModelS.astro
│       ├── HeaderModelSScroll.astro
│       └── SectionModelS.astro
├── data/                # Data configuration
│   └── menuItems.ts
├── layouts/             # Layout components
│   └── Layout.astro
├── pages/               # Page routes
│   ├── index.astro      # Homepage
│   ├── models.astro     # Model S page
│   └── modelx.astro     # Model X page
├── types/               # TypeScript type definitions
│   └── types.ts
└── env.d.ts             # Environment type definitions
```

## 🚀 Getting Started

### Prerequisites

- **Node.js** (version 18.0.0 or higher)
- **npm** or **yarn** package manager

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/ElielMato/Tesla-Landing.git
   cd Tesla-Landing
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**

   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**

   Navigate to `http://localhost:4321` to see the application running.

## 🏗️ Building for Production

```bash
# Build the project
npm run build

# Preview the production build
npm run preview
```

The build artifacts will be stored in the `dist/` directory, ready for deployment to any static hosting service.

## � License

This project is for educational purposes. Tesla and all related trademarks are property of Tesla, Inc.

---

<div align="center">

**Built with ❤️ using Astro, TypeScript, and modern web technologies**

</div>
