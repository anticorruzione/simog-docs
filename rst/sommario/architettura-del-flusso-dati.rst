Architettura del flusso dati 
=============================

L’attività di rilevazione dei dati relativi agli appalti pubblici di
lavori, servizi e forniture si sviluppa attraverso un insieme di eventi
significativi. Per ogni evento il sistema prevede una o più schede di
comunicazione in base alle caratteristiche del contratto. Gli eventi e
le relative schede gestite dal sistema sono:

-  `E01 - Fase di creazione della gara e acquisizione codici
   CIG <#e01---fase-di-creazione-della-gara-e-acquisizione-codici-cig>`__

   -  
   -  S01 – Creazione gara\ \ `S02 – Creazione
      lotto <#s02-creazione-lotto>`__

   -  
   -  `S02a – Integrazione dati CUP <\l>`__\ \ \ `S03 – Cancellazione
      gara <#s03-cancellazione-gara>`__

   -  `S04 – Cancellazione lotto <#s04-cancellazione-lotto>`__

   -  `S05 – Acquisizione requisiti
      gara/lotto <#s05-acquisizione-requisiti-garalotto>`__

   -  `S06 – Perfezionamento e pubblicazione
      gara <#s06-perfezionamento-e-pubblicazione-gara>`__

   -  `S06.1 Gestione elenco invitati <#_E02_-_Fase>`__

-  `E02 - Fase di aggiudicazione o definizione di procedura negoziata
   (rif. 4) <#_E02_-_Fase>`__

   -  `S07 – Dati comuni <#s07-dati-comuni>`__

   -  `S08 – Aggiudicazione <#s08-aggiudicazione-sopra-soglia>`__

   -  S08.1 – Pubblicazione Esito di Gara

   -  `S09 – Adesione accordo quadro
      convenzione <#s08.1-pubblicazione-esiti-di-gara>`__

   -  `S10 – Aggiudicazione Contratti
      Esclusi <#s10-aggiudicazione-contratti-esclusi>`__\ \ \ `E03 -Fase
      iniziale di esecuzione del contratto (rif.
      13) <#e03---fase-iniziale-di-esecuzione-del-contratto-rif.-13>`__

   -  `S11 –Inizio Lavori <#s11-inizio-lavori>`__

   -  `S12 – Stipula accordo quadro
      convenzione <#s12-stipula-accordo-quadro-convenzione>`__

-  `E04 - Fase di esecuzione ed avanzamento del contratto (rif.
   14) <#e04---fase-di-esecuzione-ed-avanzamento-del-contratto-rif.-14>`__

   -  `S13 – Stato avanzamento <#s13-stato-avanzamento>`__

-  `E05 - Fase di conclusione del contratto (rif.
   15) <#e05---fase-di-conclusione-del-contratto-rif.-15>`__

   -  `S14 - conclusione <#s14-conclusione>`__

-  `E06 - Fase di collaudo (rif.
   16) <#e06---fase-di-collaudo-rif.-16>`__

   -  `S15 - Collaudo <#s15-collaudo>`__

-  `E07 - Accordi bonari (rif. 17.3) <#e07-accordi-bonari-rif.-17.3>`__

   -  `S16 - Accordi Bonari <#s16---accordi-bonari>`__

-  `E08 – Sospensione (rif. 17.1) <#e08-sospensione-rif.-17.1>`__

   -  `S17 – Sospensione <#s17---sospensione>`__

-  

   -  `E09 - Varianti (rif. 17.2) <\l>`__\ \ \ `S18 -
      Variante <#s18---variante>`__

-  `E10 - Subappalto (rif. 17.4) <#e10-subappalto-rif.-17.4>`__

   -  `S19 – Subappalto <#s19---subappalto>`__

-  `E11 – Istanza di
   recesso <#e11-istanza-di-recesso-solo-per-lavori>`__

   -  `S20 – Istanza di recesso <#s20---istanza-di-recesso>`__

