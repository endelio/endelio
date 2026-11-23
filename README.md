<div align="center">

# ENDEL AI

**Full-stack product engineer** · TypeScript · React / Next.js · TanStack · Cloudflare · Supabase

I take products from empty repository to production: typed APIs, accessible interfaces, edge
deployments — and the unglamorous parts that decide whether something survives real users
(auth, rate limits, migrations, error handling).

<sub>Selected repositories are private — read access or an architecture walkthrough on request.</sub>

</div>

---

## Focus

| Area | What that means in practice |
| :--- | :--- |
| **Full-stack TypeScript** | Next.js App Router and TanStack Start — one type carried from the Postgres schema to the component props. |
| **Data-heavy product UI** | Dashboards, comparison matrices, price history, JSON tooling. Correctness first, polish that survives load. |
| **Edge & serverless** | Cloudflare Workers, Supabase (Postgres, auth, RLS). No servers to babysit at 3 a.m. |
| **Scraping & integration** | Resilient extraction pipelines, typed API layers, retries and backoff where the data source is hostile. |
| **Mobile** | Kotlin + Compose when the product belongs in a pocket. |

## Selected work

| Project | What it does | Stack |
| :--- | :--- | :--- |
| **Price Tracker** | Tracks Apple reseller pricing across stores, keeps full price history, ships a comparison matrix and an operational scraper console. | Next.js · TypeScript · cheerio · REST |
| **Logistics ERP** | Eleven-module freight workspace: orders, quotes, dispatch, carriers, claims, deals, documents, finance, leads, tracking, reports. | TanStack Start · TypeScript · Cloudflare |
| **Customer Portal** | Self-service portal with real auth flows (login, register, password reset), orders, payments, credit, notifications and support threads. | TanStack Start · TypeScript · Supabase |
| **JSON Studio** | Developer workbench: tree / table / diff views, `ajv` schema validation, YAML and XML conversion, code generation. | React · Vite · ajv · TypeScript |
| **Service Desk** | Support operations end to end: tickets, companies, invoices, knowledge base, analytics and a customer-facing portal. | TanStack Start · Supabase |
| **SubTrack** | Android subscription tracker with local persistence and offline-first storage. | Kotlin · Compose · Room |

<sub>These repositories are private. I'm glad to grant read access or walk through the architecture on a call.</sub>

## Stack

<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white">
  <img alt="TanStack" src="https://img.shields.io/badge/TanStack-FF4154?style=flat-square&logo=reactquery&logoColor=white">
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white">
  <img alt="shadcn/ui" src="https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white">
  <img alt="Cloudflare" src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white">
  <img alt="Supabase" src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white">
  <img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white">
  <img alt="Vitest" src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white">
</p>

## How I work

- **Types at the seams.** Schemas are the contract; everything downstream is derived from them, not duplicated.
- **Small, reviewable changes.** One concern per pull request, a clear description, no drive-by refactors.
- **Tests where failure is expensive.** Business rules and data transforms are covered; markup churn isn't.
- **Design for the second year.** Chosen boring technology over clever technology — the code should still be readable when the original author is gone.
- **Hardening counts as shipping.** Auth, rate limiting, error states and empty states are part of the feature, not a follow-up ticket.

## Currently

- Latest shipped surface: **Price Tracker** (scraping pipeline + history + comparison UI)
- Deep in **TanStack Start + Supabase**: typed server functions, RLS policies, migrations
- Always interested in hard product problems with real users attached

---

<div align="center">

<sub>Best reached by opening an issue or sending a direct message here on GitHub.</sub>

</div>
