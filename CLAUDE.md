# Harmonica Lab – note per Claude

Repo dei tool di Harmonica Lab (GitHub Pages: https://harmonicalab.github.io/harmonica/):
- `index.html`: Harmonica Lab Tool (accordatore / note)
- `tabscriber/index.html`: Harmonica Lab Tab Transcriber (tablatura)
- `chromatic.html`: pagina cromatica (stile vecchio, non ancora aggiornata)

## Stile da seguire sempre

Per ogni nuova pagina, grafica, video o contenuto usa il kit in `brand/` e la guida `brand/README.md`:
- Logo: `brand/logo/logo-cristallo-*.png` (da 96 px in su); sotto i 96 px l'icona `brand/icona/icona-hl-*.png`.
- Font: solo Montserrat 800 corsivo (titoli, maiuscolo), Anton (numeri, LAB), Montserrat 700 dritto (testi).
- Colori: fondo crema `#F2EEE6` / nero `#111111`, oro `#BF8C3A` (`#D6A94F` su scuro), rosso `#A02818` (`#D4503C` su scuro).
- Vetro chiaro: bianco 55%, blur 28 px, bordo bianco, angoli 30 px, pillole arrotondate.

Il logo è incorporato in base64 (webp 260 px) nell'header di `index.html` e `tabscriber/index.html` (`img.hl-logo`):
se cambia il logo, rigenera il webp da `brand/logo/logo-cristallo-2112.png` e sostituiscilo in entrambi i file.
