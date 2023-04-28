# VLSM
Creare un repo GitHub di nome VLSM e compilare il relativo README.md prevedendo:

- una descrizione del problema della variable length sm
- una descrizione della soluzione all'esercizio
- le immagini Packet Tracer della soluzione

- Il problema che ci si pone davanti e quello di suddividere la rete in modo da dare la giusta quantità di indirizzi ip in base alla richiesta della sottorete perchè in questo caso, simile a come potrebbe essere nella realtà, ogni sottorete ha un propria richiesta. Nel nostro caso l'esercizio ci dava delle piccole sottoreti, dove la più grande è quella di 50, quindi utilizziamo una classe C, cioè dove la nostra SubnetMask è 2555.255.255.0, quindi in totatle abbiamo a disposizione 254 indirizzi ip (256-2 perchè uno è Host_ID e laltro e il Broadcast_ID della rete)

- L'eserzizio si risolve nel seguente modo:

1 Prima di tutto bisogna fare la tabella con tutti i dati necessari per poterla rappresentare graficamente con le seguenti notazioni:

![1](https://user-images.githubusercontent.com/120628724/235115210-0ed6c4b4-5bf0-42ef-a3de-afbde4e2256c.PNG)

2 Nel mio caso nella colonna del # ho messo in ordine decrescente le varie sottoreti

![2](https://user-images.githubusercontent.com/120628724/235115424-7f39e177-ea01-4a33-85f5-883e200a6e0d.PNG)

3 Nella colonna "Group Size" ho assegnato alla sottorete un 

![Tabella VLSM](https://user-images.githubusercontent.com/120628724/235103733-292e6c56-0c8c-44fb-b71d-79b30ed0cbc7.PNG)
