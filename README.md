# hireflow-site

Public marketing site + demos for HireFlow, deployed at https://hireflow.velogorithm.com

## Structure

| File | Purpose |
|---|---|
| `index.html` | Product page (homepage) |
| `hireflow-manager.html` | HR/manager funnel demo (linked from product page) |
| `hireflow-newhire.html` | New hire onboarding wizard demo |
| `_headers` | Cloudflare Pages security headers |
| `_redirects` | Pretty URLs: `/manager` and `/newhire` |

## Deploy

Push to `main` — Cloudflare Pages auto-deploys within ~60 seconds.

```bash
git add . && git commit -m "your message" && git push
```

## Local preview

```bash
python3 -m http.server 8000
# Then open http://localhost:8000/
```

---

*Velogorithm · Edmonton, Alberta*
