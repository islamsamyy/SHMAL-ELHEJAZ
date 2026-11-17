# Shmal El-Hejaz — Pricing & Design System Snippets (`SHMAL-ELHEJAZ`)

## Table of Contents
- [Executive Summary & Business Utility](#executive-summary--business-utility)
- [System Architecture & Layers](#system-architecture--layers)
- [Application Modules](#application-modules)
- [Business Value, ROI & Growth Opportunities](#business-value-roi--growth-opportunities)

---

## Executive Summary & Business Utility
`SHMAL-ELHEJAZ` is a reusable frontend UI & design-system archive containing Tailwind CSS HSL design tokens (`INDEX.CSS`), component hover/spin keyframes (`CARD CSS`), and a React/TypeScript Arabic subscription pricing screen (`JAVA SCRIPT`) supporting **Silver**, **Gold**, and **Diamond** tiers with interactive upgrade modal triggers (`UpgradeModal`) and localized toast confirmations.

---

## System Architecture & Layers
| Layer | File | Responsibility |
| :--- | :--- | :--- |
| **Design Tokens Layer** | `INDEX.CSS` | Tailwind `@layer base` HSL CSS variables (`--background`, `--foreground`, `--card`, `--primary`, `--popover`) |
| **Animation & Layout CSS** | `CARD CSS` | `#root` container grid, `.logo` filter hover transitions, and `@keyframes logo-spin` |
| **React Pricing UI Layer** | `JAVA SCRIPT` | `Index` component integrating `Header`, `PricingCard`, `ComparisonTable`, `Testimonials`, `UpgradeModal`, and `useToast` |

---

## Application Modules
- **Tier Selection Handler (`handleSelectPlan`)**: Triggers an automatic `UpgradeModal` upsell when selecting the `silver` tier, and displays localized Arabic confirmation toasts for `gold` and `diamond` plans.

---

## Business Value, ROI & Growth Opportunities
- **Conversion-Optimized Upsell Funnel**: Built-in modal upsell logic nudges entry-tier (`silver`) buyers toward higher-ARPU `gold`/`diamond` plans.
- **Drop-In SaaS Module**: Ready to plug directly into `shamalelhejaz` or other Arabic SaaS/marketplace storefronts.
