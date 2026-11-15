# Deckverse Rules Agent Instructions

### Mandatory CI cost preflight - owner2026-11-12

- Follow the workspace cost-control policy before every push/dispatch, including automatic workflows. Inspect affected paths, runner/matrix, current jobs and release need; validate locally and batch verified changes before consuming shared Actions budget.
- At75% budget usage, defer optional heavy CI and repeated platform builds. For an already authorized release, prefer reviewed local artifacts plus the narrow existing signing/upload workflow; retain every required release check. If current billing is unavailable, label estimates honestly and defer optional paid work.
- Image/content/document-only changes must not launch unrelated app/native builds. Inspect existing triggers first; prepare a safe scoped correction or keep changes local rather than repeatedly triggering expensive CI. Preserve branch-required status checks and approved content-only publication.
- Diagnose failures before targeted retries; reuse valid successful artifacts. Never raise budgets, expand billing permissions, weaken checks or claim that instructions alone changed remote workflows. Record material runs/cost uncertainty in the existing task/work log.


## Shared Standards

- `../AI_PROJECT_STANDARD.md` applies when available in the Sina Software
  workspace.
- `../SINA_SOFTWARE_APP_RULES.md` does not directly apply to this content and
  rules repository.
- `../SINA_SOFTWARE_SUBSCRIPTION_STANDARD.md` does not apply.

## Working Rules

- Treat `README.md` and the existing scenario data as the source of truth.
- Preserve existing rule behavior and data formats unless explicitly asked to
  change them.
- Inspect consumers before changing a scenario contract.
- Keep changes small and validate affected scenarios and links.
- Use English for code, filenames, and documentation unless preserving
  localized product content.
