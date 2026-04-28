# Riassunto Lezione 8

## Contenuti principali
- Relazione tra convoluzione e cross-correlation.
- Introduzione alle CNN:
  - input come tensori/griglie;
  - blocchi convoluzionali;
  - condivisione dei pesi;
  - filtri/kernel appresi.
- Iperparametri dei layer convoluzionali:
  - depth;
  - kernel size;
  - stride;
  - zero padding.
- Pooling, in particolare max-pooling, come operazione non lineare di riduzione.
- Idea generale del backpropagation in blocchi convoluzionali/pooling.
- Introduzione alle RNN per dati sequenziali:
  - input di lunghezza variabile;
  - dipendenza temporale;
  - stato nascosto ricorrente.
- Esempi di dati sequenziali: testo, audio, serie temporali, video.

## Appunti aggiuntivi
- La CNN automatizza la ricerca di filtri utili: invece di progettare a mano Sobel o Gauss, lascia apprendere i kernel ai dati.
- Il pooling riduce risoluzione e sensibilita' a piccole traslazioni, ma perde parte dell'informazione spaziale.
- Le RNN vengono introdotte come risposta al limite di MLP/CNN su sequenze di lunghezza variabile.

## Cosa sapere bene
- Differenza tra convoluzione teorica e cross-correlation usata nei layer.
- Significato di stride e padding sull'output.
- Perche' la condivisione dei pesi riduce i parametri.
- Idea base di stato nascosto nelle reti ricorrenti.
