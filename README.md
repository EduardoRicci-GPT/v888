# v888.TXT — Plexo Sináptico Textual (Sprint 1)

Config-first. Papel descoberto no boot via Config+DBF. Anti-literal 2D. Auditoria com hash de identidade. Protocolo INP mínimo.

## Como rodar (MVP shadow)
1) `python -m venv .venv && source .venv/bin/activate`
2) `pip install pyyaml`
3) Preencha **apenas cabeçalhos** em `schemas/*.csv` (já prontos).
4) `python examples/run_mvp_shadow.py`

Saídas:
- `logs/audit/audit_<data>.jsonl` (eventos selados)
- Hash de identidade no retorno
