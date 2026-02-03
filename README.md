# Analisi esplorativa dei volumi di vendita
Questo progetto presenta un’analisi esplorativa dei dati (EDA) su un dataset di transazioni di un e-commerce.
L’obiettivo è analizzare i volumi di vendita, identificando i prodotti e i clienti più rilevanti e osservando l’andamento temporale delle transazioni.
L’analisi è stata svolta a scopo di studio, utilizzando **Python**, **pandas** e **matplotlib**.
Il dataset non include informazioni sui prezzi; di conseguenza, l’analisi si concentra esclusivamente sulle quantità vendute.

## Dataset
Il dataset contiene le seguenti variabili principali:

- **customer_id**: identificativo del cliente
- **product_id**: identificativo del prodotto
- **basket_date**: data della transazione
- **basket_count**: quantità acquistata

## Analisi svolte

- Controllo qualità dei dati (valori mancanti, duplicati)
- Conversione e gestione delle variabili temporali
- Analisi dei volumi di vendita
- Identificazione dei prodotti più venduti
- Identificazione dei clienti più attivi
- Analisi dell’andamento temporale delle vendite
- Visualizzazioni tramite grafici


## Risultati principali
L’analisi ha evidenziato:

- una forte concentrazione dei volumi di vendita su un numero limitato di prodotti
- un andamento temporale delle vendite con variazioni significative nel tempo
- un numero medio di articoli per transazione molto elevato, suggerendo che il dataset rappresenti transazioni aggregate piuttosto che singoli acquisti al dettaglio.

## Possibili sviluppi futuri

Il progetto potrebbe essere esteso in diverse direzioni:

- integrazione di informazioni sui prezzi per analizzare il fatturato oltre ai volumi di vendita
- analisi più approfondita del comportamento dei clienti (frequenza di acquisto)
- sviluppo di un modello predittivo per stimare i volumi di vendita futuri
