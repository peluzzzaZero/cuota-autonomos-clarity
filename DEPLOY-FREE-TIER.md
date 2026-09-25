# Deploy free-tier — Cuota Autónomos Clarity

**Cost:** €0 (no custom domain).  
**Source:** this repo root (`index.html` + `styles.css`).  
**Hard NO:** custom domain buy, Rewardful (until OK), paid ads, card spend.

## Deployed

**Public URL:** https://peluzzzazero.github.io/cuota-autonomos-clarity/  
**Public mirror:** https://github.com/peluzzzaZero/cuota-autonomos-clarity (`main` / root = site)

Same pattern as Verifactu: public mirror only (keeps Exploracion private).

### Enable Pages (if not live yet)

```bash
gh api -X POST repos/peluzzzaZero/cuota-autonomos-clarity/pages \
  -f build_type=legacy -f source='{"branch":"main","path":"/"}'
# or UI: Settings → Pages → Deploy from branch main / root
```

### Verify

```bash
gh api repos/peluzzzaZero/cuota-autonomos-clarity/pages
curl -I https://peluzzzazero.github.io/cuota-autonomos-clarity/
```

## Honesty checklist

- [x] Free static publish path
- [ ] Rewardful Quipu live + CTA real (still placeholder)
- [x] Disclosure afiliado + banner “afiliado pendiente”
- [x] Disclaimer no-asesoramiento
- [x] Citations BOE Orden PJC/297/2026 + Importass
- [x] No Ads / no domain buy / no secrets
