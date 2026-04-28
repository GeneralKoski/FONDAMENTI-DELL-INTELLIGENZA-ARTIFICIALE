# Riassunto Lezione 4

## Contenuti principali
- Apprendimento supervisionato:
  - dataset di training;
  - inferenza;
  - addestramento come ottimizzazione dei parametri.
- Idea di modello parametrico `f_theta`.
- Definizione di funzione di costo/loss.
- Loss principali presentate:
  - `L1` o geometria del taxi;
  - `L2` / MSE.
- Minimizzazione della loss con discesa del gradiente.
- Derivazione del gradiente rispetto a pesi e bias.
- Regola della catena come strumento base per propagare le derivate.

## Appunti aggiuntivi
- Questa lezione spiega il cuore del machine learning: non basta definire un modello, bisogna definire anche "come misuro l'errore".
- La parte piu' importante non e' ricordare formule isolate, ma il flusso:
  - scelgo modello;
  - scelgo loss;
  - calcolo il gradiente;
  - aggiorno i parametri.
- La chain rule qui non e' un dettaglio di analisi: e' il principio che rende possibile il backpropagation.

## Cosa sapere bene
- Differenza tra training e inferenza.
- Che cos'e' una loss e perche' serve.
- Significato di `L1` e `L2`.
- Idea di derivata della loss rispetto ai parametri.
