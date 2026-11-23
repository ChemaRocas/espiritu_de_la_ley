# Espiritu De La Ley

Personal project to see how reliably I can vibe-code (with the correct steering) an ai lawyer for mexico that can help a regular citizen navigate the murky waters of the mexican legal system

## Setup (once per computer)

```bash
python3 -m venv .venv
.venv/bin/python -m pip install -e ".[dev]"
cp .env.example .env      # then fill in the keys
```

## Running it

TODO: the command(s) to run, and what they produce.

## Where things are

- `espiritu_de_la_ley/`: the code
- `data/`: inputs the code is built from (committed)
- `output/`: everything a run produces (not committed: may contain personal data)
- `docs/`: how to run and maintain each process
- `tests/`: run them with `.venv/bin/python -m pytest`

Notes for AI coding agents are in [AGENTS.md](AGENTS.md).
