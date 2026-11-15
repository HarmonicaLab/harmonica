# Harmonica Lab – kit del marchio

Tutto quello che serve per tenere lo stesso stile su sito, Tool, video, miniature, PDF e social.
Stile "Cristallo": nero, oro e rosso, fondo crema, vetro chiaro, Montserrat e Anton.

## Cosa c'è nella cartella

| Cartella | Contenuto | Quando usarlo |
|---|---|---|
| `logo/` | Logo Cristallo completo, PNG trasparente: 2112, 1024, 512, 260, 64, 32 px | Intro dei video, miniature, PDF, banner, avatar. Da 96 px in su |
| `icona/` | Icona "HL" rotonda, PNG trasparente: 512, 180, 64, 32 px | Favicon, icona app, watermark, tutto ciò che è sotto i 96 px |
| `font/` | Anton, Montserrat Bold / Bold Italic / ExtraBold / ExtraBold Italic (.ttf) con le licenze OFL | Da installare sul Mac (doppio clic sul file → Installa) |

## Logo

- Il logo completo si usa così com'è: niente ricolorazioni, niente scritte aggiunte, niente contorni.
- Va bene sia su fondo chiaro (#F2EEE6) sia su fondo scuro (#111111).
- Sotto i 96 px le scritte non si leggono: usa l'icona HL.
- Composizione: illustrazione originale ripulita (microfono, chiave, cacciavite, ingranaggi, armonica), poi
  HARMONICA (Montserrat 800 corsivo, oro), LAB (Anton, rosso), pillola nera con bordo oro e BY SIMONE NOBILE (Montserrat 700).

## Colori

| Nome | Tema chiaro | Tema scuro | Uso |
|---|---|---|---|
| Fondo | `#F2EEE6` crema | `#111111` nero | Sfondo di pagine e video |
| Testo | `#111111` | `#F2EEE6` | Testo principale |
| Testo secondario | `#6F6A60` | `#9B958A` | Sottotitoli, etichette |
| Oro | `#BF8C3A` (accento `#B07F2A`) | `#D6A94F` | Titoli, HARMONICA, dettagli |
| Rosso | `#A02818` | `#D4503C` | LAB, parole in evidenza |
| Verde "intonato" | `#0F9D76` | `#2FD1A0` | Stato giusto nel Tool |

- Gradiente oro dei bottoni e del bordo del logo: da `#E3BF63` a `#B98F2E`, dall'alto in basso.
- Pillola attiva: nero sfumato da `#2B2B2B` a `#0B0B0B` con testo oro `#E6C168` (su tema scuro: pillola oro con testo nero).
- Nei video del Transcriber: note soffiate verdi `#1FBF84`, aspirate e bending arancio `#F07A1A`, pause grigie `#7A706A`.
- Il titolo non è mai sfumato: un colore pieno per parola (oro + rosso).

## Font (solo questi tre stili)

| Stile | Font | Dove |
|---|---|---|
| Titoli | **Montserrat ExtraBold 800 corsivo**, MAIUSCOLO, spaziatura -0,02 em | Titoli, nomi delle sezioni, bottoni, etichette, "HARMONICA" |
| Numeri ed enfasi | **Anton** (dritto) | Numeri grandi, numeri dei fori, "LAB" |
| Testi | **Montserrat Bold 700** dritto | Testi, sottotitoli, firma "BY SIMONE NOBILE" (maiuscolo spaziato) |

Sul web: `https://fonts.googleapis.com/css2?family=Anton&family=Montserrat:ital,wght@0,700;0,800;1,700;1,800&display=swap`

## Vetro (liquid glass chiaro)

- Riquadri: bianco al 55%, sfocatura 28 px con saturazione 180%, bordo bianco sottile, angoli arrotondati 30 px.
- Ombra larga e morbida, calda: `0 18px 50px rgba(60,45,20,.15)`.
- Pillole e bottoni completamente arrotondati.

## Tenerlo sul Mac

1. Scarica il kit: https://github.com/HarmonicaLab/harmonica/tree/main/brand
   (oppure tutto il repo in zip: https://github.com/HarmonicaLab/harmonica/archive/refs/heads/main.zip e prendi la cartella `brand`).
2. Copiala in `/Volumes/WD 4T/claude/brand-harmonica-lab/`.
3. Installa i font della cartella `font/` (doppio clic → Installa).
4. Per il montaggio del venerdì: copia `logo/logo-cristallo-1024.png` in `/Volumes/WD 4T/claude/monta-video/brand/` col nome `logo.png` (sostituisce il vecchio) e i `.ttf` in `brand/fonts/`.
