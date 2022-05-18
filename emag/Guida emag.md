# App emag

# Introduzione

Lo scopo dell' app ***emag Warehouse Horizon*** è quello di poter tracciare la merce in entrata ed in uscita dai magazzini, che possono essere modulati a seconda delle esigenze dell’azienda. 

Attraverso il PVI, è possibile attivare o disattivare i magazzini di competenza dell’app. Questi appariranno nel menu principale della app e potranno essere selezionati direttamente dall’utente che la sta utilizzando.  

L’app fornisce la possibilità di gestire un viaggio già creato dando conferma sulle uscite e sulle entrate della merce, oppure permette la creazione di un viaggio ex novo. 

Una volta che un viaggio è chiuso attraverso la app, gli esiti vengono direttamente passati sul software TIR Horizon. 

È consigliabile effettuare dei test di funzionamento, ricezione e chiusura viaggi prima di passare all’utilizzo della app in produzione. Per fare ciò, è possibile utilizzare la versione della app per Windows. 

La seguente guida è composta da una prima parte puramente tecnica ed un seconda parte nella quale viene descritto il funzionamento della app. 
***Se vi occorre esclusivamente conoscere il funzionamento della App, potete saltare il paragrafo “Operazioni tecniche preliminari”.*** 

***N.B.: l’app funziona ESCLUSIVAMENTE su terminali Android (che abbiano preinstallato il Play Store) che sono connessi alla rete.***  È quindi ESTREMAMENTE consigliato utilizzare un terminale che abbia sia connessione Wi-Fi che connessione dati (attraverso una sim). I test condotti sono stati effettuati con un terminale Zebra TC21.

# Operazioni tecniche preliminari

Affinchè l’applicazione funzioni correttamente è necessario svolgere delle operazioni preliminari che permettano la corretta attivazione delle funzionalità.

**1)	Download APP**

a.	Occorre scaricare la app su uno smartphone o terminale Android che abbia almeno la versione 6.0. L’applicazione è presente sul Play Store e vengono costantemente rilasciati aggiornamenti; pertanto, è necessario assicurarsi di avere sempre l’ultima versione disponibile. 

**2)	Impostare Endpoint**

Una volta scaricata la app, occorre impostare l’endpoint che permette la sincronizzazione con il database:  

![endpoint2](https://user-images.githubusercontent.com/105659714/168862217-31b6c546-6081-4a76-8866-0939c13ad5a6.png)


I link di connessione vengono rilasciati direttamente dalla software house una volta stipulato il contratto. Il cliente deve custodire i parametri di connessione oppure salvare il QR-code. Ogni terminale o smartphone deve essere configurato singolarmente. 

**3)	Abilitare Magazzini**

a.	Tornando su TIR Horizon, occorre abilitare i magazzini che devono essere di competenza della app. Per poterlo fare, aprire il modulo PVI, cliccare sul tasto “punti” e flaggare sulla colonna “IsGestitoAPP” i magazzini che si desidera gestire tramite App. Salvare premendo il tasto “Aggiorna in App”. 
  
![abilitare mag](https://user-images.githubusercontent.com/105659714/168983903-22a56dd1-67d1-47f9-ae23-3f2b38736bd6.png)
![abilitare mag2](https://user-images.githubusercontent.com/105659714/168983942-e6bd7bd6-09f0-42ab-b96a-396fac8051cc.png)

N.B.: a questo punto i punti, i mezzi e gli autisti vengono sincronizzati con la app. Potrebbe volerci qualche minuto affinchè la sincronizzazione sia completata. 


**4)	Abilitare Gestione App**

a.	Sempre sul modulo PVI, abilitare la funzione “Gestione App Magazzino”. Premere su salva, chiudere e riaprire il PVI.  Questa funzione permette l’invio dei viaggi sulla App, pertanto è di fondamentale importanza che venga abilitata prima dell’inizio della gestione con la app Warehouse Horizon. 

![abilitare gestioneapp1](https://user-images.githubusercontent.com/105659714/168985548-d7ad8b55-7cd7-4941-8abe-58cbc3db127e.png)

 
**N.B.: assicurarsi che tutti gli utenti che lavorano sul PVI abbiano chiuso e riaperto il modulo. **

**5)	Inserire conferma stampando l’etichetta  **

a.	Tutti gli ordini che verranno gestiti tramite APP richiedono che venga stampata l’etichetta da apporre sul bancale corrispondente. Una volta inserita la conferma e salvata, premere il tasto “Eti” e selezionare il tipo di stampa richiesta.  

![confermaeti](https://user-images.githubusercontent.com/105659714/168986240-0caa6d67-f827-4763-bf44-75fc6ae68d32.png)

**N.B.: se non viene stampata l’etichetta, l’ordine non viene gestito dalla APP  **

6)	Movimentare viaggi dal PVI

a.	A questo punto è possibile creare un viaggio dal PVI. Si può utilizzare l’abbinamento standard, oppure la modalità assegna viaggi.

b.	Una volta creato un viaggio di competenza del magazzino abilitato, la App riceverà le informazioni dal PVI. 



# Utilizzo della APP Warehouse Horizon

1)	Una volta aperta la app, occorre effettuare il login con le credenziali che sono state fornite dalla software house. 