-  `E12 - Variazione dei soggetti a vario titolo coinvolti nel corso del
   ciclo di vita dell’opera, ivi compreso
   l’aggiudicatario <#e12---variazione-dei-soggetti-a-vario-titolo-coinvolti-nel-corso-del-ciclo-di-vita-dellopera-ivi-compreso-laggiudicatario>`__

   -  `S21 – Variazione Anagrafica Soggetti
      Coinvolti <#s21-variazione-anagrafica-soggetti-coinvolti>`__

-  E13 - Variazione della Stazione Appaltante in corso d’opera

   7. .. rubric:: 
         Flusso di creazione della gara e di acquisizione del CIG
         :name: flusso-di-creazione-della-gara-e-di-acquisizione-del-cig

      Il diagramma di Figura 1 descrive l’evento E01 relativo al flusso
      di creazione della gara e acquisizione dei codici CIG. In seguito
      all’introduzione del sistema AVCpass è stata inserita una nuova
      scheda che consente la gestione dei requisiti che possono essere
      associati all’intera gara o a uno o più lotti che la compongono.
      Inoltre con l’introduzione del sistema di pubblicazione dei bandi
      di gara ora integrato nel portale trasparenza è stata definita una
      scheda di perfezionamento della gara e pubblicazione del relativo
      bando ed il disciplinare di gara in formato pdf.

      La pubblicazione del bando e l’avviso di aggiudicazione dovranno
      essere eseguite obbligatoriamente solo in caso di gare relative a
      contratti di lavori con importo superiore o uguale a 500.000,00
      euro e aventi come scelta del contraente uno dei seguenti valori:

      • procedura aperta,

      • procedura ristretta,

      • dialogo competitivo,

      • procedura negoziata previa pubblicazione,

      • procedura ristretta derivante da avvisi con cui si indice una
      gara.

      A seguito del comunicato del Presidente del 8/5/2014 il sistema è
      stato integrato con la scheda S02a “Integra dati CUP” utilizzabile
      durante l’intero ciclo di vita dell’appalto e attivabile dal
      dettaglio del lotto. L’inserimento dei codici CUP è obbligatorio
      per le gare che rientrano nelle fattispecie indicate dal suddetto
      comunicato.

      Espletata la fase di perfezionamento e pubblicazione il sistema in
      base ai dati acquisiti richiede l’inserimento delle schede
      successive secondo la tabella di seguito riportata.

