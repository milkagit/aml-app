## Commit conventions
- Never mix project parts in one commit: separate commits for db/, be-part/, fe-part/.
- Commit in dependency order: db → be-part → fe-part; each commit must build and pass tests.
- Use Conventional Commits with scope: feat(db), feat(api), feat(rules), feat(ui), fix(...), docs, chore.
