
### Repo
**spring-la-mia-pizzeria-crud**

### Package
-ragionevole-

### Todo
Dobbiamo realizzare un’applicazione web che ci aiuti a gestire la nostra pizzeria. Abbiamo bisogno di creare la prima pagina (index) dove mostriamo tutte le pizze che prepariamo.

Una pizza e' caratterizzata da:
- nome : string
- descrizione : string : longtext
- prezzo : int

Per l'entita' creare la tripletta di *Entity*, *Repository* e *Service*.

Aggiungere poi un controller di nome *PizzaController* che implementi il metodo index che restituisce una view per mostrare l’elenco delle pizze caricate dal database (possiamo creare una tabella con bootstrap o altro).

Nel caso in cui l'elenco delle pizze sia vuoto mostrare un messaggio che indichi all’utente che non ci sono pizze presenti nella nostra applicazione al momento.

Generare inoltre le rotte necessarie al completamento della *CRUD* (creazione, eliminazione e aggiornamento di una pizza).

Ove possibile sfruttare i *fragment* per il riutilizzo del codice `HTML`


### Todo - Pt.2
All'interno dello stesso progetto dell'esercizio precedente, aggiungere la seguente entita' e svolgere il necessario per attivare la CRUD completa:

#### Drink
- name : String : not null : unique
- description : String : log : nullable
- price : int : not null : > 0

Andranno quindi creati i 3 file per l'entita' (Entity, Repository e Service) e poi create tutte le rotte nessarie in un nuovo controller di nome *DrinkController* basato sulla rotta `/drink` (`@RequestMapping` del *controller*).
