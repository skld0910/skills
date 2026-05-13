---
name: design
description: >
  Load a brand's design system (colors, typography, components, layout) from the awesome-design-md library.
  Use when the user wants to build UI matching a specific brand's visual language,
  like "design in the style of Apple", "use Stripe design tokens", "make it look like Airbnb".
  Supports 73 brands across AI, SaaS, Fintech, E-commerce, Automotive and more.
argument-hint: [brand]
arguments: [brand]
allowed-tools: Read Grep Glob WebFetch
---

# Design System Skill

Load the DESIGN.md for the specified brand from the [awesome-design-md](https://github.com/voltagent/awesome-design-md) repository and apply its design language.

## Available brands

| Category | Brands |
|----------|--------|
| AI & LLM | claude, cohere, elevenlabs, minimax, mistral.ai, ollama, opencode.ai, replicate, runwayml, together.ai, voltagent, x.ai |
| Developer Tools | cursor, expo, lovable, raycast, superhuman, vercel, warp |
| Backend/DevOps | clickhouse, composio, hashicorp, mongodb, posthog, sanity, sentry, supabase |
| Productivity/SaaS | cal, intercom, linear.app, mintlify, notion, resend, slack, zapier, miro |
| Design/Creative | airtable, clay, figma, framer, webflow |
| Fintech/Crypto | binance, coinbase, kraken, mastercard, revolut, stripe, wise |
| E-commerce/Retail | airbnb, meta, nike, shopify, starbucks |
| Media/Consumer | apple, ibm, nvidia, pinterest, playstation, spacex, spotify, theverge, uber, vodafone, wired |
| Automotive | bmw, bmw-m, bugatti, ferrari, lamborghini, renault, tesla |

## Usage

```
/design airbnb
/design stripe
/design claude
```

## Instructions

1. Fetch the DESIGN.md from `https://raw.githubusercontent.com/voltagent/awesome-design-md/main/design-md/$brand/DESIGN.md`
2. Present a brief summary of the brand's design system (key colors, typography, component styles)
3. Apply these design tokens for any UI the user asks you to build
4. If the brand is not found, list available brands from the table above
