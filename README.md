## Status & recognition (factual)
**OASW(SO/LIC) Accelerator Event — July 2026 (GoColosseum)**  
Submission status: **Selected**. Per the portal, Selected means the submission was found **technically meritorious** and is under evaluation/consideration. 
**AFRL engagement — April 2026**  
COMMAND HOTL materials were provided to Air Force Research Laboratory contacts at their request:
- **Col Christopher Rondeau (AFRL/RQ):** after receiving the package, requested permission to share it with additional colleagues while **building out this portfolio**; permission granted (**portfolio review / distribution interest**).
- **Isaac Weintraub, PhD (Control Science Center, Air Warfare Directorate / RA):** detailed technical Q&A on risk awareness, weaponeering, kinematics, and coordination. He wrote that the exchange helped him understand **"the state of the art"** and what can be gained through **future partnerships**, and indicated he would convey **SBIR** topic materials and/or partnering.
That is attributed scientific and portfolio dialogue. 
**Technology maturity**  
Command HOTL is assessed at **TRL 5** (lab / SITL / controlled demo / Lattice developer sandbox). Decision-C2 / human-on-the-loop authority lineage. 
**Lattice**  
Sandbox / interoperability evidence (including documented scale publish–ingest work) supports Lattice-edge integration feasibility. Not a production Lattice mesh claim. Independent of Anduril; samples are not Anduril products.
**Inquiries:** mark.brown@polybolos.org  
CAGE: 1AVY9 · UEI: RUSHH9B2UQV3 · Polybolos Institute

### Hi. We study how defense systems break.

**Polybolos Institute** is a 501(c)(3) nonprofit research organization built around one question:

> How do defense systems fail, and how do we find those failure modes before an adversary does?

Named after the *Polybolos* - the ancient world's first automated repeating weapon (c. 300 BC) - we study what happens when automation, AI, and systems engineering meet time-constrained, high-stakes engagements. Not in theory. Under stress.

**Focus:** behavior at the edge - multi-effector coordination, AI decision-making under load, saturation, and resilience that hides fragility until the wrong conditions appear.

**Research domains**
- Decision latency and timing collapse
- Engagement behavior under saturation
- Distributed sensing and response synchronization
- Resource allocation under pressure
- Autonomous systems with human-on-the-loop control

Applied work lives at [polybolos.org](https://www.polybolos.org) - simulation environments, white papers, and partnership R&D with government, academia, and industry.

---

### What we publish here

This GitHub account holds **independent Anduril Lattice interoperability doors** (MIT): thin adapters that move sensor/telemetry into Lattice World Model entities, plus sandbox DX helpers for auth and CI.

These are **samples for interoperability demos** - not C2 core, not ROE, and **not an Anduril product**.

**Flagship (denied / intermittent backhaul):** keep the track picture on the edge when publish is denied; resume entity publish when the link returns. Live Sandboxes evidence in the contested-bridge repo.

| Repo | What it does |
|------|----------------|
| [polybolos-lattice-cpp-contested-bridge](https://github.com/Polybolos-Institute/polybolos-lattice-cpp-contested-bridge) | C++ WinHTTP contested bridge: edge coast + live soak evidence |
| [polybolos-denied-comms-c2](https://github.com/Polybolos-Institute/polybolos-denied-comms-c2) | Edge-native denied-comms fusion framework |
| [anduril-lattice-publish-soak](https://github.com/Polybolos-Institute/anduril-lattice-publish-soak) | Firehose entity PUT soak (5k/10k); counts 403; no client throttle |
| [anduril-lattice-rest-winhttp](https://github.com/Polybolos-Institute/anduril-lattice-rest-winhttp) | Shared WinHTTP Lattice REST client (OAuth, PUT, SSE stream) |
| [anduril-mock-lattice](https://github.com/Polybolos-Institute/anduril-mock-lattice) | Local Lattice sandbox mock for CI (OAuth + entity PUT) |
| [anduril-lattice-entity-fixtures](https://github.com/Polybolos-Institute/anduril-lattice-entity-fixtures) | Example entity JSON fixtures + mock publish tests |
| [anduril-lattice-stream-watcher](https://github.com/Polybolos-Institute/anduril-lattice-stream-watcher) | Read-only Lattice entity stream watcher (SSE) |
| [anduril-mavlink-lattice-bridge](https://github.com/Polybolos-Institute/anduril-mavlink-lattice-bridge) | MAVLink telemetry -> Lattice entities (C++/WinHTTP + Python) |
| [anduril-opensky-lattice-bridge](https://github.com/Polybolos-Institute/anduril-opensky-lattice-bridge) | OpenSky ADS-B -> Lattice entities (C++/WinHTTP + Python) |
| [anduril-dump1090-lattice-bridge](https://github.com/Polybolos-Institute/anduril-dump1090-lattice-bridge) | dump1090/readsb aircraft.json -> Lattice entities (C++/WinHTTP) |
| [anduril-lattice-sandbox-dx](https://github.com/Polybolos-Institute/anduril-lattice-sandbox-dx) | Auth checklist, TLS notes, ontology cheat sheet |
| [anduril-lattice-hgv-scenario](https://github.com/Polybolos-Institute/anduril-lattice-hgv-scenario) | HGV-like COP vignette (open North Pacific; engagement authority sealed) |
| [anduril-lattice-barksdale-scenario](https://github.com/Polybolos-Institute/anduril-lattice-barksdale-scenario) | Barksdale COP vignette (synthetic tracks; engagement authority sealed) |
| [anduril-lattice-cop-narrator](https://github.com/Polybolos-Institute/anduril-lattice-cop-narrator) | Bounded read-only COP narrator (INFO/WATCH only; not Belarx) |

**Sandboxes auth (short):** account Sandboxes Bearer in `Anduril-Sandbox-Authorization`; OAuth client id/secret per environment. Do not use an Environment JWT as the Sandboxes Bearer. Details: [anduril-lattice-sandbox-dx](https://github.com/Polybolos-Institute/anduril-lattice-sandbox-dx).

---

Website: [polybolos.org](https://www.polybolos.org)

Anduril and Lattice are trademarks of Anduril Industries.

## Contact

This repository is the open foundation (MIT).

Polybolos Institute also maintains a proprietary catalog of additional capabilities that are not published here. Contact us to discuss production deployment and commercial licensing.

mark.brown@polybolos.org · https://www.polybolos.org
