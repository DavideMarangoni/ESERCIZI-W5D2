Questo progetto prevedeva il creare un database di un ambiente a noi familiare. Ho pensato di strutturare quindi un database per una pizzeria generica.
Partendo da 0 dovevo arrivare fino ad un database strutturato con tabelle vere e proprie popolate di dati.
Il primo passo è stato quello di modellare uno schema E/R che fosse quanto più possibile normalizzato e coerente con i dati.
Il passo successivo è stato quello di tradurre tale modello E/R in una modellazione logica nella quale le prime tabelle iniziavano a prendere forma.
Il passo successivo è stato utilizzare il linguaggio SQL per creare e popolare queste tabelle. ho utilizzato diversi modi di scrittura per creare un vincolo tra le primary key
di una tabella e le foreign key di un'altra. 
Si può usare il comando CONSTRAINT per essere in grado anche di dare un nome al vincolo. Ad esempio 
CONSTRAINT PK_Pizza PRIMARY KEY Pizza (PizzaID).
Il file Excel racchiude il risultato finale.
