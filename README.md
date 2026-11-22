# tulivu-packages

Shared packages consumed by `tulivu-web` and `tulivu-backend`.

## Packages
- `shared/` (`@tulivu/shared`) - schemas, constants, utils, types shared by frontend and backend.
- `ad-platforms/` (`@tulivu/ad-platforms`) - ad platform adapters/contracts (primarily backend).

## Local development
During the initial split migration, web/backend repos may temporarily vendor copies of these packages.
Target state: consume this repo as a git submodule (pinned ref) or versioned package per `docs/REPO_SPLIT_AND_ALIGNMENT_PLAN.md` Decision #3.

## Scripts
```bash
pnpm install
pnpm typecheck
```
