
# HFT Mentor Roadmap (Summary)

Phase 0 — Baseline
- Prob/stat refresh (LLN/CLT/EVT), linear algebra for signals.
- Software: Linux perf/eBPF, C++20, Python/NumPy.
- Time sync: UTC, GPS, PTP/1588, PPS; oscillator stability.

Phase 1 — Microstructure
- LOB mechanics; priority models; order types; auctions; tick/lot/price bands.
- Matching engine cycles; update semantics; latencies (wire → userland).

Phase 2 — Data & Feeds
- Multicast vs TCP; gap detection; seq/length checks.
- Feed handlers (CPU/FPGA); normalization; book build; conflation.
- Timestamping at PHY/MAC/NIC/kernel/user.

Phase 3 — Networks & Time
- Colocation, cross‑connects, optics; switches (cut‑through/store‑forward), QoS.
- WAN (microwave/mmWave/fiber), FEC, regen; PTP grandmasters/holdover.

Phase 4 — Hardware Accel
- DPDK/AF_XDP/io_uring; kernel bypass; NIC offloads.
- FPGA flow: RTL → timing closure; SERDES; CDC; deterministic pipelines.
- On‑NIC risk checks/order encoding; latency budgets.

Phase 5 — Strategy Archetypes (sim only)
- Passive MM and reactive takers; queue models; cross‑venue/ETF/deriv arb.
- Event/auction playbooks; impact‑aware sizing (theory).

Phase 6 — Reliability & Risk
- Kill switches, throttles, SMP, fat‑finger limits; canarying/feature flags.
- SIT/UAT/sim harnesses; determinism and chaos drills.

Phase 7 — Production Ops
- Monitoring (latency histograms, PTP sanity), pcaps, incident reviews.
- Change mgmt, audits, exchange certs, documentation.

Phase 8 — Career & Craft
- Research↔engineering handoffs; interviewing; ethics & compliance.

Deliverables: skills matrix, latency budget template, design review checklists.
