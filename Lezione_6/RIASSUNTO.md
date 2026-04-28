# Riassunto Lezione 6

## Contenuti principali
- Introduzione alla visione artificiale e alle immagini digitali.
- Immagini RGB, scala di grigi, luminanza e immagine media.
- Immagine come tensore.
- Pipeline di computer vision:
  - acquisizione;
  - pre-processing;
  - feature extraction;
  - segmentazione/riconoscimento/identificazione.
- Operatori puntuali:
  - istogramma;
  - inversione dei livelli di grigio;
  - compressione logaritmica;
  - compressione di potenza;
  - espansione di contrasto.
- Implementazione con lookup tables/colormap.
- Operatori locali:
  - maschere e convoluzione discreta;
  - Sobel per i contorni;
  - Laplaciano;
  - filtri di smoothing: media, gaussiano;
  - confronto con filtri min/max/mediano.

## Appunti aggiuntivi
- Questa lezione collega matematica, immagini e implementazione pratica.
- Distinzione fondamentale:
  - operatore puntuale: ogni pixel e' trasformato indipendentemente;
  - operatore locale: ogni pixel dipende dal vicinato;
  - operatore globale: usa informazione dell'intera immagine.
- Sobel evidenzia variazioni orientate; Laplaciano evidenzia cambiamenti di intensita' di secondo ordine.

## Cosa sapere bene
- Formula della luminanza.
- Differenza tra istogramma, inversione, contrast stretching e gamma/log transform.
- Significato di convoluzione locale con maschera.
- Ruolo dei filtri Sobel, Laplaciano, medio, gaussiano e mediano.
