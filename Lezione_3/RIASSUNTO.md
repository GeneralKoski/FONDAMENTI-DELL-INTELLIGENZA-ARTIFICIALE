# Riassunto Lezione 3

## Contenuti principali
- Algoritmo di discesa del gradiente per trovare minimi di funzioni.
- Metodo iterativo `x_{k+1} = x_k - eta * grad f(x_k)`.
- Ruolo del learning rate `eta` e delle strategie di arresto.
- Introduzione ai neuroni artificiali:
  - percettrone;
  - pre-attivazione `x·w+b`;
  - neurone attivo/non attivo.
- Funzioni di attivazione:
  - Heaviside;
  - sigmoide logistica;
  - ReLU;
  - softplus;
  - tanh.
- Architetture di rete:
  - SLP;
  - MLP con strati nascosti.

## Appunti aggiuntivi
- Qui avviene il passaggio chiave da analisi matematica a modelli di apprendimento.
- Da ricordare: il gradiente dice dove la funzione cresce di piu'; per minimizzare bisogna muoversi nella direzione opposta.
- Le funzioni di attivazione introducono non linearita': senza di esse una rete profonda collasserebbe a una trasformazione lineare composta.

## Cosa sapere bene
- Update della discesa del gradiente.
- Effetto di un learning rate troppo grande o troppo piccolo.
- Struttura del neurone artificiale.
- Differenza concettuale tra SLP e MLP.
