Email dei componenti:
federico.mariani3@studio.unibo.it
lorenzo.ferri21@studio.unibo.it
marco.mondardini2@studio.unibo.it
alan.barzanti@studio.unibo.it


Il gruppo si propone di realizzare una reinterpretazione del celebre gioco arcade Frogger del 1981. 
Il gameplay si basa sul raggiungimento dell’estremità opposta della mappa, disposta in verticale, partendo dalla parte inferiore per giungere alla superiore. Per rendere l’esperienza più dinamica rispetto all’originale, abbiamo deciso di far seguire i livelli in modo continuo, una volta completato ciascun percorso. L’obiettivo del gioco è progredire il più lontano possibile, accumulando punti grazie a dei bonus, evitando ostacoli e evitando di finire in acqua.


Funzionalità minimali ritenute obbligatorie:
* Interfaccia utente: menù principale, menù di pausa e menù con punteggio finale
* Creazione randomica, possibilmente infinita, di livelli
* Creazione di ostacoli mediante utilizzo di thread
* Creazione di vari PowerUp quali recupero vita, elementi di punteggio extra ecc.
* Sistema di punteggio 
* Livello di difficoltà progressivo


Funzionalità opzionali:
* Salvataggio top 5 punteggi con nome giocatore
* Creazione di ulteriori ostacoli
* Aggiunta di musica e effetti sonori




"Challenge" principali:
* Rispetto del pattern architetturale MVC
* Gestione tramite thread degli ostacoli
* Gestione degli input
 
Suddivisione di massima del lavoro (con parte significativa del model a ognuno):
* Barzanti:
* Ferri:
* Mariani:
* Mondardini:
Creazione livelli: sistema livelli randomici, sistema di difficoltà progressiva
Creazione giocatore : vite, movimento verso le quattro direzioni, collisione, gestione punteggio
Creazione ostacoli e terreni: gestione movimento ostacoli, gestione corsie per il punteggio
Sistema di PowerUp: creazione di vari PowerUp con i relativi effetti, creazione menù
