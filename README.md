# Awesome Systems Toolbox

Topics: crypto, AI, coding, OSINT, design, and everyday life systems. A library of tools, links, and workflows that I actually use and keep updating.

> This is where I organize my stack so I can reuse it quickly without rebuilding it from scratch every time.  
> And it’s an open shelf: if any of this helps your projects, feel free to borrow it.  
> Also available in: [Russian version](./README.ru.md)

---

## Inspiration

I’m building this as a public toolbox, not a private stash.

I don’t want you to waste hours on the same research I already did once.  
With this repo, you can:

- grab a set of tested tools for a new project in minutes instead of hours  
- reuse patterns for UI, infra, crypto, OSINT, and “life ops”  

This is my way to give something back: collect what worked for me, filter out the noise, and keep only the things that helped me actually ship.

---

## Some pointers

- This is an opinionated, personal collection.  
  It is not meant to be exhaustive or “objective”. If a tool is here, it either:
  - survived at least one real use case for me, or  
  - looks strong enough to be tested soon.

- Sections are ordered top‑to‑bottom, not by “rank”:
  - Design / vibe‑UI  
  - AI & coding  
  - Crypto  
  - OSINT  
  - Life infrastructure  

- I tend to prefer:
  - tools that are at least somewhat privacy‑respecting and not pure surveillance‑adware  
  - products with clear, practical value (not just another shiny AI wrapper)

- Some entries may be paid or closed‑source if they’re genuinely useful.

---
## Contents

