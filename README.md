# automation-snippets

Daily Python utilities — small, self-contained helpers I keep rewriting while doing IT operations, DBA work, and automation.

Each file is copy-pasteable: drop into a project, adjust constants, ship.

## Index

| Date | Snippet | What |
|---|---|---|
| 2026-04-25 | [excel-autosize-cols](snippets/2026-04-25-excel-autosize-cols.py) | Auto-fit openpyxl column widths to content |

## Why

A steady GitHub activity stream and a personal library of small utilities — grep-able, version-controlled, no `~/scripts/temp.py` graveyard.

## Conventions

- **Filename:** `YYYY-MM-DD-short-name.py`
- **Header:** docstring with motivation, usage, dependencies
- **Size:** keep it under ~80 lines — if it grows past that, it deserves its own repo
- **No frameworks:** stdlib + one or two PyPI packages, max
- **Runnable:** every snippet should run as `python snippets/<file>.py` or be importable

## License

MIT — see [LICENSE](LICENSE). Use freely.
