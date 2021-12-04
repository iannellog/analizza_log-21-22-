# analizza_log[21-22]
# Progetto per estrarre descrittori degli utenti di e-learning

Scrivere un programma Python che legge una lista di log anonimizzati da un file. 

Ciascun elemento della lista di log è costituito dalle seguenti otto informazioni:

- Data/Ora
- Identificativo unico dell’utente
- Contesto dell’evento
- Componente
- Evento
- Descrizione
- Origine 
- Indirizzo IP

L'obiettivo è quello di calcolare per ogni utente un vettore di feature e salvare i dati sia in un foglio excel, sia in formato json

Possibili feature per ogni utente

- numero totale di eventi
- quante volte si è verificato ciascun evento 
- data primo evento
- data ultimo evento
- numero di giorni tra il primo e l'ultimo evento
- media e deviazione standard del numero eventi in una settimana (da lunedi' a domenica)
- altre features a piacere

