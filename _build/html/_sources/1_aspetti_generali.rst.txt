ASPETTI GENERALI
================

L’applicativo Web sviluppato nell’ambito del progetto SIMILE per i dati di Citizen Science permette di gestire tutte le informazioni fornite dai cittadini attraverso l’App “SIMILE Monitoraggio Laghi”. L’applicativo è raggiungibile al seguente indirizzo: https://simile.como.polimi.it/SimileWebAdministrator.

La finalità principale dell’applicativo consiste nella possibilità di visualizzare, inserire, cancellare e modificare i dati messi a disposizione dagli utenti attraverso un’interfaccia di semplice utilizzo. L’applicativo Web è sincronizzato con l’App, pertanto le modifiche effettuate sulla banca dati attraverso l’interfaccia Web sono visibili anche sull’App e viceversa le informazioni fornite attraverso l’App sono consultabili ed editabili attraverso l’applicativo Web. L’interfaccia Web mette a disposizione alcune funzionalità differenziate in base al profilo dell’utente che la utilizza [1]_. Questa guida è dedicata in particolare all’interfaccia di amministrazione per utenti di tipo *editor*.

Dalla Home Page è possibile accedere a tutte le funzionalità dell’applicativo (:numref:`fig1`), sia mediante gli appositi pulsanti, sia attraverso i menu disponibili nella barra degli strumenti (barra grigia posizionata nella parte superiore dello schermo). Inoltre dalla Home Page l’utente può cambiare lingua (italiano o inglese) e reimpostare la password. Le tematiche disponibili sono le seguenti: osservazioni, eventi, avvisi, foto e ambiti; gli strumenti sono invece i seguenti: agenda, analisi e linea del tempo. Inoltre, è possibile gestire i profili degli utenti che utilizzano l’App con la funzione “Utenti App” (l’App, infatti, prevede l’autenticazione degli utenti).

I dati di ciascuna tematica sono rappresentati sia in formato tabellare (sulla parte destra dello schermo) sia tramite una rappresentazione cartografica (posizionata sul lato sinistro dello schermo). La :numref:`2` mostra le funzioni della sezione cartografica: ad esempio, c’è la possibilità di visualizzare le osservazioni singolarmente oppure raggruppate in cluster; inoltre è possibile abilitare o disabilitare la visualizzazione degli strati informativi che compongono la mappa.

.. _fig1:
.. figure:: /img/Figura1.png
    
    : Home Page dell’interfaccia di amministrazione.

.. _2:
.. figure:: /img/Figura2.png
    
    : Visualizzazione cartografica dei dati.

.. [1] Sono previsti 3 profili di utenza:

    1. viewer: ha la possibilità di consultare tutti i dati senza poter apportare alcuna modifica (modalità “sola lettura”); 

    2. editor: ha la possibilità di consultare, modificare e cancellare (solo in modalità “sicura”, spostandoli nel cestino) tutti i dati; non ha tuttavia accesso alla parte di gestione degli utenti della piattaforma Web;

    3. amministratore: ha il completo controllo della piattaforma; può creare, modificare e cancellare anche in modo definitivo tutti i dati. 

    Inoltre gestisce le utenze Web (creazione, modifica e cancellazione di utenti) e può modificare i dati “specifici del progetto” (per esempio può aggiungere nuovi laghi o cambiare le geometrie di quelli esistenti).