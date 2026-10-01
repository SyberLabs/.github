
<div align="center">
  <img src="./assets/syberlabs_mark_s.png" width="150" alt="SyberLabs mark" />
  <h1>SyberLabs</h1>
  <p><strong>Independent software lab building interactive reading experiences and inspectable agent systems.</strong></p>
</div>

<!-- Reflects: SyberLabs/RISE@64c046a (PR #294, merged 2026-09-30) · verified 2026-10-01 -->
## RISE and reader-owned inference

**[RISE](https://github.com/SyberLabs/RISE)** is a live browser reader for text, time, image, and sound. Readers can present the same source in Stream or Page and control the pace and presentation. [Open RISE](https://rise.syberlabs.io/) · [See the project](https://syberlabs.io/projects/rise/)

RISE spends no shared inference. The six reading-decision routes it once served now answer `410 SHARED_INFERENCE_RETIRED`, and the RISE Worker holds no model credential of any kind. A reader who wants a bounded reading decision brings their own model: **Connect OpenRouter**, billed to the reader's own OpenRouter account, or **Run locally** (`npm run local`), which pairs RISE with a pinned Kev-4B — from **[Kev](https://github.com/jaredpalmer/kev)**, Jared Palmer's open decision-model project — on the reader's own GPU, and sends nothing to us. SyberLabs hosts no Jev or Kev endpoint for anyone.

Chamber reading and pacing run locally with no model call and no provider key — that is the default and the common case. Where a model does take part, it only proposes: RISE examines every proposal through its own code before anything is admitted. We have not independently verified a Kev reading outcome, and the earlier Jev evaluation remains [historical evidence](https://syberlabs.io/jev/) rather than a Kev result. [Inference status](https://syberlabs.io/kev/)

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
