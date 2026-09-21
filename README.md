# Agent/50

An interactive competitive-intelligence demo for exploring agent companies with publicly documented funding rounds of at least $50M.

The demo compares each company's product, buyer, market wedge, evidence, pricing motion, and go-to-market sequence. A TypeSafe/Jev integration can rerank the companies against different startup theses using typed `Choice`, `Score`, and `Noul` judgments.

## Live demo

[Open Agent/50](https://agent-50-jev.lauralin123.chatgpt.site)

## Included companies

- Sierra
- Decagon
- Harvey
- Cognition
- Glean
- Gradial

The interface links each profile to its supporting primary source. Company-reported metrics are identified as company claims rather than independent verification.

## Run locally

```bash
npm install
npm run dev
```

Open `http://localhost:3000`.

## Enable live Jev ranking

Keep the API key server-side:

```bash
TYPESAFE_API_KEY=your_key npm run dev
```

Without a key, the application remains usable in demo mode with deterministic rankings.

## Build

```bash
npm run build
```

## Research scope

This is a directional product and go-to-market analysis, not investment advice. Funding figures and market claims can change; verify the linked sources before relying on them.
