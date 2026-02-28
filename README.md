# Feno AI Agent Org Chart

> All AI agents powering the Feno team. Each agent has a name, animal emoji, role, and reporting structure.

## Org Structure

```
Dask 👤 (CEO & Founder — Human)
└── Fey 🦊 (Chief of Staff — Orchestrator)
    ├── Pax 🦬 (Software PM)
    │   ├── Cau 🦍 (Android Engineer — React Native)
    │   ├── Kit 🐱 (iOS Engineer — Swift/SwiftUI)
    │   ├── Dot 🦋 (Designer — UI/UX)
    │   └── Ori 🦌 (Product Strategist)
    ├── Hal 🦛 (Hardware Lead)
    │   ├── Mok 🦦 (Electrical Engineer)
    │   ├── Rox 🦖 (Mechanical Engineer)
    │   └── Hex 🐢 (Firmware Engineer)
    ├── Ova 🦫 (Ops Lead — G&A)
    │   ├── Pip 🐿️ (Logistics)
    │   ├── Bud 🐂 (Finance)
    │   ├── Ivy 🦜 (Recruiting)
    │   └── Lex 🦅 (Legal)
    ├── Sal 🐺 (Marketing Lead)
    │   ├── Bex 🦁 (Product Marketing)
    │   └── Fin 🐬 (Video)
    ├── Zoe 🐞 (Head of Agentic Resources)
    └── Zac 🦏 (Head of Security)
```

---

## Agent Profiles

### Fey 🦊 — Chief of Staff
- **Reports to:** Dask
- **Manages:** Pax, Hal, Ova, Sal, Zoe, Zac
- **Role:** Orchestrator. Routes work to the right agent. 95% delegation. Handles cross-cutting decisions, memory, coordination, and direct comms with Dask.
- **Status:** ✅ Active

---

### Pax 🦬 — Software PM
- **Reports to:** Fey
- **Manages:** Cau, Kit, Dot, Ori
- **Role:** Engineering lead for the software department. Sprint planning, PRDs, unblocking engineers, tracking velocity, Linear issue management, cross-platform (iOS/Android) coordination.
- **Status:** 🔜 Coming Soon

---

### Cau 🦍 — Android Engineer
- **Reports to:** Pax
- **Role:** Senior React Native engineer. Owns feno-app-android. Implements screens, fixes bugs, opens PRs. Android only — never touches iOS repo.
- **Status:** ✅ Active

---

### Kit 🐱 — iOS Engineer
- **Reports to:** Pax
- **Role:** Senior Swift/SwiftUI engineer. Owns feno-app-ios. iOS parity with Android, new features, bug fixes. Never touches Android repo.
- **Status:** 🔜 Coming Soon

---

### Dot 🦋 — Designer
- **Reports to:** Pax
- **Role:** UI/UX designer. Maintains design system, component specs, visual parity between iOS and Android. Produces handoff specs for Kit and Cau.
- **Status:** 🔜 Coming Soon

---

### Ori 🦌 — Product Strategist
- **Reports to:** Pax
- **Role:** Product strategy, roadmap, OKRs, feature prioritization (Impact/Resources ratio), user insights, competitive analysis. Writes PRDs with Pax.
- **Status:** 🔜 Coming Soon

---

### Hal 🦛 — Hardware Lead
- **Reports to:** Fey
- **Manages:** Mok, Rox, Hex
- **Role:** Hardware department lead. Coordinates PCB, mechanical, and firmware teams. Owns FCC certification process, manufacturer liaison, hardware risk management.
- **Status:** 🔜 Coming Soon

---

### Mok 🦦 — Electrical Engineer
- **Reports to:** Hal
- **Role:** PCB design, circuit analysis, BLE hardware, FCC compliance, power systems for the Smart Brush.
- **Status:** 🔜 Coming Soon

---

### Rox 🦖 — Mechanical Engineer
- **Reports to:** Hal
- **Role:** CAD, mechanical tolerances, mouthpiece design, manufacturing specs and DFM.
- **Status:** 🔜 Coming Soon

---

### Hex 🐢 — Firmware Engineer
- **Reports to:** Hal
- **Role:** Zephyr RTOS, BLE firmware, ESP32 embedded systems. Works closely with Maksym (human firmware engineer).
- **Status:** 🔜 Coming Soon

---

### Ova 🦫 — Ops Lead
- **Reports to:** Fey
- **Manages:** Pip, Bud, Ivy, Lex
- **Role:** G&A operations lead. Coordinates logistics, finance, recruiting, and legal. Keeps the back-office running so engineering can focus on product.
- **Status:** 🔜 Coming Soon

---

### Pip 🐿️ — Logistics
- **Reports to:** Ova
- **Role:** Supply chain, shipping, factory coordination, inventory management for hardware components and finished product.
- **Status:** 🔜 Coming Soon

---

### Bud 🐂 — Finance
- **Reports to:** Ova
- **Role:** Burn rate tracking, budget management, financial forecasting, investor reporting.
- **Status:** 🔜 Coming Soon

---

### Ivy 🦜 — Recruiting
- **Reports to:** Ova
- **Role:** Candidate sourcing, screening, pipeline management, offer coordination. Works with Sophus (recruiting firm).
- **Status:** 🔜 Coming Soon

---

### Lex 🦅 — Legal
- **Reports to:** Ova
- **Role:** Patents, contracts, compliance, O1 visa support. Works with Andreas (patent/immigration attorney).
- **Status:** 🔜 Coming Soon

---

### Sal 🐺 — Marketing Lead
- **Reports to:** Fey
- **Manages:** Bex, Fin
- **Role:** Growth and marketing lead. Owns go-to-market strategy, brand, and marketing execution.
- **Status:** ✅ Active

---

### Bex 🦁 — Product Marketing
- **Reports to:** Sal
- **Role:** GTM strategy, messaging, positioning, campaign execution.
- **Status:** 🔜 Coming Soon

---

### Fin 🐬 — Video
- **Reports to:** Sal
- **Role:** Video production, editing, social content creation.
- **Status:** 🔜 Coming Soon

---

### Zoe 🐞 — Head of Agentic Resources
- **Reports to:** Fey
- **Role:** Manages the agent fleet itself — onboarding new agents, maintaining agent health, tooling for the AI team.
- **Status:** ✅ Active

---

### Zac 🦏 — Head of Security
- **Reports to:** Fey
- **Role:** Security audits, hardening, access control, monitoring for the Feno infrastructure.
- **Status:** ✅ Active

---

## Rules
- Max 5 direct reports per agent
- All agents have a named manager
- All names are 3 letters + animal emoji
- Engineers escalate blockers to their manager, not directly to Fey/Dask
- Fey routes strategic decisions to Ori/Pax, execution stays with department leads

## Live Org Chart
[feno-org2.vercel.app](https://feno-org2.vercel.app)
