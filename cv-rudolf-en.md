# Dirk Matthias Rudolf

Freelance TypeScript Full-Stack Engineer  
Diplom-Informatiker (FH) · Master of Science

Freelance since 2007 · Technical Director, meta.morph Medien GmbH,
2011–2015

Berlin  
[linkedin.com/in/dirk-matthias-rudolf](https://linkedin.com/in/dirk-matthias-rudolf)  
[github.com/drudolf](https://github.com/drudolf)

German (Native) · English (Fluent)

---

## Skills

| Web Development | Smart TV Apps | Technical Project Management |
| — | — | — |
| TypeScript | Tizen | AI Tooling / MCP |
| React | webOS | Agile Methods (Scrum, Kanban) |
| Node.js / Fastify | HbbTV | Test-Driven Development |
| Prisma / PostgreSQL | Video Streaming | Continuous Integration |


---

## Projects

### 2023–2026 · Web Development — Frontend/Backend

Built a modular tool suite for managing creatives, publishers, and
targeting as part of a team, covering the full stack from database
schema and API design to SPA architecture. Implemented with TypeScript,
React, Node.js, Fastify, Prisma, and PostgreSQL.

#### Smart TV — Live TV Application

Led full technical ownership of a live TV streaming application for
Tizen and webOS, from architecture through delivery. Built with
TypeScript and HLS.js.

---

### 2020–2023 · Smart TV — Media Library

Maintained and extended a media library app across multiple Smart TV
platforms (HbbTV, Tizen, webOS, NetCast, Orsay, and others) within an
agency team. Responsibilities included device-specific debugging,
platform updates, feature development, and release coordination.

#### Smart TV — Media Library Rebuild

Rebuilt the entire stack in TypeScript, React, and Node.js, rolling out
across HbbTV, Samsung (Tizen), LG (webOS), Panasonic, Philips, Sony,
Foxxum, and Hisense.

Notable challenges: a codebase with platform-specific adaptations for
eight manufacturers; DASH live streams with timeshift (restart)
functionality; VOD, subtitle, and multi-audio track support for
accessibility. Combined manual testing on physical devices with
cross-platform regression tests in Jest.

---

### 2015–2020 · Smart TV — Streaming Platform

Led the multi-platform port of a live streaming application to Samsung
(Orsay, Tizen) and LG (NetCast, webOS) using JavaScript, Backbone.js,
and DASH/HLS.

#### Smart TV — Streaming Platform Rebuild (Multi-Tenant)

Rebuilt as a TypeScript/React platform serving eight brands across five
TV platforms (Tizen, webOS, Panasonic, Set-Top-Box, and others),
developed collaboratively as a team.

Notable challenges: 5-key remote control navigation with focus
management in React; unifying diverse client requirements and platform
constraints into a single shared codebase; smooth video playback across
all supported devices. Built with TypeScript, React, and DASH.

---

## Open Source

### [prisma-pglite-bridge](https://github.com/drudolf/prisma-pglite-bridge)

Library for fast, reliable database testing with Prisma and PGlite

Isolated Prisma database tests without Docker or an external database
server — PGlite replaces PostgreSQL in-process, compatible with Vitest
and Jest.

### [fastify-lor-zod](https://github.com/drudolf/fastify-lor-zod)

Type provider for the Fastify API framework with Zod schema validation

End-to-end type-safe validation of requests and responses, with
automatic API documentation (OpenAPI/Swagger) from a single shared
schema definition. Rewritten in TypeScript with full Zod v4 support and
improved OpenAPI export.
