# Contributing â€” Tremblay Thoughts Holding Inc

All repositories in this organization are **private research projects**.
External contributions are not accepted unless you have been explicitly invited.

---

## For Internal Contributors

### Workflow

1. **Pick a task** â€” every repo has a `TASKS.md` backlog. Start there.
2. **Open an issue** before starting non-trivial work. Use the issue templates provided.
3. **Branch naming** â€” `feat/<slug>`, `fix/<slug>`, `docs/<slug>`, `exp/<slug>`.
4. **Commits** â€” follow Conventional Commits: `feat:`, `fix:`, `docs:`, `refactor:`, `test:`.
5. **Pull request** â€” link the issue (`Closes #N`), fill the PR template, request review.
6. **Do not push directly to `main`** â€” all merges go through PRs.

### Code Standards

- Python: `black` + `ruff` (enforced via pre-commit)
- Tests: `pytest` â€” add a test for every new behavior
- No secrets or credentials committed to any repo

### IP Assignment

All work produced in the context of this organization is subject to the PIIAA.
IP vests in Tremblay Thoughts (TTH) upon creation, not upon merge.

---

## Reporting Issues

Use the issue tracker in the relevant repository.
For security issues, see [SECURITY.md](SECURITY.md).
