# OctoBot-Market-Making: portable verification records

Full raw logs are retained in the workspace maintenance evidence, not distributed here. Hashes identify those original logs. A successful build or selected test subset does not imply a full test-suite pass. Commands containing <workspace> describe the original execution environment.

[Machine-readable records](verification.json) · [Repository validation summary](../validation.md)

## Executed commands

| Check | Exit | Duration | Command | Outcomes |
| --- | ---: | ---: | --- | --- |
| build | 0 | 1.01s | `uv build --python 3.13` | Successfully built dist/octobot_market_making-2.1.1.tar.gz<br>Successfully built dist/octobot_market_making-2.1.1-py3-none-any.whl |
| compile | 0 | 0.08s | `<workspace>/OctoBot-Market-Making/.venv/bin/python -m compileall -q src` | See exit status; no test-count assertion. |
| current-sync | 0 | 0.61s | `uv sync --all-extras --python 3.14` | See exit status; no test-count assertion. |
| current-sync-2 | 0 | 2.14s | `uv sync --all-extras --python 3.14` | See exit status; no test-count assertion. |
| final-build | 0 | 2.03s | `uv build --python 3.14.8` | Successfully built dist/octobot_market_making-2.1.1.tar.gz<br>Successfully built dist/octobot_market_making-2.1.1-py3-none-any.whl |
| final-build-2 | 0 | 1.06s | `uv build --python 3.14.8` | Successfully built dist/octobot_market_making-2.1.1.tar.gz<br>Successfully built dist/octobot_market_making-2.1.1-py3-none-any.whl |
| final-compile | 0 | 0.09s | `.venv/bin/python -m compileall -q src` | See exit status; no test-count assertion. |
| final-compile-2 | 0 | 0.09s | `.venv/bin/python -m compileall -q src` | See exit status; no test-count assertion. |
| final-lock | 0 | 0.58s | `uv lock --upgrade` | See exit status; no test-count assertion. |
| final-lock-2 | 0 | 0.5s | `uv lock --upgrade` | See exit status; no test-count assertion. |
| final-sync | 0 | 0.59s | `uv sync --all-extras --frozen --python 3.14.8` | See exit status; no test-count assertion. |
| final-sync-2 | 0 | 0.65s | `uv sync --all-extras --frozen --python 3.14.8` | See exit status; no test-count assertion. |
| lock-3.13 | 0 | 0.77s | `uv lock --upgrade --python 3.13` | See exit status; no test-count assertion. |
| lock-3.14 | 0 | 0.34s | `uv lock --upgrade --python 3.14` | See exit status; no test-count assertion. |
| lock-3.15 | 0 | 1.64s | `uv lock --upgrade --python 3.15` | See exit status; no test-count assertion. |
| sync-3.13 | 1 | 7.62s | `uv sync --all-extras --python 3.13` | See exit status; no test-count assertion. |
| sync-3.14 | 1 | 3.9s | `uv sync --all-extras --python 3.14` | See exit status; no test-count assertion. |
| sync-3.15 | 1 | 5.22s | `uv sync --all-extras --python 3.15` | See exit status; no test-count assertion. |
| tests | 1 | 0.04s | `<workspace>/OctoBot-Market-Making/.venv/bin/python -m pytest tests` | See exit status; no test-count assertion. |
| tests-2 | 3 | 34.54s | `.venv/bin/python -m pytest tests` | See exit status; no test-count assertion. |
| tests-3 | 0 | 9.86s | `.venv/bin/python -m pytest tests` | 1 passed in 6.63s |
