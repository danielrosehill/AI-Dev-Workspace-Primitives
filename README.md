# AI Dev Workspace Primitives

Index of development-repository primitives — root-level `UPPERCASE.md` files that act as foundational context surfaces for AI-assisted projects.

## Convention

- Each primitive is an `UPPERCASE.md` file at the root of a project repo.
- Capital letters are the distinguishing feature, signalling foundational, agent-readable context.
- Each one expands on a classic surface (e.g. README, CONTRIBUTING) into a structured agent-facing context file.
- Layered on top: `CLAUDE.md` / `AGENTS.md`, which can inject every `UPPERCASE.md` file at the repo root as foundational context.

## Primitives

| File | Purpose |
|---|---|
| [USER_PROFILE.md](https://github.com/danielrosehill/USER_PROFILE.md) | Per-repo user profile (collaborative / out-of-VC overrides) |
| [ENVIRONMENT.md](https://github.com/danielrosehill/ENVIRONMENT.md) | Development and deployment environment |
| [SPEC.md](https://github.com/danielrosehill/SPEC.md) | First-entry authoritative project specification |
| [BUDGET.md](https://github.com/danielrosehill/BUDGET.md) | Financial constraints and cost mitigation |
| [PROJECT.md](https://github.com/danielrosehill/PROJECT.md) | Overarching plan and major architectural decisions (also where development decisions are recorded — replaces a `MEMORY.md`) |
| [TOOLS.md](https://github.com/danielrosehill/TOOLS.md) | Necessary / available tools, often via a referenced vault |
| [PROCESS.md](https://github.com/danielrosehill/PROCESS.md) | Project-specific development processes |
| [RULES.md](https://github.com/danielrosehill/RULES.md) | Guardrails and authorizations |
| [PREFERENCES.md](https://github.com/danielrosehill/PREFERENCES.md) | Persistent stack preferences (model hierarchies, libraries) |
| [LOG.md](https://github.com/danielrosehill/LOG.md) | Raw agent work log |
| [STYLE.md](https://github.com/danielrosehill/STYLE.md) | Brand palette, fonts, assets, logos |
| [SCAFFOLDS.md](https://github.com/danielrosehill/SCAFFOLDS.md) | Preferred scaffold or reference to a scaffolds library |
| [DOCS.md](https://github.com/danielrosehill/DOCS.md) | Documentation style guide and writing preferences |
| [GROUNDING.md](https://github.com/danielrosehill/GROUNDING.md) | Whitelist of authoritative URLs for grounding (official docs, canonical specs) |
| `CONTEXT.md` (pre-existing) | Loose, free-form contextual data for the repo |

## Notes

- `MEMORY.md` is intentionally omitted. Development decisions are recorded in `PROJECT.md` rather than a separate memory file.
- `CONTEXT.md` already exists as a convention for loose / scratchpad contextual data and is referenced here for completeness.
