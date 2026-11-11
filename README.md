# RAPID MOTION STUDIO

**THE ART OF MOVING IDEAS.**

Premium AI-powered creative production agency website — cinematic video production,
advertising creatives, product commercials, and visual marketing solutions for brands,
businesses, startups, creators, and agencies.

> **YOU BRING THE PRODUCT. WE BRING THE VISION.**

_Formerly VELORA MOTION STUDIO — rebranded 2026-11-11. Official logo: the orange
"RMS" monogram supplied by the owner (see `docs/REBRAND_BRIEF.md`)._

## What this project is

A complete, production-ready, admin-manageable website for RAPID MOTION STUDIO:

- **Public site** — Home, Our Work (portfolio), Services, How It Works, About Us,
  Contact, plus Privacy Policy and Terms & Conditions.
- **Cinematic experience** — full-screen hero, showreel player, filterable portfolio,
  interactive Before & After comparison slider, industries, creative process,
  pricing packages (custom-quote based), FAQ accordion.
- **Project inquiry system** — multi-step client brief form with file uploads,
  validation, unique inquiry IDs and a success page.
- **Admin dashboard** — secure login; manage portfolio, videos, images, services,
  pricing, inquiries (with status workflow and internal notes), testimonials,
  FAQs, site content, global settings, and admin accounts.

## Brand identity

| Token | Value |
|---|---|
| Deep Burgundy | `#4B101B` |
| Dark Wine | `#290B12` |
| Champagne Gold | `#D8B477` |
| Warm Metallic Gold | `#B78B50` |
| Ivory White | `#F5F0E8` |
| Soft Charcoal | `#151313` |
| Muted Rose | `#A77C80` |

Typography: Manrope (headings) + Inter (body). Apple-inspired glass interface —
frosted navigation, backdrop blur, layered translucent panels, soft shadows.

## Project status

- The live website is built and hosted in **Muse** (full-stack app with its own
  database for inquiries, portfolio, services, pricing, FAQs and settings), where
  the owner reviews and manages it.
- This repository holds the project documentation. The complete build
  specification lives in [`docs/MASTER_BRIEF.md`](docs/MASTER_BRIEF.md).

## Rules baked into the build

- No fake client testimonials, no invented partnerships or results.
- No invented prices, phone numbers, addresses, or email addresses —
  contact details and pricing are configured by the owner in the admin dashboard.
- Demo portfolio entries are clearly labelled as demo concepts.
- Sample/demo media is replaceable through the admin dashboard.

## Structure

```
.
├── README.md
└── docs/
    ├── MASTER_BRIEF.md   # Original master website development prompt / specification
    └── REBRAND_BRIEF.md  # RAPID MOTION STUDIO brand identity & refinement brief
```
