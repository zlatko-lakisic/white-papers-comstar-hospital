<!-- Hero image: assets/hero.png. Recommended 1600px wide, 16:9 or wider. -->
![COMSTAR](assets/hero.png)

# COMSTAR: The Addressable Hospital

### Federated Edge Intelligence With a Face, and Why It Is Buildable Now

Companion to *FUSION: Federated Unified Sensor Intelligence on Network*.

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
![Version](https://img.shields.io/badge/version-1.0-blue)
![Pages](https://img.shields.io/badge/pages-58-lightgrey)

### 📄 [Download the white paper (PDF)](COMSTAR-HOSPITAL_WhitePaper_v1.0.pdf)

### 📊 [Companion ROI model (Excel)](COMSTAR_Hospital_ROI_Model.xlsx)

---

## What this is

Hospitals have spent a decade instrumenting themselves. The data exists. It is accurate. And it is almost entirely unreachable by the person who needs it, because it lives in dashboards, on workstations, behind logins, in a different room from the work.

This paper proposes an architecture for **addressable edge intelligence in healthcare facilities**: a distributed layer of low-cost terminals that convert the intelligence a hospital already generates into something a clinician can talk to at the point of work.

Hard real-time inference stays on the endpoint. Heavier recognition stays on-premise. Adoption is outcome-led, beginning with operational outcomes that carry no PHI. Capacity is deterministic. The commercial case is framed as incremental value over tools the hospital already owns.

This is a concept paper with a working prototype behind it. It is not a product specification, a clinical validation, or an investment memorandum.

---

## Executive summary

Put a terminal in the room. Not a screen to walk to and log into, but a presence that knows who just walked in, listens when addressed, and answers out loud. Back it with an orchestration engine that can call the systems the hospital already owns.

Six outcomes, in ascending order of regulatory difficulty: asset readiness, room turnover, schedule conflict detection, ambient documentation, identity-aware patient interaction, and patient safety observation. The first three involve no PHI and are the entry point.

Incumbents already sell pieces of this surface. The contribution argued here is the assembly of on-premise inference, directory-sourced authorization, capability removal, deterministic capacity, readiness composition, and outcome-ordered adoption into one governable package.

---

## What the paper covers

| Section | Contents |
|---|---|
| **1. Foreword** | Why a network with a face |
| **2–3. Abstract and Executive Summary** | Proposal, outcomes, economics |
| **4. The Problem** | Last mile gap and why incumbents do not close it |
| **5. The Concept** | Addressable presence and identity architecture |
| **6. Pain Points and Outcomes** | Six things a hospital would pay to fix |
| **7. Architecture** | Three tiers, one fabric |
| **8. The Network** | Transport, Wi-Fi limits, slicing as governance |
| **9. Graceful Adoption** | Outcome first; who has to say yes |
| **10. Predictable Scaling** | Deterministic capacity versus consumption pricing |
| **11. The Value Case** | Increment framing, ranges, pilot validation plan |
| **12. Security, Privacy, and Governance** | Endpoint versus building boundaries |
| **13–15. Maturity, Considerations, Conclusion** | Built vs argued, open questions, call to action |
| **Appendices** | Reference hospital model and value assumptions |

58 pages, 14 figures.

---

## Companion workbook

Illustrative figures for a ~400-bed reference facility, framed as **incremental value over tools the hospital already owns**. Soft-dollar capacity, not posts removed, except outcome 6. Every number below is a formula over an editable assumption in the workbook.

### Value by outcome

| Outcome | Illustrative annual increment | FTE-equivalent | Type |
|---|---|---|---|
| 1. Asset location and readiness | ~$0.6M | ~3.5 | Augment |
| 2. Room readiness and turnover | ~$0.3M | ~1.0 | Augment |
| 3. Schedule and conflict detection | ~$0.9M | ~1.5 | Augment |
| 4. Ambient clinical documentation | ~$0.8–1.2M | ~3.4 | Augment |
| 5. Patient interaction | ~$0.4M | ~3.3 | Augment |
| 6. Safety observation | ~$1.7M | ~29 | Replace |
| **Illustrative full-scope total** | **~$5–7M** | **~40+** | **~29 actual posts only in outcome 6** |

### Investment and return by scope

| | Full deployment (6 outcomes, ~600 terminals) | Phase 0+1 (outcomes 1–3, ~100 terminals) |
|---|---|---|
| Capital | ~$2.5–4M+ | ~$0.6–1.2M |
| Annual operating | order ~$0.8M | order ~$0.2M |
| Illustrative annual value | ~$5–7M | ~$1.5–2.5M |

### After a soft-dollar discount

| Scope | Before finance discount | After ~30% soft-dollar haircut |
|---|---|---|
| Full deployment | ~$5–7M | ~$3.5–5M |
| Phase 0+1 | ~$1.5–2.5M | ~$1–1.7M |

**[Download the editable model (Excel)](COMSTAR_Hospital_ROI_Model.xlsx)** — replace blue input cells with the target facility's own measurements.

---

## Working sources

Editable markdown, stylesheet, figures, and workbook live in:

[white-papers / papers/comstar-hospital](https://github.com/zlatko-lakisic/white-papers/tree/main/papers/comstar-hospital)

Build from the repository root:

```bash
./build.sh comstar-hospital --check
```

---

## License

Licensed under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0).

You are free to share and adapt this material, including commercially, provided you give appropriate credit.

See [LICENSE](LICENSE) and [LICENSE.md](LICENSE.md).

*"ComStar" and the ComStar starburst are the intellectual property of Topps and Catalyst Game Labs, used affectionately in a personal, non-commercial reference implementation. Any commercial realization would carry a different name.*

---

## Feedback

Corrections and disagreement are welcome, especially on the network argument, the value model assumptions, competitive differentiation, and the regulatory path for observation workloads. Open an issue or reach out directly.

**Zlatko Lakisic**
[Portfolio](https://zlatko-lakisic.github.io/zlatko-lakisic/) · [LinkedIn](https://www.linkedin.com/in/zlatko-lakisic/)
