# Learning Log

## 2026-04-29 — Foundations and architecture choices

### What you practiced
- Converting product goals into explicit technical decisions.
- Choosing layered backend structure used in many enterprise teams.
- Separating "scaffolding" from "implementation" for safer iteration.

### Key concepts
- **Monorepo tradeoffs**: unified versioning and easier coordination vs larger repo scope.
- **Layered Spring architecture**:
  - `controller`: HTTP boundary and request/response handling
  - `service`: business logic orchestration
  - `repository`: persistence/data access abstraction
- **Manual SQL-first approach**: helps you internalize relational modeling before migration tooling.

### Questions to reflect on
- Which domain entity should be implemented first (`EmailAccount` vs `EmailMessage`)?
- What minimum fields are required for deterministic job-event classification?
- What retention default should apply to raw email bodies in local development?

### Next learning step
- Write first Architecture Decision Records and mail integration research notes with source links.
