TEMATICHE
=========

Vengono descritte di seguito le tematiche precedentemente indicate. Quando si entra nella sezione dell’applicativo Web dedicata ad una particolare tematica, è possibile accedere alle altre tematiche tornando alla Home Page oppure selezionando gli appositi pulsanti disposti nella parte inferiore dell’interfaccia grafica.

Osservazioni
------------

Questa tematica offre la possibilità di consultare, cancellare e modificare le osservazioni già caricate (con l’App oppure con l’applicativo Web) e inserire nuove osservazioni. Si veda a tal proposito la :numref:`fig3`. Ciascuna riga della tabella corrisponde a un’osservazione e riporta tutte le informazioni che sono state fornite dall’utente. Le osservazioni sono elencate in ordine cronologico, a partire dalla più recente fino alla meno recente. Le informazioni associate a ciascuna osservazione sono le seguenti:

    - numero progressivo dell’osservazione ed eventuale codice ID della chiamata [2]_;
    - data e ora dell’osservazione;
    - posizione, visualizzabile direttamente in mappa cliccando sull’apposito pulsante “vai alla posizione”;
    - ambito a cui si riferisce l’osservazione, declinato in base al lago (Como, Maggiore, Lugano), alla Regione (Lombardia, Piemonte, Canton Ticino) e allo Stato (Italia e Svizzera) di appartenenza;
    - una o più fotografie scattate dall’utente;
    - condizioni meteorologiche (stato del cielo, temperatura [°C] e velocità del vento [m/s]);
    - misurazioni, quali temperatura [°C], trasparenza dell’acqua [m], concentrazione di batteri [UFC/100 ml], concentrazione di ossigeno [mg/l] e pH [-];
    - ulteriori dettagli, quali presenza di alghe, fauna, schiume, rifiuti, odori, oli e scarichi;
    - altre informazioni testuali aggiuntive (note), indicate dall’utente;
    - data e ora di creazione e di eventuale aggiornamento dell’osservazione;
    - nome dell’utente (registrato tramite l’App) che ha condiviso l’osservazione;
    - stato dell’osservazione (attiva/cestinata).

Per quanto riguarda la geolocalizzazione dell’osservazione, è possibile visualizzare l’osservazione sulla mappa selezionando l’apposito simbolo in corrispondenza della colonna **Posizione**. In questo modo l’osservazione viene messa in evidenza nella rappresentazione cartografica; viceversa, selezionando l’osservazione sulla mappa, la corrispondente riga nella tabella viene evidenziata in verde.

Le osservazioni possono essere riordinate e filtrate sui vari campi attraverso i tasti freccia e i menu a tendina disponibili nelle intestazioni della tabella. Ad esempio, si possono visualizzare solo le osservazioni che si riferiscono al lago di Como e a condizioni meteorologiche di cielo sereno, selezionando **AMBITO** → *Lago di Como* e **Meteo** → *Sereno*.

Le stesse informazioni contenute in ciascuna riga possono essere visualizzate tramite la funzione **Vedi** (penultima colonna), che permette una consultazione più dettagliata dei dati di ciascuna osservazione.

.. _fig3:
.. figure:: /img/Figura3.png
    
    : Tematica Osservazioni: per ciascuna riga (osservazione) sono disponibili le informazioni fornite dall’utente; è possibile modificare o cestinare l’osservazione.

L’applicativo permette di inserire una nuova osservazione, selezionando la voce **NUOVO** (in alto, sopra la tabella). In particolare, è possibile inserire informazioni relative a tutti i parametri precedentemente indicati. L’interfaccia di inserimento è guidata e molto intuitiva, pertanto l’utente può selezionare le voci preimpostate in ciascuna sezione e aggiungere manualmente i valori delle variabili numeriche. Le informazioni e i dati inseriti tramite i vari sotto-menu vengono salvati effettivamente solo selezionando **SALVA** (e confermando tale scelta) in corrispondenza dell’ultima finestra; selezionando invece **ANNULLA** nell’ultima finestra, vengono annullate tutte le informazioni specificate con i vari sotto-menu di inserimento.

