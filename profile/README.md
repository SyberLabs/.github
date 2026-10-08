<div align="center">
  <img src="./assets/syberlabs_mark_300.png" width="150" alt="SyberLabs mark" />
  <h1>SyberLabs</h1>
  <p><strong>Independent software lab building interactive reading experiences and inspectable agent systems.</strong></p>
  <p>We make an instrument for reading, a workspace for thinking with AI over live data, and infrastructure that lets agents do work under human keys.</p>
</div>

<!-- Reflects: SyberLabs/RISE@7d95863 (main, 2026-10-08) · verified 2026-10-07 -->
## RISE

**[RISE](https://github.com/SyberLabs/RISE)** is a browser-based audiovisual reader. It presents text through time, image, sound and procedural visuals, so a book can be read as a timed stream or a typeset page. Open beta, Apache 2.0.

[**Open RISE →**](https://rise.syberlabs.io/) · [About the project](https://syberlabs.io/projects/rise/) · [Architecture](https://github.com/SyberLabs/RISE/blob/main/docs/specs/ARCHITECTURE.md)

Three constraints decide everything else in it:

1. **No shared inference.** Every model call runs on the reader's own key or the reader's own machine. RISE never pays for a reader's thinking, and its servers hold no model credential.
2. **A browser, no account.** There is no identity service and no server-side reader state. Nothing a reader types or reads leaves their device unless they send it.
3. **Content is static and content-addressed.** Editions, recitation, imagery and programs are files named by their hash and verified on every read.

Reading and pacing need no model at all. The optional AI reading request is bring-your-own: **Connect OpenRouter** runs hosted Jev (TypeSafe AI) on the reader's own OpenRouter account, and **Run locally** pairs RISE with a pinned Kev-4B, from **[Kev](https://github.com/jaredpalmer/kev)**, Jared Palmer's open decision-model project, on the reader's own GPU. Either way the model only proposes: RISE admits an answer only when it picks from the choices RISE offered. We have not independently verified a Kev reading outcome; the earlier Jev evaluation is [historical evidence](https://syberlabs.io/jev/), not a Kev result. [How reader-owned AI works](https://syberlabs.io/kev/)

---

## Selected work

| Project | What it is |
| --- | --- |
| **[OmniOS](https://github.com/SyberLabs/OmniOS)** | A canvas for thinking with AI over live data. Blocks pull real numbers, wires feed them into personas, and a question is answered from what the wires carry. It runs without keys on public sources and local models. A capability engine compiles OpenAPI and MCP descriptions into typed blocks; writes wait for approval. |
| **[SyberWork](https://github.com/SyberLabs/SyberWork)** | Contracts govern work. A case history records what was proposed, admitted, observed, approved and executed, in a hash-chained, signed event log. Apache 2.0. |
| **[OSAHR](https://github.com/SyberLabs/OSAHR_Cell)** | A Python kernel for exact, open, stochastic adaptive rewriting of typed directed hypergraphs, with event replay and no runtime dependencies. Apache 2.0. |
| **[Papers](https://github.com/SyberLabs/papers)** | Research artifacts at different stages, each with its evidence, claim limits and reproduction steps. |

**[Engines](https://sykosyber.github.io/engines/)** is Mateo's generative work: seven procedural engines, each a single HTML file in Canvas 2D or WebGL2, no libraries.

## How we work

Agents write much of our code. People hold the keys: nothing an agent produces is admitted until a person, or a gate a person set, accepts it. Every repository states what is implemented, what is partial, and what its results do and do not show.

---

## People

- [Mateo Robles](https://github.com/sykosyber) — product, HCI, machine learning and systems
- [Seth Carlson](https://github.com/sdcarlson) — engineering infrastructure and architecture on RISE; systems work on OSAHR

[**syberlabs.io**](https://syberlabs.io/) · [**Email**](mailto:syberlabs.software@gmail.com)
