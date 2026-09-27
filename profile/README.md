
<div align="center">
  <img src="./assets/syberlabs_mark_s.png" width="150" alt="SyberLabs mark" />
  <h1>SyberLabs</h1>
  <p><strong>Independent software lab building interactive reading experiences and inspectable agent systems.</strong></p>
</div>

## RISE and Kev

**[RISE](https://github.com/SyberLabs/RISE)** is a live browser reader for text, time, image, and sound. Readers can present the same source in Stream or Page and control the pace and presentation. [Open RISE](https://rise.syberlabs.io/) · [See the project](https://syberlabs.io/projects/rise/)

RISE has used **Jev**, TypeSafe AI's model, for bounded reading decisions. We are migrating that path to **[Kev](https://github.com/jaredpalmer/kev)**, Jared Palmer's open decision-model project. The migration work adds pinned server-side provider configuration, but we have not confirmed a live Kev deployment or independently verified a Kev reading outcome. The prior Jev evaluation remains [historical evidence](https://syberlabs.io/jev/), not a Kev result. [Kev migration status](https://syberlabs.io/kev/)

In the migration candidate, optional Scriptorium model routing suggests a composition format from a typed request. The proposed route keeps the provider credential on RISE's server and removes the reader API-key field. Its Kev behavior has not been verified live, and Jev remains an explicit rollback option. RISE still examines the resulting proposal through its own code. Chamber reading and pacing run locally without a model call or provider key.

---

## Selected work

| Project | What it is |
| --- | --- |
| **[OSAHR](https://github.com/SyberLabs/OSAHR_Cell)** | A Python kernel for stochastic, adaptive rewriting of typed hypergraphs with event replay. |
| **[OmniOS](https://github.com/SyberLabs/OmniOS)** | A canvas connecting live information sources to AI personas with inspectable context. |
| **[Papers](https://github.com/SyberLabs/papers)** | Research projects with clear status, claim limits, and reproduction steps. |

---
## People

- [Mateo Robles](https://github.com/sykosyber) — product, HCI, machine learning, and systems
- [Seth Carlson](https://github.com/sdcarlson) — Relay lead engineer; systems work on RISE and OSAHR

[**syberlabs.io**](https://syberlabs.io/) · [**Email**](mailto:syberlabs.software@gmail.com)