L’applicativo Web mette a disposizione alcune funzionalità molto utili in fase di inserimento di una nuova osservazione; vengono di seguito riassunte (:numref:`fig4`):

    - Sezione **Data**: è possibile gestire la data “effettiva” dell’osservazione: in fase di inserimento, l’applicativo imposta di *default* la data e l’ora di inserimento dell’osservazione; tuttavia, per l’inserimento asincrono delle osservazioni, è possibile indicare la data e l’ora cui si riferisce effettivamente l’osservazione.
    - Sezione **Posizione**: oltre al posizionamento manuale (ottenuto spostando con il *mouse* il *marker* sulla mappa) o al posizionamento di precisione (ottenuto inserendo direttamente le coordinate numeriche), è disponibile un servizio di *editing* avanzato della geolocalizzazione dell’osservazione, con possibilità di ricerca per località (città, indirizzo, ecc.) tramite l’utilizzo di un servizio di *geocoding* esterno (stradario di *OpenStreetMap*); inoltre, viene riconosciuto automaticamente l’ambito dell’osservazione in base alla posizione indicata: se la posizione cade al di fuori degli ambiti del progetto, l’ambito viene indicato come “sconosciuto” e l’osservazione non sarà visibile sull’App ma solo sull’applicativo Web.
    - Sezione **Foto**: è possibile importare una o più fotografie salvate in locale, specificandone il percorso (il campo "foto ID" viene compilato automaticamente dall’applicativo); per cambiare una foto già importata, si suggerisce di cancellarla e di importare con la stessa procedura la nuova fotografia.
    - Sezione **Meteo**: oltre all’inserimento manuale è possibile compilare automaticamente i dati meteo utilizzando un servizio esterno di pubblicazione dati meteorologici; con la funzionalità “cerca il meteo attuale”, l’applicativo si collega al server meteo e recupera i dati della posizione specificata, relativamente alla data e all’ora attuali, cioè dell’istante di inserimento dell’osservazione (non è possibile invece recuperare i dati meteo storici); cliccando sulla funzione “cerca il meteo attuale”, compare un *pop-up* di conferma per il caricamento dei dati attuali.
    - Sezione **Misure** (:numref:`5b`): è possibile importare misure multiple di temperatura, concentrazione di ossigeno e pH da file esterni con formati eterogenei (:kbd:`txt` e :kbd:`csv`) tramite una procedura guidata, nella quale l’utente può scegliere la struttura della tabella (con o senza *header*), il tipo di separatore (virgola, punto e virgola, spazio, tab, ecc.) e le colonne da considerare per i due campi “profondità” e “valore”; l’utente ha anche la possibilità di vedere l’anteprima della tabella prima di effettuare l’upload finale [3]_. Al momento la dimensione massima ammissibile per il file delle misure è pari a 3 MB (tuttavia, l’amministratore della piattaforma ha la possibilità di cambiare questa dimensione). A tal proposito, c’è la possibilità di visualizzare i grafici delle suddette variabili numeriche in funzione della profondità: una volta inserita la serie di valori, se si apre la finestra relativa ai dati dell’osservazione (funzione **Vedi**), nella sezione **MISURE** comparirà la funzione **GRAFICO**. Il grafico riporta sull’asse delle ascisse i valori della variabile in questione e sull’asse delle ordinate i valori di profondità (con possibilità di invertire gli assi cliccando sull’apposito tasto).

Tutte le osservazioni, create sia con l’App che con l’applicativo Web, possono essere modificate tramite la funzione **Edita** (ultima colonna). Attraverso questa funzione, l’utente può, ad esempio, migliorare la geolocalizzazione dell’osservazione, cancellare o ricaricare delle foto (per correggere ad esempio errori di orientamento, aggiungere nuove immagini, ecc.), modificare i dati meteorologici nel caso in cui siano errati, oppure aggiungere nuove misure o informazioni di dettaglio. È possibile modificare tutti i parametri precedentemente elencati; la stessa funzionalità permette anche di cestinare l’osservazione: è necessario in questo caso impostare **SI** nella sezione **Da eliminare** e poi cliccare **SALVA**. In alternativa, è possibile cestinare un’osservazione anche selezionando la corrispondente riga e usando la funzione **CESTINA** (in alto, sopra la tabella).

Il database è dotato di un sistema di cancellazione sicura del dato: una volta cestinata un’osservazione, è possibile comunque consultarla oppure recuperarla. Per la consultazione, è sufficiente filtrare le osservazioni selezionando **Stato → Cestinati**. Per recuperarla, è necessario utilizzare nuovamente la funzione **Edita** e reimpostare **NO** nella sezione **Da eliminare**. Solo l’amministratore della piattaforma può infatti rimuovere in modo permanente un dato.

.. _fig4:
.. figure:: /img/Figura4.png
    
    : Tematica Osservazioni: gestione della data effettiva dell’osservazione (1), ricerca della posizione tramite lo stradario OSM (2), upload di fotografie da locale (3) e ricerca automatica delle condizioni meteo attuali (4).

.. image:: /img/Figura5a.png

.. _5b:
.. figure:: /img/Figura5b.png
    
    : Importazione di misure multiple da file esterno (txt o csv): l’utente specifica il percorso del file, il tipo di separatore e le colonne corrispondenti a profondità e valore della variabile numerica. Viene anche riportato un esempio di grafico della temperatura in funzione della profondità.

Eventi
------

La stessa interfaccia grafica è disponibile per la sezione eventi. In questo caso è possibile consultare gli eventi o direttamente in tabella o nel dettaglio tramite il tasto **Vedi**, modificarli tramite il tasto **Edita** o creare un nuovo evento tramite la funzione **NUOVO** (tasto in alto, sopra la tabella). La creazione di un nuovo evento è possibile solo tramite l’applicativo Web. Come mostra la :numref:`6`, in questo caso la struttura della base di dati è simile a quella già descritta per la tematica Osservazioni. Per ciascun evento è possibile indicare: data e ora dell’evento, titolo e descrizione, posizione (geolocalizzazione, città e indirizzo, utilizzando lo stradario di *OpenStreetMap*), indirizzo e-mail di un referente (ed eventuale numero di telefono) e alcuni link utili (ad esempio ai siti Web degli eventi).

