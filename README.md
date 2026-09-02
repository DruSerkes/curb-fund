# The Curb Fund

One place to support the organizations building better streets, transit, and housing.

**[thecurbfund.org](https://thecurbfund.org/)**

Give once, and your donation reaches four vetted nonprofits working on transportation
and land use:

- **Strong Towns** — building a movement for financially resilient, human-scale communities
- **Transportation Alternatives** — sustainable transportation and equitable urban planning in NYC
- **YIMBY Action** — affordable housing and smart growth
- **Rail Passengers Association** — America's oldest rail passenger advocacy group

Donations are processed through [Every.org](https://www.every.org/), which retains its
standard processing fee. Nothing else is deducted.

## Development

Astro static site, deployed to Cloudflare Workers as an assets-only build — no server code.

```sh
pnpm install
pnpm dev      # local dev server
pnpm build    # static output -> dist/
pnpm preview  # preview the build
```

Node version is pinned in `.nvmrc`.
