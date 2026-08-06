## Alejandro Fantini

Product engineer in Costa Rica. I build complete systems alone: Postgres schema,
backend, frontend, infrastructure, deploy, interface and brand. No designer, no
spec, no one handing me a Figma file.

### Running in production

**[reser.app](https://reser.app)** — booking and WhatsApp automation for salons
and barbershops. TypeScript, Next.js, Postgres, Stripe. Bookings serialize behind
a Postgres advisory lock so two customers can never take the same slot, and
Stripe webhook replays die on a unique index instead of charging twice.

**[cargity.com](https://cargity.com)** — multi-tenant container tracking for
importers and freight forwarders. Twelve carriers behind one timeline, real sea
routes computed offline against ~1,600 ports, and white-label public tracking
pages a customer opens with no account. 58 tables, 176 row-level-security
policies.

**fantini.app** *(private)* — the platform a furniture manufacturer runs on.
About 30 modules, 197 endpoints, 75 tables, 928 commits since 2023. Electronic
invoicing to the national tax authority, ERP and route-optimization integrations,
item-level RFID over USB readers, thermal label printing over raw TCP.

**KARA** *(private)* — restaurant operating system. Kitchen display, POS, waiter,
host and admin: five surfaces over one schema and 162 tables, so the kitchen and
the register can never disagree about an order.

**[f1.today](https://f1.today)** — is there Formula 1 today? A yes or no in three
seconds, with live session detection, a countdown, your own timezone and one-click
calendar export. Astro 5 with Preact islands, no database and no runtime APIs.

**[Vacancy](https://vacancy-lilac.vercel.app)** — a live 3D map of Manhattan with
all 44,795 buildings extruded from NYC Open Data, listings anchored to the
building they are actually in.

### Also

Self-hosted LLMs on my own tailnet (Ollama, quantized Gemma and Qwen), measured
for latency and throughput before picking one. n8n pipelines for scraping and
retrieval, three of them published as MCP tools.

### Stack

TypeScript · React · Next.js · Node · PostgreSQL · Supabase · Stripe · Astro ·
Three.js · Tailwind · Vercel · Cloudflare · Figma

---

Most of my work lives in private repositories. Happy to walk through any of it.

📍 San José, Costa Rica · [LinkedIn](https://www.linkedin.com/in/alejandrofantini) · [Buy me a coffee](https://buymeacoffee.com/alfavar)
