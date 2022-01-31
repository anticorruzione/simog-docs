S12 – Stipula accordo quadro convenzione
========================================

+--------+--------+--------+--------+--------+--------+--------+--------+
| S12 –  |        |        |        |        |        |        |        |
| Stipul |        |        |        |        |        |        |        |
| a      |        |        |        |        |        |        |        |
| accord |        |        |        |        |        |        |        |
| o      |        |        |        |        |        |        |        |
| quadro |        |        |        |        |        |        |        |
| conven |        |        |        |        |        |        |        |
| zione  |        |        |        |        |        |        |        |
+========+========+========+========+========+========+========+========+
| COD    | ETICHE | TIPO   | FORMAT | CONTRO | MESSAG |        |        |
|        | TTA    |        | O      | LLO    | GIO    |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
|        |        |        |        | DESCRI | TIPO   |        |        |
|        |        |        |        | ZIONE  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 01     | Codice | R      | STRING | Il CIG | B      | CIG    |        |
|        | di     |        | A      | deve   |        | inesis |        |
|        | indivi |        |        | essere |        | tente  |        |
|        | duazio |        |        | esiste |        | o non  |        |
|        | ne     |        |        | nte    |        | di     |        |
|        | dell’a |        |        | ed in  |        | compet |        |
|        | ppalto |        |        | carico |        | enza   |        |
|        | CIG    |        |        | all’am |        |        |        |
|        |        |        |        | minist |        |        |        |
|        |        |        |        | razion |        |        |        |
|        |        |        |        | e      |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | appart |        |        |        |
|        |        |        |        | enenza |        |        |        |
|        |        |        |        | del    |        |        |        |
|        |        |        |        | RUP    |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **DATI |        |        |        |        |        |        |        |
| ECONOM |        |        |        |        |        |        |        |
| ICI    |        |        |        |        |        |        |        |
| CONTRA |        |        |        |        |        |        |        |
| TTO    |        |        |        |        |        |        |        |
| MULTIL |        |        |        |        |        |        |        |
| OTTO** |        |        |        |        |        |        |        |
| \  [2] |        |        |        |        |        |        |        |
| _      |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 02     | Import | C      | IMPORT | Riport |        |        |        |
|        | o      |        | O      | a      |        |        |        |
|        | compon |        |        | la     |        |        |        |
|        | ente   |        |        | somma  |        |        |        |
|        | lavori |        |        | dei    |        |        |        |
|        | in €   |        |        | valori |        |        |        |
|        | (al    |        |        | presen |        |        |        |
|        | netto  |        |        | ti     |        |        |        |
|        | dell’I |        |        | nei    |        |        |        |
|        | VA     |        |        | singol |        |        |        |
|        | e      |        |        | i      |        |        |        |
|        | degli  |        |        | lotti  |        |        |        |
|        | oneri  |        |        |        |        |        |        |
|        | di     |        |        |        |        |        |        |
|        | sicure |        |        |        |        |        |        |
|        | zza)   |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 03     | Import | C      | IMPORT | Riport |        |        |        |
|        | o      |        | O      | a      |        |        |        |
|        | compon |        |        | la     |        |        |        |
|        | ente   |        |        | somma  |        |        |        |
|        | serviz |        |        | dei    |        |        |        |
|        | i      |        |        | valori |        |        |        |
|        | in €   |        |        | presen |        |        |        |
|        | (come  |        |        | ti     |        |        |        |
|        | sopra) |        |        | nei    |        |        |        |
|        |        |        |        | singol |        |        |        |
|        |        |        |        | i      |        |        |        |
|        |        |        |        | lotti  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 04     | Import | C      | IMPORT | Riport |        |        |        |
|        | o      |        | O      | a      |        |        |        |
|        | compon |        |        | la     |        |        |        |
|        | ente   |        |        | somma  |        |        |        |
|        | fornit |        |        | dei    |        |        |        |
|        | ure    |        |        | valori |        |        |        |
|        | in €   |        |        | presen |        |        |        |
|        | (come  |        |        | ti     |        |        |        |
|        | sopra) |        |        | nei    |        |        |        |
|        |        |        |        | singol |        |        |        |
|        |        |        |        | i      |        |        |        |
|        |        |        |        | lotti  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 05     | Subtot | C      | IMPORT |        |        |        |        |
|        | ale    |        | O      |        |        |        |        |
|        | (02+03 |        |        |        |        |        |        |
|        | +04)   |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 06     | Import | C      | IMPORT | Riport |        |        |        |
|        | o      |        | O      | a      |        |        |        |
|        | totale |        |        | la     |        |        |        |
|        | per    |        |        | somma  |        |        |        |
|        | l’attu |        |        | dei    |        |        |        |
|        | azione |        |        | valori |        |        |        |
|        | della  |        |        | presen |        |        |        |
|        | sicure |        |        | ti     |        |        |        |
|        | zza    |        |        | nei    |        |        |        |
|        |        |        |        | singol |        |        |        |
|        |        |        |        | i      |        |        |        |
|        |        |        |        | lotti  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 07     | Eventu | C      | IMPORT | Riport |        |        |        |
|        | ali    |        | O      | a      |        |        |        |
|        | ulteri |        |        | la     |        |        |        |
|        | ori    |        |        | somma  |        |        |        |
|        | somme  |        |        | dei    |        |        |        |
|        | non    |        |        | valori |        |        |        |
|        | assogg |        |        | presen |        |        |        |
|        | ettate |        |        | ti     |        |        |        |
|        | al     |        |        | nei    |        |        |        |
|        | ribass |        |        | singol |        |        |        |
|        | o      |        |        | i      |        |        |        |
|        | d’asta |        |        | lotti  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 08     | Import | C      | IMPORT | Riport |        |        |        |
|        | o      |        | O      | a      |        |        |        |
|        | proget |        |        | la     |        |        |        |
|        | tazion |        |        | somma  |        |        |        |
|        | e      |        |        | dei    |        |        |        |
|        | (art.  |        |        | valori |        |        |        |
|        | 53     |        |        | presen |        |        |        |
|        | comma  |        |        | ti     |        |        |        |
|        | 2      |        |        | nei    |        |        |        |
|        | lett.  |        |        | singol |        |        |        |
|        | b, c   |        |        | i      |        |        |        |
|        | Dlgs   |        |        | lotti  |        |        |        |
|        | 163/20 |        |        |        |        |        |        |
|        | 06)    |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 09     | Import | C      | IMPORT |        |        |        |        |
|        | o      |        | O      |        |        |        |        |
|        | comple |        |        |        |        |        |        |
|        | ssivo  |        |        |        |        |        |        |
|        | appalt |        |        |        |        |        |        |
|        | o      |        |        |        |        |        |        |
|        | (05 +  |        |        |        |        |        |        |
|        | 06 +   |        |        |        |        |        |        |
|        | 07 +   |        |        |        |        |        |        |
|        | 08)    |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 10     | Import | C      | IMPORT | Riport |        |        |        |
|        | o      |        | O      | a      |        |        |        |
|        | totale |        |        | la     |        |        |        |
|        | somme  |        |        | somma  |        |        |        |
|        | a      |        |        | dei    |        |        |        |
|        | dispos |        |        | valori |        |        |        |
|        | izione |        |        | presen |        |        |        |
|        |        |        |        | ti     |        |        |        |
|        |        |        |        | nei    |        |        |        |
|        |        |        |        | singol |        |        |        |
|        |        |        |        | i      |        |        |        |
|        |        |        |        | lotti  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 11     | Import | C      | IMPORT | Riport |        |        |        |
|        | o      |        | O      | a      |        |        |        |
|        | comple |        |        | la     |        |        |        |
|        | ssivo  |        |        | somma  |        |        |        |
|        | dell’i |        |        | dei    |        |        |        |
|        | nterve |        |        | valori |        |        |        |
|        | nto    |        |        | presen |        |        |        |
|        |        |        |        | ti     |        |        |        |
|        |        |        |        | nei    |        |        |        |
|        |        |        |        | singol |        |        |        |
|        |        |        |        | i      |        |        |        |
|        |        |        |        | lotti  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 12     | Aggiud | E      | DATI_A |        |        |        |        |
|        | icatar |        | GGIUDI |        |        |        |        |
|        | io     |        | CATARI |        |        |        |        |
|        |        |        | O      |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 13     | Import | C      | IMPORT | Riport |        |        |        |
|        | o      |        | O      | a      |        |        |        |
|        | aggiud |        |        | la     |        |        |        |
|        | icazio |        |        | somma  |        |        |        |
|        | ne     |        |        | dei    |        |        |        |
|        |        |        |        | valori |        |        |        |
|        |        |        |        | presen |        |        |        |
|        |        |        |        | ti     |        |        |        |
|        |        |        |        | nei    |        |        |        |
|        |        |        |        | singol |        |        |        |
|        |        |        |        | i      |        |        |        |
|        |        |        |        | lotti  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 14.I   | data   | C      | DATA   | Riport |        |        |        |
|        | aggiud |        |        | a      |        |        |        |
|        | icazio |        |        | la     |        |        |        |
|        | ne     |        |        | data   |        |        |        |
|        | inferi |        |        | minore |        |        |        |
|        | ore    |        |        | tra i  |        |        |        |
|        |        |        |        | valori |        |        |        |
|        |        |        |        | presen |        |        |        |
|        |        |        |        | ti     |        |        |        |
|        |        |        |        | nei    |        |        |        |
|        |        |        |        | singol |        |        |        |
|        |        |        |        | i      |        |        |        |
|        |        |        |        | lotti  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 14.S   | data   | C      | DATA   | Riport |        |        |        |
|        | aggiud |        |        | a      |        |        |        |
|        | icazio |        |        | la     |        |        |        |
|        | ne     |        |        | data   |        |        |        |
|        | superi |        |        | maggio |        |        |        |
|        | ore    |        |        | re     |        |        |        |
|        |        |        |        | tra i  |        |        |        |
|        |        |        |        | valori |        |        |        |
|        |        |        |        | presen |        |        |        |
|        |        |        |        | ti     |        |        |        |
|        |        |        |        | nei    |        |        |        |
|        |        |        |        | singol |        |        |        |
|        |        |        |        | i      |        |        |        |
|        |        |        |        | lotti  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **PUBB |        |        |        |        |        |        |        |
| LICAZI |        |        |        |        |        |        |        |
| ONE    |        |        |        |        |        |        |        |
| ESITO  |        |        |        |        |        |        |        |
| PROCED |        |        |        |        |        |        |        |
| URA    |        |        |        |        |        |        |        |
| DI     |        |        |        |        |        |        |        |
| SELEZI |        |        |        |        |        |        |        |
| ONE**  |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 15     | Data   |        | DATA   | Se non | B      | Data   |        |
|        | Gazzet |        |        | è una  |        | formal |        |
|        | ta     |        |        | data   | B      | mente  |        |
|        | Uffici |        |        |        |        | non    |        |
|        | ale    |        |        | Se     |        | corret |        |
|        | Comuni |        |        | digita |        | ta     |        |
|        | tà     |        |        | ta     |        |        |        |
|        | Europe |        |        | deve   |        | Data   |        |
|        | a      |        |        | essere |        | antece |        |
|        | - GUCE |        |        | superi |        | dente  |        |
|        |        |        |        | ore    |        | la     |        |
|        |        |        |        | al     |        | data   |        |
|        |        |        |        | campo  |        | di     |        |
|        |        |        |        | S08.63 |        | aggiud |        |
|        |        |        |        | o al   |        | icazio |        |
|        |        |        |        | campo  |        | ne     |        |
|        |        |        |        | S12.14 |        |        |        |
|        |        |        |        | in     |        |        |        |
|        |        |        |        | caso   |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | contra |        |        |        |
|        |        |        |        | tti    |        |        |        |
|        |        |        |        | multil |        |        |        |
|        |        |        |        | otto   |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 16     | Gazzet | OIF    | DATA   | Se non | B      | Data   |        |
|        | ta     |        |        | è una  |        | formal |        |
|        | Uffici |        |        | data   | B      | mente  |        |
|        | ale    |        |        |        |        | non    |        |
|        | Repubb |        |        | campo  |        | corret |        |
|        | lica   |        |        | S08.63 |        | ta     |        |
|        | Italia |        |        | o al   |        |        |        |
|        | na     |        |        | campo  |        | Data   |        |
|        | - GURI |        |        | S09.16 |        | antece |        |
|        |        |        |        | o al   |        | dente  |        |
|        |        |        |        | campo  |        | la     |        |
|        |        |        |        | S12.14 |        | data   |        |
|        |        |        |        | in     |        | di     |        |
|        |        |        |        | caso   |        | aggiud |        |
|        |        |        |        | di     |        | icazio |        |
|        |        |        |        | contra |        | ne     |        |
|        |        |        |        | tti    |        |        |        |
|        |        |        |        | multil |        |        |        |
|        |        |        |        | otto   |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 17     | Quotid |        | NUMERI | Se non | B      | Il     |        |
|        | iani   |        | CO     | è un   |        | campo  |        |
|        | nazion |        |        | numero | B      | contie |        |
|        | ali    |        |        |        |        | ne     |        |
|        |        |        |        | Se >   |        | caratt |        |
|        |        |        |        | 20     |        | eri    |        |
|        |        |        |        |        |        | non    |        |
|        |        |        |        |        |        | validi |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        |        |        | Valore |        |
|        |        |        |        |        |        | elevat |        |
|        |        |        |        |        |        | o,     |        |
|        |        |        |        |        |        | verifi |        |
|        |        |        |        |        |        | care   |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 18     | Quotid |        | NUMERI | Se non | B      | Il     |        |
|        | iani   |        | CO     | è un   |        | campo  |        |
|        | locali |        |        | numero | B      | contie |        |
|        |        |        |        |        |        | ne     |        |
|        |        |        |        | Se >   |        | caratt |        |
|        |        |        |        | 20     |        | eri    |        |
|        |        |        |        |        |        | non    |        |
|        |        |        |        |        |        | validi |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        |        |        | Valore |        |
|        |        |        |        |        |        | elevat |        |
|        |        |        |        |        |        | o,     |        |
|        |        |        |        |        |        | verifi |        |
|        |        |        |        |        |        | care   |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 19     | Profil | OIF    | FLAG   | | List | B      | Selezi |        |
|        | o      |        |        | a      |        | onare  |        |
|        | del    |        |        |   di   | B      | un     |        |
|        | commit |        |        |   valo |        | valore |        |
|        | tente  |        |        | ri     |        | tra    |        |
|        |        |        |        |   da   |        | quelli |        |
|        |        |        |        |   elen |        | previs |        |
|        |        |        |        | co     |        | ti     |        |
|        |        |        |        | | Vale |        |        |        |
|        |        |        |        | :      |        | Valori |        |
|        |        |        |        |   SI o |        | zzare  |        |
|        |        |        |        |   NO   |        | almeno |        |
|        |        |        |        | | Valo |        | un     |        |
|        |        |        |        | re     |        | campo  |        |
|        |        |        |        |   di   |        | riferi |        |
|        |        |        |        |   defa |        | to     |        |
|        |        |        |        | ult:   |        | alla   |        |
|        |        |        |        |   Blan |        | pubbli |        |
|        |        |        |        | k      |        | cazion |        |
|        |        |        |        |        |        | e      |        |
|        |        |        |        | Se     |        | dell’a |        |
|        |        |        |        | campo  |        | ppalto |        |
|        |        |        |        | S12.02 |        |        |        |
|        |        |        |        | ,      |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S12.03 |        |        |        |
|        |        |        |        | ,      |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S12.04 |        |        |        |
|        |        |        |        | o      |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S12.05 |        |        |        |
|        |        |        |        | sono   |        |        |        |
|        |        |        |        | blank  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 20     | Sito   | OIF    | FLAG   | Lista  | B      | Selezi |        |
|        | Inform |        |        | di     |        | onare  |        |
|        | atico  |        |        | valori |        | un     |        |
|        | Minist |        |        | da     |        | valore |        |
|        | ero    |        |        | elenco |        | tra    |        |
|        | Infras |        |        | Vale:  |        | quelli |        |
|        | truttu |        |        | SI o   |        | previs |        |
|        | re     |        |        | NO     |        | ti     |        |
|        |        |        |        | Valore |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | defaul |        |        |        |
|        |        |        |        | t:     |        |        |        |
|        |        |        |        | Blank  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 21     | Sito   | OIF    | FLAG   | Lista  | B      | Selezi |        |
|        | inform |        |        | di     |        | onare  |        |
|        | atico  |        |        | valori |        | un     |        |
|        | Osserv |        |        | da     |        | valore |        |
|        | atorio |        |        | elenco |        | tra    |        |
|        | Contra |        |        | Vale:  |        | quelli |        |
|        | tti    |        |        | SI o   |        | previs |        |
|        | Pubbli |        |        | NO     |        | ti     |        |
|        | ci     |        |        | Valore |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | defaul |        |        |        |
|        |        |        |        | t:     |        |        |        |
|        |        |        |        | Blank  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **ACCO |        |        |        |        |        |        |        |
| RDO    |        |        |        |        |        |        |        |
| QUADRO |        |        |        |        |        |        |        |
| /CONVE |        |        |        |        |        |        |        |
| NZIONE |        |        |        |        |        |        |        |
| **     |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 22     | Data   |        | DATA   | Se     | B      | Data   |        |
|        | stipul |        |        | digita |        | di     |        |
|        | a      |        |        | ta     | B      | stipul |        |
|        | accord |        |        | deve   |        | a      |        |
|        | o      |        |        | essere | B      | del    |        |
|        | quadro |        |        | >= al  |        | contra |        |
|        | /conve |        |        | campo  |        | tto    |        |
|        | nzione |        |        | S08.63 |        | antece |        |
|        |        |        |        | o al   |        | dente  |        |
|        |        |        |        | campo  |        | alla   |        |
|        |        |        |        | S09.16 |        | data   |        |
|        |        |        |        | o al   |        | di     |        |
|        |        |        |        | campo  |        | aggiud |        |
|        |        |        |        | S12.14 |        | icazio |        |
|        |        |        |        | in     |        | ne     |        |
|        |        |        |        | caso   |        |        |        |
|        |        |        |        | di     |        | Data   |        |
|        |        |        |        | contra |        | formal |        |
|        |        |        |        | tti    |        | mente  |        |
|        |        |        |        | multil |        | non    |        |
|        |        |        |        | otto   |        | corret |        |
|        |        |        |        |        |        | ta     |        |
|        |        |        |        | Deve   |        |        |        |
|        |        |        |        | essere |        | la     |        |
|        |        |        |        | un     |        | data   |        |
|        |        |        |        | campo  |        | scaden |        |
|        |        |        |        | data   |        | za     |        |
|        |        |        |        |        |        | del    |        |
|        |        |        |        | Se     |        | contra |        |
|        |        |        |        | campo  |        | tto    |        |
|        |        |        |        | S12.24 |        | è      |        |
|        |        |        |        | valori |        | antece |        |
|        |        |        |        | zzato  |        | dente  |        |
|        |        |        |        | e      |        | alla   |        |
|        |        |        |        | campo  |        | data   |        |
|        |        |        |        | S12.22 |        | di     |        |
|        |        |        |        | >      |        | stipul |        |
|        |        |        |        | S12.24 |        | a      |        |
|        |        |        |        |        |        | del    |        |
|        |        |        |        |        |        | contra |        |
|        |        |        |        |        |        | tto    |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **TERM |        |        |        |        |        |        |        |
| INI    |        |        |        |        |        |        |        |
| DI     |        |        |        |        |        |        |        |
| ESECUZ |        |        |        |        |        |        |        |
| IONE** |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 23     | Data   |        | DATA   | Deve   | B      | Data   |        |
|        | decorr |        |        | essere |        | formal |        |
|        | enza   |        |        | un     |        | mente  |        |
|        | contra |        |        | campo  |        | non    |        |
|        | ttuale |        |        | data   |        | corret |        |
|        |        |        |        |        |        | ta     |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 24     | Data   |        | DATA   | Deve   | B      | Data   |        |
|        | scaden |        |        | essere | B      | formal |        |
|        | za     |        |        | un     |        | mente  |        |
|        | contra |        |        | campo  |        | non    |        |
|        | ttuale |        |        | data   |        | corret |        |
|        |        |        |        |        |        | ta     |        |
|        |        |        |        | Se     |        |        |        |
|        |        |        |        | digita |        | la     |        |
|        |        |        |        | ta     |        | data   |        |
|        |        |        |        | deve   |        | scaden |        |
|        |        |        |        | essere |        | za     |        |
|        |        |        |        | superi |        | del    |        |
|        |        |        |        | ore    |        | contra |        |
|        |        |        |        | al     |        | tto    |        |
|        |        |        |        | campo  |        | è      |        |
|        |        |        |        | S12.22 |        | antece |        |
|        |        |        |        |        |        | dente  |        |
|        |        |        |        |        |        | alla   |        |
|        |        |        |        |        |        | data   |        |
|        |        |        |        |        |        | di     |        |
|        |        |        |        |        |        | stipul |        |
|        |        |        |        |        |        | a      |        |
|        |        |        |        |        |        | del    |        |
|        |        |        |        |        |        | contra |        |
|        |        |        |        |        |        | tto    |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 25     | Oggett | E      |        |        |        |        |        |
|        | o      |        |        |        |        |        |        |
|        | contra |        |        |        |        |        |        |
|        | ttuale |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **SOGG |        |        |        |        |        |        |        |
| ETTI   |        |        |        |        |        |        |        |
| AGGIUD |        |        |        |        |        |        |        |
| ICATAR |        |        |        |        |        |        |        |
| I**    |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 26     | PER    | Dati   |        | `DATI_ |        |        |        |
|        | OGNI   | Sogget |        | PERSON |        |        |        |
|        | SOGGET | to     |        | A_FISI |        |        |        |
|        | TO     | incari |        | CA <#d |        |        |        |
|        | INCARI | cato   |        | ati_pe |        |        |        |
|        | CATO   |        |        | rsona_ |        |        |        |
|        |        |        |        | fisica |        |        |        |
|        |        |        |        | >`__   |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 27     |        | Ruolo  | O      | `RUOLI | Lista  | B      | Selezi |
|        |        |        |        | _RESPO | di     |        | onare  |
|        |        |        |        | NSABIL | valori |        | un     |
|        |        |        |        | E <#ru | da     |        | valore |
|        |        |        |        | oli_re | elenco |        | tra    |
|        |        |        |        | sponsa |        |        | quelli |
|        |        |        |        | bile>` |        |        | previs |
|        |        |        |        | __     |        |        | ti     |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 28     | Import | E      | IMPORT |        |        |        |        |
|        | o      |        | O      |        |        |        |        |
|        | aggiud |        |        |        |        |        |        |
|        | icazio |        |        |        |        |        |        |
|        | ne/aff |        |        |        |        |        |        |
|        | idamen |        |        |        |        |        |        |
|        | to     |        |        |        |        |        |        |
|        | in €   |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+

