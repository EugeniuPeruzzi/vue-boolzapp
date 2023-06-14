PROBLEMA: 

```

Ricreare Whatsapp in maniera molto 'junior'

Milestone 1
●   Replica della grafica con la possibilità di avere messaggi scritti dall’utente 
    (verdi) e dall’interlocutore (bianco) assegnando due classi CSS diverse
●	Visualizzazione dinamica della lista contatti: tramite la direttiva v-for, 
    visualizzare nome e immagine di ogni contatto

Milestone 2
●	Visualizzazione dinamica dei messaggi: tramite la direttiva v-for, 
    visualizzare tutti i messaggi relativi al contatto attivo all’interno del pannello della conversazione
●	Click sul contatto mostra la conversazione del contatto cliccato


```

SOLUZIONE: 

```
Milestone 1
1. Creo il file HTML
2. Creo il layout necessario per dare una certa 'impronta'
3. Crelo l'array di oggetti
    3.1 Ciclo l'array per poter visualizzare gli utenti a schermo.

Milestone 2

1. Visualizzazione dinamica dei messaggi:
    1.2 Utilizzare la direttiva v-for per iterare sulla lista dei messaggi del contatto attivo.
    1.3 Mostra ogni messaggio all'interno del pannello della conversazione.

2. Click sul contatto per mostrare la conversazione:
    2.1 Aggiungi un gestore di eventi al contatto.
    2.2 Quando viene cliccato un contatto, impostare il contatto attivo.
    2.3 La conversazione del contatto attivo verrà visualizzata nel pannello della conversazione.
```
