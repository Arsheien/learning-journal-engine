# Repository Structure

> Status: Accepted
> Last Updated: 2026-05-14

This document defines the official repository structure of the Learning Journal Engine (LJE).

The structure should remain stable unless an Architecture Decision Record (ADR) explicitly changes it.

---

# Principles

- Keep the repository simple.
- Create folders only when they have an immediate purpose.
- Documentation comes before implementation.
- Learning content is separated from project documentation.
- The engine should be extensible without restructuring the repository.

---

# Repository Structure

```text
learning-journal-engine/
│
├── .github/
│
├── assets/
│   └── README.md
│
├── docs/
│   ├── README.md
│   ├── architecture/
│   │   ├── README.md
│   │   └── repository-structure.md
│   ├── decisions/
│   │   └── README.md
│   ├── guides/
│   │   ├── README.md
│   │   └── development-principles.md
│   ├── philosophy/
│   │   ├── README.md
│   │   └── project-philosophy.md
│   └── roadmap/
│       └── README.md
│
├── modules/
│   ├── README.md
│   └── character-artist/
│       └── README.md
│
├── templates/
│   └── README.md
│
├── README.md
└── LICENSE
```

---

# Folder Responsibilities

## .github

Repository configuration.

Examples:

- Issue Templates
- Pull Request Templates
- GitHub Actions

---

## assets

Shared static resources.

Examples:

- Fonts
- Icons
- Images
- Logos

---

## docs

Project documentation.

Contains architecture, philosophy, guides, roadmaps and design decisions.

---

## modules

Learning modules.

Each module is an independent learning journey.

Examples:

- Character Artist
- Programming
- Japanese

---

## templates

Reusable templates for journals and workbooks.

Examples:

- Daily Page
- Weekly Review
- Monthly Review

---

# Future Expansion

The following directories are intentionally omitted from the initial structure.

They should only be created when development begins.

- apps/
- packages/
- engine/

---

# Repository Growth Policy

1. Prefer adding files before adding folders.
2. Avoid creating empty directories.
3. Keep documentation close to its subject.
4. One folder should have one clear responsibility.
5. Major structural changes require an ADR.

---

# Status

This document defines the initial repository structure for Milestone 0.

Future updates should preserve backward compatibility whenever possible.

---

# Next Actions

The repository structure is intentionally minimal.

The following tasks will complete the Foundation phase.

| Priority | Task | Estimated Time |
|----------|------|---------------:|
| 🔴 Immediate | Draft the Engine architecture in `docs/architecture/` | 20–30 min |
| 🔴 Immediate | Define the consumers of `templates/` in `templates/README.md` | 10 min |
| 🟡 This Week | Create the Milestone 1 plan in `docs/roadmap/` | 30 min |
| 🟡 This Week | Establish asset management guidelines for `assets/` | 15 min |
| 🟢 Later | Add the first GitHub Issue Template under `.github/` | 20 min |

---

## Notes

The Foundation phase prioritizes documentation over implementation.

Applications (`apps/`), reusable packages (`packages/`), and the engine implementation will be introduced only when actual development begins.

This keeps the repository lightweight while allowing future expansion.
