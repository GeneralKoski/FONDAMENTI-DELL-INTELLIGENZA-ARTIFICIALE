# Riassunto Lezione 5

## Contenuti principali
- Completamento del calcolo dei gradienti per reti neurali.
- Derivata della loss sul neurone di output.
- Estensione della discesa del gradiente a MLP con strati nascosti.
- Algoritmo di backpropagation:
  - errore sul layer di output;
  - propagazione all'indietro sugli strati nascosti;
  - aggiornamento dei parametri.
- Addestramento epoca per epoca su dataset.
- Teorema di approssimazione universale:
  - un MLP con un solo hidden layer puo' approssimare funzioni continue su compatti.

## Appunti aggiuntivi
- Questa e' la lezione piu' tecnica sulle reti feed-forward.
- Il backpropagation va capito come applicazione sistematica della regola della catena su una composizione di funzioni.
- Il teorema di approssimazione universale non dice che una rete piccola impari facilmente tutto; dice solo che la capacita' rappresentativa esiste.

## Cosa sapere bene
- Cosa sono le quantita' `delta` nei layer.
- Differenza tra forward pass e backward pass.
- Perche' la backpropagation e' efficiente.
- Interpretazione corretta del teorema di approssimazione universale.
