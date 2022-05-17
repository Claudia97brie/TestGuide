# App emag

# Introduzione

Lo scopo dell' app ***emag Warehouse Horizon*** è quello di poter tracciare la merce in entrata ed in uscita dai magazzini, che possono essere modulati a seconda delle esigenze dell’azienda. 

Attraverso il PVI, è possibile attivare o disattivare i magazzini di competenza dell’app. Questi appariranno nel menu principale della app e potranno essere selezionati direttamente dall’utente che la sta utilizzando.  

L’app fornisce la possibilità di gestire un viaggio già creato dando conferma sulle uscite e sulle entrate della merce, oppure permette la creazione di un viaggio ex novo. 

Una volta che un viaggio è chiuso attraverso la app, gli esiti vengono direttamente passati sul software TIR Horizon. 

È consigliabile effettuare dei test di funzionamento, ricezione e chiusura viaggi prima di passare all’utilizzo della app in produzione. Per fare ciò, è possibile utilizzare la versione della app per Windows. 

La seguente guida è composta da una prima parte puramente tecnica ed un seconda parte nella quale viene descritto il funzionamento della app. 
Se vi occorre esclusivamente conoscere il funzionamento della App, potete saltare il paragrafo “Operazioni tecniche preliminari”. 

N.B.: l’app funziona ESCLUSIVAMENTE su terminali Android (che abbiano preinstallato il Play Store) che sono connessi alla rete. È quindi ESTREMAMENTE consigliato utilizzare un terminale che abbia sia connessione Wi-Fi che connessione dati (attraverso una sim). I test condotti sono stati effettuati con un terminale Zebra TC21.

Operazioni tecniche preliminari
Affinchè l’applicazione funzioni correttamente è necessario svolgere delle operazioni preliminari che permettano la corretta attivazione delle funzionalità.
1)	Download APP
a.	Occorre scaricare la app su uno smartphone o terminale Android che abbia almeno la versione 6.0. L’applicazione è presente sul Play Store e vengono costantemente rilasciati aggiornamenti; pertanto, è necessario assicurarsi di avere sempre l’ultima versione disponibile. 
2)	Impostare Endpoint
Una volta scaricata la app, occorre impostare l’endpoint che permette la sincronizzazione con il database:  
I link di connessione vengono rilasciati direttamente dalla software house una volta stipulato il contratto. Il cliente deve custodire i parametri di connessione oppure salvare il QR-code. Ogni terminale o smartphone deve essere configurato singolarmente. 
3)	Abilitare Magazzini 
a.	Tornando su TIR Horizon, occorre abilitare i magazzini che devono essere di competenza della app. Per poterlo fare, aprire il modulo PVI, cliccare sul tasto “punti” e flaggare sulla colonna “IsGestitoAPP” i magazzini che si desidera gestire tramite App. Salvare premendo il tasto “Aggiorna in App”. 
  

 
N.B.: a questo punto i punti, i mezzi e gli autisti vengono sincronizzati con la app. Potrebbe volerci qualche minuto affinchè la sincronizzazione sia completata. 





4)	Abilitare Gestione App
a.	Sempre sul modulo PVI, abilitare la funzione “Gestione App Magazzino”. Premere su salva, chiudere e riaprire il PVI.  Questa funzione permette l’invio dei viaggi sulla App, pertanto è di fondamentale importanza che venga abilitata prima dell’inizio della gestione con la app Warehouse Horizon. 
 
N.B.: assicurarsi che tutti gli utenti che lavorano sul PVI abbiano chiuso e riaperto il modulo. 

5)	Inserire conferma stampando l’etichetta 
a.	Tutti gli ordini che verranno gestiti tramite APP richiedono che venga stampata l’etichetta da apporre sul bancale corrispondente. Una volta inserita la conferma e salvata, premere il tasto “Eti” e selezionare il tipo di stampa richiesta.  
N.B.: se non viene stampata l’etichetta, l’ordine non viene gestito dalla APP
6)	Movimentare viaggi dal PVI
a.	A questo punto è possibile creare un viaggio dal PVI. Si può utilizzare l’abbinamento standard, oppure la modalità assegna viaggi. 
b.	Una volta creato un viaggio di competenza del magazzino abilitato, la App riceverà le informazioni dal PVI. 






Utilizzo della APP Warehouse Horizon
1)	Una volta aperta la app, occorre effettuare il login con le credenziali che sono state fornite dalla software house. 
 

2)	Fatto il login, selezionare il magazzino che si vuole gestire 
 
3)	A questo punto selezionare la modalità di utilizzo:
a.	Scansione – permette di scansionare i barcode di viaggi già creati attraverso il PVI
b.	Creazione – permette di creare un nuovo viaggio direttamente dalla app
 

Modalità Scansione
La funzione “Scansione” viene utilizzata per scansionare in entrata e in uscita i bancali in transito presso il magazzino selezionato. 
 
Che sia in modalità “entrata” o in modalità “uscita”, i viaggi vengono visualizzati come lista e possono essere identificati tramite il numero del viaggio e la targa corrispondente. 
 
Premendo sul viaggio da evadere, vengono visualizzati i bancali che lo compongono e che quindi devono essere scansionati. 
 
Per scansionare i bancali, è possibile utilizzare la “sparatura” tramite i raggi infrarossi del lettore Barcode, oppure la semplice fotocamera di uno smartphone. 
Se un barcode non è scansionabile (strappato, scolorito, ecc), è possibile esitare il bancale manualmente facendo un doppio tap sulla riga di bancale interessata e premendo su “Esita Manualmente”. 




Quando il bancale è stato scansionato, diventa di colore verde. Quando tutti i bancali sono stati scansionati, il viaggio si chiude e scompare dall’ app.  Se l’operazione è stata eseguita correttamente, gli esiti vengono inviati a TIR Horizon. 
 

Per importare gli esiti, sul PVI è necessario cliccare sul tasto “Scarica App Magazzino” 

 
 

Modalità Creazione
La funzione “Creazione” viene utilizzata per creare un nuovo viaggio direttamente da APP. In questo modo i magazzinieri possono decidere quale merce caricare sul mezzo e passare l’informazione su Tir Horizon. 
 
Una volta selezionata la modalità “Creazione”, fare tap su “Aggiungi Nuovo” per creare un nuovo viaggio. 
 

Fare tap su “Posizionati qui per scansionare” e poi sparare i bancali da caricare sul viaggio. Una volta sparata l’etichetta, fare tap su “Inserisci Prodotto” per far entrare il prodotto all’interno del viaggio. 
È possibile poi selezionare il mezzo, rimorchio, autista e destinazione della merce dai menu a tendina corrispondenti. 
Una volta terminato il viaggio, flaggare il campo “Completo” e premere sul tasto di salvataggio.
In questo modo il viaggio è stato creato e TIR Horizon potrà ricevere l’informazione attraverso il PVI. 

N.B.: se non viene premuto il tasto salva, i bancali risulteranno non sparati.








Ricezione Viaggio da APP
Per fare in modo che il viaggio appena creato tramite la app venga importato sul PVI, occorre recarsi sul pulsante “Assegna Viaggi”, premere sul menu a tendina “Pianifica” e cliccare su “Ricevi Creazioni da App”.
 

In questo modo verrà creato un box con le spedizioni selezionate dal magazzino. Questo box è editabile e può essere modificato a seconda delle esigenze (cambio targa/autista; rimozione o aggiunta ordine; cambio data). 
Premendo sul tasto “Abbina”, il viaggio viene creato e può essere stampato il borderau. 