+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| * |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| * |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| S |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| E |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| T |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| T |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| O |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| R |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| E |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| O |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| R |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| D |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| I |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| N |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| A |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| R |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| I |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| O |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| * |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| * |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+===+===+===+===+===+===+===+===+===+===+===+===+===+===+===+
|   | * | * | * | * | * | * | * | * | * | * | * | * | * | * |
|   | * | * | * | * | * | * | * | * | * | * | * | * | * | * |
|   | S | S | S | S | S | S | S | S | S | S | S | S | S | S |
|   | 0 | 0 | 0 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 2 |
|   | 7 | 8 | 9 | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 |
|   | * | * | * | * | * | * | * | * | * | * | * | * | * | * |
|   | * | * | * | * | * | * | * | * | * | * | * | * | * | * |
|   |   |   |   |   |   |   | \ |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   | [ |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   | 4 |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   | ] |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   | _ |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| S | X | X |   |   | X |   | X | X | X | X | X | X | X | X |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| p |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| g |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| E | X |   |   | X |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| u |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| A | X | X |   |   |   | X |   | X |   |   |   |   | X |   |
| c |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   | [ |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   | 5 |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   | ] |   |   |   |   |   |   |
| d |   |   |   |   |   |   |   | _ |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| q |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| u |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| d |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| p |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| g |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| A | X |   |   | X |   |   |   |   |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| d |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| q |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| u |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| d |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| u |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| p |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| g |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| A | X | X |   |   | X |   | X | X | X | X | X | X | X | X |
| d |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| n |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| n |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| S |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| C |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| C |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| p |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| g |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| A | X |   |   | X |   |   |   |   |   |   |   |   |   |   |
| d |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| n |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| n |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| S |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| C |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| C |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| u |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| p |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| g |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| A | X |   | X |   | X |   | X | X | X | X | X | X | X | X |
| d |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| n |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| n |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| z |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| S |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| C |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| C |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| p |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| g |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| A | X |   | X |   |   |   |   |   |   |   |   |   |   |   |
| d |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| n |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| n |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| z |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| S |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| C |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| C |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| u |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| p |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| g |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| * |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| * |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| S |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| E |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| T |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| T |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| O |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| R |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| E |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| S |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| P |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| E |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| C |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| I |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| A |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| L |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| E |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| * |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| * |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
|   | * | * | * | * | * | * | * | * | * | * | * | * | * | * |
|   | * | * | * | * | * | * | * | * | * | * | * | * | * | * |
|   | S | S | S | S | S | S | S | S | S | S | S | S | S | S |
|   | 0 | 0 | 0 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 2 |
|   | 7 | 8 | 9 | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 |
|   | * | * | * | * | * | * | \ | * | * | * | * | * | * | * |
|   | * | * | * | * | * | * |   | * | * | * | * | * | * | * |
|   |   |   |   |   |   |   | 1 |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   | * |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   | * |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| S | X | X |   |   |   |   |   | X |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| p |   |   |   |   |   |   |   | [ |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   | 6 |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   | ] |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   | _ |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| g |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| E | X |   |   | X |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| u |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| A | X | X |   |   |   |   |   | X |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   | \ |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   | : |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   | s |   |   |   |   |   |   |
| d |   |   |   |   |   |   |   | u |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   | p |   |   |   |   |   |   |
| q |   |   |   |   |   |   |   | : |   |   |   |   |   |   |
| u |   |   |   |   |   |   |   | ` |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   | 2 |   |   |   |   |   |   |
| d |   |   |   |   |   |   |   | ` |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| p |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| g |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| A | X |   |   | X |   |   |   |   |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| d |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| q |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| u |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| d |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| u |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| p |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| g |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| A | X | X |   |   |   |   |   | X |   |   |   |   |   |   |
| d |   |   |   |   |   |   |   | \ |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   | : |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   | s |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   | u |   |   |   |   |   |   |
| n |   |   |   |   |   |   |   | p |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   | : |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   | ` |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   | 3 |   |   |   |   |   |   |
| n |   |   |   |   |   |   |   | ` |   |   |   |   |   |   |
| S |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| C |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| C |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| p |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| g |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| A | X |   |   | X |   |   |   |   |   |   |   |   |   |   |
| d |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| n |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| n |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| S |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| C |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| C |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| u |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| p |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| g |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| A | X |   | X |   |   |   |   | X |   |   |   |   |   |   |
| d |   |   |   |   |   |   |   | \ |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   | : |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   | s |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   | u |   |   |   |   |   |   |
| n |   |   |   |   |   |   |   | p |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   | : |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   | ` |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   | 3 |   |   |   |   |   |   |
| n |   |   |   |   |   |   |   | ` |   |   |   |   |   |   |
| z |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| S |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| C |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| C |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| p |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| g |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+
| A | X |   | X |   |   |   |   |   |   |   |   |   |   |   |
| d |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| n |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| n |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| z |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| S |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| C |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| C |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| e |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| c |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| u |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| p |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| r |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| s |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| o |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| g |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| l |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| i |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| a |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+---+---+---+

.. [1]
    La scheda di avanzamento deve essere compilata solo per i lotti di
   importo superiore a 500.000 euro

.. [2]
    La scheda di conclusione relativa all’accordo quadro è da definire

.. [3]
    La scheda di conclusione, non obbligatoria per i settori speciali,
   viene compilata In caso di interruzione anticipata dell’esecuzione
   del contratto

.. [4]
    La scheda di avanzamento deve essere compilata solo per i lotti di
   importo superiore a 500.000 euro

.. [5]
    La scheda di conclusione relativa all’accordo quadro è da definire

.. [6]
    La scheda di conclusione, non obbligatoria per i settori speciali,
   viene compilata In caso di interruzione anticipata dell’esecuzione
   del contratto
