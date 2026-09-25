# BUILD brief — Cuota Autónomos Clarity (for opencode / grok CLI)

## Status (2026-09-26 ~01:50 CEST)
- Repo: https://github.com/peluzzzaZero/cuota-autonomos-clarity (public)
- Local: `/workspace/repos/cuota-autonomos-clarity/`
- Pages: enabled (legacy main/); URL target https://peluzzzazero.github.io/cuota-autonomos-clarity/
- Content v1 already shipped: tramos 2026 + tipos + cambios base + tarifa plana + regularización + FAQ + Quipu placeholder + BOE/Importass cites
- Sibling Verifactu: DO NOT edit

## Optional CLI polish (ONE short free call)
```bash
source /home/box/secrets/free-tiers/env.sh
cd /workspace/repos/cuota-autonomos-clarity
opencode run -m openrouter/google/gemini-2.0-flash-exp:free \
  "Polish Spanish copy only in index.html: fix typos, keep all BOE numbers unchanged, keep Quipu CTA as placeholder, do not invent legal advice. Output: list of edits then apply."
```
Prefer OpenRouter `:free`. Spare Grok CLI quota.

## Done when
- `curl -I https://peluzzzazero.github.io/cuota-autonomos-clarity/` → 200
- Disclosure + disclaimer still visible
- No Rewardful / no spend / no Verifactu edits
