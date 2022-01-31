Modelli per la trasmissione delle informazioni
==============================================

Di seguito sono riportate tutte le schede di trasmissione definite da
ANAC che compongono le varie fasi del ciclo di vita dei contratti
pubblici.

10. .. rubric::  E01 - Fase di creazione della gara e acquisizione
       codici CIG
       :name: e01---fase-di-creazione-della-gara-e-acquisizione-codici-cig

    1. .. rubric:: S01 – Creazione gara
          :name: s01-creazione-gara

+---------+---------+---------+---------+---------+---------+---------+
| S01 –   |         |         |         |         |         |         |
| creazio |         |         |         |         |         |         |
| ne      |         |         |         |         |         |         |
| gara    |         |         |         |         |         |         |
+=========+=========+=========+=========+=========+=========+=========+
| COD     | ETICHET | TIPO    | FORMATO | CONTROL | MESSAGG |         |
|         | TA      |         |         | LO      | IO      |         |
+---------+---------+---------+---------+---------+---------+---------+
|         |         |         |         | DESCRIZ | TIPO    |         |
|         |         |         |         | IONE    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 01      | Data    | E       | DATA    |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 02      | CF      | E       | STRINGA |         |         |         |
|         | UTENTE  |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 03      | Codice  | E       | STRINGA |         |         |         |
|         | Fiscale |         |         |         |         |         |
|         | della   |         |         |         |         |         |
|         | Stazion |         |         |         |         |         |
|         | e       |         |         |         |         |         |
|         | Appalta |         |         |         |         |         |
|         | nte     |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 04      | Denom.n | E       | STRINGA |         |         |         |
|         | e       |         |         |         |         |         |
|         | della   |         |         |         |         |         |
|         | Stazion |         |         |         |         |         |
|         | e       |         |         |         |         |         |
|         | Appalta |         |         |         |         |         |
|         | nte     |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 05      | Codice  | E       | STRINGA |         |         |         |
|         | univoco |         |         |         |         |         |
|         | centro  |         |         |         |         |         |
|         | di      |         |         |         |         |         |
|         | costo   |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 06      | Denomin | E       | STRINGA |         |         |         |
|         | azione  |         |         |         |         |         |
|         | del     |         |         |         |         |         |
|         | centro  |         |         |         |         |         |
|         | di      |         |         |         |         |         |
|         | costo   |         |         |         |         |         |
|         | nell’am |         |         |         |         |         |
|         | bito    |         |         |         |         |         |
|         | della   |         |         |         |         |         |
|         | Stazion |         |         |         |         |         |
|         | e       |         |         |         |         |         |
|         | Appalta |         |         |         |         |         |
|         | nte     |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 07      | Codice  | E       | STRINGA |         |         |         |
|         | categor |         |         |         |         |         |
|         | ia      |         |         |         |         |         |
|         | della   |         |         |         |         |         |
|         | Stazion |         |         |         |         |         |
|         | e       |         |         |         |         |         |
|         | Appalta |         |         |         |         |         |
|         | nte     |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 07.1    | Categor | O       | `CATEGO | lista   | B       | selezio |
|         | ie      |         | RIE_MER | di      |         | nare    |
|         | merceol |         | CEOLOGI | valori  |         | uno o   |
|         | ogiche  |         | CHE <#c | da      |         | più     |
|         | oggetto |         | ategori | elenco  |         | valori  |
|         | della   |         | e-merce |         |         | tra     |
|         | fornitu |         | ologich |         |         | quelli  |
|         | ra      |         | e>`__   |         |         | previst |
|         | di cui  |         |         |         |         | i       |
|         | al DPCM |         |         |         |         |         |
|         | soggett |         |         |         |         |         |
|         | i       |         |         |         |         |         |
|         | aggrega |         |         |         |         |         |
|         | tori    |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 07.2    | Motivaz | OIF     | `MOTIVA | lista   | B       | Non e'  |
|         | ione    |         | ZIONE_C | di      |         | stato   |
|         | richies |         | IG_SOGG | valori  |         | indicat |
|         | ta      |         | ETTI_AG | da      |         | o       |
|         | CIG     |         | GREGATO | elenco  |         | il      |
|         |         |         | RI <#mo |         |         | campo   |
|         |         |         | tivazio | obbliga |         | Motivaz |
|         |         |         | ne_cig_ | torio   |         | ione    |
|         |         |         | soggett | solo se |         | richies |
|         |         |         | i_aggre | campo   |         | ta      |
|         |         |         | gatori> | S01.07. |         | CIG     |
|         |         |         | `__     | 1       |         |         |
|         |         |         |         | è       |         |         |
|         |         |         |         | valoriz |         |         |
|         |         |         |         | zato    |         |         |
|         |         |         |         | e       |         |         |
|         |         |         |         | S01.07. |         |         |
|         |         |         |         | 1       |         |         |
|         |         |         |         | <>      |         |         |
|         |         |         |         | ‘Lavori |         |         |
|         |         |         |         | oppure  |         |         |
|         |         |         |         | beni e  |         |         |
|         |         |         |         | servizi |         |         |
|         |         |         |         | non     |         |         |
|         |         |         |         | elencat |         |         |
|         |         |         |         | i       |         |         |
|         |         |         |         | nell'ar |         |         |
|         |         |         |         | t.      |         |         |
|         |         |         |         | 1 dPCM  |         |         |
|         |         |         |         | 24      |         |         |
|         |         |         |         | dicembr |         |         |
|         |         |         |         | e       |         |         |
|         |         |         |         | 2015’   |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 08      | Oggetto | O       | STRINGA | testo   | B       | Inserir |
|         | della   |         |         | libero  |         | e       |
|         | gara    |         |         |         |         | l’ogget |
|         |         |         |         |         |         | to      |
|         |         |         |         |         |         | della   |
|         |         |         |         |         |         | gara    |
+---------+---------+---------+---------+---------+---------+---------+
| 09      | Numero  | O       | NUMERIC | il      | B       | Inserir |
|         | Totale  |         | O       | numero  |         | e       |
|         | Lotti   |         |         | dei     | B       | il      |
|         |         |         |         | lotti   |         | numero  |
|         |         |         |         | deve    |         | dei     |
|         |         |         |         | essere  |         | lotti   |
|         |         |         |         | maggior |         |         |
|         |         |         |         | e       |         | In fase |
|         |         |         |         | o       |         | di      |
|         |         |         |         | uguale  |         | perfezi |
|         |         |         |         | ad 1    |         | onament |
|         |         |         |         |         |         | o       |
|         |         |         |         | In fase |         | viene   |
|         |         |         |         | di      |         | visuali |
|         |         |         |         | perfezi |         | zzato   |
|         |         |         |         | onament |         | il      |
|         |         |         |         | o       |         | seguent |
|         |         |         |         | il      |         | e       |
|         |         |         |         | valore  |         | messagg |
|         |         |         |         | inserit |         | io      |
|         |         |         |         | o       |         | “numero |
|         |         |         |         | deve    |         | lotti   |
|         |         |         |         | essere  |         | da      |
|         |         |         |         | coerent |         | perfezi |
|         |         |         |         | e       |         | onare   |
|         |         |         |         | col     |         | incoere |
|         |         |         |         | numero  |         | nte     |
|         |         |         |         | di      |         | rispett |
|         |         |         |         | lotti   |         | o       |
|         |         |         |         | inserit |         | ai      |
|         |         |         |         | i       |         | numero  |
|         |         |         |         |         |         | totale  |
|         |         |         |         |         |         | dei     |
|         |         |         |         |         |         | lotti   |
|         |         |         |         |         |         | della   |
|         |         |         |         |         |         | gara”   |
+---------+---------+---------+---------+---------+---------+---------+
| 10      |  [2]_Im | C       | IMPORTO |         |         |         |
|         | porto   |         |         |         |         |         |
|         | gara    |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 11      | Settore | O       | `SETTOR | lista   | B       | Selezio |
|         | del     |         | E_CONTR | di      |         | nare    |
|         | contrat |         | ATTO <# | valori  |         | un      |
|         | to      |         | settore | da      |         | valore  |
|         |         |         | _contra | elenco  |         | tra     |
|         |         |         | tto>`__ |         |         | quelli  |
|         |         |         |         |         |         | previst |
|         |         |         |         |         |         | i       |
+---------+---------+---------+---------+---------+---------+---------+
| 12      | Modalit | OIF     | `MODALI | obbliga | B       | Selezio |
|         | à       |         | TA_INDI | torio   |         | nare    |
|         | di      |         | ZIONE < | solo se |         | un      |
|         | indizio |         | #modali | campo   |         | valore  |
|         | ne      |         | ta_indi | S01.11  |         | tra     |
|         | (settor |         | zione>` | =       |         | quelli  |
|         | i       |         | __      | ‘specia |         | previst |
|         | special |         |         | le’     |         | i       |
|         | i)      |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 13      | modalit | O       | `MODALI | lista   | B       | Selezio |
|         | à       |         | TA_REAL | di      |         | nare    |
|         | di      |         | IZZAZIO | valori  |         | un      |
|         | realizz |         | NE <#mo | da      |         | valore  |
|         | azione  |         | dalita_ | elenco  |         | tra     |
|         |         |         | realizz |         |         | quelli  |
|         |         |         | azione> |         |         | previst |
|         |         |         | `__     |         |         | i       |
+---------+---------+---------+---------+---------+---------+---------+
| 14      | CIG     | OIF     | CIG     | se      | B       | Il CIG  |
|         | relativ |         |         | valoriz |         | inserit |
|         | o       |         |         | zato    | B       | o       |
|         | all’acc |         |         | deve    |         | non     |
|         | ordo    |         |         | essere  |         | corrisp |
|         | quadro/ |         |         | un CIG  |         | onde    |
|         | convenz |         |         | valido  |         | ad un   |
|         | ione    |         |         | e di    |         | accordo |
|         | cui si  |         |         | tipo    |         | quadro/ |
|         | aderisc |         |         | “Accord |         | convenz |
|         | e       |         |         | o       |         | ione    |
|         |         |         |         | quadro  |         |         |
|         |         |         |         | /       |         | Valoriz |
|         |         |         |         | Convenz |         | zare    |
|         |         |         |         | ione”   |         | il CIG  |
|         |         |         |         |         |         | dell’Ac |
|         |         |         |         | deve    |         | cordo   |
|         |         |         |         | essere  |         | quadro/ |
|         |         |         |         | valoriz |         | convenz |
|         |         |         |         | zato    |         | ione    |
|         |         |         |         | solo se |         | di      |
|         |         |         |         | S01.12  |         | riferim |
|         |         |         |         | uguale  |         | ento    |
|         |         |         |         | a       |         |         |
|         |         |         |         | codice  |         |         |
|         |         |         |         | 2 o 11. |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 15      | Gara    | O       | FLAG    | Valore: | B       | Selezio |
|         | esclusa |         |         | SI/NO/B |         | nare    |
|         | dall'ac |         |         | lank    |         | un      |
|         | quisizi |         |         |         |         | valore  |
|         | one     |         |         | Default |         | tra     |
|         | obbliga |         |         | :       |         | quelli  |
|         | toria   |         |         | NULL    |         | previst |
|         | dei     |         |         |         |         | i       |
|         | requisi |         |         |         |         |         |
|         | ti      |         |         |         |         |         |
|         | ai fini |         |         |         |         |         |
|         | AVCpass |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 16      | Informa |         | FLAG    | Valore: |         |         |
|         | zione   |         |         | SI/NO   |         |         |
|         | “Estrem |         |         |         |         |         |
|         | a       |         |         | Default |         |         |
|         | urgenza |         |         | :       |         |         |
|         | ex art. |         |         | NO      |         |         |
|         | 9 commi |         |         |         |         |         |
|         | 1 e 2   |         |         |         |         |         |
|         | D.L.    |         |         |         |         |         |
|         | 133/201 |         |         |         |         |         |
|         | 4”      |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+

.. [1]
    Il campo è calcolato come somma degli importi dei lotti associati
   alla gara ed è mostrato nel “Dettaglio gara”

.. [2]
    Il campo è calcolato come somma degli importi dei lotti associati
   alla gara ed è mostrato nel “Dettaglio gara”
