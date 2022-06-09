# GESTIONE FUEL SURCHARGE 

# INTRODUZIONE

Il Fuel surcharge (supplemento carburante) viene calcolato con riferimento al prezzo medio mensile del gasolio, rilevato ufficialmente e pubblicato dal Ministero dello Sviluppo Economico.

Si tratta di un indice di riprezzamento che viene utilizzato dalle aziende di trasporti per ammortizzare un eventuale oscillazione del prezzo del carburante. 
Prendendo a riferimento il valore del prezzo medio del gasolio da autotrazione del mese precedente , pubblicato dal Ministero dello sviluppo Economico e rintracciabile sul suo sito web, il sopradetto adeguamento tariffario automatico viene applicato in funzione della percentuale di incidenza e del prezzo di riferimento del gasolio pattuiti ed entrambi riportati sugli accordi tariffari siglati.

Pertanto ogni mese (in genere intorno al 13/14 del mese), l’azienda effettua un ricalcolo della % del fuel e la applica su tutti i listini. 

**È stato sviluppato un sistema che automatizza la gestione del fuel nei servizi accessori e permette un ricalcolo su tutto il periodo di riferimento richiesto.**

# INSERIMENTO FUEL
Per poter gestire il fuel, la prima operazione necessaria è quella di recarsi nel modulo dei servizi accessori.

Dal menu a tendina “Predefiniti”, scegliere la voce ***Percentuale Fuel*** e aggiungerla cliccando sulla freccetta nera.

N.B.: se si utilizza l’inserimento manuale della voce, è fondamentale che in “Classe” venga impostata la voce SACFUE

![percentuale fuel](https://user-images.githubusercontent.com/105659714/172847727-f22448e8-b65b-467e-bfac-ebf75c8c0d53.png)

**Essendo il fuel applicato in % sul nolo, occorre impostare come Tipo = PERC e flaggare il campo “automatico”. Inserire poi l’importo assegnato al fuel.**

![fue](https://user-images.githubusercontent.com/105659714/172847948-06a7baf1-6da5-4b7f-8c94-b8e431a3af28.png)

A questo punto, ogni volta che viene inserita una nuova conferma, al prezzo salvato verrà applicata una % di maggiorazione con la descrizione “Percentuale Fuel”.

# RICALCOLO FUEL

Dato che ogni mese il fuel può variare, è stata inserita una funzione che permette di modificare l’importo fuel su tutti i clienti che hanno attivo il servizio.

Aprendo il modulo Listini (se almeno un cliente ha attiva la funzione Fuel), appare un campo “PercentualeFuel”. Facendo click su questa voce, è possibile definire il valore % che verrà impostato su tutti i clienti. 

![cambio perc](https://user-images.githubusercontent.com/105659714/172848254-77391c12-601e-4adb-a0bf-20855c48cd87.png)

Una volta definita la percentuale fuel del mese, è possibile procedere con il ricalcolo dei prezzi. 

Aprendo il modulo Conferme, premere sul tasto RP. 
È possibile definire un periodo a cui applicare il riprezzamento Fuel. 

**N.B.: Lasciando vuoto il campo cliente, il riprezzamento verrà effettuato su tutti i clienti che hanno il Fuel.**

![proced](https://user-images.githubusercontent.com/105659714/172848584-6a05daf0-05a5-4d1f-bd4f-210fd767001c.png)

Una volta definiti i parametri, premere sul tasto “Gasolio” per procedere al riprezzamento. 


