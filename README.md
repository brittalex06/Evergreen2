# Evergreen

Evergreen is an independent digital banking experience concept built with React and Vite. It is not a bank or financial institution and does not offer deposit accounts, transfers, payments, investment products, or financial advice.

## Included

- Responsive public pages: home, about, products, pricing, security, support, and legal
- Prototype login and signup screens with explicit sample-only disclosures
- Sample account workspace: dashboard, accounts, CSV export, transfer preview, savings goals, settings, and administration preview
- Accessible navigation, semantic page structure, reduced-motion support, and responsive layouts
- Netlify build configuration and SPA route fallback

## Run locally

```bash
npm install
npm run dev
```

Create a production build with:

```bash
npm run build
npm run preview
```

## Deploy to Netlify

1. Import `brittalex06/Evergreen2` in Netlify.
2. Use the build command `npm run build`.
3. Set the publish directory to `dist`.
4. Deploy from the `main` branch.

The repository includes `netlify.toml` with these settings and a single-page-app route fallback.

## Important security and product limitations

This repository currently contains a front-end prototype only. The sample login does not authenticate a user, sample balances and transactions are fictional, and the transfer and goal screens do not submit financial instructions. The administration page is a visual preview, not an authorization boundary. No real credentials or sensitive financial information should be entered.

Before any real financial service is offered, the project needs a properly designed and independently reviewed backend, secure identity and session management, server-side authorization, a regulated banking partner, verified product disclosures, data protection controls, monitoring, and legal/compliance review. Never rely on client-side role checks to protect administrative or financial operations.
