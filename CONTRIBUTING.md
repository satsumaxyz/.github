# Contributing

Thanks for your interest. Most repositories here are private while Satsuma is
under active development; this guide applies to all of them unless a
repository has its own.

## Workflow

1. Branch from the default branch — never commit to `main` directly.
   Name branches `feat/…`, `fix/…`, `chore/…`, `docs/…`.
2. Keep each pull request to one change, with a title in the imperative
   ("Add …", "Fix …") and a description of what and why.
3. Make sure the repository's build, tests and linters pass (see its
   `README.md` / `AGENTS.md`).
4. Pull requests are **squash-merged**; the branch is deleted on merge.

## Rules

- Never commit secrets: `.env`, `.dev.vars`, keys, seeds, tokens. Use the
  `*.example` files and the platform's secret store.
- Don't put host names, IP addresses or custody details in code, docs or
  commit messages.
- Repositories Satsuma built and owns (topic `satsuma-built`) change only
  through Satsuma's own process — open an issue rather than a pull request.

## AI coding agents

Every repository has an `AGENTS.md` with build/test commands and conventions
for coding agents (`CLAUDE.md` imports it).
