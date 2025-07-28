# Software-Gestione-Magazzino
First Project of the Master in Data Science by Professional.AI

Il primo progetto del master ha richiesto la costruzione di un software di gestione da riga di comando per un negozio di alimentari. Il software deve essere in grado di svolgere i seguenti compiti:
- Elencare tutti i prodotti presenti
- Registrare le vendite effettuate
- Mostrare i profitti lordi e netti
- Mostrare un menù di aiuto con tutti i comandi disponibili

Per raggiungere questi obiettivi ho definito una classe Wms() con i seguenti attributi:
- Inventory
- Gross
- Net
e i seguenti metodi:
- Select new operation
- Add product
- List products
- Sell product
- Profits
- Delete product
- Check pos value
- Help
- Close
più una funzione di caricamento dell'inventario (Load inventory) al di fuori della classe Wms().
I diversi input richiesti nell'interazione con l'utente sono stati gestiti attraverso logico Try/Assert/Except, per poter presentare eventuali messaggi di errore senza causare la chiusura dell'operatività del software.
All'interno del codice è possibile trovare la spiegazione di tutti i metodi.
