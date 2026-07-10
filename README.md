# Gastos Colombia PWA

A modern, local-first personal expense tracking Progressive Web App built with React, TypeScript, Vite, Tailwind CSS, Dexie.js, React Router, Recharts, React Hook Form, and Zod.

## Highlights

- Fully Spanish Colombia user interface with COP currency formatting.
- IndexedDB persistence through Dexie; no backend, accounts, or cloud storage.
- Offline-capable PWA with manifest, service worker, and installable app shell.
- Dashboard with monthly spending, budget progress, category warnings, and key metrics.
- Editable categories with icons, monthly budgets, spending status, and progress bars.
- Fast expense entry with validation, search, category filter, and month history filter.
- Statistics page with pie, line, and bar charts.
- Recurring expenses, savings goal tracking, visual notifications, and monthly reset prompt.
- JSON, CSV, and Excel-compatible exports plus JSON restore.
- Responsive layout with desktop sidebar and mobile bottom navigation.

## Run locally

```bash
pnpm install
pnpm dev
```

## Build

```bash
pnpm build
```

The app is intentionally local-only. All user data remains in the browser's IndexedDB storage for the installed device.
