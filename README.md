# Rilevamento-Login-AI

Questo progetto ha l'obiettivo di simulare un semplice sistema di rilevamento accessi sospetti utilizzando tecniche di analisi dati e machine learning. L'idea è quella di applicare un modello di classificazione (Random Forest) per distinguere i tentativi di login legittimi da quelli potenzialmente sospetti, basandosi principalmente sul numero di fallimenti consecutivi da parte di un indirizzo IP.

## Descrizione

Lo script crea un dataset simulato contenente timestamp, indirizzi IP, ID utente e stato del login (riuscito o fallito). Viene calcolato il numero cumulativo di tentativi falliti per ogni IP, e vengono identificati i tentativi sospetti superata una certa soglia. Infine, viene addestrato un modello di machine learning per prevedere la probabilità di successo di un login sulla base del comportamento osservato.

## Obiettivi principali

- Simulare un flusso di log di accessi
- Analizzare i tentativi falliti per IP
- Evidenziare accessi sospetti
- Allenare un modello Random Forest per la classificazione
- Calcolare l’accuratezza del modello

## Tecnologie utilizzate

- Python
- pandas
- matplotlib
- scikit-learn

## Note

Questo progetto è a scopo dimostrativo e non è pensato per essere utilizzato in ambienti di produzione. Attualmente non è collegato a file di log reali, ma il codice può essere facilmente esteso per leggere da file `.log`, `.csv`, o database contenenti eventi di autenticazione.

## Estensioni possibili

- Connessione a log reali di sistema o web server
- Alert automatici in presenza di attività sospette
- Dashboard interattiva per il monitoraggio in tempo reale
- Test in ambienti simulati o piattaforme come TryHackMe o Hack The Box

## Autore

*DaenAIHax*
