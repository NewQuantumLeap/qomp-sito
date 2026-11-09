# Sito di presentazione Qomp

Repository del sito statico di presentazione di Qomp (New Quantum Leap S.R.L.).

La copia in questo repository è la bozza v2 del 9 novembre 2026. Il file di ingresso è `index.html` (favicon, marchio e font sono incorporati nella pagina). Le note della cartella originale sono in `LEGGIMI.md`; le licenze dei font sono in `licenze/`.

## Vedere il sito in locale

Dalla radice del repository:

```bash
python3 -m http.server 8000
```

Aprire poi `http://localhost:8000/` nel browser. Si può anche aprire direttamente `index.html`.

Favicon e immagine Open Graph (`preview-desktop.png`) usano percorsi relativi, così la pagina resta valida anche se il sito è servito da una sottocartella.