- [Design / Vibe UI](#design--vibe-ui)  
- [AI & Coding](#ai--coding)  
  - [AI coding environments](#ai-coding-environments)  
  - [General AI / chat](#general-ai--chat)  
  - [Dev tooling & automation](#dev-tooling--automation)  
- [Crypto](#crypto)  
  - [Wallets & key management](#wallets--key-management)  
  - [On‑chain analytics & explorers](#on-chain-analytics--explorers)  
  - [Market data & rankings](#market-data--rankings)  
  - [Infra / privacy / accounts](#infra--privacy--accounts)  
  - [Numbers, SIMs, cards](#numbers-sims-cards)  
- [OSINT](#osint)  
  - [People / profiles](#people--profiles)  
  - [Domains, IP, infrastructure](#domains-ip-infrastructure)  
  - [Crypto OSINT](#crypto-osint)  
- [Life Infrastructure](#life-infrastructure)  
  - [Notes & knowledge](#notes--knowledge)  
  - [Health / tracking](#health--tracking)  
  - [Ops / privacy / money](#ops--privacy--money)  
- [Contributing](#contributing)


---

## Design / Vibe UI

### Galleries & references

| Tool / Site   | Link                                            | What it’s for                                                                                           |
|---------------|-------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| Mobbin        | https://mobbin.com                              | Studying real product flows: dashboards, auth, billing, settings, lists, forms                         |
| Dribbble      | https://dribbble.com                            | Getting visual vibe: hero sections, concepts, illustration styles                                      |
| Lapa Ninja    | https://www.lapa.ninja                          | Stealing landing structures for SaaS/startups (hero, features, pricing, FAQ, footer)                   |
| Landingfolio  | https://www.landingfolio.com                    | Copy‑worthy sections (pricing, signup, testimonials, 404, empty states) as patterns                    |
| Footer.design | https://www.footer.design                       | Quickly picking a decent footer layout instead of reinventing it                                       |

### Components & micro‑UI

| Tool / Site      | Link                             | What it’s for                                                                 |
|------------------|----------------------------------|-------------------------------------------------------------------------------|
| Reactbits        | https://reactbits.dev           | Dropping in animated React components: text, backgrounds, cursors, cards     |
| Uiverse          | https://uiverse.io              | Small animated UI bits (buttons, toggles, loaders, inputs) ready to copy     |
| Realtime Colors  | https://realtimecolors.com      | Testing color themes on realistic UI and exporting palettes to CSS/Tailwind  |

### Icons & illustrations

| Tool / Site         | Link                                                                 | What it’s for                                                                                 |
|---------------------|----------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| Flaticon            | https://www.flaticon.com                                            | Large icon sets in SVG/PNG/fonts, quick edits via web editor and collections                 |
| Phosphor Icons      | https://phosphoricons.com                                           | Consistent multi‑weight icon family for product UI, with React/Vue/Svelte + Figma support    |
| Feather Icons       | https://feathericons.com                                            | Minimal, clean open‑source icon set for lightweight interfaces                               |
| Icons8              | https://icons8.com                                                  | Icons, illustrations and photos for UI and marketing visuals                                 |
| Icons8 Figma plugin | https://www.figma.com/community/plugin/791103617505812222/icons8-icons-illustrations-photos | Dropping Icons8 assets straight into Figma without leaving the editor |

### Identity / logo

| Tool / Site   | Link           | What it’s for                                                     |
|---------------|----------------|-------------------------------------------------------------------|
| Figr Identity | (Figma plugin) | Auto‑building identity systems and design tokens directly in Figma|
| Higgsfield    | https://higgsfield.ai | Generating hero images and seamless video loops / short promos with AI |
| Logo Diffusion| https://logodiffusion.com | Rapid‑fire logo exploration via diffusion before polishing in Figma |

### 3D, animation & FX

| Tool / Site    | Link                             | What it’s for                                                                 |
|----------------|----------------------------------|-------------------------------------------------------------------------------|
| Spline         | https://spline.design           | Creating 3D objects/scenes for hero sections and interactive visuals         |
| Unicorn Studio | https://www.unicorn.studio      | No‑code WebGL effects and backgrounds on top of existing UI                  |
| Rive           | https://rive.app                | State‑driven icons, loaders and micro‑animations that react to your app      |
| Paper Animator | https://paperanimator.com       | Quick paper‑style animations for standout illustrations/sections             |

### Design tools & Figma

| Tool / Site    | Link                     | What it’s for                                                                 |
|----------------|--------------------------|-------------------------------------------------------------------------------|
| Figma          | https://www.figma.com    | Main hub where all design work, components and prototypes live               |
| HTML.to.design | https://www.html.to.design | Pulling existing websites into Figma as editable layouts/blocks             |
| Flamel 3D      | (Figma plugin)           | Generating consistent 3D icon sets with AI directly in Figma                |
| Figma AI (Make)| —                        | Quickly drafting screens and React code from textual app descriptions        |


---

## AI & Coding

### AI coding environments

| Tool / Site | Link | What it’s for |
|------------|------|---------------|
| Cursor | https://cursor.sh | Main AI IDE: repo‑level context, autocomplete, refactors, feature generation |
| Claude Code | https://claude.ai | Deep reviews, architecture, and refactors via chat with access to code |
| Antigravity | https://antigravityide.org | Google IDE with Gemini agents: autocomplete, natural‑language commands, autonomous tasks in code/terminal/browser |
| v0 by Vercel | https://v0.dev | Generate React/Next/Tailwind UI from prompts, fast landing pages and dashboards |
| Lovable | https://lovable.dev | Text‑to‑app: fast prototypes and full‑stack apps from natural‑language specs |

### General AI / chat

| Tool / Site | Link | What it’s for |
|------------|------|---------------|
| ChatGPT | https://chat.openai.com | General coding assistance, ideas, text, and quick prototypes |
| Perplexity | https://www.perplexity.ai | Research, tool comparisons, specs and architecture drafts on top of the web |
| Grok | https://x.ai | Fast answers and code/meme‑vibe directly inside the X ecosystem |
| Gemini | https://gemini.google.com | Integrated with Google stack, assistant for code and content tasks |

### Dev tooling & automation

| Tool / Site | Link | What it’s for |
|------------|------|---------------|
| GitHub Copilot | https://github.com/features/copilot | Inline code and test suggestions in IDE, kills boilerplate and routine |

---

## Crypto

### Wallets & key management

| Tool / Site | Link | What it’s for |
|------------|------|---------------|
| Phantom | https://phantom.app | Main Solana wallet for on‑chain, NFTs, and dApp integrations |
| Backpack | https://backpack.app | Wallet + xNFT ecosystem on Solana, convenient for app‑specific flows |
| Rabby | https://rabby.io | EVM wallet with strong UX and safety focus for DeFi |
| MetaMask | https://metamask.io | Default EVM browser wallet used by most dApps “by default” |
| Ledger / Trezor | https://www.ledger.com | Cold storage for private keys and larger balances, plugged into hot wallets |

### On‑chain analytics & explorers

| Tool / Site | Link | What it’s for |
|------------|------|---------------|
| Dune | https://dune.com | SQL dashboards for on‑chain data, protocol metrics and trends |
| Arkham | https://arkhamintelligence.com | On‑chain OSINT: wallet labels, entity graphs, and activity tracking |
| BscScan | https://bscscan.com | Explorer for BNB Chain: transactions, contracts, tokens |
| Solscan | https://solscan.io | Explorer for Solana: transactions, programs, events, debugging integrations |
| Dexscreener | https://dexscreener.com | Real‑time charts and liquidity across many DEX pairs and chains |
| Birdeye | https://birdeye.so | Charts and analytics for Solana (and others), filters for volume and trends |
| GMGN | https://gmgn.ai | Terminal + bots for memecoins, smart‑money tracking and fast trading |
| Axiom | — | Fill in your actual use case here once it solidifies |

### Market data & rankings

| Tool / Site | Link | What it’s for |
|------------|------|---------------|
| CoinGecko | https://www.coingecko.com | Prices, volumes, token metrics, and market lists |
| CoinMarketCap | https://coinmarketcap.com | Classic market aggregator, listings, historical data |
| DefiLlama | https://defillama.com | TVL, protocols, chains, and DeFi metrics |
| CryptoRank | https://cryptorank.io | Launchpads, vesting, tokenomics, and event calendars |

### Infra / privacy / accounts

| Tool / Site | Link | What it’s for |
|------------|------|---------------|
| HAPP | https://www.happ.su/main | Proxy / VPN / anonymity layer around your crypto activity (describe your exact setup) |
| Stealthsurf | https://stealthsurf.app | Private browsing / residential IPs / bypassing geo‑restrictions |
| Webshare | https://www.webshare.io | Rotating proxies for farming and multi‑account setups |

### Numbers, SIMs, cards

| Tool / Site | Link | What it’s for |
|------------|------|---------------|
| 5SIM | https://5sim.net | Temporary phone numbers for exchange / service registrations |
| Solcard | https://app.solcard.cc/ | Fiat ↔ Solana cards / payment bridges — describe how you actually use it |

---

## OSINT

### People / profiles

| Tool / Site | Link | What it’s for |
|------------|------|---------------|
| Google Dorks | https://google.com | Advanced search over profiles, leaks, and documents |
| LinkedIn | https://www.linkedin.com | Profiles, connections, and career history |
| Telegram search / bots | — | Channels, usernames, cross‑interest intersections |

### Domains, IP, infrastructure

| Tool / Site | Link | What it’s for |
|------------|------|---------------|
| Whoer | https://whoer.net/ru |  IP |
| Shodan | https://www.shodan.io | Exposed hosts, services, and banners by IP/ranges |
| Censys | https://search.censys.io | Certificates, hosts, and internet snapshots by services/TLS |

### Crypto OSINT

| Tool / Site | Link | What it’s for |
|------------|------|---------------|
| Arkham | https://arkhamintelligence.com | Wallet tracing and on‑chain activity, entity graphs |
| Dune | https://dune.com | Public dashboards and custom queries for on‑chain data |

---

## Life Infrastructure

### Notes & knowledge

| Tool / Site | Link | What it’s for |
|------------|------|---------------|
| Obsidian | https://obsidian.md | Local notes, PKM, markdown brain backup |
| Obsidian Publish | https://publish.obsidian.md | Public mirror of your notes / knowledge base |

### Health / tracking

| Tool / Site | Link | What it’s for |
|------------|------|---------------|
| AutoSleep (with Apple Watch) | https://autosleepapp.tantsissa.com | Fully automatic sleep tracking, sleep quality scoring and trends |


### Ops / privacy / money

| Tool / Site | Link | What it’s for |
|------------|------|---------------|

---

## Contributing

I’m always happy to discover new tools.  
If you think something belongs here:

- open an issue with a link  
- add 1–2 sentences on why it’s actually good and which section it fits into  

---

## Stay in touch

If you want to see how I actually use this toolbox in practice, or you’re just curious about my content and experiments:

- TWITTER / X (ENG): https://x.com/@sunch0x  
- Telegram (RU): https://t.me/sunch_exe  
- Obsidian / notes repo: https://publish.obsidian.md/sunch0x.dev  

---

## License

Nothing suffocating here: just link back to me — it’s nice to know this work is useful to someone.

This repository is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are allowed to:

- **Share** — copy and redistribute the material in any medium or format  
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially  

Under the following condition:

- **Attribution** — you must give appropriate credit and link back to this repository.  

A simple way to do this is:

> Based on the “awesome-systems-toolbox” curated by [sunch0x](https://github.com/sunch0x).
