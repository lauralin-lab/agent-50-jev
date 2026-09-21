# Robotics/Map

An interactive robotics-intelligence tracker covering company funding, technical talent, research publications, platforms, deployments, and live website signals.

The demo compares leading robotics companies across research strength, capital, deployment maturity, and talent density. A TypeSafe/Jev integration classifies live competitive signals with typed `Choice`, `Score`, and `Noul` judgments.

## Live demo

[Open Robotics/Map](https://agent-50-jev.lauralin123.chatgpt.site)

## Initial landscape

- Figure
- Physical Intelligence
- Skild AI
- 1X
- Apptronik
- Agility Robotics
- FieldAI
- Waabi
- Shield AI
- Dexterity

The interface links each profile to its supporting primary source. Company-reported metrics are identified as company claims rather than independent verification.

## Run locally

```bash
npm install
npm run dev
```

Open `http://localhost:3000`.

## Enable live Jev signal classification

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
