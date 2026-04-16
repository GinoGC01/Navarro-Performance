# Navarro Performance 🏎️🔥

**Navarro Performance** is a high-end automotive tuning and performance workshop web application. Built with a focus on raw mechanical aggression and surgical precision, the site serves as the digital storefront for elite ECU remapping, dyno testing, and custom performance builds.

## 🚀 Technology Stack

- **Framework:** [Astro 5+](https://astro.build/)
- **Styling:** [Tailwind CSS v4](https://tailwindcss.com/blog/tailwindcss-v4-alpha) (using the new `@theme` engine)
- **Transitions:** [Astro View Transitions API](https://docs.astro.build/en/guides/view-transitions/) for seamless, app-like navigation.
- **Typography:**
  - **Headline:** *Space Grotesk* (Aggressive, technical)
  - **Body:** *Work Sans* (Clean, readable)
- **Aesthetics:** Dark mode by default, glassmorphism, vivid neon accents (#FF5E00), and Bento-style layouts.

## ✨ Key Features

- **Performance Catalog:** A detailed list of tuning stages (1-3), custom calibrations, and hardware installations.
- **Bento Grid Layout:** Modern and responsive grid system for showcasing services and technical specifications.
- **View Transitions:** Smooth `fade` and `slide` animations between pages (`Home` <-> `Tunning`).
- **Responsive Design:** Optimized for all devices, from ultra-wide monitors to mobile smartphones.
- **Dynamic Action:** Integrated appointment booking flow and service configuration.

## 🛠 Project Structure

```text
/
├── src/
│   ├── layouts/
│   │   ├── Layout.astro   # Main wrapper with View Transitions
│   │   ├── Header.astro   # Sticky navigation with mobile optimization
│   │   └── Footer.astro   # Detailed site footer
│   ├── pages/
│   │   ├── index.astro     # Home page (Catalog/Landing)
│   │   └── tunning.astro   # Tuning services & technical showcase
│   └── styles/
│       └── global.css      # Tailwind v4 theme and custom utilities
├── public/
│   └── images/             # Local assets for builds and hardware
├── package.json
└── astro.config.mjs
```

## 🏁 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (latest LTS recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/GinoGC01/Navarro-Performance.git
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Build for production:
   ```bash
   npm run build
   ```

## 📄 License

This project is specialized for internal use and demonstration purposes for **Navarro Performance**. All rights reserved.

---
*Built with speed, engineered for power.*
