# Project Log

## 2026-04-29 — Initial learning-first scaffold

### Files created/modified
- `docs/project-log.md`
- `docs/learning-log.md`
- `docs/research/mail-integrations.md`
- `docs/decisions/` (directory)
- `frontend/README.md`
- `frontend/src/app/.gitkeep`
- `frontend/src/components/.gitkeep`
- `frontend/src/pages/.gitkeep`
- `frontend/src/api/.gitkeep`
- `frontend/src/types/.gitkeep`
- `frontend/src/hooks/.gitkeep`
- `frontend/src/features/.gitkeep`
- `backend/README.md`
- `backend/src/main/java/com/example/jobtracker/controller/.gitkeep`
- `backend/src/main/java/com/example/jobtracker/service/.gitkeep`
- `backend/src/main/java/com/example/jobtracker/repository/.gitkeep`
- `backend/src/main/java/com/example/jobtracker/model/.gitkeep`
- `backend/src/main/java/com/example/jobtracker/dto/.gitkeep`
- `backend/src/main/java/com/example/jobtracker/config/.gitkeep`
- `backend/src/main/java/com/example/jobtracker/exception/.gitkeep`
- `backend/src/test/java/com/example/jobtracker/.gitkeep`
- `sql/README.md`
- `sql/schema-draft.sql`

### Reason for each change
- Established the approved monorepo structure without adding framework dependencies yet.
- Created documentation-first workflow artifacts (`project-log`, `learning-log`) as requested.
- Added research placeholder for mail API investigation before implementation.
- Added backend layered package skeleton (`controller/service/repository`) to match enterprise-learning preference.
- Added frontend learning-oriented folders for React+TypeScript architecture.
- Added SQL draft area for manual schema authoring and future Flyway migration planning.

### Concepts to learn from this step
- Why documentation-first scaffolding improves decision clarity.
- Monorepo organization and cross-project boundaries.
- Layered architecture responsibilities in Spring Boot.
- Frontend folder responsibilities in React+TypeScript.
- SQL-first schema iteration before migration automation.

### Next recommended step
1. Add decision records under `docs/decisions/` for the chosen architecture constraints.
2. Draft `docs/research/mail-integrations.md` with verified provider/API details and open questions.
3. Scaffold minimal frontend (`npm create vite`) and backend (`spring initializr`) only after review.
