# Amrut Insurance & Investment

> **Licensed IRDAI Registered Insurance Advisory (Reg. No. 2017342)**  
> 15+ Years of Impartial Insurance Advisory • 5,000+ Families Protected Across India • Surat, Gujarat

A modern, fast, and accessible digital insurance advisory platform built with **Astro 5/7** and **Tailwind CSS v4**, styled using the **Ramp-inspired warm editorial visual system** documented in [`DESIGN.md`](./DESIGN.md).

---

## 🛡️ About Amrut Insurance

Amrut Insurance & Investment is an independent insurance advisory founded by **Amrut Patel** (IRDAI Reg. 2017342) based in Udhna, Surat, Gujarat. The platform provides transparent, impartial guidance across **28+ leading Indian insurance companies** with a focus on genuine consumer savings, zero spam calls, and personal claim assistance.

### Key Advisory Services
- **Family Health (Mediclaim)**: Cashless admission across 14,000+ network hospitals, **0% GST exemption** (saving 18% statutory tax), and Section 80D deductions. Impartial advice across Care Health, Star Health, and Bajaj Allianz.
- **Motor Insurance (Two-Wheeler & Private Car)**: Instant policy delivery on WhatsApp in 15 minutes, statutory RTO compliance, **up to 50% No-Claim Bonus (NCB) transfer**, and cashless repair network across 10,000+ garages.
- **Term Life Cover**: Pure life financial protection up to ₹1 Crore+ with **0% GST exemption** and tax savings under Section 80C & 10(10D) through LIC of India and Tata AIA Life.
- **Commercial & Fleet Vehicles**: Mandatory coverage for auto-rickshaws, delivery tempos (Tata Ace, Bolero Pickup), and heavy cargo trucks with IMT-23 and driver liability.
- **Business & Industrial Risk**: Workmen's Compensation (WC Act for factory labor), Fire & Shopkeeper MSME packages, and Marine Cargo Inland transit protection.

---

## 🎨 Design System

The visual design is governed by [`DESIGN.md`](./DESIGN.md), adapting the **Ramp editorial design language** from [OpenDesignMD](https://opendesignmd.com/designs/ramp/):

- **Warm Neutral Palette**:
  - `Canvas`: `#F4F2F0` (warm stone)
  - `Paper`: `#FFFFFF` (elevated white cards)
  - `Ink`: `#000000` & `Muted Ink`: `#1A1919` (high-contrast typography and dark section bands)
  - `Savings Badges`: Subtle mint washes (`#EFFCF8`) with deep forest green text (`#006642`) for 0% GST and NCB savings callouts.
- **Section Movement**: Dark `#000000` hero and closing consultation movements alternating with warm stone `#F4F2F0` and `#FFFFFF` product breakdowns.
- **Typographic Restraint**: Swiss-influenced hierarchy using regular-weight (400) display typography with negative letter-tracking, paired with 11px uppercase tracked eyebrows and 16px body copy with generous line heights (`leading-relaxed`).
- **12px Card Language**: Consistent `12px` border radius across all primary policy cards, stat tiles, and interactive components.

---

## 🚀 Tech Stack

- **Framework**: [Astro](https://astro.build) (v7 / Static Site Generation)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com) with `@tailwindcss/vite`
- **Typography**: Inter (Clean Grotesque) & JetBrains Mono (Rates, License & Numbers)
- **SEO & Structured Data**: Built-in JSON-LD `InsuranceAgency` schema, Open Graph tags, canonical URLs, and zero-flash dark mode support.
- **Direct Conversion**: One-click WhatsApp consultation (`wa.me`) with pre-filled policy query parameters and direct phone dialing.

---

## 📁 Project Structure

```text
amrut-insurance-and-investment/
├── public/                 # Static assets, logos, and favicons
│   ├── favicon.svg
│   ├── og-image.svg
│   └── logos/              # Partner insurer logos (LIC, Tata AIA, Bajaj, etc.)
├── src/
│   ├── assets/             # Vector illustrations and background shapes
│   ├── components/         # Reusable Astro UI components
│   ├── layouts/
│   │   └── Layout.astro    # Master layout (SEO meta, Nav, Footer, Theme toggle)
│   ├── pages/
│   │   ├── index.astro     # Home: Hero, Partner strip, Starter plans, All categories
│   │   ├── services.astro  # Detailed policy guide, required documents & rates
│   │   ├── about.astro     # IRDAI credentials, advisor background & track record
│   │   └── contact.astro   # Office location, Google Maps, WhatsApp & phone forms
│   └── styles/
│       └── global.css      # Tailwind v4 theme configuration & base utilities
├── AGENTS.md               # Assistant development instructions
├── DESIGN.md               # Ramp-inspired design system tokens & guidelines
├── package.json
└── tsconfig.json
```

---

## 🛠️ Development & Commands

All commands are run from the project root using `npm`:

| Command | Action |
| :--- | :--- |
| `npm install` | Install all dependencies |
| `npx astro dev --background` | Start the local Astro development server in background mode |
| `npx astro dev status` | Check status of the background development server |
| `npx astro dev logs` | Inspect background development server logs |
| `npx astro dev stop` | Stop the background development server |
| `npm run build` | Build production-ready static site to `./dist/` |
| `npm run preview` | Preview production build locally at `http://localhost:4321` |

> Refer to [`AGENTS.md`](./AGENTS.md) for background dev server management rules.

---

## 📍 Office & Contact

- **Advisor**: Amrut Patel (IRDAI Reg. No. 2017342)
- **Phone**: [+91 98241 39239](tel:+919824139239)
- **Email**: [amrutpatel39@gmail.com](mailto:amrutpatel39@gmail.com)
- **Address**: Shop No. 123, Palika Bazar, Nr. Komal International Circle, Bamroli Road, Udhna, Surat, Gujarat 395002
- **Website**: [https://amrutinsurance.in](https://amrutinsurance.in)
