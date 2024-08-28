# GiocoPython
Questo progetto di Stefano Benigni implementa un gioco utilizzando Processing.py, una
modalità di Python per il framework di sviluppo creativo Processing.
Il gioco è basato su uno scenario classico di sopravvivenza spaziale, dove il giocatore
controlla un'astronave per difendersi dai nemici che avanzano.
L'obiettivo del gioco è eliminare quanti più nemici possibile usando dei proiettili, evitando
collisioni che causerebbero la sconfitta del giocatore.
# Componenti Principali
1. Astronave del Giocatore: L'astronave è controllata dal giocatore tramite il
movimento del mouse. Può sparare proiettili per eliminare i nemici. Se un nemico
collide con l'astronave del giocatore, la partita finisce.
2. Nemici: I nemici appaiono nella parte superiore dello schermo e si muovono verso il
basso. Ogni nemico ha una certa quantità di punti che contribuiscono al punteggio
totale del giocatore quando viene eliminato.
3. Proiettili: Il giocatore può sparare proiettili per distruggere i nemici. Ogni volta che
un proiettile colpisce un nemico, entrambi vengono rimossi dalla schermata e il
punteggio del giocatore aumenta.
4. Livelli di Gioco: Ogni volta che tutti i nemici vengono eliminati, un nuovo livello
inizia con nemici più veloci e più difficili da eliminare, aumentando così la sfida.
5. Punteggio e Livello: Il punteggio del giocatore viene mostrato in tempo reale e
aumenta con l'eliminazione dei nemici. Il livello corrente viene anch'esso visualizzato
e aumenta quando il giocatore elimina tutti i nemici presenti.
# Controlli di Gioco
• Movimento: Il giocatore muove l'astronave utilizzando il mouse.
• Sparare: I proiettili vengono creati cliccando con il mouse.
• Ricominciare il Gioco: Se il giocatore perde, può premere il tasto "R" per
ricominciare una nuova partita.
# Altro:
• Gestione delle Collisioni: Il gioco rileva le collisioni tra i proiettili e i nemici, e tra i
nemici e l'astronave del giocatore, utilizzando il controllo delle sovrapposizioni dei
rettangoli. Se c'è una collisione tra un nemico e l'astronave, il gioco finisce. Se c'è una
collisione tra un proiettile e un nemico, entrambi vengono rimossi e il punteggio
aumenta.
• Reset del Gioco: Quando il giocatore perde, può premere il tasto "R" per resettare lo
stato del gioco, svuotare le liste dei nemici e dei proiettili, ricreare i nemici e riportare
il punteggio a zero così anche il livello.
• Incremento del Livello: Quando tutti i nemici sono stati eliminati, il livello aumenta
e vengono generati nuovi nemici con velocità maggiore, aumentando così la difficoltà.

![4](https://github.com/user-attachments/assets/13c0bb44-8c91-48ad-b6ab-a4c8934c4782)
![1](https://github.com/user-attachments/assets/8006e7cc-9e09-4518-9f72-828a3c6bf740)
![2](https://github.com/user-attachments/assets/bffa0c4f-04ba-43c3-84fa-81281de64750)
![3](https://github.com/user-attachments/assets/096efed5-061d-40c2-b756-51d1ca537403)
![Uploading 3.jpeg…]()