**
**

13. .. rubric::  E04 - Fase di esecuzione ed avanzamento del contratto
       (rif. 14)
       :name: e04---fase-di-esecuzione-ed-avanzamento-del-contratto-rif.-14

    1. .. rubric:: S13 – Stato Avanzamento
          :name: s13-stato-avanzamento

+--------+--------+--------+--------+--------+--------+--------+--------+
| S13 –  |        |        |        |        |        |        |        |
| stato  |        |        |        |        |        |        |        |
| avanza |        |        |        |        |        |        |        |
| mento  |        |        |        |        |        |        |        |
+========+========+========+========+========+========+========+========+
| COD    | ETICHE | TIPO   | FORMAT | CONTRO | MESSAG |        |        |
|        | TTA    |        | O      | LLO    | GIO    |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
|        |        |        |        | DESCRI | TIPO   |        |        |
|        |        |        |        | ZIONE  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **RIFE |        |        |        |        |        |        |        |
| RIMENT |        |        |        |        |        |        |        |
| O      |        |        |        |        |        |        |        |
| AI     |        |        |        |        |        |        |        |
| DATI   |        |        |        |        |        |        |        |
| DELLA  |        |        |        |        |        |        |        |
| FASE   |        |        |        |        |        |        |        |
| DI     |        |        |        |        |        |        |        |
| AGGIUD |        |        |        |        |        |        |        |
| ICAZIO |        |        |        |        |        |        |        |
| NE     |        |        |        |        |        |        |        |
| O DI   |        |        |        |        |        |        |        |
| DEFINI |        |        |        |        |        |        |        |
| ZIONE  |        |        |        |        |        |        |        |
| DI     |        |        |        |        |        |        |        |
| PROCED |        |        |        |        |        |        |        |
| URA    |        |        |        |        |        |        |        |
| NEGOZI |        |        |        |        |        |        |        |
| ATA**  |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 01     | Codice | E      | STRING | Il CIG | B      | CIG    |        |
|        | di     |        | A      | deve   |        | inesis |        |
|        | indivi |        |        | essere |        | tente  |        |
|        | duazio |        |        | esiste |        | o non  |        |
|        | ne     |        |        | nte    |        | di     |        |
|        | dell’a |        |        | ed in  |        | compet |        |
|        | ppalto |        |        | carico |        | enza   |        |
|        | CIG    |        |        | all’am |        |        |        |
|        |        |        |        | minist |        |        |        |
|        |        |        |        | razion |        |        |        |
|        |        |        |        | e      |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | appart |        |        |        |
|        |        |        |        | enenza |        |        |        |
|        |        |        |        | del    |        |        |        |
|        |        |        |        | RUP    |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 02     | Stato  | C      | NUMERI |        |        |        |        |
|        | di     |        | CO     |        |        |        |        |
|        | avanza |        |        |        |        |        |        |
|        | mento  |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 03     | Denomi | O      | TESTO  |        |        |        |        |
|        | nazion |        |        |        |        |        |        |
|        | e      |        |        |        |        |        |        |
|        | dello  |        |        |        |        |        |        |
|        | stato  |        |        |        |        |        |        |
|        | di     |        |        |        |        |        |        |
|        | avanza |        |        |        |        |        |        |
|        | mento  |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 04     | Modali | O      | `MODAL | Lista  | B      | Selezi |        |
|        | tà     |        | ITA_PA | di     |        | onare  |        |
|        | di     |        | GAMENT | valori |        | almeno |        |
|        | pagame |        | O <#mo | da     |        | un     |        |
|        | nto    |        | dalita | elenco |        | valore |        |
|        | del    |        | _pagam | Valore |        | tra    |        |
|        | corris |        | ento>` | di     |        | quelli |        |
|        | pettiv |        | __     | defaul |        | previs |        |
|        | o      |        |        | t:     |        | ti     |        |
|        | (art.5 |        |        | Blank  |        |        |        |
|        | 3      |        |        |        |        |        |        |
|        | c.6    |        |        |        |        |        |        |
|        | D.Lgs  |        |        |        |        |        |        |
|        | 163/20 |        |        |        |        |        |        |
|        | 06)    |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 05     | SOLO   | Eventu |        | IMPORT | Se     | B      | Il     |
|        | PER    | ale    |        | O      | valori |        | campo  |
|        | STATO  | antici |        |        | zzato  | W      | contie |
|        | AVANZA | pazion |        |        | deve   |        | ne     |
|        | MENTO  | e      |        |        | essere | B      | caratt |
|        | N. 1   | (Solo  |        |        | un     |        | eri    |
|        |        | per    |        |        | campo  |        | non    |
|        |        | Stato  |        |        | valuta |        | validi |
|        |        | avanza |        |        |        |        |        |
|        |        | mento  |        |        | Se     |        | Antici |
|        |        | n.1)   |        |        | campo  |        | pazion |
|        |        |        |        |        | S13.02 |        | e      |
|        |        |        |        |        | > 1 il |        | non    |
|        |        |        |        |        | dato   |        | ammess |
|        |        |        |        |        | NON    |        | a      |
|        |        |        |        |        | deve   |        | in uno |
|        |        |        |        |        | essere |        | stato  |
|        |        |        |        |        | inseri |        | di     |
|        |        |        |        |        | to     |        | avanza |
|        |        |        |        |        |        |        | mento  |
|        |        |        |        |        | Se     |        | succes |
|        |        |        |        |        | valori |        | sivo   |
|        |        |        |        |        | zzato, |        | al     |
|        |        |        |        |        | il     |        | primo  |
|        |        |        |        |        | valore |        |        |
|        |        |        |        |        | immess |        | Valore |
|        |        |        |        |        | o      |        | elevat |
|        |        |        |        |        | deve   |        | o,     |
|        |        |        |        |        | essere |        | verifi |
|        |        |        |        |        | <=     |        | care   |
|        |        |        |        |        | campo  |        |        |
|        |        |        |        |        | S08.26 |        |        |
|        |        |        |        |        | o al   |        |        |
|        |        |        |        |        | campo  |        |        |
|        |        |        |        |        | S09.12 |        |        |
|        |        |        |        |        | o al   |        |        |
|        |        |        |        |        | campo  |        |        |
|        |        |        |        |        | S11.09 |        |        |
|        |        |        |        |        | in     |        |        |
|        |        |        |        |        | caso   |        |        |
|        |        |        |        |        | di     |        |        |
|        |        |        |        |        | contra |        |        |
|        |        |        |        |        | tto    |        |        |
|        |        |        |        |        | multil |        |        |
|        |        |        |        |        | otto   |        |        |
|        |        |        |        |        | o al   |        |        |
|        |        |        |        |        | campo  |        |        |
|        |        |        |        |        | S12.09 |        |        |
|        |        |        |        |        | in     |        |        |
|        |        |        |        |        | caso   |        |        |
|        |        |        |        |        | di     |        |        |
|        |        |        |        |        | stipul |        |        |
|        |        |        |        |        | a      |        |        |
|        |        |        |        |        | di     |        |        |
|        |        |        |        |        | accord |        |        |
|        |        |        |        |        | o      |        |        |
|        |        |        |        |        | quadro |        |        |
|        |        |        |        |        | multil |        |        |
|        |        |        |        |        | otto   |        |        |
|        |        |        |        |        | oppure |        |        |
|        |        |        |        |        | al     |        |        |
|        |        |        |        |        | campo  |        |        |
|        |        |        |        |        | S18.11 |        |        |
|        |        |        |        |        | dell’u |        |        |
|        |        |        |        |        | ltima  |        |        |
|        |        |        |        |        | scheda |        |        |
|        |        |        |        |        | varian |        |        |
|        |        |        |        |        | te     |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 06     |        | Data   | OIF    | DATA   | Se non | B      | Non è  |
|        |        | del    |        |        | valori |        | stata  |
|        |        | certif |        |        | zzato  | B      | indica |
|        |        | icato  |        |        | e      |        | ta     |
|        |        | di     |        |        | campo  | B      | la     |
|        |        | pagame |        |        | S13.04 |        | data   |
|        |        | nto    |        |        | è      | W      | di     |
|        |        | relati |        |        | stato  |        | Scheda |
|        |        | vo     |        |        | valori |        | Avanza |
|        |        | all'an |        |        | zzato  |        | menti  |
|        |        | ticipa |        |        |        |        | - Data |
|        |        | zione  |        |        | Se     |        | antici |
|        |        | (Solo  |        |        | campo  |        | pazion |
|        |        | per    |        |        | S13.04 |        | e      |
|        |        | Stato  |        |        | non è  |        |        |
|        |        | avanza |        |        | valori |        | Campo  |
|        |        | mento  |        |        | zzatoS |        | non    |
|        |        | n.1)   |        |        | e      |        | richie |
|        |        |        |        |        | valori |        | sto    |
|        |        |        |        |        | zzato  |        |        |
|        |        |        |        |        | deve   |        | Data   |
|        |        |        |        |        | essere |        | formal |
|        |        |        |        |        | un     |        | mente  |
|        |        |        |        |        | campo  |        | non    |
|        |        |        |        |        | data   |        | corret |
|        |        |        |        |        | valido |        | ta     |
|        |        |        |        |        |        |        |        |
|        |        |        |        |        | Se     |        | Data   |
|        |        |        |        |        | valori |        | antece |
|        |        |        |        |        | zzato  |        | dente  |
|        |        |        |        |        | deve   |        | la     |
|        |        |        |        |        | essere |        | data   |
|        |        |        |        |        | > di   |        | di     |
|        |        |        |        |        | campo  |        | aggiud |
|        |        |        |        |        | S08.63 |        | icazio |
|        |        |        |        |        | o al   |        | ne,    |
|        |        |        |        |        | campo  |        | verifi |
|        |        |        |        |        | S09.16 |        | care   |
|        |        |        |        |        | o al   |        |        |
|        |        |        |        |        | campo  |        |        |
|        |        |        |        |        | S11.14 |        |        |
|        |        |        |        |        | in     |        |        |
|        |        |        |        |        | caso   |        |        |
|        |        |        |        |        | di     |        |        |
|        |        |        |        |        | contra |        |        |
|        |        |        |        |        | tti    |        |        |
|        |        |        |        |        | multil |        |        |
|        |        |        |        |        | otto   |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 07     | Data   | O      | DATA   | Deve   | B      | Data   |        |
|        | Stato  |        |        | essere |        | formal |        |
|        | di     |        |        | un     | B      | mente  |        |
|        | avanza |        |        | campo  |        | non    |        |
|        | mento  |        |        | data   | W      | corret |        |
|        |        |        |        |        |        | ta     |        |
|        |        |        |        | Se non |        |        |        |
|        |        |        |        | valori |        | | Non  |        |
|        |        |        |        | zzato  |        |   e'   |        |
|        |        |        |        |        |        |   stat |        |
|        |        |        |        | Se     |        | a      |        |
|        |        |        |        | valori |        |   indi |        |
|        |        |        |        | zzato  |        | cata   |        |
|        |        |        |        | deve   |        |   la   |        |
|        |        |        |        | essere |        |   data |        |
|        |        |        |        | >      |        |   di   |        |
|        |        |        |        | campo  |        |   Sche |        |
|        |        |        |        | S08.63 |        | da     |        |
|        |        |        |        | o al   |        |   Avan |        |
|        |        |        |        | campo  |        | zament |        |
|        |        |        |        | S09.16 |        | i      |        |
|        |        |        |        | o al   |        | | Data |        |
|        |        |        |        | campo  |        |   ante |        |
|        |        |        |        | S11.14 |        | cedent |        |
|        |        |        |        | in     |        | e      |        |
|        |        |        |        | caso   |        |   la   |        |
|        |        |        |        | di     |        |   data |        |
|        |        |        |        | contra |        |   di   |        |
|        |        |        |        | tti    |        |   aggi |        |
|        |        |        |        | multil |        | udicaz |        |
|        |        |        |        | otto   |        | ione,  |        |
|        |        |        |        |        |        |   veri |        |
|        |        |        |        |        |        | ficare |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 08     | Import | O      | IMPORT | deve   | B      | Il     |        |
|        | o      |        | O      | essere |        | campo  |        |
|        | stato  |        |        | un     | B      | contie |        |
|        | avanza |        |        | campo  |        | ne     |        |
|        | mento  |        |        | valuta | B      | caratt |        |
|        |        |        |        |        |        | eri    |        |
|        |        |        |        | Se non |        | non    |        |
|        |        |        |        | valori |        | validi |        |
|        |        |        |        | zzato  |        |        |        |
|        |        |        |        |        |        | Il     |        |
|        |        |        |        | Il     |        | campo  |        |
|        |        |        |        | valore |        | è      |        |
|        |        |        |        | immess |        | obblig |        |
|        |        |        |        | o      |        | atorio |        |
|        |        |        |        | deve   |        |        |        |
|        |        |        |        | essere |        | Valore |        |
|        |        |        |        | <=     |        | elevat |        |
|        |        |        |        | campo  |        | o,     |        |
|        |        |        |        | S08.26 |        | verifi |        |
|        |        |        |        | o      |        | care   |        |
|        |        |        |        | S09.12 |        |        |        |
|        |        |        |        | o al   |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S11.09 |        |        |        |
|        |        |        |        | in     |        |        |        |
|        |        |        |        | caso   |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | contra |        |        |        |
|        |        |        |        | tto    |        |        |        |
|        |        |        |        | multil |        |        |        |
|        |        |        |        | otto   |        |        |        |
|        |        |        |        | o al   |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S12.09 |        |        |        |
|        |        |        |        | in     |        |        |        |
|        |        |        |        | caso   |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | stipul |        |        |        |
|        |        |        |        | a      |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | accord |        |        |        |
|        |        |        |        | o      |        |        |        |
|        |        |        |        | quadro |        |        |        |
|        |        |        |        | multil |        |        |        |
|        |        |        |        | otto   |        |        |        |
|        |        |        |        | oppure |        |        |        |
|        |        |        |        | al     |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S18.11 |        |        |        |
|        |        |        |        | dell’u |        |        |        |
|        |        |        |        | ltima  |        |        |        |
|        |        |        |        | scheda |        |        |        |
|        |        |        |        | varian |        |        |        |
|        |        |        |        | te     |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 09     | Data   |        | DATA   | Deve   | B      | Data   |        |
|        | di     |        |        | essere |        | formal |        |
|        | emissi |        |        | un     | W      | mente  |        |
|        | one    |        |        | campo  |        | non    |        |
|        | del    |        |        | data   |        | corret |        |
|        | certif |        |        |        |        | ta     |        |
|        | icato/ |        |        | Se     |        |        |        |
|        | mandat |        |        | valori |        | Data   |        |
|        | o      |        |        | zzato  |        | antece |        |
|        | di     |        |        | deve   |        | dente  |        |
|        | pagame |        |        | essere |        | la     |        |
|        | nto    |        |        | >      |        | data   |        |
|        |        |        |        | campo  |        | di     |        |
|        |        |        |        | S08.63 |        | aggiud |        |
|        |        |        |        | o al   |        | icazio |        |
|        |        |        |        | campo  |        | ne,    |        |
|        |        |        |        | S09.16 |        | verifi |        |
|        |        |        |        | o al   |        | care   |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S11.14 |        |        |        |
|        |        |        |        | in     |        |        |        |
|        |        |        |        | caso   |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | contra |        |        |        |
|        |        |        |        | tti    |        |        |        |
|        |        |        |        | multil |        |        |        |
|        |        |        |        | otto   |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 10     | Import | OIF    | IMPORT | deve   | B      | Data   |        |
|        | o      |        | O      | essere |        | formal |        |
|        | del    |        |        | un     | B      | mente  |        |
|        | certif |        |        | campo  |        | non    |        |
|        | icato/ |        |        | valuta |        | corret |        |
|        | mandat |        |        |        |        | ta     |        |
|        | o      |        |        | Il     |        | Valore |        |
|        | di     |        |        | valore |        | elevat |        |
|        | pagame |        |        | immess |        | o,     |        |
|        | nto    |        |        | o      |        | verifi |        |
|        |        |        |        | deve   |        | care   |        |
|        |        |        |        | essere |        |        |        |
|        |        |        |        | <= di  |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S08.26 |        |        |        |
|        |        |        |        | o al   |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S09.12 |        |        |        |
|        |        |        |        | o al   |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S11.09 |        |        |        |
|        |        |        |        | in     |        |        |        |
|        |        |        |        | caso   |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | contra |        |        |        |
|        |        |        |        | tto    |        |        |        |
|        |        |        |        | multil |        |        |        |
|        |        |        |        | otto   |        |        |        |
|        |        |        |        | o al   |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S12.09 |        |        |        |
|        |        |        |        | in     |        |        |        |
|        |        |        |        | caso   |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | stipul |        |        |        |
|        |        |        |        | a      |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | accord |        |        |        |
|        |        |        |        | o      |        |        |        |
|        |        |        |        | quadro |        |        |        |
|        |        |        |        | multil |        |        |        |
|        |        |        |        | otto   |        |        |        |
|        |        |        |        | oppure |        |        |        |
|        |        |        |        | al     |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S18.11 |        |        |        |
|        |        |        |        | dell’u |        |        |        |
|        |        |        |        | ltima  |        |        |        |
|        |        |        |        | scheda |        |        |        |
|        |        |        |        | varian |        |        |        |
|        |        |        |        | te     |        |        |        |
|        |        |        |        | varian |        |        |        |
|        |        |        |        | te     |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 11     | L'avan | O      | `AVANZ | Lista  | B      | Selezi |        |
|        | zament |        | AMENTO | di     |        | onare  |        |
|        | o      |        |  <#ava | valori |        | un     |        |
|        | raggiu |        | nzamen | da     |        | valore |        |
|        | nto,   |        | to>`__ | elenco |        | tra    |        |
|        | rispet |        |        | Valore |        | quelli |        |
|        | to     |        |        | di     |        | previs |        |
|        | al     |        |        | defaul |        | ti     |        |
|        | cronop |        |        | t:     |        |        |        |
|        | rogram |        |        | Blank  |        |        |        |
|        | ma     |        |        |        |        |        |        |
|        | di     |        |        |        |        |        |        |
|        | previs |        |        |        |        |        |        |
|        | ione   |        |        |        |        |        |        |
|        | regist |        |        |        |        |        |        |
|        | ra     |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 12     | Indica | OIF    | NUMERI | | Camp | B      | Inseri |        |
|        | re     |        | CO     | o      |        | re     |        |
|        | lo     |        |        |   obbl | B      | i      |        |
|        | scosta |        |        | igator |        | giorni |        |
|        | mento  |        |        | io     | W      | di     |        |
|        | regist |        |        |   se   |        | scosta |        |
|        | rato   |        |        |   S02. |        | mento  |        |
|        | in     |        |        | 07     |        |        |        |
|        | numero |        |        |   =    |        | Digita |        |
|        | di     |        |        |   “LAV |        | re     |        |
|        | giorni |        |        | ORI”   |        | solo   |        |
|        |        |        |        |   e    |        | numeri |        |
|        |        |        |        |   camp |        | senza  |        |
|        |        |        |        | o      |        | segni  |        |
|        |        |        |        |   S13. |        | di     |        |
|        |        |        |        | 11     |        | interp |        |
|        |        |        |        |   vale |        | unzion |        |
|        |        |        |        |   10 o |        | e      |        |
|        |        |        |        |   11   |        |        |        |
|        |        |        |        | | Se   |        | Verifi |        |
|        |        |        |        |   valo |        | care   |        |
|        |        |        |        | rizzat |        | numero |        |
|        |        |        |        | o      |        | di     |        |
|        |        |        |        |   Deve |        | giorni |        |
|        |        |        |        |   esse |        | di     |        |
|        |        |        |        | re     |        | scosta |        |
|        |        |        |        |   un   |        | mento  |        |
|        |        |        |        |   camp |        |        |        |
|        |        |        |        | o      |        |        |        |
|        |        |        |        |   nume |        |        |        |
|        |        |        |        | rico   |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Se il  |        |        |        |
|        |        |        |        | valore |        |        |        |
|        |        |        |        | risult |        |        |        |
|        |        |        |        | a      |        |        |        |
|        |        |        |        | > 99   |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 13     | Indica |        | NUMERI | Se     | B      | Digita |        |
|        | re     |        | CO     | valori |        | re     |        |
|        | il     |        |        | zzato  | W      | solo   |        |
|        | numero |        |        | deve   |        | numeri |        |
|        | di     |        |        | essere |        | senza  |        |
|        | giorni |        |        | un     |        | segni  |        |
|        | di     |        |        | campo  |        | di     |        |
|        | prorog |        |        | numeri |        | interp |        |
|        | a      |        |        | co     |        | unzion |        |
|        | conces |        |        |        |        | e      |        |
|        | si     |        |        | Se il  |        |        |        |
|        | (non   |        |        | valore |        | Verifi |        |
|        | conseg |        |        | risult |        | care   |        |
|        | uenti  |        |        | a      |        | numero |        |
|        | a      |        |        | > 99   |        | di     |        |
|        | varian |        |        |        |        | giorni |        |
|        | ti)    |        |        |        |        | di     |        |
|        |        |        |        |        |        | prorog |        |
|        |        |        |        |        |        | a      |        |
+--------+--------+--------+--------+--------+--------+--------+--------+

14. .. rubric::  E05 - Fase di conclusione del contratto (rif. 15)
       :name: e05---fase-di-conclusione-del-contratto-rif.-15

    2. .. rubric:: S14 – Conclusione
          :name: s14-conclusione

+---------+---------+---------+---------+---------+---------+---------+
| **S14 – |         |         |         |         |         |         |
| Conclus |         |         |         |         |         |         |
| ione**  |         |         |         |         |         |         |
+=========+=========+=========+=========+=========+=========+=========+
| COD     | ETICHET | TIPO    | FORMATO | CONTROL | MESSAGG |         |
|         | TA      |         |         | LO      | IO      |         |
+---------+---------+---------+---------+---------+---------+---------+
|         |         |         |         | DESCRIZ | TIPO    |         |
|         |         |         |         | IONE    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **RIFER |         |         |         |         |         |         |
| IMENTO  |         |         |         |         |         |         |
| AI DATI |         |         |         |         |         |         |
| DELLA   |         |         |         |         |         |         |
| FASE DI |         |         |         |         |         |         |
| AGGIUDI |         |         |         |         |         |         |
| CAZIONE |         |         |         |         |         |         |
| O DI    |         |         |         |         |         |         |
| DEFINIZ |         |         |         |         |         |         |
| IONE    |         |         |         |         |         |         |
| DI      |         |         |         |         |         |         |
| PROCEDU |         |         |         |         |         |         |
| RA      |         |         |         |         |         |         |
| NEGOZIA |         |         |         |         |         |         |
| TA**    |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 01      | Codice  | R       | STRINGA | Il CIG  | B       | CIG     |
|         | di      |         |         | deve    |         | inesist |
|         | individ |         |         | essere  |         | ente    |
|         | uazione |         |         | esisten |         | o non   |
|         | dell’ap |         |         | te      |         | di      |
|         | palto   |         |         | ed in   |         | compete |
|         | CIG     |         |         | carico  |         | nza     |
|         |         |         |         | all’amm |         |         |
|         |         |         |         | inistra |         |         |
|         |         |         |         | zione   |         |         |
|         |         |         |         | di      |         |         |
|         |         |         |         | apparte |         |         |
|         |         |         |         | nenza   |         |         |
|         |         |         |         | del RUP |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **INTER |         |         |         |         |         |         |
| RUZIONE |         |         |         |         |         |         |
| ANTICIP |         |         |         |         |         |         |
| ATA     |         |         |         |         |         |         |
| DEL     |         |         |         |         |         |         |
| PROCEDI |         |         |         |         |         |         |
| MENTO** |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 02      | Causa   |         | `MOTIVI | Lista   |         |         |
|         | dell'   |         | _INTERR | di      |         |         |
|         | interru |         | UZIONE  | valori  |         |         |
|         | zione   |         | <#motiv | da      |         |         |
|         | anticip |         | i_inter | elenco  |         |         |
|         | ata     |         | ruzione | Valore  |         |         |
|         |         |         | >`__    | di      |         |         |
|         |         |         |         | default |         |         |
|         |         |         |         | :       |         |         |
|         |         |         |         | Blank   |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 03      | Motivaz | OIF     | `MOTIVI | Obbliga | B       | Campo   |
|         | ione    |         | _RISOLU | torio   |         | obbliga |
|         | della   |         | ZIONE < | se      |         | torio   |
|         | risoluz |         | #motivi | campo   |         |         |
|         | ione    |         | _risolu | S14.02  |         | Selezio |
|         | (in     |         | zione>` | = 2     |         | nare    |
|         | caso di |         | __      | Lista   |         | un      |
|         | risoluz |         |         | di      |         | valore  |
|         | ione)   |         |         | valori  |         | tra     |
|         |         |         |         | da      |         | quelli  |
|         |         |         |         | elenco  |         | previst |
|         |         |         |         | Valore  |         | i       |
|         |         |         |         | di      |         |         |
|         |         |         |         | default |         |         |
|         |         |         |         | :       |         |         |
|         |         |         |         | Blank   |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 04.L    | Data    | OIF     | DATA    | Obbliga | B       | Campo   |
|         | interru |         |         | torio   |         | obbliga |
|         | zione   |         |         | se      | B       | torio   |
|         | anticip |         |         | campo   |         |         |
|         | ata     |         |         | S14.02  | B       | Data    |
|         |         |         |         | è       |         | formalm |
|         |         |         |         | valoriz |         | ente    |
|         |         |         |         | zato    |         | non     |
|         |         |         |         |         |         | corrett |
|         |         |         |         | Campo   |         | a       |
|         |         |         |         | data    |         |         |
|         |         |         |         |         |         | Data    |
|         |         |         |         | Se      |         | anteced |
|         |         |         |         | valoriz |         | ente    |
|         |         |         |         | zato    |         | la data |
|         |         |         |         | deve    |         | di      |
|         |         |         |         | essere  |         | aggiudi |
|         |         |         |         | > di    |         | cazione |
|         |         |         |         | campo   |         | ,       |
|         |         |         |         | S08.63  |         | verific |
|         |         |         |         | o al    |         | are     |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S09.16  |         |         |
|         |         |         |         | o al    |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S11.14  |         |         |
|         |         |         |         | in caso |         |         |
|         |         |         |         | di      |         |         |
|         |         |         |         | contrat |         |         |
|         |         |         |         | ti      |         |         |
|         |         |         |         | multilo |         |         |
|         |         |         |         | tto     |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 04.SF   | Data    | OIF     | DATA    | Obbliga | B       | Campo   |
|         | conclus |         |         | torio   |         | obbliga |
|         | ione    |         |         | se      | B       | torio   |
|         | anticip |         |         | campo   |         |         |
|         | ata     |         |         | S14.02  | B       | Data    |
|         |         |         |         |         |         | formalm |
|         |         |         |         | è       |         | ente    |
|         |         |         |         | valoriz |         | non     |
|         |         |         |         | zato    |         | corrett |
|         |         |         |         |         |         | a       |
|         |         |         |         | Campo   |         |         |
|         |         |         |         | data    |         | Data    |
|         |         |         |         |         |         | anteced |
|         |         |         |         | Se      |         | ente    |
|         |         |         |         | valoriz |         | la data |
|         |         |         |         | zato    |         | di      |
|         |         |         |         | deve    |         | aggiudi |
|         |         |         |         | essere  |         | cazione |
|         |         |         |         | > di    |         | ,       |
|         |         |         |         | campo   |         | verific |
|         |         |         |         | S08.63  |         | are     |
|         |         |         |         | o al    |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S09.16  |         |         |
|         |         |         |         | o al    |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S11.14  |         |         |
|         |         |         |         | in caso |         |         |
|         |         |         |         | di      |         |         |
|         |         |         |         | contrat |         |         |
|         |         |         |         | ti      |         |         |
|         |         |         |         | multilo |         |         |
|         |         |         |         | tto     |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 05      | Oneri   | OIF     | `ONERI_ | Obbliga | B       | Campo   |
|         | economi |         | ECONOMI | torio   |         | obbliga |
|         | ci      |         | CI_RISO | se      |         | torio   |
|         | derivan |         | LUZIONE | campo   |         |         |
|         | ti      |         | _RECESE | S14.02  |         | Selezio |
|         | dalla   |         | SSO <#o | = 2, 4  |         | nare    |
|         | risoluz |         | neri_ec | o 5     |         | un      |
|         | ione/re |         | onomici | vale    |         | valore  |
|         | cesso   |         | _risolu | “Risolu |         | tra     |
|         |         |         | zione_r | zione”  |         | quelli  |
|         |         |         | ecesess | o       |         | previst |
|         |         |         | o>`__   | “Recess |         | i       |
|         |         |         |         | o”      |         |         |
|         |         |         |         |         |         |         |
|         |         |         |         | | Lista |         |         |
|         |         |         |         |   di    |         |         |
|         |         |         |         |   valor |         |         |
|         |         |         |         | i       |         |         |
|         |         |         |         |   da    |         |         |
|         |         |         |         |   elenc |         |         |
|         |         |         |         | o       |         |         |
|         |         |         |         | | Valor |         |         |
|         |         |         |         | e       |         |         |
|         |         |         |         |   di    |         |         |
|         |         |         |         |   defau |         |         |
|         |         |         |         | lt:     |         |         |
|         |         |         |         |   Blank |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 06      | Importo | OIF     | IMPORTO | Obbliga | B       | Inserir |
|         |         |         |         | torio   |         | e       |
|         |         |         |         | se      | B       | solo    |
|         |         |         |         | campo   |         | numeri  |
|         |         |         |         | S14.05  | B       |         |
|         |         |         |         | è       |         | Valore  |
|         |         |         |         | valoriz | B       | elevato |
|         |         |         |         | zato    |         | ,       |
|         |         |         |         |         |         | verific |
|         |         |         |         | Deve    |         | are     |
|         |         |         |         | essere  |         |         |
|         |         |         |         | un      |         | Inserir |
|         |         |         |         | campo   |         | e       |
|         |         |         |         | valuta  |         | importo |
|         |         |         |         |         |         | oneri   |
|         |         |         |         | Il      |         | economi |
|         |         |         |         | valore  |         | ci      |
|         |         |         |         | immesso |         |         |
|         |         |         |         | deve    |         | Risoluz |
|         |         |         |         | essere  |         | ione/re |
|         |         |         |         | < di    |         | scissio |
|         |         |         |         | campo   |         | ne      |
|         |         |         |         | S08.28  |         | senza   |
|         |         |         |         | o al    |         | oneri!  |
|         |         |         |         | campo   |         | Verific |
|         |         |         |         | S09.12  |         | are.    |
|         |         |         |         |         |         |         |
|         |         |         |         | Valore  |         |         |
|         |         |         |         | ammesso |         |         |
|         |         |         |         | = 0     |         |         |
|         |         |         |         | solo se |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S14.05  |         |         |
|         |         |         |         | = 0     |         |         |
|         |         |         |         |         |         |         |
|         |         |         |         | Se il   |         |         |
|         |         |         |         | valore  |         |         |
|         |         |         |         | > 0 e   |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S14.05  |         |         |
|         |         |         |         | = 0     |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 07      | Incamer | OIF     | FLAG    | | Vale  | B       | Selezio |
|         | ata     |         |         |   SI/NO |         | nare    |
|         | polizza |         |         | | Valor |         | un      |
|         |         |         |         | e       |         | valore  |
|         |         |         |         |   di    |         | tra     |
|         |         |         |         |   defau |         | quelli  |
|         |         |         |         | lt:     |         | previst |
|         |         |         |         |   Blank |         | i       |
|         |         |         |         |         |         |         |
|         |         |         |         | Se non  |         |         |
|         |         |         |         | valoriz |         |         |
|         |         |         |         | zato    |         |         |
|         |         |         |         | e campo |         |         |
|         |         |         |         | S14.02  |         |         |
|         |         |         |         | è       |         |         |
|         |         |         |         | valoriz |         |         |
|         |         |         |         | zato    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **ULIMA |         |         |         |         |         |         |
| ZIONE   |         |         |         |         |         |         |
| DELLE   |         |         |         |         |         |         |
| PRESTAZ |         |         |         |         |         |         |
| IONI**  |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 08.L    | Data    | P       | DATA    | Campo   | B       | inserir |
|         | verbale |         |         | precomp |         | e       |
|         | consegn |         |         | ilato   |         | la data |
|         | a       |         |         | con il  |         | verbale |
|         | definit |         |         | campo   |         | consegn |
|         | iva     |         |         | S11.32. |         | a       |
|         |         |         |         | L       |         | definit |
|         |         |         |         |         |         | iva     |
|         |         |         |         | Se i    |         |         |
|         |         |         |         | campi   |         |         |
|         |         |         |         | S14.02  |         |         |
|         |         |         |         | e       |         |         |
|         |         |         |         | S14.08. |         |         |
|         |         |         |         | L       |         |         |
|         |         |         |         | non     |         |         |
|         |         |         |         | sono    |         |         |
|         |         |         |         | valoriz |         |         |
|         |         |         |         | zati    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 08.SF   | Data    | P       | DATA    | Campo   | B       | inserir |
|         | verbale |         |         | precomp |         | e       |
|         | di      |         |         | ilato   |         | la data |
|         | avvio   |         |         | con il  |         | verbale |
|         | dell'es |         |         | campo   |         | consegn |
|         | ecuzion |         |         | S11.32. |         | a       |
|         | e       |         |         | SF      |         | definit |
|         | del     |         |         |         |         | iva     |
|         | contrat |         |         | Se i    |         |         |
|         | to      |         |         | campi   |         |         |
|         |         |         |         | S14.02  |         |         |
|         |         |         |         | e       |         |         |
|         |         |         |         | S14.08. |         |         |
|         |         |         |         | SF      |         |         |
|         |         |         |         | non     |         |         |
|         |         |         |         | sono    |         |         |
|         |         |         |         | valoriz |         |         |
|         |         |         |         | zati    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 09      | Termine | P       | DATA    | Campo   | B       | inserir |
|         | contrat |         |         | precomp |         | e       |
|         | tuale   |         |         | ilato   |         | il      |
|         | ultimaz |         |         | con il  |         | termine |
|         | ione    |         |         | campo   |         | contrat |
|         | lavori/ |         |         | S11.35  |         | tuale   |
|         | seriviz |         |         |         |         | ultimaz |
|         | i/forni |         |         | Se i    |         | ione    |
|         | ture    |         |         | campi   |         | lavori/ |
|         |         |         |         | S14.02  |         | servizi |
|         |         |         |         | e       |         | /fornit |
|         |         |         |         | S14.09  |         | ure     |
|         |         |         |         | non     |         |         |
|         |         |         |         | sono    |         |         |
|         |         |         |         | valoriz |         |         |
|         |         |         |         | zati    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 10.L    | Data    | O       | DATA    | Se non  | B       | Non è   |
|         | ultimaz |         |         | valoriz |         | stata   |
|         | ione    |         |         | zato    | B       | indicat |
|         | Lavoro  |         |         | e campo |         | a       |
|         |         |         |         | S14.04  | B       | la data |
|         |         |         |         | non     |         | di      |
|         |         |         |         | valoriz |         | ultimaz |
|         |         |         |         | zato    |         | ione    |
|         |         |         |         |         |         |         |
|         |         |         |         | Se      |         | Data    |
|         |         |         |         | valoriz |         | formalm |
|         |         |         |         | zato    |         | ente    |
|         |         |         |         | deve    |         | non     |
|         |         |         |         | essere  |         | corrett |
|         |         |         |         | una     |         | a       |
|         |         |         |         | data    |         |         |
|         |         |         |         | valida  |         | Data    |
|         |         |         |         |         |         | precede |
|         |         |         |         | Se      |         | nte     |
|         |         |         |         | valoriz |         | alla    |
|         |         |         |         | zato    |         | data di |
|         |         |         |         | deve    |         | Aggiudi |
|         |         |         |         | essere  |         | cazione |
|         |         |         |         | > di    |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S08.63  |         |         |
|         |         |         |         | o al    |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S09.16  |         |         |
|         |         |         |         | o al    |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S11.14  |         |         |
|         |         |         |         | in caso |         |         |
|         |         |         |         | di      |         |         |
|         |         |         |         | contrat |         |         |
|         |         |         |         | ti      |         |         |
|         |         |         |         | multilo |         |         |
|         |         |         |         | tto     |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 10.SF   | Data    | O       | DATA    | Se non  | B       | Non è   |
|         | ultimaz |         |         | valoriz |         | stata   |
|         | ione    |         |         | zato    | B       | indicat |
|         | Fornitu |         |         | e campo |         | a       |
|         | ra      |         |         | S14.04  | B       | la data |
|         | (Data   |         |         | non     |         | di      |
|         | ultimaz |         |         | valoriz |         | ultimaz |
|         | ione    |         |         | zato    |         | ione    |
|         | prestaz |         |         |         |         | delle   |
|         | ioni)   |         |         | Se      |         | prestaz |
|         |         |         |         | valoriz |         | ioni    |
|         |         |         |         | zato    |         |         |
|         |         |         |         | deve    |         | Data    |
|         |         |         |         | essere  |         | formalm |
|         |         |         |         | una     |         | ente    |
|         |         |         |         | data    |         | non     |
|         |         |         |         | valida  |         | corrett |
|         |         |         |         |         |         | a       |
|         |         |         |         | Se      |         |         |
|         |         |         |         | valoriz |         | Data    |
|         |         |         |         | zato    |         | anteced |
|         |         |         |         | deve    |         | ente    |
|         |         |         |         | essere  |         | la data |
|         |         |         |         | > di    |         | di      |
|         |         |         |         | campo   |         | aggiudi |
|         |         |         |         | S08.63  |         | cazione |
|         |         |         |         | o al    |         | ,       |
|         |         |         |         | campo   |         | verific |
|         |         |         |         | S09.16  |         | are     |
|         |         |         |         | o al    |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S11.14  |         |         |
|         |         |         |         | in caso |         |         |
|         |         |         |         | di      |         |         |
|         |         |         |         | contrat |         |         |
|         |         |         |         | ti      |         |         |
|         |         |         |         | multilo |         |         |
|         |         |         |         | tto     |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 11      | Numero  |         | NUMERIC | Deve    | B       | Digitar |
|         | infortu |         | O       | essere  |         | e       |
|         | ni      |         |         | un      | W       | solo    |
|         |         |         |         | campo   |         | numeri  |
|         |         |         |         | numeric | B       | senza   |
|         |         |         |         | o       |         | segni   |
|         |         |         |         | Valore  |         | di      |
|         |         |         |         | di      |         | interpu |
|         |         |         |         | default |         | nzione  |
|         |         |         |         | = 0     |         |         |
|         |         |         |         |         |         | Verific |
|         |         |         |         | | Se il |         | are     |
|         |         |         |         |   valor |         | numero  |
|         |         |         |         | e       |         | di      |
|         |         |         |         |   risul |         | infortu |
|         |         |         |         | ta      |         | ni      |
|         |         |         |         |   > 9   |         |         |
|         |         |         |         | | Se <  |         | Numero  |
|         |         |         |         |   S14.1 |         | totale  |
|         |         |         |         | 2       |         | degli   |
|         |         |         |         |   +     |         | infortu |
|         |         |         |         |   S14.1 |         | ni      |
|         |         |         |         | 3       |         | incoere |
|         |         |         |         |         |         | nte     |
|         |         |         |         |         |         | rispett |
|         |         |         |         |         |         | o       |
|         |         |         |         |         |         | al      |
|         |         |         |         |         |         | numero  |
|         |         |         |         |         |         | degli   |
|         |         |         |         |         |         | infortu |
|         |         |         |         |         |         | ni      |
|         |         |         |         |         |         | mortali |
|         |         |         |         |         |         | e con   |
|         |         |         |         |         |         | postumi |
|         |         |         |         |         |         | permane |
|         |         |         |         |         |         | nti     |
+---------+---------+---------+---------+---------+---------+---------+
| 12      | di cui  |         | NUMERIC | Deve    | B       | Digitar |
|         | con     |         | O       | essere  |         | e       |
|         | postumi |         |         | un      |         | solo    |
|         | permane |         |         | campo   |         | numeri  |
|         | nti     |         |         | numeric |         | senza   |
|         |         |         |         | o       |         | segni   |
|         |         |         |         | >=0     |         | di      |
|         |         |         |         |         |         | interpu |
|         |         |         |         |         |         | nzione  |
+---------+---------+---------+---------+---------+---------+---------+
| 13      | di cui  |         | NUMERIC | Deve    | B       | Digitar |
|         | mortali |         | O       | essere  |         | e       |
|         |         |         |         | un      |         | solo    |
|         |         |         |         | campo   |         | numeri  |
|         |         |         |         | numeric |         | senza   |
|         |         |         |         | o       |         | segni   |
|         |         |         |         | >=0     |         | di      |
|         |         |         |         |         |         | interpu |
|         |         |         |         |         |         | nzione  |
+---------+---------+---------+---------+---------+---------+---------+
| 14      | Indicar | P       | NUMERIC | Il      | B       | Digitar |
|         | e       |         | O       | campo è |         | e       |
|         | il      |         |         | precomp | W       | solo    |
|         | numero  |         |         | ilato   |         | numeri  |
|         | di      |         |         | con la  |         | senza   |
|         | giorni  |         |         | somma   |         | segni   |
|         | di      |         |         | dei     |         | di      |
|         | proroga |         |         | giorni  |         | interpu |
|         | concess |         |         | indicat |         | nzione  |
|         | i       |         |         | i       |         |         |
|         | (non    |         |         | nel     |         | Verific |
|         | consegu |         |         | campo   |         | are     |
|         | enti    |         |         | S13.13  |         | numero  |
|         | a       |         |         | oppure  |         | di      |
|         | variant |         |         | con 0   |         | giorni  |
|         | i)      |         |         |         |         | di      |
|         |         |         |         | Se      |         | proroga |
|         |         |         |         | valoriz |         |         |
|         |         |         |         | zato    |         |         |
|         |         |         |         | deve    |         |         |
|         |         |         |         | essere  |         |         |
|         |         |         |         | un      |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | numeric |         |         |
|         |         |         |         | o       |         |         |
|         |         |         |         | >= 0    |         |         |
|         |         |         |         |         |         |         |
|         |         |         |         | Se il   |         |         |
|         |         |         |         | valore  |         |         |
|         |         |         |         | risulta |         |         |
|         |         |         |         | > 99    |         |         |
+---------+---------+---------+---------+---------+---------+---------+

15. .. rubric::  E06 - Fase di collaudo (rif. 16)
       :name: e06---fase-di-collaudo-rif.-16

    3. .. rubric:: S15 – Collaudo
          :name: s15-collaudo

+--------+--------+--------+--------+--------+--------+--------+--------+
| **S15  |        |        |        |        |        |        |        |
| –      |        |        |        |        |        |        |        |
| Collau |        |        |        |        |        |        |        |
| do**   |        |        |        |        |        |        |        |
+========+========+========+========+========+========+========+========+
| COD    | ETICHE | TIPO   | FORMAT | CONTRO | MESSAG |        |        |
|        | TTA    |        | O      | LLO    | GIO    |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
|        |        |        |        | DESCRI | TIPO   |        |        |
|        |        |        |        | ZIONE  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **RIFE |        |        |        |        |        |        |        |
| RIMENT |        |        |        |        |        |        |        |
| O      |        |        |        |        |        |        |        |
| AI     |        |        |        |        |        |        |        |
| DATI   |        |        |        |        |        |        |        |
| DELLA  |        |        |        |        |        |        |        |
| FASE   |        |        |        |        |        |        |        |
| DI     |        |        |        |        |        |        |        |
| AGGIUD |        |        |        |        |        |        |        |
| ICAZIO |        |        |        |        |        |        |        |
| NE     |        |        |        |        |        |        |        |
| O DI   |        |        |        |        |        |        |        |
| DEFINI |        |        |        |        |        |        |        |
| ZIONE  |        |        |        |        |        |        |        |
| DI     |        |        |        |        |        |        |        |
| PROCED |        |        |        |        |        |        |        |
| URA    |        |        |        |        |        |        |        |
| NEGOZI |        |        |        |        |        |        |        |
| ATA**  |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 01     | Codice | R      | STRING | Il CIG | B      | CIG    |        |
|        | di     |        | A      | deve   |        | inesis |        |
|        | indivi |        |        | essere |        | tente  |        |
|        | duazio |        |        | esiste |        | o non  |        |
|        | ne     |        |        | nte    |        | di     |        |
|        | dell’a |        |        | ed in  |        | compet |        |
|        | ppalto |        |        | carico |        | enza   |        |
|        | CIG    |        |        | all’am |        |        |        |
|        |        |        |        | minist |        |        |        |
|        |        |        |        | razion |        |        |        |
|        |        |        |        | e      |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | appart |        |        |        |
|        |        |        |        | enenza |        |        |        |
|        |        |        |        | del    |        |        |        |
|        |        |        |        | RUP    |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **COLL |        |        |        |        |        |        |        |
| AUDO/V |        |        |        |        |        |        |        |
| ERIFIC |        |        |        |        |        |        |        |
| A      |        |        |        |        |        |        |        |
| DI     |        |        |        |        |        |        |        |
| CONFOR |        |        |        |        |        |        |        |
| MITA’  |        |        |        |        |        |        |        |
| DELLE  |        |        |        |        |        |        |        |
| PRESTA |        |        |        |        |        |        |        |
| ZIONI  |        |        |        |        |        |        |        |
| ESEGUI |        |        |        |        |        |        |        |
| TE     |        |        |        |        |        |        |        |
| o      |        |        |        |        |        |        |        |
| ESITI  |        |        |        |        |        |        |        |
| DI     |        |        |        |        |        |        |        |
| ACCERT |        |        |        |        |        |        |        |
| AMENTO |        |        |        |        |        |        |        |
| TECNIC |        |        |        |        |        |        |        |
| O-CONT |        |        |        |        |        |        |        |
| ABILE* |        |        |        |        |        |        |        |
| *      |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 02     | Data   |        | DATA   | Se     | B      | Data   |        |
|        | del    |        |        | valori |        | formal |        |
|        | collau |        |        | zzato  | B      | mente  |        |
|        | do     |        |        | deve   |        | non    |        |
|        | static |        |        | essere |        | corret |        |
|        | o      |        |        | una    |        | ta     |        |
|        | (ove   |        |        | data   |        |        |        |
|        | ricorr |        |        | valida |        | Data   |        |
|        | a)     |        |        |        |        | antece |        |
|        |        |        |        | Se     |        | dente  |        |
|        |        |        |        | valori |        | la     |        |
|        |        |        |        | zzato  |        | data   |        |
|        |        |        |        | deve   |        | di     |        |
|        |        |        |        | essere |        | effett |        |
|        |        |        |        | > di   |        | ivo    |        |
|        |        |        |        | campo  |        | inizio |        |
|        |        |        |        | S11.34 |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 03     | Se     | OIF    | DATA   | Se non | B      | Specif |        |
|        | S02.07 |        |        | valori |        | icare  |        |
|        | = L    |        |        | zzato  | B      | data   |        |
|        |        |        |        | e      |        | del    |        |
|        | “Data  |        |        | campo  | B      | certif |        |
|        | del    |        |        | S15.04 |        | icato  |        |
|        | certif |        |        | non    | B      | di     |        |
|        | icato  |        |        | valori |        | regola |        |
|        | di     |        |        | zzato  | W      | re     |        |
|        | regola |        |        |        |        | esecuz |        |
|        | re     |        |        | Se     | W      | ione   |        |
|        | esecuz |        |        | valori |        | o le   |        |
|        | ione”  |        |        | zzato  | W      | modali |        |
|        |        |        |        | e      |        | tà     |        |
|        | Se     |        |        | campo  |        | del    |        |
|        | S02.07 |        |        | S15.04 |        | collau |        |
|        | = S o  |        |        | valori |        | do     |        |
|        | F      |        |        | zzato  |        | tecnic |        |
|        |        |        |        |        |        | o      |        |
|        | “Data  |        |        | Se     |        | ammini |        |
|        | dell’a |        |        | valori |        | strati |        |
|        | ttesta |        |        | zzato  |        | vo     |        |
|        | to     |        |        | deve   |        |        |        |
|        | di     |        |        | essere |        | Certif |        |
|        | regola |        |        | una    |        | icato  |        |
|        | re     |        |        | data   |        | di     |        |
|        | esecuz |        |        | valida |        | regola |        |
|        | ione”  |        |        |        |        | re     |        |
|        |        |        |        | Se     |        | esecuz |        |
|        |        |        |        | valori |        | ione   |        |
|        |        |        |        | zzato  |        | non    |        |
|        |        |        |        | deve   |        | previs |        |
|        |        |        |        | essere |        | to     |        |
|        |        |        |        | >=     |        | in     |        |
|        |        |        |        | S14.10 |        | caso   |        |
|        |        |        |        | .L     |        | di     |        |
|        |        |        |        | oppure |        | collau |        |
|        |        |        |        | >=     |        | do     |        |
|        |        |        |        | S14.10 |        | tecnic |        |
|        |        |        |        | .SF    |        | o/ammi |        |
|        |        |        |        |        |        | nistra |        |
|        |        |        |        | se     |        | tivo   |        |
|        |        |        |        | valori |        |        |        |
|        |        |        |        | zzato  |        | Data   |        |
|        |        |        |        | e      |        | del    |        |
|        |        |        |        | valore |        | certif |        |
|        |        |        |        | di     |        | icato  |        |
|        |        |        |        | campo  |        | di     |        |
|        |        |        |        | S08.28 |        | regola |        |
|        |        |        |        | >      |        | re     |        |
|        |        |        |        | 1.000. |        | esecuz |        |
|        |        |        |        | 000    |        | ione   |        |
|        |        |        |        | € e    |        | non    |        |
|        |        |        |        | S02.07 |        | valida |        |
|        |        |        |        | =      |        |        |        |
|        |        |        |        | “LAVOR |        | Data   |        |
|        |        |        |        | I”     |        | antece |        |
|        |        |        |        |        |        | dente  |        |
|        |        |        |        | se     |        | la     |        |
|        |        |        |        | valori |        | data   |        |
|        |        |        |        | zzato  |        | di     |        |
|        |        |        |        | e il   |        | ultima |        |
|        |        |        |        | valore |        | zione  |        |
|        |        |        |        | del    |        |        |        |
|        |        |        |        | campo  |        | Previs |        |
|        |        |        |        | S09.12 |        | to     |        |
|        |        |        |        | >      |        | certif |        |
|        |        |        |        | 1.000. |        | icato  |        |
|        |        |        |        | 000    |        | di     |        |
|        |        |        |        | € e    |        | collau |        |
|        |        |        |        | S02.07 |        | do     |        |
|        |        |        |        | =      |        |        |        |
|        |        |        |        | “LAVOR |        | Previs |        |
|        |        |        |        | I”     |        | to     |        |
|        |        |        |        |        |        | certif |        |
|        |        |        |        | se     |        | icato  |        |
|        |        |        |        | valori |        | di     |        |
|        |        |        |        | zzato  |        | collau |        |
|        |        |        |        | e il   |        | do     |        |
|        |        |        |        | contra |        |        |        |
|        |        |        |        | tto    |        | Previs |        |
|        |        |        |        | è      |        | to     |        |
|        |        |        |        | multil |        | certif |        |
|        |        |        |        | otto   |        | icato  |        |
|        |        |        |        | ed il  |        | di     |        |
|        |        |        |        | valore |        | collau |        |
|        |        |        |        | del    |        | do     |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S11.11 |        |        |        |
|        |        |        |        | >      |        |        |        |
|        |        |        |        | 1.000. |        |        |        |
|        |        |        |        | 000    |        |        |        |
|        |        |        |        | € e    |        |        |        |
|        |        |        |        | S02.07 |        |        |        |
|        |        |        |        | =      |        |        |        |
|        |        |        |        | “LAVOR |        |        |        |
|        |        |        |        | I”     |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 04     | Se     | OIF    | `MODO_ | | List | B      | Specif |        |
|        | S02.07 |        | COLLAU | a      |        | icare  |        |
|        | = L    |        | DO <#m |   di   | B      | data   |        |
|        |        |        | odo_co |   valo |        | del    |        |
|        | “Modal |        | llaudo | ri     | W      | certif |        |
|        | ità    |        | >`__   |   da   |        | icato  |        |
|        | del    |        |        |   elen | W      | di     |        |
|        | collau |        |        | co     |        | regola |        |
|        | do     |        |        |   (sel |        | re     |        |
|        | tecnic |        |        | ezione |        | esecuz |        |
|        | o/ammi |        |        |   sing |        | ione   |        |
|        | nistra |        |        | ola)   |        | o le   |        |
|        | tivo”  |        |        | | Valo |        | modali |        |
|        |        |        |        | re     |        | tà     |        |
|        | Se     |        |        |   di   |        | del    |        |
|        | S02.07 |        |        |   defa |        | collau |        |
|        | = S o  |        |        | ult:   |        | do     |        |
|        | F      |        |        |   Blan |        | tecnic |        |
|        |        |        |        | k      |        | o      |        |
|        | “Modal |        |        |        |        | ammini |        |
|        | ità    |        |        | Se non |        | strati |        |
|        | di     |        |        | valori |        | vo     |        |
|        | collau |        |        | zzato  |        |        |        |
|        | do     |        |        | e      |        | Collau |        |
|        | /verif |        |        | campo  |        | do     |        |
|        | ica    |        |        | S15.03 |        | tecnic |        |
|        | di     |        |        | non    |        | o-ammi |        |
|        | confor |        |        | valori |        | nistra |        |
|        | mità”  |        |        | zzato  |        | tivo   |        |
|        |        |        |        |        |        | non    |        |
|        |        |        |        | Se     |        | previs |        |
|        |        |        |        | valori |        | to     |        |
|        |        |        |        | zzato  |        | in     |        |
|        |        |        |        | e      |        | presen |        |
|        |        |        |        | campo  |        | za     |        |
|        |        |        |        | S15.03 |        | di     |        |
|        |        |        |        | valori |        | certif |        |
|        |        |        |        | zzato  |        | icazio |        |
|        |        |        |        |        |        | ne     |        |
|        |        |        |        | se     |        | di     |        |
|        |        |        |        | valori |        | regola |        |
|        |        |        |        | zzato  |        | re     |        |
|        |        |        |        | e      |        | esecuz |        |
|        |        |        |        | valore |        | ione   |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | campo  |        | Redige |        |
|        |        |        |        | S08.28 |        | re     |        |
|        |        |        |        | <=     |        | certif |        |
|        |        |        |        | 500.00 |        | icato  |        |
|        |        |        |        | 0      |        | regola |        |
|        |        |        |        | € e    |        | re     |        |
|        |        |        |        | S02.07 |        | di     |        |
|        |        |        |        | =      |        | esecuz |        |
|        |        |        |        | “LAVOR |        | ione   |        |
|        |        |        |        | I”     |        | in     |        |
|        |        |        |        |        |        | luogo  |        |
|        |        |        |        | se     |        | del    |        |
|        |        |        |        | valori |        | certif |        |
|        |        |        |        | zzato  |        | icato  |        |
|        |        |        |        | e il   |        | di     |        |
|        |        |        |        | valore |        | collau |        |
|        |        |        |        | del    |        | do     |        |
|        |        |        |        | campo  |        | per    |        |
|        |        |        |        | S09.12 |        | somme  |        |
|        |        |        |        | >      |        | inferi |        |
|        |        |        |        | 1.000. |        | ori    |        |
|        |        |        |        | 000    |        | a      |        |
|        |        |        |        | € e    |        | 500.00 |        |
|        |        |        |        | S02.07 |        | 0      |        |
|        |        |        |        | =      |        | euro   |        |
|        |        |        |        | “LAVOR |        |        |        |
|        |        |        |        | I”     |        | Previs |        |
|        |        |        |        |        |        | to     |        |
|        |        |        |        |        |        | certif |        |
|        |        |        |        |        |        | icato  |        |
|        |        |        |        |        |        | di     |        |
|        |        |        |        |        |        | regola |        |
|        |        |        |        |        |        | re     |        |
|        |        |        |        |        |        | esecuz |        |
|        |        |        |        |        |        | ione   |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 05     | Data   | OIF    | DATA   | Se non | B      | Non è  |        |
|        | nomina |        |        | valori |        | stata  |        |
|        | collau |        |        | zzato  | B      | indica |        |
|        | datore |        |        | e      |        | ta     |        |
|        | /Commi |        |        | campo  |        | la     |        |
|        | ssione |        |        | S15.04 |        | data   |        |
|        |        |        |        | valori |        | di     |        |
|        |        |        |        | zzato  |        | nomina |        |
|        |        |        |        |        |        | del    |        |
|        |        |        |        | Se     |        | collau |        |
|        |        |        |        | valori |        | datore |        |
|        |        |        |        | zzato  |        | /      |        |
|        |        |        |        | deve   |        | Commis |        |
|        |        |        |        | essere |        | sione  |        |
|        |        |        |        | una    |        |        |        |
|        |        |        |        | data   |        | Data   |        |
|        |        |        |        | formal |        | di     |        |
|        |        |        |        | mente  |        | nomina |        |
|        |        |        |        | valida |        | del    |        |
|        |        |        |        |        |        | collau |        |
|        |        |        |        |        |        | datore |        |
|        |        |        |        |        |        | /commi |        |
|        |        |        |        |        |        | ssione |        |
|        |        |        |        |        |        | non    |        |
|        |        |        |        |        |        | valida |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 06     | Data   | OIF    | DATA   | Se non | B      | Non è  |        |
|        | inizio |        |        | valori |        | stata  |        |
|        | operaz |        |        | zzato  | B      | indica |        |
|        | ioni   |        |        | e      |        | ta     |        |
|        | di     |        |        | campo  | B      | la     |        |
|        | collau |        |        | S15.04 |        | data   |        |
|        | do     |        |        | valori |        | di     |        |
|        |        |        |        | zzato  |        | nomina |        |
|        |        |        |        |        |        | del    |        |
|        |        |        |        | Se     |        | collau |        |
|        |        |        |        | valori |        | datore |        |
|        |        |        |        | zzato  |        | /Commi |        |
|        |        |        |        | deve   |        | ssione |        |
|        |        |        |        | essere |        |        |        |
|        |        |        |        | una    |        | Data   |        |
|        |        |        |        | data   |        | inizio |        |
|        |        |        |        | formal |        | operaz |        |
|        |        |        |        | mente  |        | ioni   |        |
|        |        |        |        | valida |        | di     |        |
|        |        |        |        |        |        | collau |        |
|        |        |        |        | Se     |        | do     |        |
|        |        |        |        | valori |        | non    |        |
|        |        |        |        | zzato  |        | valida |        |
|        |        |        |        | deve   |        |        |        |
|        |        |        |        | essere |        | Data   |        |
|        |        |        |        | >= di  |        | antece |        |
|        |        |        |        | campo  |        | dente  |        |
|        |        |        |        | S15.05 |        | la     |        |
|        |        |        |        |        |        | data   |        |
|        |        |        |        |        |        | di     |        |
|        |        |        |        |        |        | nomina |        |
|        |        |        |        |        |        | della  |        |
|        |        |        |        |        |        | commis |        |
|        |        |        |        |        |        | sione  |        |
|        |        |        |        |        |        | di     |        |
|        |        |        |        |        |        | collau |        |
|        |        |        |        |        |        | do/col |        |
|        |        |        |        |        |        | laudat |        |
|        |        |        |        |        |        | ore    |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 07     | Se     | OIF    | DATA   | Se non | B      | Non è  |        |
|        | S02.07 |        |        | valori |        | stata  |        |
|        | = L    |        |        | zzato  | B      | indica |        |
|        |        |        |        | e      |        | ta     |        |
|        | “Data  |        |        | campo  | B      | la     |        |
|        | redazi |        |        | S15.04 |        | data   |        |
|        | one    |        |        | valori | W      | di     |        |
|        | certif |        |        | zzato  |        | redazi |        |
|        | icato  |        |        |        | W      | one    |        |
|        | di     |        |        | Se     |        | del    |        |
|        | collau |        |        | valori |        | certif |        |
|        | do”    |        |        | zzato  |        | icato  |        |
|        |        |        |        | deve   |        | di     |        |
|        | Se     |        |        | essere |        | collau |        |
|        | S02.07 |        |        | una    |        | do     |        |
|        | = S o  |        |        | data   |        |        |        |
|        | F      |        |        | formal |        | Data   |        |
|        |        |        |        | mente  |        | redazi |        |
|        | “Data  |        |        | valida |        | one    |        |
|        | redazi |        |        |        |        | certif |        |
|        | one    |        |        | Deve   |        | icato  |        |
|        | certif |        |        | essere |        | di     |        |
|        | icato  |        |        | >= di  |        | collau |        |
|        | di     |        |        | campo  |        | do     |        |
|        | collau |        |        | S15.06 |        | non    |        |
|        | do/ver |        |        |        |        | valida |        |
|        | ifica  |        |        | Se     |        |        |        |
|        | di     |        |        | valori |        | | Data |        |
|        | confor |        |        | zzato  |        |   ante |        |
|        | mità”  |        |        | e      |        | cedent |        |
|        |        |        |        | campo  |        | e      |        |
|        |        |        |        | S08.28 |        |   la   |        |
|        |        |        |        | <= €   |        |   data |        |
|        |        |        |        | 500.00 |        |   di   |        |
|        |        |        |        | 0      |        |   iniz |        |
|        |        |        |        | e      |        | io     |        |
|        |        |        |        | S02.07 |        |   oper |        |
|        |        |        |        | =      |        | azioni |        |
|        |        |        |        | “LAVOR |        |   di   |        |
|        |        |        |        | I”     |        |   coll |        |
|        |        |        |        |        |        | audo   |        |
|        |        |        |        | se     |        | | Prev |        |
|        |        |        |        | valori |        | isto   |        |
|        |        |        |        | zzato  |        |   cert |        |
|        |        |        |        | e il   |        | ificat |        |
|        |        |        |        | valore |        | o      |        |
|        |        |        |        | del    |        |   di   |        |
|        |        |        |        | campo  |        |   rego |        |
|        |        |        |        | S09.12 |        | lare   |        |
|        |        |        |        | >      |        |   esec |        |
|        |        |        |        | 1.000. |        | uzione |        |
|        |        |        |        | 000    |        |        |        |
|        |        |        |        | € e    |        | Previs |        |
|        |        |        |        | S02.07 |        | to     |        |
|        |        |        |        | =      |        | certif |        |
|        |        |        |        | “LAVOR |        | icato  |        |
|        |        |        |        | I”     |        | di     |        |
|        |        |        |        |        |        | regola |        |
|        |        |        |        |        |        | re     |        |
|        |        |        |        |        |        | esecuz |        |
|        |        |        |        |        |        | ione   |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 08     | Data   |        | DATA   | Se     | B      | Data   |        |
|        | delibe |        |        | valori |        | delibe |        |
|        | ra     |        |        | zzato  | B      | ra     |        |
|        | di     |        |        | deve   |        | di     |        |
|        | ammiss |        |        | essere |        | ammiss |        |
|        | ibilit |        |        | una    |        | ibilit |        |
|        | à      |        |        | data   |        | à      |        |
|        | del    |        |        | formal |        | del    |        |
|        | collau |        |        | mente  |        | collau |        |
|        | do     |        |        | valida |        | do     |        |
|        | (ove   |        |        |        |        | non    |        |
|        | previs |        |        | Se     |        | valida |        |
|        | ta)    |        |        | valori |        |        |        |
|        |        |        |        | zzato  |        | Data   |        |
|        |        |        |        | deve   |        | antece |        |
|        |        |        |        | essere |        | dente  |        |
|        |        |        |        | >= di  |        | la     |        |
|        |        |        |        | campo  |        | data   |        |
|        |        |        |        | S15.07 |        | di     |        |
|        |        |        |        |        |        | redazi |        |
|        |        |        |        |        |        | one    |        |
|        |        |        |        |        |        | del    |        |
|        |        |        |        |        |        | certif |        |
|        |        |        |        |        |        | icato  |        |
|        |        |        |        |        |        | di     |        |
|        |        |        |        |        |        | collau |        |
|        |        |        |        |        |        | do     |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 09     | Esito  | O      | FLAG   | Lista  | B      | Selezi |        |
|        | del    |        |        | di     |        | onare  |        |
|        | collau |        |        | valori |        | un     |        |
|        | do     |        |        | da     |        | valore |        |
|        | per    |        |        | elenco |        | tra    |        |
|        | serviz |        |        | :      |        | quelli |        |
|        | i      |        |        | Positi |        | previs |        |
|        | :      |        |        | vo/Neg |        | ti     |        |
|        | Esito  |        |        | ativo  |        |        |        |
|        | del    |        |        | Valore |        |        |        |
|        | collau |        |        | di     |        |        |        |
|        | do/    |        |        | defaul |        |        |        |
|        | verifi |        |        | t:     |        |        |        |
|        | ca     |        |        | Blank  |        |        |        |
|        | di     |        |        |        |        |        |        |
|        | confor |        |        |        |        |        |        |
|        | mità   |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 10.L   | Import | O      | IMPORT | Valori | B      | Non è  |        |
|        | o      |        | O      | zzazio |        | stato  |        |
|        | finale |        |        | ne     | B      | indica |        |
|        | compon |        |        | (deve  |        | to     |        |
|        | enti   |        |        | essere |        | l’impo |        |
|        | lavori |        |        | > 0 )  |        | rto    |        |
|        | in €   |        |        |        |        | lavori |        |
|        | (al    |        |        | Valori |        |        |        |
|        | netto  |        |        | numeri |        | Il     |        |
|        | dell’I |        |        | ci     |        | valore |        |
|        | VA     |        |        | senza  |        | digita |        |
|        | e      |        |        | segni  |        | to     |        |
|        | degli  |        |        | di     |        | contie |        |
|        | oneri  |        |        | interp |        | ne     |        |
|        | di     |        |        | unzion |        | caratt |        |
|        | sicure |        |        | e      |        | eri    |        |
|        | zza)   |        |        | e tre  |        | non    |        |
|        |        |        |        | decima |        | ammess |        |
|        |        |        |        | li     |        | i      |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 10.SF  | Import |        | IMPORT | Se     | B      | Il     |        |
|        | o      |        | O      | valori |        | valore |        |
|        | finale |        |        | zzato: |        | digita |        |
|        | compon |        |        | valori |        | to     |        |
|        | enti   |        |        | numeri |        | contie |        |
|        | lavori |        |        | ci     |        | ne     |        |
|        | in €   |        |        | senza  |        | caratt |        |
|        | (al    |        |        | segni  |        | eri    |        |
|        | netto  |        |        | di     |        | non    |        |
|        | dell’I |        |        | interp |        | ammess |        |
|        | VA     |        |        | unzion |        | i      |        |
|        | e      |        |        | e      |        |        |        |
|        | degli  |        |        | e tre  |        |        |        |
|        | oneri  |        |        | decima |        |        |        |
|        | di     |        |        | li     |        |        |        |
|        | sicure |        |        |        |        |        |        |
|        | zza)   |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 11.L   | Import |        | IMPORT | Se     | B      | Il     |        |
|        | o      |        | O      | valori |        | valore |        |
|        | finale |        |        | zzato  |        | digita |        |
|        | compon |        |        | deve   |        | to     |        |
|        | enti   |        |        | essere |        | contie |        |
|        | serviz |        |        | un     |        | ne     |        |
|        | i      |        |        | campo  |        | caratt |        |
|        | in €   |        |        | numeri |        | eri    |        |
|        | (al    |        |        | co,    |        | non    |        |
|        | netto  |        |        | valori |        | ammess |        |
|        | dell’I |        |        | numeri |        | i      |        |
|        | VA     |        |        | ci     |        |        |        |
|        | e      |        |        | senza  |        |        |        |
|        | degli  |        |        | segni  |        |        |        |
|        | oneri  |        |        | di     |        |        |        |
|        | di     |        |        | interp |        |        |        |
|        | sicure |        |        | unzion |        |        |        |
|        | zza)   |        |        | e      |        |        |        |
|        |        |        |        | e tre  |        |        |        |
|        |        |        |        | decima |        |        |        |
|        |        |        |        | li     |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 11.SF  | Import | OIF    | IMPORT | Se     | B      | Non è  |        |
|        | o      |        | O      | S02.07 |        | stato  |        |
|        | finale |        |        | =      | B      | indica |        |
|        | compon |        |        | “SERVI |        | to     |        |
|        | enti   |        |        | ZI”    |        | l’impo |        |
|        | serviz |        |        | deve   |        | rto    |        |
|        | i      |        |        | essere |        | serviz |        |
|        | in €   |        |        | > 0    |        | i      |        |
|        | (al    |        |        |        |        |        |        |
|        | netto  |        |        | Se     |        | Il     |        |
|        | dell’I |        |        | valori |        | valore |        |
|        | VA     |        |        | zzato: |        | digita |        |
|        | e      |        |        | valori |        | to     |        |
|        | degli  |        |        | numeri |        | contie |        |
|        | oneri  |        |        | ci     |        | ne     |        |
|        | di     |        |        | senza  |        | caratt |        |
|        | sicure |        |        | segni  |        | eri    |        |
|        | zza)   |        |        | di     |        | non    |        |
|        |        |        |        | interp |        | ammess |        |
|        |        |        |        | unzion |        | i.     |        |
|        |        |        |        | e      |        |        |        |
|        |        |        |        | e tre  |        |        |        |
|        |        |        |        | decima |        |        |        |
|        |        |        |        | li     |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 12.L   | Import |        | IMPORT | Se     | B      | Il     |        |
|        | o      |        | O      | valori |        | valore |        |
|        | finale |        |        | zzato  |        | digita |        |
|        | compon |        |        | deve   |        | to     |        |
|        | enti   |        |        | essere |        | contie |        |
|        | fornit |        |        | un     |        | ne     |        |
|        | ure    |        |        | campo  |        | caratt |        |
|        | in €   |        |        | numeri |        | eri    |        |
|        | (al    |        |        | co,    |        | non    |        |
|        | netto  |        |        | valori |        | ammess |        |
|        | dell’I |        |        | numeri |        | i      |        |
|        | VA     |        |        | ci     |        |        |        |
|        | e      |        |        | senza  |        |        |        |
|        | degli  |        |        | segni  |        |        |        |
|        | oneri  |        |        | di     |        |        |        |
|        | di     |        |        | interp |        |        |        |
|        | sicure |        |        | unzion |        |        |        |
|        | zza)   |        |        | e      |        |        |        |
|        |        |        |        | e tre  |        |        |        |
|        |        |        |        | decima |        |        |        |
|        |        |        |        | li     |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 12.SF  | Import | OIF    | IMPORT | Se     | B      | Non è  |        |
|        | o      |        | O      | S02.07 |        | stato  |        |
|        | finale |        |        | =      | B      | indica |        |
|        | compon |        |        | “FORNI |        | to     |        |
|        | enti   |        |        | TURE”  |        | l’impo |        |
|        | fornit |        |        | deve   |        | rto    |        |
|        | ure    |        |        | essere |        | serviz |        |
|        | in €   |        |        | > 0    |        | i      |        |
|        | (al    |        |        |        |        |        |        |
|        | netto  |        |        | Se     |        | Il     |        |
|        | dell’I |        |        | valori |        | valore |        |
|        | VA     |        |        | zzato: |        | digita |        |
|        | e      |        |        | valori |        | to     |        |
|        | degli  |        |        | numeri |        | contie |        |
|        | oneri  |        |        | ci     |        | ne     |        |
|        | di     |        |        | senza  |        | caratt |        |
|        | sicure |        |        | segni  |        | eri    |        |
|        | zza)   |        |        | di     |        | non    |        |
|        |        |        |        | interp |        | ammess |        |
|        |        |        |        | unzion |        | i.     |        |
|        |        |        |        | e      |        |        |        |
|        |        |        |        | e tre  |        |        |        |
|        |        |        |        | decima |        |        |        |
|        |        |        |        | li     |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 13     | SubTot | C      | IMPORT |        |        |        |        |
|        | ale    |        | O      |        |        |        |        |
|        | (S15.1 |        |        |        |        |        |        |
|        | 0+S15. |        |        |        |        |        |        |
|        | 11+S15 |        |        |        |        |        |        |
|        | .12)   |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 14     | Import |        | IMPORT | Deve   | B      | Il     |        |
|        | o      |        | O      | essere |        | valore |        |
|        | finale |        |        | un     | W      | digita |        |
|        | per    |        |        | campo  |        | to     |        |
|        | l’attu |        |        | numeri |        | contie |        |
|        | azione |        |        | co     |        | ne     |        |
|        | della  |        |        | con    |        | caratt |        |
|        | sicure |        |        | defaul |        | eri    |        |
|        | zza    |        |        | t      |        | non    |        |
|        |        |        |        | a zero |        | ammess |        |
|        |        |        |        |        |        | i      |        |
|        |        |        |        | senza  |        |        |        |
|        |        |        |        | segni  |        | Verifi |        |
|        |        |        |        | di     |        | care   |        |
|        |        |        |        | interp |        | l’impo |        |
|        |        |        |        | unzion |        | rto    |        |
|        |        |        |        | e      |        | digita |        |
|        |        |        |        | e tre  |        | to     |        |
|        |        |        |        | decima |        |        |        |
|        |        |        |        | li     |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Se il  |        |        |        |
|        |        |        |        | valore |        |        |        |
|        |        |        |        | risult |        |        |        |
|        |        |        |        | a      |        |        |        |
|        |        |        |        | >      |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S15.13 |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 15     | Import |        | IMPORT | | Deve | B      | Il     |        |
|        | o      |        | O      |   esse |        | valore |        |
|        | proget |        |        | re     | B      | digita |        |
|        | tazion |        |        |   un   |        | to     |        |
|        | e      |        |        |   camp |        | contie |        |
|        | (art.  |        |        | o      |        | ne     |        |
|        | 53     |        |        |   nume |        | caratt |        |
|        | comma  |        |        | rico   |        | eri    |        |
|        | 2 lett |        |        |   senz |        | non    |        |
|        | b, c   |        |        | a      |        | ammess |        |
|        | Dlgs   |        |        |   segn |        | i      |        |
|        | 163/20 |        |        | i      |        |        |        |
|        | 06)    |        |        |   di   |        | Verifi |        |
|        |        |        |        |   inte |        | care   |        |
|        |        |        |        | rpunzi |        | l’impo |        |
|        |        |        |        | one    |        | rto    |        |
|        |        |        |        |   e    |        | digita |        |
|        |        |        |        |   tre  |        | to     |        |
|        |        |        |        |   deci |        |        |        |
|        |        |        |        | mali   |        |        |        |
|        |        |        |        | | con  |        |        |        |
|        |        |        |        |   defa |        |        |        |
|        |        |        |        | ult    |        |        |        |
|        |        |        |        |   a    |        |        |        |
|        |        |        |        |   zero |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Se il  |        |        |        |
|        |        |        |        | valore |        |        |        |
|        |        |        |        | risult |        |        |        |
|        |        |        |        | a      |        |        |        |
|        |        |        |        | > di   |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S15.13 |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 16     | Import | C      | IMPORT |        |        |        |        |
|        | o      |        | O      |        |        |        |        |
|        | finale |        |        |        |        |        |        |
|        | comple |        |        |        |        |        |        |
|        | ssivo  |        |        |        |        |        |        |
|        | dell’a |        |        |        |        |        |        |
|        | ppalto |        |        |        |        |        |        |
|        | (S15.1 |        |        |        |        |        |        |
|        | 3+S15. |        |        |        |        |        |        |
|        | 14+S15 |        |        |        |        |        |        |
|        | .15)   |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 17     | Import | O      | IMPORT | Deve   | B      | Non è  |        |
|        | o      |        | O      | essere |        | stato  |        |
|        | comple |        |        | un     | B      | indica |        |
|        | ssivo  |        |        | campo  |        | to     |        |
|        | “somme |        |        | numeri |        | l’impo |        |
|        | a      |        |        | co     |        | rto    |        |
|        | dispos |        |        | >=0    |        | delle  |        |
|        | izione |        |        |        |        | somme  |        |
|        | ”      |        |        | Valori |        | a      |        |
|        | effett |        |        | numeri |        | dispos |        |
|        | ivamen |        |        | ci     |        | izione |        |
|        | te     |        |        | senza  |        | effett |        |
|        | impieg |        |        | segni  |        | ivamen |        |
|        | ate    |        |        | di     |        | te     |        |
|        |        |        |        | interp |        | impieg |        |
|        |        |        |        | unzion |        | ate    |        |
|        |        |        |        | e      |        |        |        |
|        |        |        |        | e tre  |        | Il     |        |
|        |        |        |        | decima |        | valore |        |
|        |        |        |        | li     |        | digita |        |
|        |        |        |        |        |        | to     |        |
|        |        |        |        |        |        | contie |        |
|        |        |        |        |        |        | ne     |        |
|        |        |        |        |        |        | caratt |        |
|        |        |        |        |        |        | eri    |        |
|        |        |        |        |        |        | non    |        |
|        |        |        |        |        |        | ammess |        |
|        |        |        |        |        |        | i      |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 18     | Import | C      | IMPORT |        |        |        |        |
|        | o      |        | O      |        |        |        |        |
|        | a      |        |        |        |        |        |        |
|        | consun |        |        |        |        |        |        |
|        | tivo   |        |        |        |        |        |        |
|        | dell’i |        |        |        |        |        |        |
|        | nterve |        |        |        |        |        |        |
|        | nto    |        |        |        |        |        |        |
|        | (S15.1 |        |        |        |        |        |        |
|        | 6      |        |        |        |        |        |        |
|        | +      |        |        |        |        |        |        |
|        | S15.17 |        |        |        |        |        |        |
|        | )      |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 19     | Lavori | O      | FLAG   | Lista  | B      |        |        |
|        | annual |        |        | di     |        |        |        |
|        | i      |        |        | valori |        |        |        |
|        | estesi |        |        | da     |        |        |        |
|        | a più  |        |        | elenco |        |        |        |
|        | eserci |        |        | :      |        |        |        |
|        | zi     |        |        | SI/NO  |        |        |        |
|        |        |        |        | Valore |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | defaul |        |        |        |
|        |        |        |        | t:     |        |        |        |
|        |        |        |        | Blank  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **CONT |        |        |        |        |        |        |        |
| ENZIOS |        |        |        |        |        |        |        |
| O**    |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 20     | Numero |        | NUMERI | Deve   | B      | Il     |        |
|        | totale |        | CO     | essere |        | valore |        |
|        | riserv |        |        | un     |        | digita |        |
|        | e      |        |        | campo  |        | to     |        |
|        | defini |        |        | numeri |        | contie |        |
|        | te     |        |        | co     |        | ne     |        |
|        | con    |        |        |        |        | caratt |        |
|        | accord |        |        |        |        | eri    |        |
|        | o      |        |        |        |        | non    |        |
|        | bonari |        |        |        |        | ammess |        |
|        | o      |        |        |        |        | i      |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 21     | Oneri  | OIF    | IMPORT | Campo  | B      | Non è  |        |
|        | comple |        | O      | obblig |        | stato  |        |
|        | ssivi  |        |        | atorio |        | indica |        |
|        | deriva |        |        | se     |        | to     |        |
|        | nti    |        |        | campo  |        | l’impo |        |
|        |        |        |        | S15.20 |        | rto    |        |
|        |        |        |        | > 0    |        | delle  |        |
|        |        |        |        |        |        | somme  |        |
|        |        |        |        | Deve   |        | a      |        |
|        |        |        |        | essere |        | dispos |        |
|        |        |        |        | un     |        | izione |        |
|        |        |        |        | campo  |        | effett |        |
|        |        |        |        | numeri |        | ivamen |        |
|        |        |        |        | co     |        | te     |        |
|        |        |        |        |        |        | impieg |        |
|        |        |        |        | valori |        | ate    |        |
|        |        |        |        | numeri |        |        |        |
|        |        |        |        | ci     |        | Il     |        |
|        |        |        |        | senza  |        | valore |        |
|        |        |        |        | segni  |        | digita |        |
|        |        |        |        | di     |        | to     |        |
|        |        |        |        | interp |        | contie |        |
|        |        |        |        | unzion |        | ne     |        |
|        |        |        |        | e      |        | caratt |        |
|        |        |        |        | e tre  |        | eri    |        |
|        |        |        |        | decima |        | non    |        |
|        |        |        |        | li     |        | ammess |        |
|        |        |        |        |        |        | i      |        |
|        |        |        |        | Se il  |        |        |        |
|        |        |        |        | valore |        | Verifi |        |
|        |        |        |        | risult |        | care   |        |
|        |        |        |        | a      |        | l’impo |        |
|        |        |        |        | > di   |        | rto    |        |
|        |        |        |        | campo  |        | digita |        |
|        |        |        |        | S15.18 |        | to     |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 22     | PER    | Ulteri |        | FLAG   | Lista  | B      | Selezi |
|        | OGNI   | ori    |        |        | di     |        | onare  |
|        | MODALI | riserv |        |        | valori |        | tra    |
|        | TA’    | e      |        |        | da     |        | quelli |
|        | DI     | defini |        |        | elenco |        | previs |
|        | DEFINI | te     |        |        | Valore |        | ti     |
|        | ZIONE  | o da   |        |        | di     |        |        |
|        |        | defini |        |        | defaul |        |        |
|        |        | re     |        |        | t:     |        |        |
|        |        | con    |        |        | Blank  |        |        |
|        |        | divers |        |        |        |        |        |
|        |        | a      |        |        |        |        |        |
|        |        | modali |        |        |        |        |        |
|        |        | tà     |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 23     |        | Numero |        | NUMERI | Deve   | B      | Il     |
|        |        | riserv |        | CO     | essere |        | valore |
|        |        | e      |        |        | un     |        | digita |
|        |        | defini |        |        | campo  |        | to     |
|        |        | te     |        |        | numeri |        | contie |
|        |        |        |        |        | co     |        | ne     |
|        |        |        |        |        |        |        | caratt |
|        |        |        |        |        |        |        | eri    |
|        |        |        |        |        |        |        | non    |
|        |        |        |        |        |        |        | ammess |
|        |        |        |        |        |        |        | i      |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 24     |        | Numero |        | NUMERI | Deve   | B      | Il     |
|        |        | riserv |        | CO     | essere |        | valore |
|        |        | e      |        |        | un     |        | digita |
|        |        | da     |        |        | campo  |        | to     |
|        |        | defini |        |        | numeri |        | contie |
|        |        | re     |        |        | co     |        | ne     |
|        |        |        |        |        |        |        | caratt |
|        |        |        |        |        |        |        | eri    |
|        |        |        |        |        |        |        | non    |
|        |        |        |        |        |        |        | ammess |
|        |        |        |        |        |        |        | i      |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 25     |        | Import | OIF    | IMPORT | Deve   | B      | Il     |
|        |        | o      |        | O      | essere |        | valore |
|        |        | totale |        |        | un     |        | digita |
|        |        | richie |        |        | campo  |        | to     |
|        |        | sto    |        |        | numeri |        | contie |
|        |        |        |        |        | co     |        | ne     |
|        |        |        |        |        | valori |        | caratt |
|        |        |        |        |        | numeri |        | eri    |
|        |        |        |        |        | ci     |        | non    |
|        |        |        |        |        | senza  |        | ammess |
|        |        |        |        |        | segni  |        | i      |
|        |        |        |        |        | di     |        |        |
|        |        |        |        |        | interp |        |        |
|        |        |        |        |        | unzion |        |        |
|        |        |        |        |        | e      |        |        |
|        |        |        |        |        | e tre  |        |        |
|        |        |        |        |        | decima |        |        |
|        |        |        |        |        | li     |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 26     |        | Import | OIF    | IMPORT | Deve   | B      | Il     |
|        |        | o      |        | O      | essere |        | valore |
|        |        | totale |        |        | un     |        | digita |
|        |        | eventu |        |        | campo  |        | to     |
|        |        | ale    |        |        | numeri |        | contie |
|        |        | defini |        |        | co     |        | ne     |
|        |        | zione  |        |        | valori |        | caratt |
|        |        |        |        |        | numeri |        | eri    |
|        |        |        |        |        | ci     |        | non    |
|        |        |        |        |        | senza  |        | ammess |
|        |        |        |        |        | segni  |        | i      |
|        |        |        |        |        | di     |        |        |
|        |        |        |        |        | interp |        |        |
|        |        |        |        |        | unzion |        |        |
|        |        |        |        |        | e      |        |        |
|        |        |        |        |        | e tre  |        |        |
|        |        |        |        |        | decima |        |        |
|        |        |        |        |        | li     |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 27     | Numero | C      | NUMERI |        |        |        |        |
|        | totale |        | CO     |        |        |        |        |
|        | riserv |        |        |        |        |        |        |
|        | e      |        |        |        |        |        |        |
|        | avanza |        |        |        |        |        |        |
|        | te     |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 28     | Numero | C      | NUMERI |        |        |        |        |
|        | totale |        | CO     |        |        |        |        |
|        | riserv |        |        |        |        |        |        |
|        | e      |        |        |        |        |        |        |
|        | defini |        |        |        |        |        |        |
|        | te     |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 29     | Import | C      | IMPORT |        |        |        |        |
|        | o      |        | O      |        |        |        |        |
|        | totale |        |        |        |        |        |        |
|        | conten |        |        |        |        |        |        |
|        | zioso  |        |        |        |        |        |        |
|        | risolt |        |        |        |        |        |        |
|        | o      |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **SOGG |        |        |        |        |        |        |        |
| ETTI   |        |        |        |        |        |        |        |
| AI     |        |        |        |        |        |        |        |
| QUALI  |        |        |        |        |        |        |        |
| SONO   |        |        |        |        |        |        |        |
| STATI  |        |        |        |        |        |        |        |
| CONFER |        |        |        |        |        |        |        |
| ITI    |        |        |        |        |        |        |        |
| INCARI |        |        |        |        |        |        |        |
| CHI**  |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 30     | PER    | Dati   |        | `DATI_ |        |        |        |
|        | OGNI   | Sogget |        | PERSON |        |        |        |
|        | SOGGET | to     |        | A_FISI |        |        |        |
|        | TO     | incari |        | CA <#d |        |        |        |
|        | INCARI | cato   |        | ati_pe |        |        |        |
|        | CATO   |        |        | rsona_ |        |        |        |
|        |        |        |        | fisica |        |        |        |
|        |        |        |        | >`__   |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 31     |        | Ruolo  | O      | `RUOLI | Lista  | B      | Selezi |
|        |        |        |        | _RESPO | di     |        | onare  |
|        |        |        |        | NSABIL | valori |        | un     |
|        |        |        |        | E <#ru | da     |        | valore |
|        |        |        |        | oli_re | elenco |        | tra    |
|        |        |        |        | sponsa |        |        | quelli |
|        |        |        |        | bile>` |        |        | previs |
|        |        |        |        | __     |        |        | ti     |
+--------+--------+--------+--------+--------+--------+--------+--------+

16. .. rubric::  E07 – Accordi bonari (rif. 17.3)
       :name: e07-accordi-bonari-rif.-17.3

    4. .. rubric:: S16 - Accordi Bonari
          :name: s16---accordi-bonari

+---------+---------+---------+---------+---------+---------+---------+
| S16 -   |         |         |         |         |         |         |
| Accordi |         |         |         |         |         |         |
| Bonari  |         |         |         |         |         |         |
+=========+=========+=========+=========+=========+=========+=========+
| COD     | ETICHET | TIPO    | FORMATO | CONTROL | MESSAGG |         |
|         | TA      |         |         | LO      | IO      |         |
+---------+---------+---------+---------+---------+---------+---------+
|         |         |         |         | DESCRIZ | TIPO    |         |
|         |         |         |         | IONE    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 01      | Codice  | R       | STRINGA | Il CIG  | B       | CIG     |
|         | di      |         |         | deve    |         | inesist |
|         | individ |         |         | essere  |         | ente    |
|         | uazione |         |         | esisten |         | o non   |
|         | dell’ap |         |         | te      |         | di      |
|         | palto   |         |         | ed in   |         | compete |
|         | CIG     |         |         | carico  |         | nza     |
|         |         |         |         | all’amm |         |         |
|         |         |         |         | inistra |         |         |
|         |         |         |         | zione   |         |         |
|         |         |         |         | di      |         |         |
|         |         |         |         | apparte |         |         |
|         |         |         |         | nenza   |         |         |
|         |         |         |         | del RUP |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **ACCOR |         |         |         |         |         |         |
| DI      |         |         |         |         |         |         |
| BONARI* |         |         |         |         |         |         |
| *       |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 02      | Data    | O       | DATA    | Campo   | B       | Data    |
|         | dell’ac |         |         | data    |         | formalm |
|         | cordo   |         |         |         | B       | ente    |
|         | bonario |         |         | Se      |         | non     |
|         |         |         |         | valoriz |         | corrett |
|         |         |         |         | zato    |         | a       |
|         |         |         |         | deve    |         |         |
|         |         |         |         | essere  |         | Data    |
|         |         |         |         | >= di   |         | anteced |
|         |         |         |         | campo   |         | ente    |
|         |         |         |         | S11.25  |         | la data |
|         |         |         |         |         |         | di      |
|         |         |         |         |         |         | stipula |
|         |         |         |         |         |         | del     |
|         |         |         |         |         |         | contrat |
|         |         |         |         |         |         | to      |
+---------+---------+---------+---------+---------+---------+---------+
| 03      | Oneri   |         | IMPORTO | deve    | B       | Inserir |
|         | derivan |         |         | essere  |         | e       |
|         | ti      |         |         | un      | W       | solo    |
|         |         |         |         | campo   |         | numeri  |
|         |         |         |         | valuta  |         |         |
|         |         |         |         |         |         | Non è   |
|         |         |         |         | se il   |         | stato   |
|         |         |         |         | valore  |         | valoriz |
|         |         |         |         | = 0     |         | zato    |
|         |         |         |         |         |         | il      |
|         |         |         |         |         |         | nuovo   |
|         |         |         |         |         |         | importo |
|         |         |         |         |         |         | della   |
|         |         |         |         |         |         | sicurez |
|         |         |         |         |         |         | za      |
+---------+---------+---------+---------+---------+---------+---------+
| 04      | Numero  |         | NUMERIC | deve    | B       | Inserir |
|         | di      |         | O       | essere  |         | e       |
|         | riserve |         |         | un      |         | solo    |
|         | transat |         |         | campo   |         | numeri  |
|         | e       |         |         | numeric |         |         |
|         |         |         |         | o       |         |         |
+---------+---------+---------+---------+---------+---------+---------+

17. .. rubric::  E08 – Sospensione (rif. 17.1)
       :name: e08-sospensione-rif.-17.1

    5. .. rubric:: S17 - Sospensione
          :name: s17---sospensione

+---------+---------+---------+---------+---------+---------+---------+
| S17 -   |         |         |         |         |         |         |
| Sospens |         |         |         |         |         |         |
| ione    |         |         |         |         |         |         |
+=========+=========+=========+=========+=========+=========+=========+
| COD     | ETICHET | TIPO    | FORMATO | CONTROL | MESSAGG |         |
|         | TA      |         |         | LO      | IO      |         |
+---------+---------+---------+---------+---------+---------+---------+
|         |         |         |         | DESCRIZ | TIPO    |         |
|         |         |         |         | IONE    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **RIFER |         |         |         |         |         |         |
| IMENTO  |         |         |         |         |         |         |
| AI DATI |         |         |         |         |         |         |
| DELLA   |         |         |         |         |         |         |
| FASE DI |         |         |         |         |         |         |
| AGGIUDI |         |         |         |         |         |         |
| CAZIONE |         |         |         |         |         |         |
| O DI    |         |         |         |         |         |         |
| DEFINIZ |         |         |         |         |         |         |
| IONE    |         |         |         |         |         |         |
| DI      |         |         |         |         |         |         |
| PROCEDU |         |         |         |         |         |         |
| RA      |         |         |         |         |         |         |
| NEGOZIA |         |         |         |         |         |         |
| TA**    |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 01      | Codice  | R       | STRINGA | Il CIG  | B       | CIG     |
|         | di      |         |         | deve    |         | inesist |
|         | individ |         |         | essere  |         | ente    |
|         | uazione |         |         | esisten |         | o non   |
|         | dell’ap |         |         | te      |         | di      |
|         | palto   |         |         | ed in   |         | compete |
|         | CIG     |         |         | carico  |         | nza     |
|         |         |         |         | all’amm |         |         |
|         |         |         |         | inistra |         |         |
|         |         |         |         | zione   |         |         |
|         |         |         |         | di      |         |         |
|         |         |         |         | apparte |         |         |
|         |         |         |         | nenza   |         |         |
|         |         |         |         | del RUP |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **SOSPE |         |         |         |         |         |         |
| NSIONI  |         |         |         |         |         |         |
| DELL’ES |         |         |         |         |         |         |
| ECUZION |         |         |         |         |         |         |
| E**     |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 02      | Data    | O       | DATA    | Campo   | B       | Data    |
|         | del     |         |         | data    |         | formalm |
|         | verbale |         |         |         | B       | ente    |
|         | di      |         |         | Se      |         | non     |
|         | sospens |         |         | valoriz |         | corrett |
|         | ione    |         |         | zato    |         | a       |
|         |         |         |         | deve    |         |         |
|         |         |         |         | essere  |         | Data    |
|         |         |         |         | >= di   |         | anteced |
|         |         |         |         | campo   |         | ente    |
|         |         |         |         | S11.34  |         | la data |
|         |         |         |         |         |         | di      |
|         |         |         |         |         |         | effetti |
|         |         |         |         |         |         | vo      |
|         |         |         |         |         |         | inizio  |
+---------+---------+---------+---------+---------+---------+---------+
| 03      | Data    |         | DATA    | Campo   | B       | Data    |
|         | del     |         |         | data    |         | formalm |
|         | verbale |         |         |         |         | ente    |
|         | di      |         |         | Deve    |         | non     |
|         | ripresa |         |         | essere  |         | corrett |
|         |         |         |         | previst |         | a       |
|         |         |         |         | a       |         |         |
|         |         |         |         | la      |         |         |
|         |         |         |         | possibi |         |         |
|         |         |         |         | lità    |         |         |
|         |         |         |         | di      |         |         |
|         |         |         |         | valoriz |         |         |
|         |         |         |         | zare    |         |         |
|         |         |         |         | il      |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | success |         |         |
|         |         |         |         | ivament |         |         |
|         |         |         |         | e       |         |         |
|         |         |         |         | alla    |         |         |
|         |         |         |         | conferm |         |         |
|         |         |         |         | a       |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 04      | Motivaz | O       | `MOTIVI | Lista   | B       | Selezio |
|         | ione    |         | _SOSPEN | di      |         | nare    |
|         | della   |         | SIONE < | valori  |         | un      |
|         | sospens |         | #motivi | da      |         | valore  |
|         | ione    |         | _sospen | elenco  |         | tra     |
|         |         |         | sione>` | Valore  |         | quelli  |
|         |         |         | __      | di      |         | previst |
|         |         |         |         | default |         | i       |
|         |         |         |         | :       |         |         |
|         |         |         |         | Blank   |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 05      | E’      | O       | FLAG    | Vale SI |         | Selezio |
|         | stato   |         |         | –NO     |         | nare    |
|         | superat |         |         | Valore  |         | un      |
|         | o       |         |         | di      |         | valore  |
|         | il      |         |         | default |         | tra     |
|         | quarto  |         |         | :       |         | quelli  |
|         | del     |         |         | Blank   |         | previst |
|         | tempo   |         |         |         |         | i       |
|         | contrat |         |         |         |         |         |
|         | tuale   |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 06      | Iscrizi | O       | FLAG    | Vale SI | B       | Selezio |
|         | one     |         |         | -NO     |         | nare    |
|         | di      |         |         | Valore  |         | un      |
|         | riserve |         |         | di      |         | valore  |
|         | dell’ap |         |         | default |         | tra     |
|         | paltato |         |         | :       |         | quelli  |
|         | re      |         |         | Blank   |         | previst |
|         | nei     |         |         |         |         | i       |
|         | verbali |         |         |         |         |         |
|         | di      |         |         |         |         |         |
|         | sospens |         |         |         |         |         |
|         | ione    |         |         |         |         |         |
|         | e/o     |         |         |         |         |         |
|         | ripresa |         |         |         |         |         |
|         | lavori  |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 07      | Verbale | O       | FLAG    | Vale SI | B       | Selezio |
|         | /i      |         |         | -NO     |         | nare    |
|         | non     |         |         | Valore  |         | un      |
|         | sottosc |         |         | di      |         | valore  |
|         | ritti   |         |         | default |         | tra     |
|         | dall’ap |         |         | :       |         | quelli  |
|         | paltato |         |         | Blank   |         | previst |
|         | re      |         |         |         |         | i       |
+---------+---------+---------+---------+---------+---------+---------+

18. .. rubric::  E09 – Varianti (rif. 17.2)
       :name: e09-varianti-rif.-17.2

    6. .. rubric:: S18 - Variante
          :name: s18---variante

+---------+---------+---------+---------+---------+---------+---------+
| S18 -   |         |         |         |         |         |         |
| Variant |         |         |         |         |         |         |
| e       |         |         |         |         |         |         |
+=========+=========+=========+=========+=========+=========+=========+
| COD     | ETICHET | TIPO    | FORMATO | CONTROL | MESSAGG |         |
|         | TA      |         |         | LO      | IO      |         |
+---------+---------+---------+---------+---------+---------+---------+
|         |         |         |         | DESCRIZ | TIPO    |         |
|         |         |         |         | IONE    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **RIFER |         |         |         |         |         |         |
| IMENTO  |         |         |         |         |         |         |
| AI DATI |         |         |         |         |         |         |
| DELLA   |         |         |         |         |         |         |
| FASE DI |         |         |         |         |         |         |
| AGGIUDI |         |         |         |         |         |         |
| CAZIONE |         |         |         |         |         |         |
| O DI    |         |         |         |         |         |         |
| DEFINIZ |         |         |         |         |         |         |
| IONE    |         |         |         |         |         |         |
| DI      |         |         |         |         |         |         |
| PROCEDU |         |         |         |         |         |         |
| RA      |         |         |         |         |         |         |
| NEGOZIA |         |         |         |         |         |         |
| TA**    |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 01      | Codice  | R       | STRINGA | Il CIG  | B       | CIG     |
|         | di      |         |         | deve    |         | inesist |
|         | individ |         |         | essere  |         | ente    |
|         | uazione |         |         | esisten |         | o non   |
|         | dell’ap |         |         | te      |         | di      |
|         | palto   |         |         | ed in   |         | compete |
|         | CIG     |         |         | carico  |         | nza     |
|         |         |         |         | all’amm |         |         |
|         |         |         |         | inistra |         |         |
|         |         |         |         | zione   |         |         |
|         |         |         |         | di      |         |         |
|         |         |         |         | apparte |         |         |
|         |         |         |         | nenza   |         |         |
|         |         |         |         | del RUP |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **VARIA |         |         |         |         |         |         |
| NTE**   |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 02      | Data di | O       | DATA    | Campo   | B       | Data    |
|         | approva |         |         | data    | W       | formalm |
|         | zione   |         |         |         |         | ente    |
|         | della   |         |         | Se      |         | non     |
|         | variant |         |         | valoriz |         | corrett |
|         | e       |         |         | zato    |         | a       |
|         |         |         |         | deve    |         |         |
|         |         |         |         | essere  |         | Data    |
|         |         |         |         | >=      |         | anteced |
|         |         |         |         | campo   |         | ente    |
|         |         |         |         | S11.34  |         | la data |
|         |         |         |         |         |         | di      |
|         |         |         |         |         |         | effetti |
|         |         |         |         |         |         | vo      |
|         |         |         |         |         |         | inizio  |
+---------+---------+---------+---------+---------+---------+---------+
| 03      | Motivaz |         | `MOTIVI | Lista   | B       | Selezio |
|         | ione/i  |         | _VARIAN | di      |         | nare    |
|         | della/e |         | TE <#mo | valori  |         | almeno  |
|         | variant |         | tivi_va | da      |         | un      |
|         | e/i     |         | riante> | elenco  |         | valore  |
|         |         |         | `__     | Valore  |         | tra     |
|         |         |         |         | di      |         | quelli  |
|         |         |         |         | default |         | previst |
|         |         |         |         | :       |         | i       |
|         |         |         |         | Blank   |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 04      | Altre   | OIF     | TESTO   | Se non  | B       | Indicar |
|         | motivaz |         |         | valoriz |         | e       |
|         | ioni    |         |         | zato    |         | almeno  |
|         |         |         |         | e campo |         | una     |
|         |         |         |         | S18.03  |         | motivaz |
|         |         |         |         | = blank |         | ione    |
|         |         |         |         |         |         | che ha  |
|         |         |         |         | Testo   |         | determi |
|         |         |         |         | libero  |         | nato    |
|         |         |         |         | separat |         | l’insor |
|         |         |         |         | o       |         | gere    |
|         |         |         |         | da una  |         | di una  |
|         |         |         |         | virgola |         | variant |
|         |         |         |         |         |         | e       |
+---------+---------+---------+---------+---------+---------+---------+
| **QUADR |         |         |         |         |         |         |
| O       |         |         |         |         |         |         |
| ECONOMI |         |         |         |         |         |         |
| CO      |         |         |         |         |         |         |
| DELLA   |         |         |         |         |         |         |
| VARIANT |         |         |         |         |         |         |
| E**     |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 05      | Importo | OIF     | IMPORTO | deve    | B       | Inserir |
|         | contrat |         |         | essere  |         | e       |
|         | tuale   |         |         | un      | B       | solo    |
|         | rideter |         |         | campo   |         | numeri  |
|         | minato  |         |         | valuta  |         |         |
|         | compone |         |         |         |         | Assenza |
|         | nte     |         |         | se il   |         | di      |
|         | lavori  |         |         | valore  |         | valori  |
|         | in €    |         |         | è = 0   |         | riferit |
|         | (al     |         |         | and     |         | i       |
|         | netto   |         |         | campo   |         | al      |
|         | dell’IV |         |         | S18.06  |         | quadro  |
|         | A       |         |         | = 0 and |         | economi |
|         | e degli |         |         | campo   |         | co      |
|         | oneri   |         |         | S18.07  |         |         |
|         | di      |         |         | = 0     |         |         |
|         | sicurez |         |         |         |         |         |
|         | za)     |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 06      | Importo | OIF     | IMPORTO | deve    | B       | Inserir |
|         | contrat |         |         | essere  |         | e       |
|         | tuale   |         |         | un      | B       | solo    |
|         | rideter |         |         | campo   |         | numeri  |
|         | minato  |         |         | valuta  |         |         |
|         | compone |         |         |         |         | Assenza |
|         | nte     |         |         | se il   |         | di      |
|         | servizi |         |         | valore  |         | valori  |
|         | in €    |         |         | è = 0   |         | riferit |
|         | (al     |         |         | and     |         | i       |
|         | netto   |         |         | campo   |         | al      |
|         | dell’IV |         |         | S18.05  |         | quadro  |
|         | A       |         |         | = 0 and |         | economi |
|         | e degli |         |         | campo   |         | co      |
|         | oneri   |         |         | S18.07  |         |         |
|         | di      |         |         | = 0     |         |         |
|         | sicurez |         |         |         |         |         |
|         | za)     |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 07      | Importo | OIF     | IMPORTO | deve    | B       | Inserir |
|         | contrat |         |         | essere  |         | e       |
|         | tuale   |         |         | un      | B       | solo    |
|         | rideter |         |         | campo   |         | numeri  |
|         | minato  |         |         | valuta  |         |         |
|         | compone |         |         |         |         | Assenza |
|         | nte     |         |         | se il   |         | di      |
|         | fornitu |         |         | valore  |         | valori  |
|         | re      |         |         | = 0 and |         | riferit |
|         | in €    |         |         | campo   |         | i       |
|         | (al     |         |         | S18.05  |         | al      |
|         | netto   |         |         | = 0 and |         | quadro  |
|         | dell’IV |         |         | campo   |         | economi |
|         | A       |         |         | S18.06  |         | co      |
|         | e degli |         |         | = 0     |         |         |
|         | oneri   |         |         |         |         |         |
|         | di      |         |         |         |         |         |
|         | sicurez |         |         |         |         |         |
|         | za)     |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 08      | Sub     | C       | IMPORTO |         |         |         |
|         | totale  |         |         |         |         |         |
|         | (05+06+ |         |         |         |         |         |
|         | 07)     |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 09      | Nuovo   |         | IMPORTO | deve    | B       | Inserir |
|         | importo |         |         | essere  |         | e       |
|         | totale  |         |         | un      | W       | solo    |
|         | per     |         |         | campo   |         | numeri  |
|         | l’attua |         |         | valuta  |         |         |
|         | zione   |         |         |         |         | Non è   |
|         | della   |         |         | se il   |         | stato   |
|         | sicurez |         |         | valore  |         | valoriz |
|         | za      |         |         | = 0     |         | zato    |
|         | (non    |         |         |         |         | l’impor |
|         | soggett |         |         |         |         | to      |
|         | o       |         |         |         |         | della   |
|         | a       |         |         |         |         | sicurez |
|         | ribasso |         |         |         |         | za      |
|         | )       |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 10      | Importo |         | IMPORTO | deve    | B       | Inserir |
|         | progett |         |         | essere  |         | e       |
|         | azione  |         |         | un      | W       | solo    |
|         | (art.   |         |         | campo   |         | numeri  |
|         | 53      |         |         | valuta  |         |         |
|         | comma 2 |         |         |         |         | Non è   |
|         | lettera |         |         | se il   |         | stato   |
|         | c Dlgs  |         |         | valore  |         | valoriz |
|         | 163/200 |         |         | = 0     |         | zato    |
|         | 6)      |         |         |         |         | l’      |
|         |         |         |         |         |         | importo |
|         |         |         |         |         |         | della   |
|         |         |         |         |         |         | progett |
|         |         |         |         |         |         | azione  |
+---------+---------+---------+---------+---------+---------+---------+
| 10a     | Ulterio |         | IMPORTO | Deve    | B       | Inserir |
|         | ri      |         |         | essere  |         | e       |
|         | somme   |         |         | un      |         | solo    |
|         | non     |         |         | campo   |         | numeri  |
|         | soggett |         |         | valuta  |         |         |
|         | e       |         |         |         |         |         |
|         | a       |         |         |         |         |         |
|         | ribasso |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 11      | Importo | C       | IMPORTO |         |         |         |
|         | comples |         |         |         |         |         |
|         | sivo    |         |         |         |         |         |
|         | appalto |         |         |         |         |         |
|         | rideter |         |         |         |         |         |
|         | minato  |         |         |         |         |         |
|         | (08+09+ |         |         |         |         |         |
|         | 10)     |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 12      | Nuovo   |         | IMPORTO | deve    | B       | Inserir |
|         | importo |         |         | essere  |         | e       |
|         | totale  |         |         | un      | W       | solo    |
|         | somme a |         |         | campo   |         | numeri  |
|         | disposi |         |         | valuta  |         |         |
|         | zione   |         |         |         |         | Non è   |
|         |         |         |         | se il   |         | stato   |
|         |         |         |         | valore  |         | valoriz |
|         |         |         |         | = 0     |         | zato    |
|         |         |         |         |         |         | l’      |
|         |         |         |         |         |         | importo |
|         |         |         |         |         |         | delladi |
|         |         |         |         |         |         | sposizi |
|         |         |         |         |         |         | one     |
+---------+---------+---------+---------+---------+---------+---------+
| 13      | Importo | C       | IMPORTO |         |         |         |
|         | comples |         |         |         |         |         |
|         | sivo    |         |         |         |         |         |
|         | dell’in |         |         |         |         |         |
|         | tervent |         |         |         |         |         |
|         | o       |         |         |         |         |         |
|         | (11+12) |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **ATTI  |         |         |         |         |         |         |
| AGGIUNT |         |         |         |         |         |         |
| IVI     |         |         |         |         |         |         |
| /SOTTOM |         |         |         |         |         |         |
| ISSIONE |         |         |         |         |         |         |
| **      |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 14      | Data    |         | DATA    | deve    | B       | Data    |
|         | sottosc |         |         | essere  |         | formalm |
|         | rizione |         |         | un      | W       | ente    |
|         | eventua |         |         | campo   |         | non     |
|         | le      |         |         | data    |         | corrett |
|         | atto    |         |         |         |         | a       |
|         | aggiunt |         |         | Se      |         |         |
|         | ivo/    |         |         | valoriz |         | Data    |
|         | sottomi |         |         | zato    |         | anteced |
|         | ssione  |         |         | deve    |         | ente    |
|         |         |         |         | essere  |         | la data |
|         |         |         |         | > di    |         | di      |
|         |         |         |         | campo   |         | effetti |
|         |         |         |         | S11.34  |         | vo      |
|         |         |         |         |         |         | inizio  |
+---------+---------+---------+---------+---------+---------+---------+
| 15      | Numero  |         | NUMERIC | deve    | B       | Il      |
|         | di      |         | O       | essere  |         | campo   |
|         | giorni  |         |         | un      |         | contien |
|         | di      |         |         | campo   |         | e       |
|         | proroga |         |         | numeric |         | caratte |
|         | concess |         |         | o       |         | ri      |
|         | i/tempo |         |         |         |         | non     |
|         | aggiunt |         |         |         |         | validi  |
|         | ivo     |         |         |         |         |         |
|         | rispett |         |         |         |         |         |
|         | o       |         |         |         |         |         |
|         | ai      |         |         |         |         |         |
|         | termini |         |         |         |         |         |
|         | contrat |         |         |         |         |         |
|         | tuali   |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+

19. .. rubric:: E10 – Subappalto (rif. 17.4)
       :name: e10-subappalto-rif.-17.4

    7. .. rubric:: S19 - Subappalto
          :name: s19---subappalto

+---------+---------+---------+---------+---------+---------+---------+
| S19 -   |         |         |         |         |         |         |
| Subappa |         |         |         |         |         |         |
| lto     |         |         |         |         |         |         |
+=========+=========+=========+=========+=========+=========+=========+
| COD     | ETICHET | TIPO    | FORMATO | CONTROL | MESSAGG |         |
|         | TA      |         |         | LO      | IO      |         |
+---------+---------+---------+---------+---------+---------+---------+
|         |         |         |         | DESCRIZ | TIPO    |         |
|         |         |         |         | IONE    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **RIFER |         |         |         |         |         |         |
| IMENTO  |         |         |         |         |         |         |
| AI DATI |         |         |         |         |         |         |
| DELLA   |         |         |         |         |         |         |
| FASE DI |         |         |         |         |         |         |
| AGGIUDI |         |         |         |         |         |         |
| CAZIONE |         |         |         |         |         |         |
| O DI    |         |         |         |         |         |         |
| DEFINIZ |         |         |         |         |         |         |
| IONE    |         |         |         |         |         |         |
| DI      |         |         |         |         |         |         |
| PROCEDU |         |         |         |         |         |         |
| RA      |         |         |         |         |         |         |
| NEGOZIA |         |         |         |         |         |         |
| TA**    |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 01      | Codice  | R       | STRINGA | Il CIG  | B       | CIG     |
|         | di      |         |         | deve    |         | inesist |
|         | individ |         |         | essere  |         | ente    |
|         | uazione |         |         | esisten |         | o non   |
|         | dell’ap |         |         | te      |         | di      |
|         | palto   |         |         | ed in   |         | compete |
|         | CIG     |         |         | carico  |         | nza     |
|         |         |         |         | all’amm |         |         |
|         |         |         |         | inistra |         |         |
|         |         |         |         | zione   |         |         |
|         |         |         |         | di      |         |         |
|         |         |         |         | apparte |         |         |
|         |         |         |         | nenza   |         |         |
|         |         |         |         | del RUP |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **SUBAP |         |         |         |         |         |         |
| PALTO** |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 02      | Codice  | O       | STRINGA | Campo   | B       | Non è   |
|         | fiscale |         |         | obbliga |         | stato   |
|         | ditta   |         |         | torio   |         | inserit |
|         | subappa |         |         |         |         | o       |
|         | ltatric |         |         |         |         | il      |
|         | e       |         |         |         |         | codice  |
|         |         |         |         |         |         | fiscale |
|         |         |         |         |         |         | della   |
|         |         |         |         |         |         | ditta   |
|         |         |         |         |         |         | subappa |
|         |         |         |         |         |         | ltatric |
|         |         |         |         |         |         | e       |
+---------+---------+---------+---------+---------+---------+---------+
| 03      | Codice  | OIF     | Lista   | Campo   | B       | Non è   |
|         | fiscale |         | di      | obbliga |         | stato   |
|         | ditta   |         | DATI_AG | torio   | B       | inserit |
|         | aggiudi |         | GIUDICA | se      |         | o       |
|         | catrice |         | TARIO   | l’aggiu |         | il      |
|         | nel     |         |         | dicazio |         | codice  |
|         | caso di |         |         | ne      |         | fiscale |
|         | aggiudi |         |         | contien |         | della   |
|         | catari  |         |         | e       |         | ditta   |
|         | multipl |         |         | più     |         | aggiudi |
|         | i       |         |         | aggiudi |         | catrice |
|         |         |         |         | catari  |         |         |
|         |         |         |         |         |         | codice  |
|         |         |         |         | deve    |         | fiscale |
|         |         |         |         | trattar |         | formalm |
|         |         |         |         | si      |         | ente    |
|         |         |         |         | di un   |         | non     |
|         |         |         |         | codice  |         | corrett |
|         |         |         |         | fiscale |         | o       |
|         |         |         |         | di      |         |         |
|         |         |         |         | persona |         |         |
|         |         |         |         | fisica  |         |         |
|         |         |         |         | o       |         |         |
|         |         |         |         | giuridi |         |         |
|         |         |         |         | ca      |         |         |
|         |         |         |         | formalm |         |         |
|         |         |         |         | ente    |         |         |
|         |         |         |         | valido  |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 04      | Data di |         | DATA    | deve    | B       | Data    |
|         | autoriz |         |         | essere  |         | formalm |
|         | zazione |         |         | un      | W       | ente    |
|         | subappa |         |         | campo   |         | non     |
|         | lto     |         |         | data    | **      | corrett |
|         |         |         |         |         | **\ W   | a       |
|         |         |         |         | Se      |         |         |
|         |         |         |         | valoriz |         | Data    |
|         |         |         |         | zato    |         | anteced |
|         |         |         |         | deve    |         | ente    |
|         |         |         |         | essere  |         | la data |
|         |         |         |         | > del   |         | di      |
|         |         |         |         | campo   |         | stipula |
|         |         |         |         | S11.25  |         | del     |
|         |         |         |         |         |         | contrat |
|         |         |         |         | Se      |         | to      |
|         |         |         |         | valoriz |         |         |
|         |         |         |         | zato    |         | Data    |
|         |         |         |         | deve    |         | anteced |
|         |         |         |         | essere  |         | ente    |
|         |         |         |         | > di    |         | la data |
|         |         |         |         | campo   |         | di      |
|         |         |         |         | S08.63  |         | aggiudi |
|         |         |         |         | o al    |         | cazione |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S09.16  |         |         |
|         |         |         |         | o al    |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S11.14  |         |         |
|         |         |         |         | in caso |         |         |
|         |         |         |         | di      |         |         |
|         |         |         |         | contrat |         |         |
|         |         |         |         | ti      |         |         |
|         |         |         |         | multilo |         |         |
|         |         |         |         | tto     |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 05      | Lavoro/ |         | TESTO   | testo   |         |         |
|         | Servizi |         |         | libero  |         |         |
|         | o/      |         |         |         |         |         |
|         | /Fornit |         |         |         |         |         |
|         | ura     |         |         |         |         |         |
|         | subappa |         |         |         |         |         |
|         | lto     |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 06      | Importo | O       | IMPORTO | deve    | B       | Inserir |
|         | presunt |         |         | essere  |         | e       |
|         | o       |         |         | un      | B       | solo    |
|         | Lavoro/ |         |         | campo   |         | numeri  |
|         | Servizi |         |         | valuta  |         |         |
|         | o/Forni |         |         |         |         | Non è   |
|         | tura,   |         |         | se non  |         | stato   |
|         | subappa |         |         | valoriz |         | valoriz |
|         | lto     |         |         | zato    |         | zato    |
|         |         |         |         |         |         | Importo |
|         |         |         |         |         |         | presunt |
|         |         |         |         |         |         | o       |
|         |         |         |         |         |         | Lavoro/ |
|         |         |         |         |         |         | Servizi |
|         |         |         |         |         |         | o/Forni |
|         |         |         |         |         |         | tura,   |
|         |         |         |         |         |         | subappa |
|         |         |         |         |         |         | lto     |
+---------+---------+---------+---------+---------+---------+---------+
| 07      | Categor | O       | `CATEGO | Lista   | B       | Selezio |
|         | ia      |         | RIA <#c | di      |         | nare    |
|         | Lavoro/ |         | ategori | valori  |         | un      |
|         | Servizi |         | a>`__   | da      |         | valore  |
|         | o/forni |         |         | elenco  |         | tra     |
|         | tura,   |         |         | Valore  |         | quelli  |
|         | subappa |         |         | di      |         | previst |
|         | lto     |         |         | default |         | i       |
|         |         |         |         | :       |         |         |
|         |         |         |         | Blank   |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 08      | CPV     | O       | `CODICE | Lista   | B       | Selezio |
|         | corrent |         | _CPV <# | di      |         | nare    |
|         | i       |         | codice_ | valori  |         | un      |
|         |         |         | cpv>`__ | da      |         | valore  |
|         |         |         |         | elenco  |         | tra     |
|         |         |         |         |         |         | quelli  |
|         |         |         |         | Valore  |         | previst |
|         |         |         |         | di      |         | i       |
|         |         |         |         | default |         |         |
|         |         |         |         | :       |         |         |
|         |         |         |         | Blank   |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 09      | Importo |         | IMPORTO | se      | B       | Inserir |
|         | effetti |         |         | valoriz |         | e       |
|         | vo      |         |         | zato    |         | solo    |
|         | Lavoro/ |         |         | deve    |         | numeri  |
|         | Servizi |         |         | essere  |         |         |
|         | o/Forni |         |         | un      |         |         |
|         | tura,   |         |         | campo   |         |         |
|         | subappa |         |         | valuta  |         |         |
|         | lto     |         |         |         |         |         |
|         |         |         |         | Deve    |         |         |
|         |         |         |         | essere  |         |         |
|         |         |         |         | previst |         |         |
|         |         |         |         | a       |         |         |
|         |         |         |         | la      |         |         |
|         |         |         |         | possibi |         |         |
|         |         |         |         | lità    |         |         |
|         |         |         |         | di      |         |         |
|         |         |         |         | valoriz |         |         |
|         |         |         |         | zare    |         |         |
|         |         |         |         | il      |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | success |         |         |
|         |         |         |         | ivament |         |         |
|         |         |         |         | e       |         |         |
|         |         |         |         | alla    |         |         |
|         |         |         |         | conferm |         |         |
|         |         |         |         | a.      |         |         |
+---------+---------+---------+---------+---------+---------+---------+

20. .. rubric:: E11 – Istanza di recesso *(solo per lavori)*
       :name: e11-istanza-di-recesso-solo-per-lavori

    8. .. rubric:: S20 - Istanza di recesso
          :name: s20---istanza-di-recesso

+---------+---------+---------+---------+---------+---------+---------+
| S20 -   |         |         |         |         |         |         |
| Istanza |         |         |         |         |         |         |
| di      |         |         |         |         |         |         |
| recesso |         |         |         |         |         |         |
+=========+=========+=========+=========+=========+=========+=========+
| COD     | ETICHET | TIPO    | FORMATO | CONTROL | MESSAGG |         |
|         | TA      |         |         | LO      | IO      |         |
+---------+---------+---------+---------+---------+---------+---------+
|         |         |         |         | DESCRIZ | TIPO    |         |
|         |         |         |         | IONE    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **RIFER |         |         |         |         |         |         |
| IMENTO  |         |         |         |         |         |         |
| AI DATI |         |         |         |         |         |         |
| DELLA   |         |         |         |         |         |         |
| FASE DI |         |         |         |         |         |         |
| AGGIUDI |         |         |         |         |         |         |
| CAZIONE |         |         |         |         |         |         |
| O DI    |         |         |         |         |         |         |
| DEFINIZ |         |         |         |         |         |         |
| IONE    |         |         |         |         |         |         |
| DI      |         |         |         |         |         |         |
| PROCEDU |         |         |         |         |         |         |
| RA      |         |         |         |         |         |         |
| NEGOZIA |         |         |         |         |         |         |
| TA**    |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 01      | Codice  | R       | STRINGA | Il CIG  | B       | CIG     |
|         | di      |         |         | deve    |         | inesist |
|         | individ |         |         | essere  |         | ente    |
|         | uazione |         |         | esisten |         | o non   |
|         | dell’ap |         |         | te      |         | di      |
|         | palto   |         |         | ed in   |         | compete |
|         | CIG     |         |         | carico  |         | nza     |
|         |         |         |         | all’amm |         |         |
|         |         |         |         | inistra |         |         |
|         |         |         |         | zione   |         |         |
|         |         |         |         | di      |         |         |
|         |         |         |         | apparte |         |         |
|         |         |         |         | nenza   |         |         |
|         |         |         |         | del RUP |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **RITAR |         |         |         |         |         |         |
| DO      |         |         |         |         |         |         |
| O       |         |         |         |         |         |         |
| SOSPENS |         |         |         |         |         |         |
| IONE    |         |         |         |         |         |         |
| NELLA   |         |         |         |         |         |         |
| CONSEGN |         |         |         |         |         |         |
| A**     |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 02      | Termine | O       | DATA    | Se      | B       | Data    |
|         | previst |         |         | valoriz |         | formalm |
|         | o       |         |         | zato    | B       | ente    |
|         | per la  |         |         | deve    |         | non     |
|         | consegn |         |         | essere  |         | corrett |
|         | a       |         |         | una     |         | a       |
|         | ai      |         |         | data    |         |         |
|         | sensi   |         |         | valida  |         | Indicar |
|         | del     |         |         |         |         | e       |
|         | comma 8 |         |         | se non  |         | il      |
|         | dell’ar |         |         | valoriz |         | termine |
|         | t.      |         |         | zata    |         | previst |
|         | 153 DPR |         |         |         |         | o       |
|         | 207/201 |         |         |         |         | per la  |
|         | 0       |         |         |         |         | consegn |
|         |         |         |         |         |         | a       |
+---------+---------+---------+---------+---------+---------+---------+
| 03      | Data    | P       | DATA    | Assume  | B       | Data    |
|         | della   |         |         | il      |         | consegn |
|         | consegn |         |         | valore  | W       | a       |
|         | a       |         |         | del     |         | lavori  |
|         | dei     |         |         | campo   |         | non     |
|         | lavori  |         |         | S11.32. |         | valida  |
|         |         |         |         |         |         |         |
|         |         |         |         | In      |         | Si e'   |
|         |         |         |         | alterna |         | sicuri  |
|         |         |         |         | tiva    |         | del     |
|         |         |         |         | (campo  |         | valore  |
|         |         |         |         | S11.32  |         | della   |
|         |         |         |         | non     |         | data    |
|         |         |         |         | valoriz |         | digitat |
|         |         |         |         | zato)   |         | a?      |
|         |         |         |         | assume  |         |         |
|         |         |         |         | il      |         |         |
|         |         |         |         | valore  |         |         |
|         |         |         |         | del     |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S11.31. |         |         |
|         |         |         |         |         |         |         |
|         |         |         |         | In      |         |         |
|         |         |         |         | alterna |         |         |
|         |         |         |         | tiva    |         |         |
|         |         |         |         | (campo  |         |         |
|         |         |         |         | S11.31  |         |         |
|         |         |         |         | non     |         |         |
|         |         |         |         | valoriz |         |         |
|         |         |         |         | zato)   |         |         |
|         |         |         |         | deve    |         |         |
|         |         |         |         | essere  |         |         |
|         |         |         |         | valoriz |         |         |
|         |         |         |         | zato    |         |         |
|         |         |         |         | in      |         |         |
|         |         |         |         | questa  |         |         |
|         |         |         |         | scheda  |         |         |
|         |         |         |         | con i   |         |         |
|         |         |         |         | seguent |         |         |
|         |         |         |         | i       |         |         |
|         |         |         |         | control |         |         |
|         |         |         |         | li:     |         |         |
|         |         |         |         |         |         |         |
|         |         |         |         | - Deve  |         |         |
|         |         |         |         | essere  |         |         |
|         |         |         |         | un      |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | data    |         |         |
|         |         |         |         | formalm |         |         |
|         |         |         |         | ente    |         |         |
|         |         |         |         | valido  |         |         |
|         |         |         |         |         |         |         |
|         |         |         |         | - Se    |         |         |
|         |         |         |         | l’anno  |         |         |
|         |         |         |         | è       |         |         |
|         |         |         |         | superio |         |         |
|         |         |         |         | re      |         |         |
|         |         |         |         | all’ann |         |         |
|         |         |         |         | o       |         |         |
|         |         |         |         | in      |         |         |
|         |         |         |         | corso   |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 04      | Tipolog |         | `TIPOLO | Lista   | B       | Selezio |
|         | ia      |         | GIA_COM | di      |         | nare    |
|         | comunic |         | UNICAZI | valori  |         | almeno  |
|         | azione  |         | ONE <#t | da      |         | un      |
|         |         |         | ipologi | elenco  |         | valore  |
|         |         |         | a_comun | Valore  |         | tra     |
|         |         |         | icazion | di      |         | quelli  |
|         |         |         | e>`__   | default |         | previst |
|         |         |         |         | :       |         | i       |
|         |         |         |         | Blank   |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 05      | Ritardo | C       | NUMERIC |         |         |         |
|         | della   |         | O       |         |         |         |
|         | consegn |         |         |         |         |         |
|         | a       |         |         |         |         |         |
|         | in      |         |         |         |         |         |
|         | giorni  |         |         |         |         |         |
|         | (in     |         |         |         |         |         |
|         | caso di |         |         |         |         |         |
|         | ritardo |         |         |         |         |         |
|         | )       |         |         |         |         |         |
|         | (3-2)   |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 06      | Durata  |         | NUMERIC | deve    | B       | Inserir |
|         | della   |         | O       | essere  |         | e       |
|         | sospens |         |         | un      |         | solo    |
|         | ione    |         |         | campo   |         | numeri  |
|         | in      |         |         | numeric |         |         |
|         | giorni  |         |         | o       |         |         |
|         | (in     |         |         |         |         |         |
|         | caso di |         |         |         |         |         |
|         | sospens |         |         |         |         |         |
|         | ione)   |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 07      | Motivaz |         | TESTO   | Testo   |         |         |
|         | ione    |         |         | libero  |         |         |
|         | della   |         |         |         |         |         |
|         | sospens |         |         |         |         |         |
|         | ione/ri |         |         |         |         |         |
|         | tardo   |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **ISTAN |         |         |         |         |         |         |
| ZA      |         |         |         |         |         |         |
| DI      |         |         |         |         |         |         |
| RECESSO |         |         |         |         |         |         |
| **      |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 09      | Data di | O       | DATA    | Campo   | B       | Data    |
|         | present |         |         | data    |         | formalm |
|         | azione  |         |         |         |         | ente    |
|         | dell’is |         |         |         |         | non     |
|         | tanza   |         |         |         |         | corrett |
|         | di      |         |         |         |         | a       |
|         | recesso |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 10      | L’istan | O       | FLAG    | | Lista | B       | Selezio |
|         | za      |         |         |   di    |         | nare    |
|         | di      |         |         |   valor |         | un      |
|         | recesso |         |         | i       |         | valore  |
|         | è stata |         |         |   da    |         | tra     |
|         | accolta |         |         |   elenc |         | quelli  |
|         |         |         |         | o       |         | previst |
|         |         |         |         | | Valor |         | i       |
|         |         |         |         | e       |         |         |
|         |         |         |         |   di    |         |         |
|         |         |         |         |   defau |         |         |
|         |         |         |         | lt:     |         |         |
|         |         |         |         |   Blank |         |         |
|         |         |         |         |         |         |         |
|         |         |         |         | Vale SI |         |         |
|         |         |         |         | o NO    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 11      | Si è    |         | FLAG    | | Lista | B       | Selezio |
|         | procedu |         |         |   di    |         | nare    |
|         | to      |         |         |   valor |         | un      |
|         | a       |         |         | i       |         | valore  |
|         | consegn |         |         |   da    |         | tra     |
|         | a       |         |         |   elenc |         | quelli  |
|         | tardiva |         |         | o       |         | previst |
|         | (in     |         |         | | Valor |         | i       |
|         | caso di |         |         | e       |         |         |
|         | ritardo |         |         |   di    |         |         |
|         | )       |         |         |   defau |         |         |
|         |         |         |         | lt:     |         |         |
|         |         |         |         |   Blank |         |         |
|         |         |         |         |         |         |         |
|         |         |         |         | Vale SI |         |         |
|         |         |         |         | o NO    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 12      | Si è    |         | FLAG    | | Lista | B       | Selezio |
|         | procedu |         |         |   di    |         | nare    |
|         | to      |         |         |   valor |         | un      |
|         | alla    |         |         | i       |         | valore  |
|         | ripresa |         |         |   da    |         | tra     |
|         | dei     |         |         |   elenc |         | quelli  |
|         | lavori  |         |         | o       |         | previst |
|         | (in     |         |         | | Valor |         | i       |
|         | caso di |         |         | e       |         |         |
|         | sospens |         |         |   di    |         |         |
|         | ione)   |         |         |   defau |         |         |
|         |         |         |         | lt:     |         |         |
|         |         |         |         |   Blank |         |         |
|         |         |         |         |         |         |         |
|         |         |         |         | Vale SI |         |         |
|         |         |         |         | o NO    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 13      | L’appal |         | FLAG    | | Lista | B       | Selezio |
|         | tatore  |         |         |   di    |         | nare    |
|         | ha      |         |         |   valor |         | un      |
|         | formula |         |         | i       |         | valore  |
|         | to      |         |         |   da    |         | tra     |
|         | riserve |         |         |   elenc |         | quelli  |
|         |         |         |         | o       |         | previst |
|         |         |         |         | | Valor |         | i       |
|         |         |         |         | e       |         |         |
|         |         |         |         |   di    |         |         |
|         |         |         |         |   defau |         |         |
|         |         |         |         | lt:     |         |         |
|         |         |         |         |   Blank |         |         |
|         |         |         |         |         |         |         |
|         |         |         |         | Vale SI |         |         |
|         |         |         |         | o NO    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 14      | Eventua |         | IMPORTO | deve    | B       | Inserir |
|         | le      |         |         | essere  |         | e       |
|         | rimbors |         |         | un      | W       | solo    |
|         | o       |         |         | campo   |         | numeri  |
|         | delle   |         |         | valuta  |         |         |
|         | spese   |         |         |         |         | Non è   |
|         | in €    |         |         | se il   |         | stato   |
|         |         |         |         | valore  |         | valoriz |
|         |         |         |         | = 0     |         | zato    |
|         |         |         |         |         |         | l’impor |
|         |         |         |         |         |         | to      |
|         |         |         |         |         |         | del     |
|         |         |         |         |         |         | rimbors |
|         |         |         |         |         |         | o       |
|         |         |         |         |         |         | spese   |
+---------+---------+---------+---------+---------+---------+---------+
| 15      | Eventua |         | IMPORTO | deve    | B       | Inserir |
|         | le      |         |         | essere  |         | e       |
|         | compens |         |         | un      | W       | solo    |
|         | o       |         |         | campo   |         | numeri  |
|         | degli   |         |         | valuta  |         |         |
|         | oneri   |         |         |         |         | Non è   |
|         | derivan |         |         | se il   |         | stato   |
|         | ti      |         |         | valore  |         | valoriz |
|         | dal     |         |         | = 0     |         | zato    |
|         | ritardo |         |         |         |         | l’impor |
|         | in €    |         |         |         |         | to      |
|         |         |         |         |         |         | degli   |
|         |         |         |         |         |         | oneri   |
|         |         |         |         |         |         | derivan |
|         |         |         |         |         |         | ti      |
|         |         |         |         |         |         | dal     |
|         |         |         |         |         |         | ritardo |
+---------+---------+---------+---------+---------+---------+---------+

21. .. rubric:: E12 - Variazione dei soggetti a vario titolo coinvolti
       nel corso del ciclo di vita dell’opera, ivi compreso
       l’aggiudicatario
       :name: e12---variazione-dei-soggetti-a-vario-titolo-coinvolti-nel-corso-del-ciclo-di-vita-dellopera-ivi-compreso-laggiudicatario

    9. .. rubric::  S21 – Variazione Anagrafica Soggetti Coinvolti  [3]_
          :name: s21-variazione-anagrafica-soggetti-coinvolti

+--------+--------+--------+--------+--------+--------+--------+--------+
| S16 -  |        |        |        |        |        |        |        |
| Accord |        |        |        |        |        |        |        |
| i      |        |        |        |        |        |        |        |
| Bonari |        |        |        |        |        |        |        |
+========+========+========+========+========+========+========+========+
| COD    | ETICHE | TIPO   | FORMAT | CONTRO | MESSAG |        |        |
|        | TTA    |        | O      | LLO    | GIO    |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
|        |        |        |        | DESCRI | TIPO   |        |        |
|        |        |        |        | ZIONE  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 01     | Codice | R      | STRING | Il CIG | B      | CIG    |        |
|        | di     |        | A      | deve   |        | inesis |        |
|        | indivi |        |        | essere |        | tente  |        |
|        | duazio |        |        | esiste |        | o non  |        |
|        | ne     |        |        | nte    |        | di     |        |
|        | dell’a |        |        | ed in  |        | compet |        |
|        | ppalto |        |        | carico |        | enza   |        |
|        | CIG    |        |        | all’am |        |        |        |
|        |        |        |        | minist |        |        |        |
|        |        |        |        | razion |        |        |        |
|        |        |        |        | e      |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | appart |        |        |        |
|        |        |        |        | enenza |        |        |        |
|        |        |        |        | del    |        |        |        |
|        |        |        |        | RUP    |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
|        |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 02     | Motiva | O      | DATA   | Campo  | B      | Data   |        |
|        | zione  |        |        | data   |        | formal |        |
|        | della  |        |        |        | B      | mente  |        |
|        | variaz |        |        | Se     |        | non    |        |
|        | ione   |        |        | valori |        | corret |        |
|        | anagra |        |        | zzato  |        | ta     |        |
|        | fica   |        |        | deve   |        |        |        |
|        |        |        |        | essere |        | Data   |        |
|        |        |        |        | >= di  |        | antece |        |
|        |        |        |        | campo  |        | dente  |        |
|        |        |        |        | S11.25 |        | la     |        |
|        |        |        |        |        |        | data   |        |
|        |        |        |        |        |        | di     |        |
|        |        |        |        |        |        | stipul |        |
|        |        |        |        |        |        | a      |        |
|        |        |        |        |        |        | del    |        |
|        |        |        |        |        |        | contra |        |
|        |        |        |        |        |        | tto    |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **PRES |        |        |        |        |        |        |        |
| TAZION |        |        |        |        |        |        |        |
| I      |        |        |        |        |        |        |        |
| PROGET |        |        |        |        |        |        |        |
| TUALI* |        |        |        |        |        |        |        |
| *      |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 03     | RIPETE | Dati   | P      | `DATI_ | Il     | B      | E’     |
|        | RE     | anagra |        | PERSON | sogget |        | necess |
|        | PER    | fici   |        | A_FISI | to     |        | ario   |
|        | OGNI   | del    |        | CA <#d | può    |        | scegli |
|        | SOGGET | sogget |        | ati_pe | essere |        | ere    |
|        | TO     | to     |        | rsona_ | un     |        | un     |
|        | INCARI |        |        | fisica | incari |        | sogget |
|        | CATO   |        |        | >`__   | cato   |        | to     |
|        |        |        |        |        | (perso |        | per    |
|        |        |        |        | o      | na     |        | poter  |
|        |        |        |        |        | fisica |        | proseg |
|        |        |        |        | `DATI_ | )      |        | uire   |
|        |        |        |        | PERSON | oppure |        |        |
|        |        |        |        | A_GIUR | un     |        |        |
|        |        |        |        | IDICA  | operat |        |        |
|        |        |        |        | <#dati | ore    |        |        |
|        |        |        |        | _perso | econom |        |        |
|        |        |        |        | na_giu | ico    |        |        |
|        |        |        |        | ridica | (perso |        |        |
|        |        |        |        | >`__   | na     |        |        |
|        |        |        |        |        | giurid |        |        |
|        |        |        |        |        | ica)   |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 04     |        | CIG    | P      | STRING | Valori | W      | Assenz |
|        |        | affida |        | A      | zzazio |        | a      |
|        |        | mento  |        |        | ne     |        | CIG    |
|        |        | incari |        |        | se si  |        | dell’a |
|        |        | co     |        |        | è      |        | ffidam |
|        |        | estern |        |        | selezi |        | ento   |
|        |        | o      |        |        | onato  |        | di     |
|        |        | di     |        |        | nel    |        | incari |
|        |        | proget |        |        | campo  |        | co     |
|        |        | tazion |        |        | S08.09 |        | estern |
|        |        | e      |        |        | “Proge |        | o      |
|        |        | (in    |        |        | ttista |        | di     |
|        |        | caso   |        |        | estern |        | proget |
|        |        | di     |        |        | o      |        | tazion |
|        |        | proget |        |        | alla   |        | e      |
|        |        | tista  |        |        | S.A.”  |        |        |
|        |        | estern |        |        |        |        |        |
|        |        | o)     |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 05     |        | Data   | P      | DATA   | Valori | B      | Indica |
|        |        | di     |        |        | zzazio |        | re     |
|        |        | affida |        |        | ne     | B      | la     |
|        |        | mento  |        |        | se si  |        | data   |
|        |        | incari |        |        | è      |        | dell’a |
|        |        | co     |        |        | selezi |        | ffidam |
|        |        | (per   |        |        | onato  |        | ento   |
|        |        | proget |        |        | nel    |        | di     |
|        |        | tazion |        |        | campo  |        | incari |
|        |        | e      |        |        | S08.09 |        | co     |
|        |        | estern |        |        | “Proge |        | estern |
|        |        | a)     |        |        | ttista |        | o      |
|        |        |        |        |        | estern |        | di     |
|        |        |        |        |        | o      |        | proget |
|        |        |        |        |        | alla   |        | tazion |
|        |        |        |        |        | S.A.”  |        | e      |
|        |        |        |        |        |        |        |        |
|        |        |        |        |        | Deve   |        | Data   |
|        |        |        |        |        | essere |        | formal |
|        |        |        |        |        | un     |        | mente  |
|        |        |        |        |        | campo  |        | non    |
|        |        |        |        |        | data   |        | corret |
|        |        |        |        |        |        |        | ta     |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 06     |        | Data   | P      | DATA   | Valori | B      | Indica |
|        |        | di     |        |        | zzazio |        | re     |
|        |        | conseg |        |        | ne     | B      | la     |
|        |        | na     |        |        | se si  |        | data   |
|        |        | proget |        |        | è      |        | di     |
|        |        | to     |        |        | selezi |        | conseg |
|        |        | (per   |        |        | onato  |        | na     |
|        |        | proget |        |        | nel    |        | del    |
|        |        | tazion |        |        | campo  |        | proget |
|        |        | e      |        |        | S08.09 |        | to     |
|        |        | estern |        |        | “Proge |        | (per   |
|        |        | a)     |        |        | ttista |        | la     |
|        |        |        |        |        | estern |        | proget |
|        |        |        |        |        | o      |        | tazion |
|        |        |        |        |        | alla   |        | e      |
|        |        |        |        |        | S.A.”  |        | estern |
|        |        |        |        |        |        |        | a)     |
|        |        |        |        |        | Deve   |        |        |
|        |        |        |        |        | essere |        | Data   |
|        |        |        |        |        | un     |        | formal |
|        |        |        |        |        | campo  |        | mente  |
|        |        |        |        |        | data   |        | non    |
|        |        |        |        |        |        |        | corret |
|        |        |        |        |        |        |        | ta     |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 07     |        | Tipolo | P      | `TIPO_ | Lista  | B      | Selezi |
|        |        | gia    |        | SOGGET | valori |        | onare  |
|        |        | del    |        | TO <#t | da     |        | un     |
|        |        | sogget |        | ipo_so | elenco |        | valore |
|        |        | to     |        | ggetto |        |        | tra    |
|        |        | incari |        | >`__   |        |        | quelli |
|        |        | cato   |        |        |        |        | previs |
|        |        | della  |        |        |        |        | ti     |
|        |        | presta |        |        |        |        |        |
|        |        | zione  |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **AGGI |        |        |        |        |        |        |        |
| UDICAZ |        |        |        |        |        |        |        |
| IONE   |        |        |        |        |        |        |        |
| /      |        |        |        |        |        |        |        |
| AFFIDA |        |        |        |        |        |        |        |
| MENTO* |        |        |        |        |        |        |        |
| *      |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 08     | PER    | Dati   | P      | `DATI_ | Se non | B      | Il     |
|        | OGNI   | Aggiud |        | PERSON | inseri |        | campo  |
|        | AGGIUD | icatar |        | A_GIUR | to     |        | è      |
|        | ICATAR | io     |        | IDICA  | almeno |        | obblig |
|        | IO     |        |        | <#dati | un     |        | atorio |
|        |        |        |        | _perso | aggiud |        |        |
|        |        |        |        | na_giu | icatar |        |        |
|        |        |        |        | ridica | io     |        |        |
|        |        |        |        | >`__   |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **ANAG |        |        |        |        |        |        |        |
| RAFICA |        |        |        |        |        |        |        |
| E      |        |        |        |        |        |        |        |
| RIFERI |        |        |        |        |        |        |        |
| MENTI  |        |        |        |        |        |        |        |
| DEI    |        |        |        |        |        |        |        |
| SOGGET |        |        |        |        |        |        |        |
| TI     |        |        |        |        |        |        |        |
| AI     |        |        |        |        |        |        |        |
| QUALI  |        |        |        |        |        |        |        |
| LA     |        |        |        |        |        |        |        |
| STAZIO |        |        |        |        |        |        |        |
| NE     |        |        |        |        |        |        |        |
| APPALT |        |        |        |        |        |        |        |
| ANTE   |        |        |        |        |        |        |        |
| HA     |        |        |        |        |        |        |        |
| CONFER |        |        |        |        |        |        |        |
| ITO    |        |        |        |        |        |        |        |
| INCARI |        |        |        |        |        |        |        |
| CHI**  |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 66     | PER    | Dati   | P      | `DATI_ | Se non | B      | Il     |
|        | OGNI   | Sogget |        | PERSON | inseri |        | campo  |
|        | SOGGET | to     |        | A_FISI | to     |        | è      |
|        | TO     | incari |        | CA <#d | almeno |        | obblig |
|        | INCARI | cato   |        | ati_pe | un     |        | atorio |
|        | CATO   |        |        | rsona_ | aggiud |        |        |
|        |        |        |        | fisica | icatar |        |        |
|        |        |        |        | >`__   | io     |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 67     |        | Ruolo  | P      | `RUOLI | Lista  | B      | Selezi |
|        |        |        |        | _RESPO | di     |        | onare  |
|        |        |        |        | NSABIL | valori | W      | un     |
|        |        |        |        | E <#ru | da     |        | valore |
|        |        |        |        | oli_re | elenco |        | tra    |
|        |        |        |        | sponsa |        |        | quelli |
|        |        |        |        | bile>` | Deve   |        | previs |
|        |        |        |        | __     | essere |        | ti     |
|        |        |        |        |        | inseri |        |        |
|        |        |        |        |        | to     |        | Non    |
|        |        |        |        |        | almeno |        | sono   |
|        |        |        |        |        | un     |        | stati  |
|        |        |        |        |        | incari |        | inseri |
|        |        |        |        |        | cato   |        | ti     |
|        |        |        |        |        |        |        | incari |
|        |        |        |        |        |        |        | cati   |
+--------+--------+--------+--------+--------+--------+--------+--------+

3. .. rubric:: Codifiche e formati
      :name: codifiche-e-formati

   22. .. rubric::  Strutture dati semplici
          :name: strutture-dati-semplici

+-----------------------+-----------------------+-----------------------+
| **TIPO**              | **Descrizione**       | **Formato**           |
+=======================+=======================+=======================+
| DATA                  | campo di tipo data    | dd/mm/yyyy            |
+-----------------------+-----------------------+-----------------------+
| ORA                   | campo di tipo ora     | hh:mm                 |
+-----------------------+-----------------------+-----------------------+
| STRINGA               | sequenza di caratteri |                       |
|                       | numerici ed           |                       |
|                       | alfanumerici          |                       |
+-----------------------+-----------------------+-----------------------+
| TESTO                 | sequenza di caratteri |                       |
|                       | numerici ed           |                       |
|                       | alfanumerici su più   |                       |
|                       | righe                 |                       |
+-----------------------+-----------------------+-----------------------+
| NUMERICO              | sequenza di caratteri |                       |
|                       | numerici              |                       |
+-----------------------+-----------------------+-----------------------+
| IMPORTO               | sequenza di caratteri | € 999.999.999,999     |
|                       | numerici              |                       |
+-----------------------+-----------------------+-----------------------+
| FLAG                  | scelta SI/NO          |                       |
+-----------------------+-----------------------+-----------------------+
| PERCENTUALE           | Valore percentuale    | 999,99999%            |
+-----------------------+-----------------------+-----------------------+

23. .. rubric::  Strutture dati complesse
       :name: strutture-dati-complesse

    12. .. rubric:: DATI_PERSONA_FISICA
           :name: dati_persona_fisica

+---------+---------+---------+---------+---------+---------+---------+
| DATI_PE |         |         |         |         |         |         |
| RSONA_F |         |         |         |         |         |         |
| ISICA   |         |         |         |         |         |         |
+=========+=========+=========+=========+=========+=========+=========+
| COD     | ETICHET | TIPO    | FORMATO | CONTROL | MESSAGG |         |
|         | TA      |         |         | LO      | IO      |         |
+---------+---------+---------+---------+---------+---------+---------+
|         |         |         |         | DESCRIZ | TIPO    |         |
|         |         |         |         | IONE    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 01      | Codice  |         | STRINGA | Deve    | W       | Codice  |
|         | fiscale |         |         | essere  |         | fiscale |
|         |         |         |         | formalm |         | formalm |
|         |         |         |         | ente    |         | ente    |
|         |         |         |         | corrett |         | non     |
|         |         |         |         | o       |         | corrett |
|         |         |         |         |         |         | o       |
|         |         |         |         |         |         |         |
|         |         |         |         |         |         | Non è   |
|         |         |         |         |         |         | stato   |
|         |         |         |         |         |         | indicat |
|         |         |         |         |         |         | o       |
|         |         |         |         |         |         | il      |
|         |         |         |         |         |         | codice  |
|         |         |         |         |         |         | fiscale |
|         |         |         |         |         |         | del     |
|         |         |         |         |         |         | soggett |
|         |         |         |         |         |         | o       |
+---------+---------+---------+---------+---------+---------+---------+
| 02      | Cognome |         | STRINGA | Valoriz | W       | Non è   |
|         |         |         |         | zazione |         | stato   |
|         |         |         |         |         |         | indicat |
|         |         |         |         |         |         | o       |
|         |         |         |         |         |         | il      |
|         |         |         |         |         |         | nominat |
|         |         |         |         |         |         | ivo     |
|         |         |         |         |         |         | del     |
|         |         |         |         |         |         | soggett |
|         |         |         |         |         |         | o       |
+---------+---------+---------+---------+---------+---------+---------+
| 02      | Nome    |         | STRINGA | Valoriz | W       | Non è   |
|         |         |         |         | zazione |         | stato   |
|         |         |         |         |         |         | indicat |
|         |         |         |         |         |         | o       |
|         |         |         |         |         |         | il      |
|         |         |         |         |         |         | nominat |
|         |         |         |         |         |         | ivo     |
|         |         |         |         |         |         | del     |
|         |         |         |         |         |         | soggett |
|         |         |         |         |         |         | o       |
+---------+---------+---------+---------+---------+---------+---------+
| 03      | Telefon |         | NUMERIC | Se      | W       | l       |
|         | o       |         | O       | valoriz |         | numero  |
|         |         |         |         | zato    |         | di      |
|         |         |         |         | deve    |         | telefon |
|         |         |         |         | essere  |         | o       |
|         |         |         |         | interam |         | deve    |
|         |         |         |         | ente    |         | essere  |
|         |         |         |         | numeric |         | interam |
|         |         |         |         | o       |         | ente    |
|         |         |         |         |         |         | numeric |
|         |         |         |         |         |         | o       |
+---------+---------+---------+---------+---------+---------+---------+
| 04      | Fax     |         | NUMERIC | Se      | W       | Il      |
|         |         |         | O       | valoriz |         | numero  |
|         |         |         |         | zato    |         | di fax  |
|         |         |         |         | deve    |         | deve    |
|         |         |         |         | essere  |         | essere  |
|         |         |         |         | interam |         | interam |
|         |         |         |         | ente    |         | ente    |
|         |         |         |         | numeric |         | numeric |
|         |         |         |         | o       |         | o       |
+---------+---------+---------+---------+---------+---------+---------+
| 05      | E-mail  |         | STRINGA | Se      | W       | L’indir |
|         |         |         |         | valoriz |         | izzo    |
|         |         |         |         | zato    |         | e-mail  |
|         |         |         |         | deve    |         | indicat |
|         |         |         |         | essere  |         | o       |
|         |         |         |         | un      |         | non è   |
|         |         |         |         | indiriz |         | valido  |
|         |         |         |         | zo      |         |         |
|         |         |         |         | e-mail  |         |         |
|         |         |         |         | valido  |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 06      | Indiriz |         | STRINGA |         |         |         |
|         | zo      |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 07      | CAP     |         | NUMERIC |         |         |         |
|         |         |         | O       |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 08      | Comune  |         | CODICE_ |         |         |         |
|         | Istat   |         | ISTAT   |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+

.. [1]
    questa sezione viene visualizzata solo in presenza di contratti
   multilotto ed è utilizzata come riferimento per i controlli
   successivi

.. [2]
    questa sezione viene visualizzata solo in presenza di contratti
   multilotto ed è utilizzata come riferimento per i controlli
   successivi

.. [3]
    La seguente scheda consente di effettuare variazioni anagrafiche
   dopo aver confermato una scheda di aggiudicazione.
