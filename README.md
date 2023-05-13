# VLSM
Creare un repo GitHub di nome VLSM e compilare il relativo README.md prevedendo:

- una descrizione del problema della variable length sm
- una descrizione della soluzione all'esercizio
- le immagini Packet Tracer della soluzione

- Il problema che ci si pone davanti e quello di suddividere la rete in modo da dare la giusta quantità di indirizzi ip in base alla richiesta della sottorete perchè in questo caso, simile a come potrebbe essere nella realtà, ogni sottorete ha un propria richiesta. Nel nostro caso l'esercizio ci dava delle piccole sottoreti, dove la più grande è quella di 50, quindi utilizziamo una classe C, cioè dove la nostra SubnetMask è 2555.255.255.0, quindi in totatle abbiamo a disposizione 254 indirizzi ip (256-2 perchè uno è Host_ID e laltro e il Broadcast_ID della rete)

- L'eserzizio si risolve nel seguente modo:

1 Prima di tutto bisogna fare la tabella con tutti i dati necessari per poterla rappresentare graficamente con le seguenti notazioni:

![Tabella VLSM](https://user-images.githubusercontent.com/120628724/235103733-292e6c56-0c8c-44fb-b71d-79b30ed0cbc7.PNG)

 Nel mio caso nella colonna del # ho messo in ordine decrescente le varie sottoreti
 
 Nella colonna "Group Size" ho assegnato alla sottorete un numero di Indirizzi Ip
 
 Nella colonna "HOST ID" ho assegnato il primo indirizzo della sottorete come indentidicativo del dispositivo
 
 Nella colonna "BROADCAST ID" ho assegnato l'ultimo indirizzo ip della sottorete che serve per mandare un messaggio a tutti i dipsositivi compresi nella sottorete
 
 Nella colonna "CIDR" (Classless Inter-Domain Routing) ho dato una quantità definita di indirizzi ip per quanto ne avesse bisogno la sottorete
 
 Nella colonna "GATEWAY" ho assegnato il penultimo indirizzo ip della nostra sottorete e che ci serve appunto per farci uscire dalla nostra rete attuale
 
 Nella colonna "RANGE HOST" ho semplicemnete inserito il numero di ip che possono essere utilizatti dai dispositivi che utilizzeremo


