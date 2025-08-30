# Light-Phase HFT Roadmap (Survey Sprint)

## Purpose
Quick, structured overview of all phases (~6–8 weeks). Breadth > depth. Goal: build mental map of the HFT field before deep dive.

## Structure
- **1–2 sessions per phase**.
- Focus: definitions, diagrams, latency budgets, failure modes.
- Deliverable: "HFT Landscape Notes" (~10–15 pages).

---

## Phase Breakdown

### Phase 0 — Baseline
- **Topics:** LLN/CLT/EVT, linear algebra recap, Linux perf tools, time sync basics (UTC/PTP/GPS).
- **Deliverable:** 1-page cheat sheet of formulas + latency measurement units.

### Phase 1 — Microstructure
- **Topics:** LOB mechanics, order types, priority models, matching cycle.
- **Deliverable:** Lifecycle diagram of an order (wire → engine → book update).

### Phase 2 — Data & Feeds
- **Topics:** Multicast vs TCP, gap detection, normalization, timestamp layers.
- **Deliverable:** Feed flow diagram (PHY → NIC → handler → book).

### Phase 3 — Networks & Time
- **Topics:** Colo setup, cross-connects, optics, switches, WAN (microwave vs fiber), PTP sanity.
- **Deliverable:** Latency budget table (wire → wire, hop breakdown).

### Phase 4 — Hardware Accel
- **Topics:** Kernel bypass (DPDK, AF_XDP), FPGA pipeline concept, NIC offloads.
- **Deliverable:** Block diagram of NIC → FPGA → exchange.

### Phase 5 — Strategy Archetypes (Sim Only)
- **Topics:** Passive MM, reactive takers, arb, queue models.
- **Deliverable:** One-page comparison of archetypes with risks/latency needs.

### Phase 6 — Reliability & Risk
- **Topics:** Kill switches, throttles, chaos drills, SIT/UAT.
- **Deliverable:** Checklist of risk controls (per layer: order, session, system).

### Phase 7 — Production Ops
- **Topics:** Monitoring (latency histograms, PTP sanity), incident review.
- **Deliverable:** Ops flow summary (detect → diagnose → recover).

### Phase 8 — Career & Craft
- **Topics:** Research ↔ engineering handoffs, interviewing, ethics.
- **Deliverable:** Reflection note (what excites me most, what to explore deeper).

---

## Timeline
- **Total Duration:** ~6–8 weeks.
- **Cadence:** 1–2 sessions per week.
- **End Product:** “HFT Landscape Notes” (structured field guide).

---

## After Survey
- Restart roadmap with **Phase 0 deep dive**.
- Build **skills matrix** and track mastery per phase.
- Proceed through full roadmap (12–18 months).

