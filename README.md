### Caner Olcay

Wrocław, Poland. B.Eng. in Electronics & Computer Engineering — Wrocław University of Science and Technology.

I work in Python and SQL: backend services, APIs, and the data behind them. My day job is freight operations at RXO, so most of what I build sits close to how logistics actually runs — shipments, carriers, exceptions, and the reporting around them.

---

**Open source**

- [pytest-dev/pytest#14969](https://github.com/pytest-dev/pytest/pull/14969) — *merged.* Fixed `MonkeyPatch.setattr()` leaving inherited attributes in the instance `__dict__` after `undo()`. The old value was recorded with `getattr()`, which follows the MRO, so teardown wrote an entry that was never there — freezing non-data descriptors for every later lookup. Closed a long-standing issue.
- [sqlfluff/sqlfluff#8485](https://github.com/sqlfluff/sqlfluff/pull/8485) — *open.* Databricks dialect: made `PRIVATE` streaming tables and `CREATE FLOW` append flows parsable, with rejection tests so the grammar doesn't become a rubber stamp.

Both were developed with AI assistance and disclosed as such under each project's contribution policy.

---

**Projects**

- **Lucid** — AI study app, live on the App Store in 12 languages. Co-founder and backend engineer. FastAPI service, 20+ REST endpoints, OCR → embeddings → pgvector retrieval, Redis rate limiting, SSE streaming, 200+ tests.
  [uselucid.app](https://uselucid.app/) · [App Store](https://apps.apple.com/us/app/lucid-ai-flashcards-quiz/id6766661083)
- **[Solvro/ml-mcp](https://github.com/Solvro/ml-mcp)** — MCP server for my university's software development student group. Knowledge-graph retrieval over Neo4j, served through FastAPI.
- **NeuroPark** — 3D vehicle detection from single 2D traffic-camera images (YOLOv8, MiDaS, Open3D), validated against LiDAR. Presented at the KPZ25 engineering conference.

---

**Working with**

| | |
|---|---|
| Backend | Python · FastAPI · Flask · Pydantic · SQLAlchemy · Alembic · REST APIs · JWT |
| Data | PostgreSQL · SQL · pgvector · Redis · Neo4j · Supabase |
| AI / ML | RAG · LangChain · LangGraph · MCP · OpenAI API · OCR · PyTorch · YOLO · OpenCV |
| Infra & tooling | Docker · Git · GitHub Actions · Linux · AWS · pytest · Prefect |
| Also | C,C++ — embedded and signal-processing work from my degree |

---

[canerolcay.com](https://canerolcay.com) · [LinkedIn](https://www.linkedin.com/in/caner-olcay-bb3760257)
