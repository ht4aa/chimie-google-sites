# Chimie — Proiect interdisciplinar

Site static pentru un proiect școlar de chimie, găzduit pe GitHub Pages la [berbechimie.site](https://berbechimie.site).

## Structură

- `/acasa/` — pagina principală
- `/h2o/` — apa
- `/co2/` — dioxid de carbon
- `/nacl/` — clorură de sodiu
- `/quiz/` — quiz interdisciplinar
- `404.html` — pagină custom pentru rute inexistente

Conținutul HTML provine dintr-un export Google Sites, peste care e injectat un navbar custom și câteva ajustări de stil.

## Deploy

Push pe `main` → GitHub Actions rulează `.github/workflows/pages.yml` și publică automat pe Pages.
