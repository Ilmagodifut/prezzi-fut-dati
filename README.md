# prezzi-fut-dati

I dati dell'app **Prezzi FUT** (https://prezzi-icon.pages.dev): prezzi delle carte speciali di FC 27, storico di 24 ore e storico orario di 30 giorni.

- Il lavoro `.github/workflows/prezzi.yml` guarda fut.gg ogni 20 secondi e rifà i dati appena cambiano.
- I file escono sul ramo `dati`: `promo-quando.json`, `promo-vista.json`, `promo-24h.json`, `storia/<id % 128>.json`.
- Prezzi = il «compralo subito» più basso, non le vendite.

La copia buona del codice sta nel repo privato FUTMAGO, in `tools/prezzi-icon/lavoro/`.
