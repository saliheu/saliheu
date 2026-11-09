### Salih Enes Ünal

Backend developer. Computer Engineering, Eskişehir Osmangazi University, 2026.

I write backend services in Go and Python. For the past year I have been working on
LLM based systems: retrieval, agents, and fine-tuning open models for narrow tasks.

**Backend** Go (Gin, GORM) · Python (FastAPI) · PostgreSQL · Redis · REST · Docker
**AI** LangChain · RAG · LLM/VLM integration · open-model fine-tuning · OpenCV
**Also** TypeScript · Node.js · Vue · React · C# (ASP.NET Core) · MS SQL

---

#### Projects

**[go-address-validator](https://github.com/saliheu/go-address-validator)** · Go, Gin, GORM, PostgreSQL, Redis, Docker

An address validation API over the GeoNames dataset. Administrative hierarchies are
not the same shape in every country, so one self-referencing table with a numeric
level replaces fixed province/district columns. Turkish breaks naive string matching
in two ways the language runtime will not warn you about, so every lookup goes
through a Turkish-aware normalizer. Matching returns a confidence score rather than
a boolean, because real input is truncated and misspelled.

**[pixel-bar](https://github.com/saliheu/pixel-bar)** · Node.js, TypeScript, ws, PixiJS

A realtime 2D virtual bar. Four rooms of 25 players each, fully isolated from one
another, with six multiplayer minigames running over a single WebSocket protocol.
All state lives in server memory, no database. 23 end to end checks cover room
isolation, capacity rejection and counter cleanup.

**[turnuva-panosu](https://github.com/saliheu/turnuva-panosu)** · TypeScript, Vite, Netlify Functions

Tournament management for school sports. Group draw, round-robin scheduling,
qualification rules and bracket generation are each their own module. Admin sessions
use HMAC signed cookies with constant time password comparison. 36 unit tests.

**[seu-mobilya](https://github.com/saliheu/seu-mobilya)** · Vue 3, TypeScript, three.js

A made-to-measure furniture configurator. 209 designs, a rule engine that rejects
invalid layouts, and a live three.js scene with a 180 cm figure for scale. 242 tests
cover every product in the catalog plus the rule engine.

---

[LinkedIn](https://linkedin.com/in/salihenesu) · salihenesu@gmail.com · Eskişehir