![Immagine6](https://user-images.githubusercontent.com/105659714/168986534-f9aab833-86e0-4f7f-9648-e5d53faa093a.jpg)

 

2)	Fatto il login, selezionare il magazzino che si vuole gestire 

![magazzini](https://user-images.githubusercontent.com/105659714/168986659-dc495a4e-95b1-4005-9c01-7d5ee8787f54.jpg)

 
3)	A questo punto selezionare la modalità di utilizzo:

a.	Scansione – permette di scansionare i barcode di viaggi già creati attraverso il PVI

b.	Creazione – permette di creare un nuovo viaggio direttamente dalla app

![modalia](https://user-images.githubusercontent.com/105659714/168986742-6c535f1b-2977-4a82-9547-bc3d1c47019a.jpg)

 

**Modalità Scansione  **

La funzione “Scansione” viene utilizzata per scansionare in entrata e in uscita i bancali in transito presso il magazzino selezionato. 

![scansione](https://user-images.githubusercontent.com/105659714/168986948-0bfff51d-960f-4dd3-a8e0-a677d3e1ef9f.png)

 
Che sia in modalità “entrata” o in modalità “uscita”, i viaggi vengono visualizzati come lista e possono essere identificati tramite il numero del viaggio e la targa corrispondente. 

![daevadere](https://user-images.githubusercontent.com/105659714/168987128-880499d0-6ead-4033-94c9-c3378b0098fb.png)

 
Premendo sul viaggio da evadere, vengono visualizzati i bancali che lo compongono e che quindi devono essere scansionati.

![viaggio1](https://user-images.githubusercontent.com/105659714/168987191-ced69fc3-564f-4571-887f-12404217951a.png)
 
Per scansionare i bancali, è possibile utilizzare la “sparatura” tramite i raggi infrarossi del lettore Barcode, oppure la semplice fotocamera di uno smartphone. 
Se un barcode non è scansionabile (strappato, scolorito, ecc), è possibile esitare il bancale manualmente facendo un doppio tap sulla riga di bancale interessata e premendo su “Esita Manualmente”. 


Quando il bancale è stato scansionato, diventa di colore verde. Quando tutti i bancali sono stati scansionati, il viaggio si chiude e scompare dall’ app.  Se l’operazione è stata eseguita correttamente, gli esiti vengono inviati a TIR Horizon. 

![verde](https://user-images.githubusercontent.com/105659714/168987320-5cf357f3-c4b2-442d-8015-a1158933bc25.png)


Per importare gli esiti, sul PVI è necessario cliccare sul tasto “Scarica App Magazzino” 

![scaricaapp](https://user-images.githubusercontent.com/105659714/168987385-dca93d58-c1c4-4a32-a9cc-a0384e6d8f66.png) 
 

**Modalità Creazione**

La funzione “Creazione” viene utilizzata per creare un nuovo viaggio direttamente da APP. In questo modo i magazzinieri possono decidere quale merce caricare sul mezzo e passare l’informazione su Tir Horizon. 
 
Una volta selezionata la modalità “Creazione”, fare tap su “Aggiungi Nuovo” per creare un nuovo viaggio. 

![aggiunginuovo](https://user-images.githubusercontent.com/105659714/168987944-92eb5b60-5aa2-47bb-89f9-2eb8550245c5.png) 
 

Fare tap su “Posizionati qui per scansionare” e poi sparare i bancali da caricare sul viaggio. Una volta sparata l’etichetta, fare tap su “Inserisci Prodotto” per far entrare il prodotto all’interno del viaggio. 

È possibile poi selezionare il mezzo, rimorchio, autista e destinazione della merce dai menu a tendina corrispondenti. 

Una volta terminato il viaggio, flaggare il campo “Completo” e premere sul tasto di salvataggio.

In questo modo il viaggio è stato creato e TIR Horizon potrà ricevere l’informazione attraverso il PVI. 

**N.B.: se non viene premuto il tasto salva, i bancali risulteranno non sparati.**

Ricezione Viaggio da APP
Per fare in modo che il viaggio appena creato tramite la app venga importato sul PVI, occorre recarsi sul pulsante “Assegna Viaggi”, premere sul menu a tendina “Pianifica” e cliccare su “Ricevi Creazioni da App”.
 

In questo modo verrà creato un box con le spedizioni selezionate dal magazzino. Questo box è editabile e può essere modificato a seconda delle esigenze (cambio targa/autista; rimozione o aggiunta ordine; cambio data). 
Premendo sul tasto “Abbina”, il viaggio viene creato e può essere stampato il borderau. 


