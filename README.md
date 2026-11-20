# Anis Torabi

**Backend & AI Automation Engineer**

I build backend systems and AI-assisted workflows that turn unstructured business input into validated, human-reviewable operations.

## Engineering Focus
- Python backend services and API design with FastAPI, Pydantic, and SQLAlchemy
- LLM integration, structured extraction, and provider abstraction
- Deterministic business rules, source-evidence validation, and role-based workflows
- Reproducible testing and systems-level research

## Selected Work

### [AI Order Processing Agent](https://github.com/forgeblueai/ai-order-processing-agent)
A B2B order-processing backend that separates language-model extraction from deterministic business validation and order-state transitions.
- Structured extraction through a provider interface with local Ollama integration
- Pydantic validation and source-evidence checks for extracted product references and quantities
- Deterministic inventory, pricing, and order-lifecycle handling
- SQLAlchemy persistence and role-based API authorization
- An 85-case synthetic benchmark corpus and evaluation harness

The extended private-demo runtime is being validated separately in [Draft PR #25](https://github.com/forgeblueai/ai-order-processing-agent/pull/25); it is not merged into `main` or released as a public demo (status checked 2026-11-20).

### [PHP Core Lab](https://github.com/forgeblueai/php-core-lab)
A reproducible research environment for PHP runtime behavior and memory-allocation boundaries.
- Exact upstream source revisions and reproducible build configurations
- PHPT regression tests and bounded resource-exhaustion probes
- Separate AddressSanitizer and UndefinedBehaviorSanitizer validation
- Evidence reports that distinguish observed runtime behavior from confirmed defects

## Upstream Contribution
- [php/php-src#24618 — Fix GH-24492: handle base64_encode() soft OOM](https://github.com/php/php-src/pull/24618): a proposed targeted fix with a reproducer and PHPT coverage. The pull request remains open and unmerged (checked 2026-11-20). It is not presented as an accepted upstream change or a new CVE.

## Background
Earlier work includes Linux infrastructure and security operations, as well as enterprise blockchain network development using Hyperledger Fabric and Polkadot in a private banking environment. Confidential project details are intentionally omitted.

## Contact
[LinkedIn](https://www.linkedin.com/in/anis-torabi)
