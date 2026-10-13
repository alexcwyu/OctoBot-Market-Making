# OctoBot-Market-Making: portable verification records

<!-- current-documentation-provenance -->
Documentation reviewed: 2026-10-13 · Git source base: `21e0d4c21b4f6460e36113d5254cab55a22108ec` · [Current architecture and feature guide](../ayu-develop.md).
Historical execution commands/results below retain their original dates and scope; this metadata update is not a new application test run.
<!-- /current-documentation-provenance -->


These records retain exact commands, outcomes, original-log hashes and available source snapshots. Failed, interrupted and earlier exploratory commands remain visible. A later focused pass proves only its own scope.

[Machine-readable records](verification.json) · [Validation](../validation.md) · [Engineering guide](../ayu-develop.md)

Original logs remain in the workspace maintenance evidence. Tracked source hashes exclude untracked additions and later edits, as stated in each captured snapshot.

| Check | Exit | Duration | Command |
| --- | ---: | ---: | --- |
| build | 0 | 1.01s | `uv build --python 3.13` |
| compile | 0 | 0.08s | `<workspace>/OctoBot-Market-Making/.venv/bin/python -m compileall -q src` |
| current-sync-2 | 0 | 2.14s | `uv sync --all-extras --python 3.14` |
| current-sync | 0 | 0.61s | `uv sync --all-extras --python 3.14` |
| final-build-2 | 0 | 1.06s | `uv build --python 3.14.8` |
| final-build | 0 | 2.03s | `uv build --python 3.14.8` |
| final-compile-2 | 0 | 0.09s | `.venv/bin/python -m compileall -q src` |
| final-compile | 0 | 0.09s | `.venv/bin/python -m compileall -q src` |
| final-lock-2 | 0 | 0.5s | `uv lock --upgrade` |
| final-lock | 0 | 0.58s | `uv lock --upgrade` |
| final-sync-2 | 0 | 0.65s | `uv sync --all-extras --frozen --python 3.14.8` |
| final-sync | 0 | 0.59s | `uv sync --all-extras --frozen --python 3.14.8` |
| lock-3.13 | 0 | 0.77s | `uv lock --upgrade --python 3.13` |
| lock-3.14 | 0 | 0.34s | `uv lock --upgrade --python 3.14` |
| lock-3.15 | 0 | 1.64s | `uv lock --upgrade --python 3.15` |
| compile | 0 | 0.06s | `.venv/bin/python -Werror -m compileall -q src` |
| sync | 0 | 3.02s | `uv sync --all-extras --frozen --python 3.15.0` |
| build | 0 | 1.06s | `uv build --python 3.15.0` |
| compile | 0 | 0.08s | `/tmp/octobot-market-making-final315-control/bin/python -Werror -m compileall -q src` |
| lock | 0 | 1.9s | `uv lock` |
| sync | 0 | 1.41s | `uv sync --all-extras --frozen --python 3.15.0` |
| tests | 0 | 9.62s | `/tmp/octobot-market-making-final315-control/bin/python -m pytest tests --tb=short` |
| sync-3.13 | 1 | 7.62s | `uv sync --all-extras --python 3.13` |
| sync-3.14 | 1 | 3.9s | `uv sync --all-extras --python 3.14` |
| sync-3.15 | 1 | 5.22s | `uv sync --all-extras --python 3.15` |
| tests-2 | 3 | 34.54s | `.venv/bin/python -m pytest tests` |
| tests-3 | 0 | 9.86s | `.venv/bin/python -m pytest tests` |
| tests | 1 | 0.04s | `<workspace>/OctoBot-Market-Making/.venv/bin/python -m pytest tests` |
