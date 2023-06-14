PROBLEMA:
Milestone 1
●	Replica della grafica con la possibilità di avere messaggi scritti dall’utente (verdi) e dall’interlocutore (bianco) assegnando due classi CSS diverse
●	Visualizzazione dinamica della lista contatti: tramite la direttiva v-for, visualizzare nome e immagine di ogni contatto

SOLUZIONE:
1 - Creare il markup statico;
    1.1 - Applicare due classi CSS per differenziare i messaggi ricevuti da quelli inviati;
2 - Visualizzare dinamicamente la lista contatti;
    2.1 - Creare nel data l'array di oggetti con le relative proprietà;
    2.2 - Utilizzare il v-for per mostrare a video nome e immagine dei contatti;

PROBLEMA:
Milestone 2
●	Visualizzazione dinamica dei messaggi: tramite la direttiva v-for, visualizzare tutti i messaggi relativi al contatto attivo all’interno del pannello della conversazione
●	Click sul contatto mostra la conversazione del contatto cliccato

SOLUZIONE:
1 - Creare un ciclo v-for per mostrare dinamicamente i messaggi;
    1.1 - Utilizzare il v-binding di classe con una condizione;
    1.2 - ? SE lo status è = a 'received', assegna la classe white;
    1.3 - : ALTRIMENTI assegna la classe green; 
2 - Creare un evento al click richiamando una funzione;
    2.1 - Creare la funzione;


PROBLEMA:
Milestone 3
●	Aggiunta di un messaggio: l’utente scrive un testo nella parte bassa e digitando “enter” il testo viene aggiunto al thread sopra, come messaggio verde
●	Risposta dall’interlocutore: ad ogni inserimento di un messaggio, l’utente riceverà un “ok” come risposta, che apparirà dopo 1 secondo.

SOLUZIONE:
1 - Aggiungere un v-model per attivare l'input;
2 - Aggiungere un evento keyup.enter in cui richiamo una funzione;
3 - Creare una funzione;
    3.1 - Creare un oggetto;
    3.2 - Pushare l'oggetto
    3.3 - Visualizzare nella chat il nuovo messaggio;
    3.4 - Svuotare l'input;
    3.5 - Creare un set Timeout;
    3.6 - Creare un oggetto;
    3.7 . Pushare il nuovo oggetto;
    3.8 - Visualizzare la risposta automatica;