Anche gli eventi, come le osservazioni, possono essere cestinati. In questo modo è possibile tenere memoria degli eventi passati. È necessario selezionare l’evento che si vuole eliminare e selezionare **CESTINA** (in alto).

.. _6:
.. figure:: /img/Figura6.png
    
    : Tematica Eventi: per ciascuna riga (evento) sono disponibili una serie di informazioni legate all’evento, che l’utente può modificare o cestinare.

Avvisi
------

Anche per la tematica Avvisi la visualizzazione dei dati è analoga (:numref:`7`): tramite l’applicativo Web è possibile creare un nuovo avviso oppure modificare o cestinare un avviso esistente. Le informazioni associate a ciascun avviso sono analoghe a quelle già descritte per gli eventi, con la differenza che gli avvisi hanno anche una data di “scadenza”, dopo la quale non sono più visibili sull’App. Anche gli avvisi possono essere georeferenziati (ed è dunque possibile la creazione, la modifica e la cancellazione dell’eventuale posizione, utilizzando lo stradario di *OpenStreetMap*).

.. _7:
.. figure:: /img/Figura7.png
    
    : Tematica Avvisi: per ciascuna riga (avviso) sono disponibili una serie di informazioni; l’utente può modificare o cestinare ciascun avviso.

Foto
----

La sezione Foto mette a disposizione la visualizzazione, in ordine cronologico, delle fotografie caricate dagli utenti (:numref:`8`). Per ciascuna foto sono riportate la data e l’ora di caricamento e le informazioni aggiuntive specificate dall’utente (condizioni meteorologiche, presenza di rifiuti, di alghe, di fauna, ecc.). Anche in questo caso è riportata sulla sinistra una rappresentazione cartografica della posizione delle relative osservazioni.

Anche la sezione Foto rende disponibile alcune funzionalità di *editing*. Cliccando su una fotografia, si apre l’interfaccia di visualizzazione della corrispondente osservazione: nel tab **Foto** è possibile eliminare la foto tramite il tasto “elimina” che compare sotto la fotografia; nel tab **SysInfo**, il tasto **CESTINA/RIPRISTINA** presente alla voce **Da eliminare** permette invece di cestinare o ripristinare l’intera osservazione.

C’è infine la possibilità di filtrare le fotografie in funzione dello stato dell’osservazione a cui appartengono. Nella parte superiore dell’interfaccia grafica sono presenti tre pulsanti: **Attivi** (per la visualizzazione delle foto corrispondenti a osservazioni attive), **Cestinati** (per la visualizzazione delle foto corrispondenti a osservazioni cestinate) e **Tutti** (per la visualizzazione di tutte le fotografie, indipendentemente dallo stato dell’osservazione). Si noti che, anche quando si visualizzano indistintamente tutte le foto, quelle relative a osservazioni cestinate risultano comunque riconoscibili per un fondo di colore grigio (lo stesso utilizzato anche per le altre tematiche cestinate).

.. _8:
.. figure:: /img/Figura8.png
    
    : Tematica Foto: per ogni fotografia si riportano la data e l’ora di caricamento e le informazioni specificate dall’utente.

Ambiti
------

Attraverso la tematica Ambiti è possibile consultare il perimetro dei diversi ambiti in cui è stata suddivisa l’area di interesse (:numref:`9`). Si tratta di otto ambiti, divisi tra Italia e Svizzera [4]_. Per ciascun ambito sono specificati lo Stato e la Regione di appartenenza, il lago di riferimento e la data e l’ora di creazione e di aggiornamento.

.. _9:
.. figure:: /img/Figura9.png
    
    : Tematica Ambiti: per ogni ambito è indicato lo Stato, la Regione e il lago di riferimento, insieme alla data di creazione e aggiornamento.

.. [2] Quando un utente invia un’osservazione con l’App, ha la possibilità di aprire una segnalazione ufficiale – a cui viene assegnato un identificativo univoco – alle autorità competenti. L’ID viene generato automaticamente dall’App e compare direttamente nell’applicativo Web nel campo “ID Chiamata”.

.. [3] C’è comunque la possibilità di aggiungere manualmente i valori in funzione della profondità. Ad esempio, se si vuole inserire una serie di valori di temperatura, nella sezione **Misure** dell’osservazione, si seleziona **NUOVO** (oppure **EDITA**, se l’osservazione è già stata inserita) e, in corrispondenza della variabile **Temperatura**, si seleziona **NUOVO**: nella parte superiore dell’interfaccia di inserimento, si clicca sul tasto **Aggiungi** (simbolo **+**) tante volte quanti sono i valori di temperatura che si vogliono inserire, e in corrispondenza di ciascuna riga si specificano profondità e valore di temperatura.

.. [4] Nell’applicativo è già implementata una funzionalità che permette all’amministratore della piattaforma di creare un nuovo ambito. Tale funzionalità può essere utilizzata nel caso in cui si decida di ampliare gli ambiti di utilizzo dell’applicativo. L’amministratore ha anche la possibilità di editare gli ambiti già esistenti.