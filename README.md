# Kumbuild — Tell us what to build.

Done-for-you website service for small businesses. The customer tells Kumbuild what they want, Kumbuild builds and delivers it.

- **Brand:** Kumbuild
- **Tagline:** Tell us what to build.
- **Website:** [kumbuild.com](https://kumbuild.com)

## What we build

- **Business website** — 1–5 pages for shops, clinics, tuition & coaching, salons, gyms, restaurants, cafés
- **Landing page** — single page for Instagram / Facebook bio-link traffic
- **Booking / enquiry website** — appointment / enquiry form, services, timings (enquiry form, not a live calendar)
- **Catalogue / menu website** — products / menu with photos and prices, order via WhatsApp (not e-commerce checkout)

Every site is mobile-first, fast-loading, WhatsApp-first, with Google Maps, contact / enquiry form, basic SEO, and SSL.

## Platform

Monorepo — Astro + React/Vite frontend, Go backend, PostgreSQL + Redis, Cloudflare Pages.

- `frontend/apps/web` — kumbuild.com (Astro)
- `frontend/apps/account` — account.kumbuild.com (React + Vite)
- `frontend/apps/admin` — admin.kumbuild.com (React + Vite)
- `frontend/apps/home` — home.kumbuild.com (React + Vite)
- `frontend/apps/blog` — blog.kumbuild.com (Astro)
- `frontend/apps/docs` — docs.kumbuild.com (Astro + Starlight)
- `backend/` — Go API

## Status

The platform is under active development. The project history currently lives at [dusmamud/kumbuild](https://github.com/dusmamud/kumbuild); code migration to this account is in progress.
