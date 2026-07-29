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

| Repo | What it does |
|------|----------------|
| [anduril-lattice-hgv-scenario](https://github.com/Polybolos-Institute/anduril-lattice-hgv-scenario) | HGV-like COP vignette (open North Pacific; engagement authority sealed) |
| [anduril-lattice-barksdale-scenario](https://github.com/Polybolos-Institute/anduril-lattice-barksdale-scenario) | Barksdale COP vignette (synthetic tracks; engagement authority sealed) |
| [anduril-lattice-publish-soak](https://github.com/Polybolos-Institute/anduril-lattice-publish-soak) | Firehose entity PUT soak (5k/10k); counts 403 as Lattice-side evidence |
| [anduril-lattice-cop-narrator](https://github.com/Polybolos-Institute/anduril-lattice-cop-narrator) | Bounded read-only COP narrator (INFO/WATCH only; not Belarx) |
| [anduril-mavlink-lattice-bridge](https://github.com/Polybolos-Institute/anduril-mavlink-lattice-bridge) | MAVLink telemetry -> Lattice entities (C++/WinHTTP + Python) |
| [anduril-opensky-lattice-bridge](https://github.com/Polybolos-Institute/anduril-opensky-lattice-bridge) | OpenSky ADS-B -> Lattice entities (C++/WinHTTP + Python) |
| [anduril-dump1090-lattice-bridge](https://github.com/Polybolos-Institute/anduril-dump1090-lattice-bridge) | dump1090/readsb aircraft.json -> Lattice entities (C++/WinHTTP) |
| [anduril-lattice-rest-winhttp](https://github.com/Polybolos-Institute/anduril-lattice-rest-winhttp) | Shared WinHTTP Lattice REST client (OAuth, PUT, SSE stream) |
| [anduril-lattice-stream-watcher](https://github.com/Polybolos-Institute/anduril-lattice-stream-watcher) | Read-only Lattice entity stream watcher (SSE) |
| [anduril-lattice-entity-fixtures](https://github.com/Polybolos-Institute/anduril-lattice-entity-fixtures) | Example entity JSON fixtures + mock publish tests |
| [anduril-mock-lattice](https://github.com/Polybolos-Institute/anduril-mock-lattice) | Local Lattice sandbox mock for CI (OAuth + entity PUT) |
| [anduril-lattice-sandbox-dx](https://github.com/Polybolos-Institute/anduril-lattice-sandbox-dx) | Auth checklist, TLS notes, ontology cheat sheet |

**Sandboxes auth (short):** account Sandboxes Bearer in `Anduril-Sandbox-Authorization`; OAuth client id/secret per environment. Do not use an Environment JWT as the Sandboxes Bearer. Details: [anduril-lattice-sandbox-dx](https://github.com/Polybolos-Institute/anduril-lattice-sandbox-dx).

---

Website: [polybolos.org](https://www.polybolos.org)

Anduril and Lattice are trademarks of Anduril Industries.
