# Mattis Regnaut

**Full-Stack Developer · AI/LLM Engineer · Security Researcher**

---

## About

Developer with a focus on LLM infrastructure, model deployment, and web development.  
Interested in the intersection of open-source AI tooling, backend systems, and application security.

---

## Skills

**AI & LLM**
- Model inference & serving — vLLM, LM Studio, Ollama
- Quantization — GPTQ, AWQ, FP8 dynamic (see [HuggingFace ↗](https://huggingface.co/MattisR))
- LLM APIs — OpenAI, Anthropic Claude, Mistral
- Prompt engineering, RAG pipelines

**Infrastructure & DevOps**
- AWS EC2 — deployment & inference of large models
- Docker — containerization of ML workloads
- Linux server administration

**Web Development**
- Backend — Laravel, Node.js
- Frontend — Next.js, Vue.js, SvelteKit
- Systems — Rust (Axum)

---

## Open Source Contributions

[**prism-php/prism**](https://github.com/prism-php/prism) — Unified LLM interface for Laravel (2.3k ⭐)

| PR | Type | Description |
|---|---|---|
| [#748](https://github.com/prism-php/prism/pull/748) | Feature | Added `keep_alive` option for Ollama provider |
| [#687](https://github.com/prism-php/prism/pull/687) | Bug fix | Fixed response parsing when output contains ` ```json ` blocks |
| [#403](https://github.com/prism-php/prism/pull/403) | Feature | Added multimodal support to PrismServer API endpoints |

---

## Security Research

**[CVE-2024-47186](https://www.wiz.io/vulnerability-database/cve/cve-2024-47186)** — XSS in [Filament](https://github.com/filamentphp/filament) (Laravel full-stack framework)  
Unvalidated color values passed to `ColorColumn` / `ColorEntry` components allowed XSS injection via Laravel's `@style` Blade directive. Affected versions v3.0.0–v3.2.114. Patched in v3.2.115 following responsible disclosure. CVSS 3.1: **6.1 (Medium)**

---

## Published Models

| Model | Task | Downloads |
|---|---|---|
| [Voxtral-Small-24B-2507-FP8-dynamic](https://huggingface.co/MattisR/Voxtral-Small-24B-2507-FP8-dynamic) | Automatic Speech Recognition (24B) | 26 |

---

## Contact

[HuggingFace](https://huggingface.co/MattisR) · [GitHub](https://github.com/sv-LayZ)
