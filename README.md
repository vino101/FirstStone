# Firststone Construction Company

> Building Tomorrow, Today.

A premium, production-ready 3D website for a multi-million-dollar construction company — featuring an immersive React Three Fiber scene, smooth animations, and a polished corporate experience.

## Tech Stack

- **React 19** + **Vite**
- **Tailwind CSS** (custom design system)
- **React Router DOM** (routing + code splitting)
- **React Three Fiber** + **@react-three/drei** + **@react-three/postprocessing** (3D hero scene with Bloom)
- **Framer Motion** (page transitions, reveal animations, micro-interactions)
- **GSAP** (animation utility)
- **Lenis** (smooth scroll)
- **SwiperJS** (testimonials carousel)
- **Lucide React** (icons)
- **Supabase** (contact form persistence)

## Getting Started

```bash
npm install
npm run dev      # start dev server
npm run build    # production build
npm run preview  # preview production build
```

## Project Structure

```
src/
  components/      # Navbar, Footer, Loader, ScrollProgress, CustomCursor, etc.
    three/         # R3F HeroScene (skyscrapers, crane, excavator, bloom)
  sections/home/   # Home page sections (Hero, About, Services, Projects...)
  pages/           # Routed pages (Home, About, Services, Projects, Contact...)
  layouts/         # RootLayout
  hooks/           # useLenis, useCountUp, useInViewOnce
  context/         # ThemeContext (dark/light)
  data/            # services, projects, team, testimonials, news, jobs
  services/        # supabase client
  utils/           # icon helper
```

## Features

- Interactive 3D hero with rotating skyscrapers, animated crane, excavator, floating steel beams, clouds, dynamic lighting, and Bloom post-processing
- Sticky responsive navbar with mobile drawer
- Dark / light mode toggle (persisted)
- Loading screen, scroll progress bar, custom cursor, back-to-top
- Animated statistics counters
- Filterable project portfolio with detail pages
- 15 service pages with detail views
- Industries, Why Choose Us, Team, Testimonials (Swiper), Partners, FAQ
- Careers page with job openings + application form
- News & blog grid
- Contact form persisted to Supabase (`contact_messages` table, RLS-enabled)
- Page transitions, reveal-on-scroll, parallax, hover micro-interactions
- SEO meta tags, responsive across mobile → desktop, accessible markup

## Configuration

Supabase credentials are pre-populated in `.env`. No manual setup required.
