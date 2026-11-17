# Shmal El-Hejaz — Pricing & Design System Snippets (`SHMAL-ELHEJAZ`)

A frontend UI/design-system archive containing Tailwind CSS design tokens (`INDEX.CSS`), component animation styles (`CARD CSS`), and a React/TypeScript Arabic subscription pricing page (`JAVA SCRIPT`) for tiered plans (Silver, Gold, Diamond).

---

## 1. Executive Summary & Purpose
`SHMAL-ELHEJAZ` preserves reusable styling tokens and an interactive Arabic-language SaaS/service pricing interface (`Index` component with `PricingCard`, `ComparisonTable`, `Testimonials`, and `UpgradeModal`).

## 2. Architectural Layers & Files
| File | Layer / Role | Details |
| :--- | :--- | :--- |
| `INDEX.CSS` | **Design Tokens Layer** | Tailwind `@layer base` HSL CSS variables (`--background`, `--card`, `--primary`, `--popover`) |
| `CARD CSS` | **Component Styles Layer** | Container layout (`#root`), hover filter transitions, and keyframe animations |
| `JAVA SCRIPT` | **React UI Layer** | TSX component implementing Silver/Gold/Diamond tier selection, upgrade modal trigger, and Arabic toast notifications (`useToast`) |

## 3. Business Value & Growth Opportunities
- **Drop-In Pricing Funnel**: Ready to be integrated into any Next.js/Vite Arabic SaaS or agency platform (e.g., `shamalelhejaz`) to drive tiered subscription upgrades with automated modal upsells for lower tiers.
