S10 – Aggiudicazione Contratti Esclusi
======================================

+--------+--------+--------+--------+--------+--------+--------+--------+
| **S10  |        |        |        |        |        |        |        |
| –      |        |        |        |        |        |        |        |
| Aggiud |        |        |        |        |        |        |        |
| icazio |        |        |        |        |        |        |        |
| ne     |        |        |        |        |        |        |        |
| Contra |        |        |        |        |        |        |        |
| tti    |        |        |        |        |        |        |        |
| Esclus |        |        |        |        |        |        |        |
| i**    |        |        |        |        |        |        |        |
+========+========+========+========+========+========+========+========+
| **COD* | ETICHE | TIPO   | FORMAT | CONTRO | MESSAG |        |        |
| *      | TTA    |        | O      | LLO    | GIO    |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
|        |        |        |        | DESCRI | TIPO   |        |        |
|        |        |        |        | ZIONE  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 01     | Codice | E      | STRING |        |        |        |        |
|        | di     |        | A      |        |        |        |        |
|        | indivi |        |        |        |        |        |        |
|        | duazio |        |        |        |        |        |        |
|        | ne     |        |        |        |        |        |        |
|        | dell'a |        |        |        |        |        |        |
|        | ppalto |        |        |        |        |        |        |
|        | (CIG)  |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **OGGE |        |        |        |        |        |        |        |
| TTO    |        |        |        |        |        |        |        |
| DELL’A |        |        |        |        |        |        |        |
| PPALTO |        |        |        |        |        |        |        |
| **     |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 02     | Codice | P      | `CODIC | Valori | B      | Codice |        |
|        | del    |        | E_ISTA | zzare  |        | ISTAT  |        |
|        | luogo  |        | T <#co | in     |        | obblig |        |
|        | di     |        | dice_i | altern |        | atorio |        |
|        | esecuz |        | stat>` | ativa  |        | se     |        |
|        | ione   |        | __     | al     |        | codice |        |
|        | del    |        |        | campo  |        | NUTS   |        |
|        | contra |        |        | S10.03 |        | non è  |        |
|        | tto    |        |        |        |        | valori |        |
|        | (ISTAT |        |        |        |        | zzato  |        |
|        | )      |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 03     | Codice | P      | `CODIC | Valori | B      | Codice |        |
|        | del    |        | E_NUTS | zzare  |        | NUTS   |        |
|        | luogo  |        |  <#cod | in     |        | obblig |        |
|        | di     |        | ice_nu | altern |        | atorio |        |
|        | esecuz |        | ts>`__ | ativa  |        | se     |        |
|        | ione   |        |        | al     |        | codice |        |
|        | del    |        |        | campo  |        | ISTAT  |        |
|        | contra |        |        | S10.02 |        | non è  |        |
|        | tto    |        |        |        |        | valori |        |
|        | (NUTS) |        |        |        |        | zzato  |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 04     | Codice | P      | STRING | Se     | B      | Il     |        |
|        | CUP(ev |        | A      | inseri |        | codice |        |
|        | entual |        |        | to     |        | CUP    |        |
|        | e)     |        |        | deve   |        | non è  |        |
|        |        |        |        | essere |        | valido |        |
|        |        |        |        | coeren |        |        |        |
|        |        |        |        | te     |        |        |        |
|        |        |        |        | (15    |        |        |        |
|        |        |        |        | caratt |        |        |        |
|        |        |        |        | eri    |        |        |        |
|        |        |        |        | alfanu |        |        |        |
|        |        |        |        | merici |        |        |        |
|        |        |        |        | )      |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 04.1   | L'appa | O      | FLAG   | Valore | B      | “Selez |        |
|        | lto    | (E [2] |        | :      |        | ionare |        |
|        | è      | _)     |        | SI/NO/ |        | un     |        |
|        | finali |        |        | Blank  |        | valore |        |
|        | zzato  |        |        |        |        | tra    |        |
|        | alla   |        |        | Defaul |        | quelli |        |
|        | realiz |        |        | t:     |        | previs |        |
|        | zazion |        |        | NULL   |        | ti”    |        |
|        | e      |        |        |        |        |        |        |
|        | di     |        |        | Se     |        |        |        |
|        | proget |        |        | obblig |        |        |        |
|        | ti     |        |        | atorio |        |        |        |
|        | d'inve |        |        | e      |        |        |        |
|        | stimen |        |        | campo  |        |        |        |
|        | to     |        |        | non    |        |        |        |
|        | pubbli |        |        | valori |        |        |        |
|        | co     |        |        | zzato  |        |        |        |
|        | per i  |        |        |        |        |        |        |
|        | quali  |        |        |        |        |        |        |
|        | è      |        |        |        |        |        |        |
|        | previs |        |        |        |        |        |        |
|        | ta     |        |        |        |        |        |        |
|        | l'acqu |        |        |        |        |        |        |
|        | isizio |        |        |        |        |        |        |
|        | ne     |        |        |        |        |        |        |
|        | del    |        |        |        |        |        |        |
|        | codice |        |        |        |        |        |        |
|        | CUP ai |        |        |        |        |        |        |
|        | sensi  |        |        |        |        |        |        |
|        | dell'a |        |        |        |        |        |        |
|        | rt.    |        |        |        |        |        |        |
|        | 11 L.  |        |        |        |        |        |        |
|        | 3/2003 |        |        |        |        |        |        |
|        | e      |        |        |        |        |        |        |
|        | ss.mm. |        |        |        |        |        |        |
|        | ?      |        |        |        |        |        |        |
|        | (E'    |        |        |        |        |        |        |
|        | necess |        |        |        |        |        |        |
|        | ario   |        |        |        |        |        |        |
|        | acquis |        |        |        |        |        |        |
|        | ire    |        |        |        |        |        |        |
|        | e      |        |        |        |        |        |        |
|        | comuni |        |        |        |        |        |        |
|        | care   |        |        |        |        |        |        |
|        | il CUP |        |        |        |        |        |        |
|        | per    |        |        |        |        |        |        |
|        | interv |        |        |        |        |        |        |
|        | enti   |        |        |        |        |        |        |
|        | finanz |        |        |        |        |        |        |
|        | iati,  |        |        |        |        |        |        |
|        | anche  |        |        |        |        |        |        |
|        | in     |        |        |        |        |        |        |
|        | parte, |        |        |        |        |        |        |
|        | con    |        |        |        |        |        |        |
|        | risors |        |        |        |        |        |        |
|        | e      |        |        |        |        |        |        |
|        | Comuni |        |        |        |        |        |        |
|        | tarie) |        |        |        |        |        |        |
|        | (Si/No |        |        |        |        |        |        |
|        | )      |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 04.2   | Cup    | OIF    | STRING | Sono   | B      | Il     |        |
|        | associ | (E)    | A      | ammess |        | codice |        |
|        | ati    |        |        | i      |        | CUP    |        |
|        | al     |        |        | uno o  |        | non è  |        |
|        | lotto  |        |        | più    |        | valido |        |
|        |        |        |        | codici |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Se     |        |        |        |
|        |        |        |        | inseri |        |        |        |
|        |        |        |        | to     |        |        |        |
|        |        |        |        | deve   |        |        |        |
|        |        |        |        | essere |        |        |        |
|        |        |        |        | coeren |        |        |        |
|        |        |        |        | te     |        |        |        |
|        |        |        |        | (15    |        |        |        |
|        |        |        |        | caratt |        |        |        |
|        |        |        |        | eri    |        |        |        |
|        |        |        |        | alfanu |        |        |        |
|        |        |        |        | merici |        |        |        |
|        |        |        |        | )      |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **DATI |        |        |        |        |        |        |        |
| ECONOM |        |        |        |        |        |        |        |
| ICI    |        |        |        |        |        |        |        |
| DELL'A |        |        |        |        |        |        |        |
| PPALTO |        |        |        |        |        |        |        |
| **     |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 05     | Import |        | IMPORT |        | B      | Il     |        |
|        | o      |        | O      |        |        | campo  |        |
|        | sogget |        |        |        |        | contie |        |
|        | to     |        |        |        |        | ne     |        |
|        | a      |        |        |        |        | caratt |        |
|        | ribass |        |        |        |        | eri    |        |
|        | o      |        |        |        |        | non    |        |
|        |        |        |        |        |        | validi |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 06     | Import |        | IMPORT |        | B      | Il     |        |
|        | o      |        | O      |        |        | campo  |        |
|        | per    |        |        |        | W      | contie |        |
|        | l'attu |        |        |        |        | ne     |        |
|        | azione |        |        |        |        | caratt |        |
|        | della  |        |        |        |        | eri    |        |
|        | sicure |        |        |        |        | non    |        |
|        | zza    |        |        |        |        | validi |        |
|        | e      |        |        |        |        |        |        |
|        | altre  |        |        |        |        | Non e' |        |
|        | somme  |        |        |        |        | stato  |        |
|        | non    |        |        |        |        | indica |        |
|        | sogget |        |        |        |        | to     |        |
|        | te     |        |        |        |        | l'impo |        |
|        | a      |        |        |        |        | rto    |        |
|        | ribass |        |        |        |        | totale |        |
|        | o      |        |        |        |        | per    |        |
|        |        |        |        |        |        | l'attu |        |
|        |        |        |        |        |        | azione |        |
|        |        |        |        |        |        | della  |        |
|        |        |        |        |        |        | sicure |        |
|        |        |        |        |        |        | zza    |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 07     | Import | O      | IMPORT | Valori | B      | Non è  |        |
|        | o      |        | O      | zzazio |        | stato  |        |
|        | totale |        |        | ne     | W      | indica |        |
|        | somme  |        |        | (deve  |        | to     |        |
|        | a      |        |        | essere | B      | l’impo |        |
|        | dispos |        |        | >= 0)  |        | rto    |        |
|        | izione |        |        |        |        | totale |        |
|        |        |        |        | Se     |        | delle  |        |
|        |        |        |        | vale 0 |        | somme  |        |
|        |        |        |        |        |        | a      |        |
|        |        |        |        | Valori |        | dispos |        |
|        |        |        |        | numeri |        | izione |        |
|        |        |        |        | ci     |        |        |        |
|        |        |        |        | senza  |        | Non e' |        |
|        |        |        |        | segni  |        | stato  |        |
|        |        |        |        | di     |        | indica |        |
|        |        |        |        | interp |        | to     |        |
|        |        |        |        | unzion |        | l'impo |        |
|        |        |        |        | e      |        | rto    |        |
|        |        |        |        | e tre  |        | totale |        |
|        |        |        |        | decima |        | delle  |        |
|        |        |        |        | li     |        | somme  |        |
|        |        |        |        |        |        | a      |        |
|        |        |        |        |        |        | dispos |        |
|        |        |        |        |        |        | izione |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        |        |        | Il     |        |
|        |        |        |        |        |        | campo  |        |
|        |        |        |        |        |        | contie |        |
|        |        |        |        |        |        | ne     |        |
|        |        |        |        |        |        | caratt |        |
|        |        |        |        |        |        | eri    |        |
|        |        |        |        |        |        | non    |        |
|        |        |        |        |        |        | validi |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 08     | Import | C      | NUMERI | Se     | W      | L’impo |        |
|        | o      |        | CO     | campo  |        | rto    |        |
|        | comple |        |        | S08.16 |        | comple |        |
|        | ssivo  |        | (Somma | > 0 e  |        | ssivo  |        |
|        | dell'i |        | dei    | S08.28 |        | degli  |        |
|        | nterve |        | valori | >      |        | interv |        |
|        | nto    |        | dei    | S08.16 |        | enti   |        |
|        |        |        | campi  |        |        | non è  |        |
|        |        |        | S10.05 |        |        | intera |        |
|        |        |        | ,      |        |        | mente  |        |
|        |        |        | .06,   |        |        | copert |        |
|        |        |        | .07)   |        |        | o      |        |
|        |        |        |        |        |        | dall’i |        |
|        |        |        |        |        |        | mporto |        |
|        |        |        |        |        |        | cumula |        |
|        |        |        |        |        |        | tivo   |        |
|        |        |        |        |        |        | dei    |        |
|        |        |        |        |        |        | finanz |        |
|        |        |        |        |        |        | iament |        |
|        |        |        |        |        |        | i      |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **DATI |        |        |        |        |        |        |        |
| PROCED |        |        |        |        |        |        |        |
| URALI  |        |        |        |        |        |        |        |
| DELL'A |        |        |        |        |        |        |        |
| PPALTO |        |        |        |        |        |        |        |
| **     |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 09     | Proced | O      | `SCELT | Lista  | B      | Selezi |        |
|        | ura    |        | A_CONT | di     |        | onare  |        |
|        | di     |        | RAENTE | valori |        | un     |        |
|        | scelta |        |  <#sce | da     |        | valore |        |
|        | contra |        | lta_co | elenco |        | tra    |        |
|        | ente   |        | ntraen |        |        | quelli |        |
|        |        |        | te>`__ |        |        | previs |        |
|        |        |        |        |        |        | ti     |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 10     | Ricors | O      | FLAG   | Lista  | B      | Selezi |        |
|        | o      |        |        | di     |        | onare  |        |
|        | all'as |        |        | valori |        | almeno |        |
|        | ta     |        |        | da     |        | un     |        |
|        | elettr |        |        | elenco |        | opzion |        |
|        | onica  |        |        | Vale:  |        | e      |        |
|        |        |        |        | SI o   |        | per    |        |
|        |        |        |        | NO     |        | tutti  |        |
|        |        |        |        | Valore |        | i      |        |
|        |        |        |        | di     |        | campi  |        |
|        |        |        |        | defaul |        | Si/No  |        |
|        |        |        |        | t:     |        |        |        |
|        |        |        |        | blank  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **AGGI |        |        |        |        |        |        |        |
| UDICAZ |        |        |        |        |        |        |        |
| IONE   |        |        |        |        |        |        |        |
| /      |        |        |        |        |        |        |        |
| AFFIDA |        |        |        |        |        |        |        |
| MENTO* |        |        |        |        |        |        |        |
| *      |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 11     | Ribass |        | PERCEN | Il     | W      | Il     |        |
|        | o      |        | TUALE  | valore |        | valore |        |
|        | di     |        |        | deve   | B      | del    |        |
|        | aggiud |        |        | essere |        | campo  |        |
|        | icazio |        |        | percen | B      | “Ribas |        |
|        | ne     |        |        | tuale  |        | so     |        |
|        |        |        |        | con la |        | aggiud |        |
|        |        |        |        | possib |        | icazio |        |
|        |        |        |        | ilità  |        | ne”    |        |
|        |        |        |        | di     |        | non è  |        |
|        |        |        |        | arriva |        | coeren |        |
|        |        |        |        | re     |        | te     |        |
|        |        |        |        | alla   |        |        |        |
|        |        |        |        | quinta |        | valore |        |
|        |        |        |        | cifra  |        | percen |        |
|        |        |        |        | decima |        | tuale  |        |
|        |        |        |        | le     |        | non    |        |
|        |        |        |        |        |        | corret |        |
|        |        |        |        | Se     |        | to     |        |
|        |        |        |        | valori |        |        |        |
|        |        |        |        | zzato  |        | Sono   |        |
|        |        |        |        | deve   |        | stati  |        |
|        |        |        |        | essere |        | indica |        |
|        |        |        |        | >=0 e  |        | ti     |        |
|        |        |        |        | <100   |        | sia il |        |
|        |        |        |        |        |        | ribass |        |
|        |        |        |        | in     |        | o      |        |
|        |        |        |        | altern |        | di     |        |
|        |        |        |        | ativa  |        | aggiud |        |
|        |        |        |        | al     |        | icazio |        |
|        |        |        |        | campo  |        | ne     |        |
|        |        |        |        | S10.12 |        | sia    |        |
|        |        |        |        |        |        | l’offe |        |
|        |        |        |        |        |        | rta    |        |
|        |        |        |        |        |        | in     |        |
|        |        |        |        |        |        | aument |        |
|        |        |        |        |        |        | o      |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 12     | Offert |        | PERCEN | Il     | W      | Il     |        |
|        | a      |        | TUALE  | valore |        | valore |        |
|        | in     |        |        | deve   | B      | del    |        |
|        | aument |        |        | essere |        | campo  |        |
|        | o      |        |        | percen | | **   | “Offer |        |
|        |        |        |        | tuale  |   **   | ta     |        |
|        |        |        |        | con la | | B    | in     |        |
|        |        |        |        | possib |        | aument |        |
|        |        |        |        | ilità  |        | o”     |        |
|        |        |        |        | di     |        | non è  |        |
|        |        |        |        | arriva |        | coeren |        |
|        |        |        |        | re     |        | te     |        |
|        |        |        |        | alla   |        |        |        |
|        |        |        |        | quinta |        | Il     |        |
|        |        |        |        | cifra  |        | valore |        |
|        |        |        |        | decima |        | del    |        |
|        |        |        |        | le     |        | campo  |        |
|        |        |        |        |        |        | “Ribas |        |
|        |        |        |        | Se     |        | so     |        |
|        |        |        |        | valori |        | aggiud |        |
|        |        |        |        | zzato  |        | icazio |        |
|        |        |        |        | deve   |        | ne”    |        |
|        |        |        |        | essere |        | non è  |        |
|        |        |        |        | >=0    |        | coeren |        |
|        |        |        |        |        |        | te     |        |
|        |        |        |        | In     |        |        |        |
|        |        |        |        | altern |        | Sono   |        |
|        |        |        |        | ativa  |        | stati  |        |
|        |        |        |        | al     |        | indica |        |
|        |        |        |        | campo  |        | ti     |        |
|        |        |        |        | S10.11 |        | sia il |        |
|        |        |        |        |        |        | ribass |        |
|        |        |        |        |        |        | o      |        |
|        |        |        |        |        |        | di     |        |
|        |        |        |        |        |        | aggiud |        |
|        |        |        |        |        |        | icazio |        |
|        |        |        |        |        |        | ne     |        |
|        |        |        |        |        |        | sia    |        |
|        |        |        |        |        |        | l’offe |        |
|        |        |        |        |        |        | rta    |        |
|        |        |        |        |        |        | in     |        |
|        |        |        |        |        |        | aument |        |
|        |        |        |        |        |        | o      |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 13     | Import | O      | IMPORT | valore | B      | Inseri |        |
|        | o      |        | O      | numeri |        | re     |        |
|        | di     |        |        | co     | W      | l’impo |        |
|        | aggiud |        |        | >\ **= |        | rto    |        |
|        | icazio |        |        | **     | W      | di     |        |
|        | ne/aff |        |        | 0      |        | aggiud |        |
|        | idamen |        |        |        |        | icazio |        |
|        | to     |        |        | Se >   |        | ne     |        |
|        |        |        |        | S08.26 |        |        |        |
|        |        |        |        | e      |        | Verifi |        |
|        |        |        |        | S01.11 |        | care   |        |
|        |        |        |        | =      |        | il     |        |
|        |        |        |        | ‘ORDIN |        | valore |        |
|        |        |        |        | ARIO’  |        | dell’i |        |
|        |        |        |        |        |        | mporto |        |
|        |        |        |        | Se >   |        | di     |        |
|        |        |        |        | dell’i |        | aggiud |        |
|        |        |        |        | ndice  |        | icazio |        |
|        |        |        |        | di     |        | ne     |        |
|        |        |        |        | disper |        |        |        |
|        |        |        |        | sione  |        | Verifi |        |
|        |        |        |        | “devia |        | care   |        |
|        |        |        |        | zione  |        | la     |        |
|        |        |        |        | standa |        | corret |        |
|        |        |        |        | rd”    |        | tezza  |        |
|        |        |        |        |        |        | dell’i |        |
|        |        |        |        |        |        | mporto |        |
|        |        |        |        |        |        | di     |        |
|        |        |        |        |        |        | aggiud |        |
|        |        |        |        |        |        | icazio |        |
|        |        |        |        |        |        | ne/aff |        |
|        |        |        |        |        |        | idamen |        |
|        |        |        |        |        |        | to     |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 14     | Data   | O      | DATA   | deve   | B      | Non è  |        |
|        | di     |        |        | essere |        | stata  |        |
|        | aggiud |        |        | un     | B      | indica |        |
|        | icazio |        |        | campo  |        | ta     |        |
|        | ne     |        |        | data   |        | la     |        |
|        | defini |        |        |        |        | data   |        |
|        | tiva   |        |        | | deve |        | di     |        |
|        | o      |        |        |   esse |        | aggiud |        |
|        | defini |        |        | re     |        | icazio |        |
|        | zione  |        |        |   una  |        | ne     |        |
|        | proced |        |        |   data |        | defini |        |
|        | ura    |        |        |   vali |        | tiva   |        |
|        | negozi |        |        | da:    |        | o      |        |
|        | ata    |        |        | | <=   |        | defini |        |
|        |        |        |        |   data |        | zione  |        |
|        |        |        |        |   odie |        | della  |        |
|        |        |        |        | rna    |        | proced |        |
|        |        |        |        |   e    |        | ura    |        |
|        |        |        |        |   >=01 |        | negozi |        |
|        |        |        |        | /01/20 |        | ata    |        |
|        |        |        |        | 08     |        |        |        |
|        |        |        |        |        |        | Data   |        |
|        |        |        |        |        |        | di     |        |
|        |        |        |        |        |        | aggiud |        |
|        |        |        |        |        |        | icazio |        |
|        |        |        |        |        |        | ne     |        |
|        |        |        |        |        |        | non    |        |
|        |        |        |        |        |        | valida |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 15     | Data   |        | DATA   |        |        |        |        |
|        | stipul |        |        |        |        |        |        |
|        | a      |        |        |        |        |        |        |
|        | contra |        |        |        |        |        |        |
|        | tto    |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 16     | Durata |        | NUMERI |        |        |        |        |
|        | contra |        | CO     |        |        |        |        |
|        | ttuale |        |        |        |        |        |        |
|        | in     |        |        |        |        |        |        |
|        | giorni |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 17     | PER    | Dati   | O      | `DATI_ | Se non | B      | Il     |
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
| 18     | PER    | Dati   | O      | `DATI_ | Se non | B      | Il     |
|        | OGNI   | Sogget |        | PERSON | inseri |        | campo  |
|        | SOGGET | to     |        | A_FISI | to     |        | è      |
|        | TO     | incari |        | CA <#d | almeno |        | obblig |
|        | INCARI | cato   |        | ati_pe | un     |        | atorio |
|        | CATO   |        |        | rsona_ | aggiud |        |        |
|        |        |        |        | fisica | icatar |        |        |
|        |        |        |        | >`__   | io     |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 19     |        | Ruolo  | O      | `RUOLI | Lista  | B      | “Selez |
|        |        |        |        | _RESPO | di     |        | ionare |
|        |        |        |        | NSABIL | valori | W      | un     |
|        |        |        |        | E <#ru | da     |        | valore |
|        |        |        |        | oli_re | elenco |        | tra    |
|        |        |        |        | sponsa |        |        | quelli |
|        |        |        |        | bile>` | Deve   |        | previs |
|        |        |        |        | __     | essere |        | ti”    |
|        |        |        |        |        | inseri |        |        |
|        |        |        |        |        | to     |        | Non    |
|        |        |        |        |        | almeno |        | sono   |
|        |        |        |        |        | un     |        | stati  |
|        |        |        |        |        | incari |        | inseri |
|        |        |        |        |        | cato   |        | ti     |
|        |        |        |        |        |        |        | incari |
|        |        |        |        |        |        |        | cati   |
+--------+--------+--------+--------+--------+--------+--------+--------+

12. .. rubric::  E03 - Fase iniziale di esecuzione del contratto (rif.
       13)
       :name: e03---fase-iniziale-di-esecuzione-del-contratto-rif.-13

    10. .. rubric:: S11 – Inizio Lavori
           :name: s11-inizio-lavori

+--------+--------+--------+--------+--------+--------+--------+--------+
| S11 –  |        |        |        |        |        |        |        |
| Inizio |        |        |        |        |        |        |        |
| Lavori |        |        |        |        |        |        |        |
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
| \  [4] |        |        |        |        |        |        |        |
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
| 15     | Data   | E      |        |        |        |        |        |
|        | Gazzet |        |        |        |        |        |        |
|        | ta     |        |        |        |        |        |        |
|        | Uffici |        |        |        |        |        |        |
|        | ale    |        |        |        |        |        |        |
|        | Comuni |        |        |        |        |        |        |
|        | tà     |        |        |        |        |        |        |
|        | Europe |        |        |        |        |        |        |
|        | a      |        |        |        |        |        |        |
|        | - GUCE |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 16     | Data   | E      |        |        |        |        |        |
|        | Gazzet |        |        |        |        |        |        |
|        | ta     |        |        |        |        |        |        |
|        | Uffici |        |        |        |        |        |        |
|        | ale    |        |        |        |        |        |        |
|        | Region |        |        |        |        |        |        |
|        | ale    |        |        |        |        |        |        |
|        | o      |        |        |        |        |        |        |
|        | Bollet |        |        |        |        |        |        |
|        | tino   |        |        |        |        |        |        |
|        | Region |        |        |        |        |        |        |
|        | ale    |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 17     | Data   | E      |        |        |        |        |        |
|        | Gazzet |        |        |        |        |        |        |
|        | ta     |        |        |        |        |        |        |
|        | Uffici |        |        |        |        |        |        |
|        | ale    |        |        |        |        |        |        |
|        | Repubb |        |        |        |        |        |        |
|        | lica   |        |        |        |        |        |        |
|        | Italia |        |        |        |        |        |        |
|        | na     |        |        |        |        |        |        |
|        | - GURI |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 18     | Albo   | E      |        |        |        |        |        |
|        | pretor |        |        |        |        |        |        |
|        | io     |        |        |        |        |        |        |
|        | del    |        |        |        |        |        |        |
|        | Comune |        |        |        |        |        |        |
|        | ove si |        |        |        |        |        |        |
|        | eseguo |        |        |        |        |        |        |
|        | no     |        |        |        |        |        |        |
|        | i      |        |        |        |        |        |        |
|        | lavori |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 19     | Quotid | E      |        |        |        |        |        |
|        | iani   |        |        |        |        |        |        |
|        | nazion |        |        |        |        |        |        |
|        | ali    |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 20     | Quotid | E      |        |        |        |        |        |
|        | iani   |        |        |        |        |        |        |
|        | locali |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 21     | Period | E      |        |        |        |        |        |
|        | ici    |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 22     | Profil | E      |        |        |        |        |        |
|        | o      |        |        |        |        |        |        |
|        | del    |        |        |        |        |        |        |
|        | commit |        |        |        |        |        |        |
|        | tente  |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 23     | Sito   | E      |        |        |        |        |        |
|        | Inform |        |        |        |        |        |        |
|        | atico  |        |        |        |        |        |        |
|        | Minist |        |        |        |        |        |        |
|        | ero    |        |        |        |        |        |        |
|        | Infras |        |        |        |        |        |        |
|        | truttu |        |        |        |        |        |        |
|        | re     |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 24     | Sito   | E      |        |        |        |        |        |
|        | inform |        |        |        |        |        |        |
|        | atico  |        |        |        |        |        |        |
|        | Osserv |        |        |        |        |        |        |
|        | atorio |        |        |        |        |        |        |
|        | Contra |        |        |        |        |        |        |
|        | tti    |        |        |        |        |        |        |
|        | Pubbli |        |        |        |        |        |        |
|        | ci     |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **CONT |        |        |        |        |        |        |        |
| RATTO  |        |        |        |        |        |        |        |
| DI     |        |        |        |        |        |        |        |
| APPALT |        |        |        |        |        |        |        |
| O**    |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 25     | Data   |        | DATA   | Se     | B      | data   |        |
|        | stipul |        |        | digita |        | antece |        |
|        | a      |        |        | ta     | B      | dente  |        |
|        | del    |        |        | deve   |        | la     |        |
|        | contra |        |        | essere |        | data   |        |
|        | tto    |        |        | >= al  |        | di     |        |
|        |        |        |        | campo  |        | data   |        |
|        |        |        |        | S08.63 |        | di     |        |
|        |        |        |        | o al   |        | aggiud |        |
|        |        |        |        | campo  |        | icazio |        |
|        |        |        |        | S09.16 |        | ne     |        |
|        |        |        |        | o al   |        |        |        |
|        |        |        |        | campo  |        | Data   |        |
|        |        |        |        | S11.14 |        | formal |        |
|        |        |        |        | .I     |        | mente  |        |
|        |        |        |        | in     |        | non    |        |
|        |        |        |        | caso   |        | corret |        |
|        |        |        |        | di     |        | ta     |        |
|        |        |        |        | contra |        |        |        |
|        |        |        |        | tti    |        |        |        |
|        |        |        |        | multil |        |        |        |
|        |        |        |        | otto   |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Deve   |        |        |        |
|        |        |        |        | essere |        |        |        |
|        |        |        |        | un     |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | data   |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 26     | Data   |        | DATA   | | Se   | B      | Data   |        |
|        | esecut |        |        |   valo |        | formal |        |
|        | ività  |        |        | rizzat | B      | mente  |        |
|        | del    |        |        | o      |        | non    |        |
|        | contra |        |        |   deve | W      | corret |        |
|        | tto    |        |        |   esse |        | ta     |        |
|        | (ove   |        |        | re     |        |        |        |
|        | previs |        |        |   un   |        | Data   |        |
|        | ta)    |        |        |   camp |        | non    |        |
|        |        |        |        | o      |        | coeren |        |
|        |        |        |        |   data |        | te,    |        |
|        |        |        |        | | deve |        | verifi |        |
|        |        |        |        |   esse |        | care   |        |
|        |        |        |        | re     |        | la     |        |
|        |        |        |        |   >=   |        | data   |        |
|        |        |        |        |   di   |        | di     |        |
|        |        |        |        |   camp |        | stipul |        |
|        |        |        |        | o      |        | a      |        |
|        |        |        |        |   S11. |        | del    |        |
|        |        |        |        | 25     |        | contra |        |
|        |        |        |        |        |        | tto    |        |
|        |        |        |        | se     |        |        |        |
|        |        |        |        | l’anno |        | Si è   |        |
|        |        |        |        | è      |        | sicuri |        |
|        |        |        |        | superi |        | del    |        |
|        |        |        |        | ore    |        | valore |        |
|        |        |        |        | all’an |        | della  |        |
|        |        |        |        | no     |        | data   |        |
|        |        |        |        | in     |        | digita |        |
|        |        |        |        | corso  |        | ta?    |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 27     | Import | O      | IMPORT | Deve   | B      | il     |        |
|        | o      |        | O      | essere |        | campo  |        |
|        | cauzio |        |        | un     |        | contie |        |
|        | ne     |        |        | campo  |        | ne     |        |
|        | defini |        |        | valuta |        | caratt |        |
|        | tiva   |        |        |        |        | eri    |        |
|        | in €   |        |        |        |        | non    |        |
|        |        |        |        |        |        | validi |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **TERM |        |        |        |        |        |        |        |
| INI    |        |        |        |        |        |        |        |
| DI     |        |        |        |        |        |        |        |
| ESECUZ |        |        |        |        |        |        |        |
| IONE** |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 28     | Data   |        | DATA   | Deve   | B      | Data   |        |
|        | dispos |        |        | essere |        | formal |        |
|        | izione |        |        | un     |        | mente  |        |
|        | dell’i |        |        | campo  |        | non    |        |
|        | nizio  |        |        | data   |        | corret |        |
|        | della  |        |        |        |        | ta     |        |
|        | prog.  |        |        |        |        |        |        |
|        | Esecut |        |        |        |        |        |        |
|        | iva(ar |        |        |        |        |        |        |
|        | t      |        |        |        |        |        |        |
|        | 53     |        |        |        |        |        |        |
|        | comma  |        |        |        |        |        |        |
|        | 2      |        |        |        |        |        |        |
|        | lett.  |        |        |        |        |        |        |
|        | b, c   |        |        |        |        |        |        |
|        | Dlgs   |        |        |        |        |        |        |
|        | 163/20 |        |        |        |        |        |        |
|        | 06)    |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 29     | Data   |        | DATA   | Deve   | B      | Data   |        |
|        | approv |        |        | essere | B      | formal |        |
|        | azione |        |        | un     |        | mente  |        |
|        | del    |        |        | campo  |        | non    |        |
|        | proget |        |        | data   |        | corret |        |
|        | to     |        |        |        |        | ta     |        |
|        | Esecut |        |        | Se     |        |        |        |
|        | ivo    |        |        | digita |        | Data   |        |
|        | (art   |        |        | ta     |        | antece |        |
|        | 53     |        |        | deve   |        | dente  |        |
|        | comma  |        |        | essere |        | la     |        |
|        | 2      |        |        | superi |        | data   |        |
|        | lett.  |        |        | ore    |        | di     |        |
|        | b, c   |        |        | al     |        | inizio |        |
|        | Dlgs   |        |        | campo  |        | proget |        |
|        | 163/20 |        |        | S11.28 |        | tazion |        |
|        | 06)    |        |        |        |        | e      |        |
|        |        |        |        |        |        | esecut |        |
|        |        |        |        |        |        | iva    |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 30.L   | Conseg | O      | FLAG   | Lista  | B      | Selezi |        |
|        | na     |        |        | di     |        | onare  |        |
|        | frazio |        |        | valori |        | un     |        |
|        | nata   |        |        | da     |        | valore |        |
|        |        |        |        | elenco |        | tra    |        |
|        |        |        |        | Vale:  |        | quelli |        |
|        |        |        |        | SI o   |        | previs |        |
|        |        |        |        | NO     |        | ti     |        |
|        |        |        |        | Valore |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | defaul |        |        |        |
|        |        |        |        | t:     |        |        |        |
|        |        |        |        | Blank  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 30.SF  | L'avvi | O      | FLAG   | Lista  | B      | Selezi |        |
|        | o      |        |        | di     |        | onare  |        |
|        | dell'e |        |        | valori |        | un     |        |
|        | secuzi |        |        | da     |        | valore |        |
|        | one    |        |        | elenco |        | tra    |        |
|        | del    |        |        | Vale:  |        | quelli |        |
|        | contra |        |        | SI o   |        | previs |        |
|        | tto    |        |        | NO     |        | ti     |        |
|        | e' per |        |        | Valore |        |        |        |
|        | fasi   |        |        | di     |        |        |        |
|        |        |        |        | defaul |        |        |        |
|        |        |        |        | t:     |        |        |        |
|        |        |        |        | Blank  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 31.L   | Data   | OIF    | DATA   | Se     | B      | Data   |        |
|        | verbal |        |        | valori |        | formal |        |
|        | e      |        |        | zzato  | B      | mente  |        |
|        | prima  |        |        | deve   |        | non    |        |
|        | conseg |        |        | essere | W      | corret |        |
|        | na     |        |        | un     |        | ta     |        |
|        | lavori |        |        | campo  | W      |        |        |
|        |        |        |        | data   |        | Indica |        |
|        |        |        |        |        |        | re     |        |
|        |        |        |        | | Obbl |        | la     |        |
|        |        |        |        | igator |        | data   |        |
|        |        |        |        | ia     |        | del    |        |
|        |        |        |        |   se   |        | verbal |        |
|        |        |        |        |   camp |        | e      |        |
|        |        |        |        | o      |        | di     |        |
|        |        |        |        |   S11. |        | prima  |        |
|        |        |        |        | 30.L   |        | conseg |        |
|        |        |        |        |   vale |        | na     |        |
|        |        |        |        |   “SI” |        | lavori |        |
|        |        |        |        | | Se   |        |        |        |
|        |        |        |        |   camp |        | Verifi |        |
|        |        |        |        | o      |        | care   |        |
|        |        |        |        |   S11. |        | con la |        |
|        |        |        |        | 33     |        | data   |        |
|        |        |        |        |   =    |        | di     |        |
|        |        |        |        |   “NO” |        | stipul |        |
|        |        |        |        |   allo |        | a      |        |
|        |        |        |        | ra     |        | del    |        |
|        |        |        |        |   deve |        | contra |        |
|        |        |        |        |   esse |        | tto    |        |
|        |        |        |        | re     |        |        |        |
|        |        |        |        |   >=   |        | Si è   |        |
|        |        |        |        |   S11. |        | sicuri |        |
|        |        |        |        | 25     |        | del    |        |
|        |        |        |        |        |        | valore |        |
|        |        |        |        | se     |        | della  |        |
|        |        |        |        | l’anno |        | data   |        |
|        |        |        |        | è      |        | digita |        |
|        |        |        |        | superi |        | ta?    |        |
|        |        |        |        | ore    |        |        |        |
|        |        |        |        | all’an |        |        |        |
|        |        |        |        | no     |        |        |        |
|        |        |        |        | in     |        |        |        |
|        |        |        |        | corso  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 31.SF  | Data   | OIF    | DATA   | Se     | B      | Data   |        |
|        | verbal |        |        | valori |        | formal |        |
|        | e      |        |        | zzato  | B      | mente  |        |
|        | di     |        |        | deve   |        | non    |        |
|        | avvio  |        |        | essere | W      | corret |        |
|        | della  |        |        | un     |        | ta     |        |
|        | prima  |        |        | campo  | W      |        |        |
|        | fase   |        |        | data   |        | Indica |        |
|        | dell'e |        |        |        |        | re     |        |
|        | secuzi |        |        | | Obbl |        | la     |        |
|        | one    |        |        | igator |        | data   |        |
|        | del    |        |        | ia     |        | del    |        |
|        | contra |        |        |   se   |        | verbal |        |
|        | tto    |        |        |   camp |        | e      |        |
|        |        |        |        | o      |        | di     |        |
|        |        |        |        |   S11. |        | prima  |        |
|        |        |        |        | 30.SF  |        | conseg |        |
|        |        |        |        |   vale |        | na     |        |
|        |        |        |        |   “SI” |        | lavori |        |
|        |        |        |        | | Se   |        |        |        |
|        |        |        |        |   camp |        | Verifi |        |
|        |        |        |        | o      |        | care   |        |
|        |        |        |        |   S11. |        | con la |        |
|        |        |        |        | 3320   |        | data   |        |
|        |        |        |        |   =    |        | di     |        |
|        |        |        |        |   “NO” |        | stipul |        |
|        |        |        |        |   allo |        | a      |        |
|        |        |        |        | ra     |        | del    |        |
|        |        |        |        |   deve |        | contra |        |
|        |        |        |        |   esse |        | tto    |        |
|        |        |        |        | re     |        |        |        |
|        |        |        |        |   >=   |        | Si è   |        |
|        |        |        |        |   S11. |        | sicuri |        |
|        |        |        |        | 25     |        | del    |        |
|        |        |        |        |        |        | valore |        |
|        |        |        |        | se     |        | della  |        |
|        |        |        |        | l’anno |        | data   |        |
|        |        |        |        | è      |        | digita |        |
|        |        |        |        | superi |        | ta?    |        |
|        |        |        |        | ore    |        |        |        |
|        |        |        |        | all’an |        |        |        |
|        |        |        |        | no     |        |        |        |
|        |        |        |        | in     |        |        |        |
|        |        |        |        | corso  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 32.L   | Data   | OIF    | DATA   | Se     | B      | Data   |        |
|        | verbal |        |        | valori |        | formal |        |
|        | e      |        |        | zzato  | B      | mente  |        |
|        | conseg |        |        | deve   |        | non    |        |
|        | na     |        |        | essere | W      | corret |        |
|        | defini |        |        | un     |        | ta     |        |
|        | tiva   |        |        | campo  | W      |        |        |
|        |        |        |        | data   |        | Data   |        |
|        |        |        |        |        |        | non    |        |
|        |        |        |        | Se     |        | valori |        |
|        |        |        |        | campo  |        | zzata  |        |
|        |        |        |        | S11.30 |        |        |        |
|        |        |        |        | .L     |        | Data   |        |
|        |        |        |        | vale   |        | non    |        |
|        |        |        |        | “NO”   |        | congru |        |
|        |        |        |        | deve   |        | a      |        |
|        |        |        |        | essere |        | con la |        |
|        |        |        |        | compil |        | data   |        |
|        |        |        |        | ata    |        | stipul |        |
|        |        |        |        | obblig |        | a      |        |
|        |        |        |        | atoria |        | contra |        |
|        |        |        |        | mente  |        | tto    |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Se     |        | Si è   |        |
|        |        |        |        | campo  |        | sicuri |        |
|        |        |        |        | S11.33 |        | del    |        |
|        |        |        |        | 20     |        | valore |        |
|        |        |        |        | vale   |        | della  |        |
|        |        |        |        | NO     |        | data   |        |
|        |        |        |        | deve   |        | digita |        |
|        |        |        |        | essere |        | ta?    |        |
|        |        |        |        | >=     |        |        |        |
|        |        |        |        | S11.25 |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Se     |        |        |        |
|        |        |        |        | l’anno |        |        |        |
|        |        |        |        | è      |        |        |        |
|        |        |        |        | superi |        |        |        |
|        |        |        |        | ore    |        |        |        |
|        |        |        |        | all’an |        |        |        |
|        |        |        |        | no     |        |        |        |
|        |        |        |        | in     |        |        |        |
|        |        |        |        | corso  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 32.SF  | Data   | OIF    | DATA   | Se     | B      | Data   |        |
|        | verbal |        |        | valori |        | formal |        |
|        | e      |        |        | zzato  | B      | mente  |        |
|        | di     |        |        | deve   |        | non    |        |
|        | avvio  |        |        | essere | W      | corret |        |
|        | dell'e |        |        | un     |        | ta     |        |
|        | secuzi |        |        | campo  | W      |        |        |
|        | one    |        |        | data   |        | Data   |        |
|        | del    |        |        |        |        | non    |        |
|        | contra |        |        | Se     |        | valori |        |
|        | tto    |        |        | campo  |        | zzata  |        |
|        |        |        |        | S11.30 |        |        |        |
|        |        |        |        | .SF    |        | Data   |        |
|        |        |        |        | vale   |        | non    |        |
|        |        |        |        | “NO”   |        | congru |        |
|        |        |        |        | deve   |        | a      |        |
|        |        |        |        | essere |        | con la |        |
|        |        |        |        | compil |        | data   |        |
|        |        |        |        | ata    |        | stipul |        |
|        |        |        |        | obblig |        | a      |        |
|        |        |        |        | atoria |        | contra |        |
|        |        |        |        | mente  |        | tto    |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Se     |        | Si è   |        |
|        |        |        |        | campo  |        | sicuri |        |
|        |        |        |        | S11.33 |        | del    |        |
|        |        |        |        | vale   |        | valore |        |
|        |        |        |        | NO     |        | della  |        |
|        |        |        |        | deve   |        | data   |        |
|        |        |        |        | essere |        | digita |        |
|        |        |        |        | >=     |        | ta?    |        |
|        |        |        |        | S11.25 |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Se     |        |        |        |
|        |        |        |        | l’anno |        |        |        |
|        |        |        |        | è      |        |        |        |
|        |        |        |        | superi |        |        |        |
|        |        |        |        | ore    |        |        |        |
|        |        |        |        | all’an |        |        |        |
|        |        |        |        | no     |        |        |        |
|        |        |        |        | in     |        |        |        |
|        |        |        |        | corso  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 33     | Conseg | O      | FLAG   | Lista  | B      | Selezi |        |
|        | na     |        |        | di     |        | onare  |        |
|        | sotto  |        |        | valori |        | un     |        |
|        | riserv |        |        | da     |        | valore |        |
|        | a      |        |        | elenco |        | tra    |        |
|        | di     |        |        | Vale:  |        | quelli |        |
|        | legge? |        |        | SI o   |        | previs |        |
|        |        |        |        | NO     |        | ti     |        |
|        |        |        |        | Valore |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | defaul |        |        |        |
|        |        |        |        | t:     |        |        |        |
|        |        |        |        | Blank  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 34     | Data   |        | DATA   | Deve   | B      | Data   |        |
|        | di     |        |        | essere |        | formal |        |
|        | effett |        |        | un     | W      | mente  |        |
|        | ivo    |        |        | campo  |        | non    |        |
|        | inizio |        |        | data   | W      | corret |        |
|        | lavori |        |        |        |        | ta     |        |
|        | /servi |        |        | Se     |        |        |        |
|        | zi/for |        |        | campo  |        | Data   |        |
|        | niture |        |        | S11.33 |        | non    |        |
|        |        |        |        | vale   |        | congru |        |
|        |        |        |        | NO     |        | a      |        |
|        |        |        |        | deve   |        | con la |        |
|        |        |        |        | essere |        | data   |        |
|        |        |        |        | >=     |        | stipul |        |
|        |        |        |        | S11.25 |        | a      |        |
|        |        |        |        |        |        | contra |        |
|        |        |        |        | Se     |        | tto    |        |
|        |        |        |        | l’anno |        |        |        |
|        |        |        |        | è      |        | Si è   |        |
|        |        |        |        | superi |        | sicuri |        |
|        |        |        |        | ore    |        | del    |        |
|        |        |        |        | all’an |        | valore |        |
|        |        |        |        | no     |        | della  |        |
|        |        |        |        | in     |        | data   |        |
|        |        |        |        | corso  |        | digita |        |
|        |        |        |        |        |        | ta?    |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 35     | Data   | OIF    | DATA   | Se     | B      | Data   |        |
|        | fine   |        |        | valori |        | formal |        |
|        | previs |        |        | zzato  | B      | mente  |        |
|        | ta     |        |        | deve   |        | non    |        |
|        | per    |        |        | essere | W      | corret |        |
|        | dare   |        |        | una    |        | ta     |        |
|        | ultima |        |        | data   | W      |        |        |
|        | zione  |        |        | valida |        | Data   |        |
|        | ai     |        |        |        | W      | non    |        |
|        | lavori |        |        | | Se   |        | congru |        |
|        | /servi |        |        |   camp |        | a      |        |
|        | zi/for |        |        | o      |        | con la |        |
|        | niture |        |        |   S11. |        | data   |        |
|        |        |        |        | 30.L   |        | stipul |        |
|        |        |        |        |   o    |        | a      |        |
|        |        |        |        |   S11. |        | contra |        |
|        |        |        |        | 30.SF  |        | tto    |        |
|        |        |        |        |   vale |        | o con  |        |
|        |        |        |        |   NO e |        | data   |        |
|        |        |        |        |   il   |        | di     |        |
|        |        |        |        |   camp |        | effett |        |
|        |        |        |        | o      |        | ivo    |        |
|        |        |        |        |   S11. |        | inizio |        |
|        |        |        |        | 25     |        |        |        |
|        |        |        |        |   è    |        | attenz |        |
|        |        |        |        |   stat |        | ione,  |        |
|        |        |        |        | o      |        | tratta |        |
|        |        |        |        |   comp |        | si     |        |
|        |        |        |        | ilato  |        | di     |        |
|        |        |        |        |   deve |        | conseg |        |
|        |        |        |        |   esse |        | na     |        |
|        |        |        |        | re     |        | frazio |        |
|        |        |        |        |   >    |        | nata   |        |
|        |        |        |        |   S11. |        |        |        |
|        |        |        |        | 25     |        | Si è   |        |
|        |        |        |        |   altr |        | sicuri |        |
|        |        |        |        | imenti |        | del    |        |
|        |        |        |        | | deve |        | valore |        |
|        |        |        |        |   esse |        | della  |        |
|        |        |        |        | re     |        | data   |        |
|        |        |        |        |   > di |        | digita |        |
|        |        |        |        |   camp |        | ta?    |        |
|        |        |        |        | o      |        |        |        |
|        |        |        |        |   S11. |        | Data   |        |
|        |        |        |        | 34     |        | antece |        |
|        |        |        |        |        |        | dente  |        |
|        |        |        |        | Se     |        | la     |        |
|        |        |        |        | campo  |        | data   |        |
|        |        |        |        | S11.30 |        | di     |        |
|        |        |        |        | .L     |        | Scheda |        |
|        |        |        |        | o      |        | Inizio |        |
|        |        |        |        | S11.30 |        | - Data |        |
|        |        |        |        | .SF    |        | Stipul |        |
|        |        |        |        | vale   |        | a”     |        |
|        |        |        |        | SI     |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Se     |        |        |        |
|        |        |        |        | l’anno |        |        |        |
|        |        |        |        | è      |        |        |        |
|        |        |        |        | superi |        |        |        |
|        |        |        |        | ore    |        |        |        |
|        |        |        |        | all’an |        |        |        |
|        |        |        |        | no     |        |        |        |
|        |        |        |        | in     |        |        |        |
|        |        |        |        | corso  |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Se     |        |        |        |
|        |        |        |        | valori |        |        |        |
|        |        |        |        | zzato  |        |        |        |
|        |        |        |        | e      |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S11.25 |        |        |        |
|        |        |        |        | >      |        |        |        |
|        |        |        |        | S11.35 |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **POSI |        |        |        |        |        |        |        |
| ZIONE  |        |        |        |        |        |        |        |
| CONTRI |        |        |        |        |        |        |        |
| BUTIVA |        |        |        |        |        |        |        |
| /ASSIC |        |        |        |        |        |        |        |
| URATIV |        |        |        |        |        |        |        |
| A      |        |        |        |        |        |        |        |
| IMPRES |        |        |        |        |        |        |        |
| A      |        |        |        |        |        |        |        |
| AFFIDA |        |        |        |        |        |        |        |
| TARIA/ |        |        |        |        |        |        |        |
| AGGIUD |        |        |        |        |        |        |        |
| ICATAR |        |        |        |        |        |        |        |
| IA**   |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 36     | RIPETE | Codice | O      | LISTA  | Selezi | B      | E’     |
|        | RE     | fiscal |        | AGGIUD | onare  |        | necess |
|        | PER    | e      |        | ICATAR | un     |        | ario   |
|        | OGNI   | Aggiud |        | I      | aggiud |        | selezi |
|        | IMPRES | icatar |        |        | icatar |        | onare  |
|        | A      | io     |        |        | io     |        | un     |
|        | AFFIDA |        |        |        | indica |        | sogget |
|        | TARIA/ |        |        |        | to     |        | to     |
|        | AGGIUD |        |        |        | nella  |        | per    |
|        | ICATAR |        |        |        | lista  |        | poter  |
|        | IA     |        |        |        | tra    |        | proseg |
|        |        |        |        |        | quelli |        | uire   |
|        |        |        |        |        | inseri |        |        |
|        |        |        |        |        | ti     |        |        |
|        |        |        |        |        | nella  |        |        |
|        |        |        |        |        | scheda |        |        |
|        |        |        |        |        | aggiud |        |        |
|        |        |        |        |        | icazio |        |        |
|        |        |        |        |        | ne     |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 37     |        | Denomi | E      | STRING |        |        |        |
|        |        | nazion |        | A      |        |        |        |
|        |        | e      |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 38     |        | Codice |        | STRING | Se     | W      | Codice |
|        |        | INPS   |        | A      | valori |        | INPS   |
|        |        |        |        |        | zzati  |        | assent |
|        |        |        |        |        | i      |        | e      |
|        |        |        |        |        | campi  |        |        |
|        |        |        |        |        | S11.36 |        |        |
|        |        |        |        |        | e      |        |        |
|        |        |        |        |        | S11.37 |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 39     |        | Codice |        | STRING | Se     | W      | codice |
|        |        | INAIL  |        | A      | valori |        | INAIL  |
|        |        |        |        |        | zzati  |        | assent |
|        |        |        |        |        | i      |        | e      |
|        |        |        |        |        | campi  |        |        |
|        |        |        |        |        | S11.36 |        |        |
|        |        |        |        |        | e      |        |        |
|        |        |        |        |        | S11.37 |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 40     |        | Codice |        | STRING | Se     | W      | Codice |
|        |        | Cassa  |        | A      | valori |        | cassa  |
|        |        | Edile/ |        |        | zzati  |        | edile  |
|        |        | Cassa  |        |        | i      |        | o      |
|        |        | previd |        |        | campi  |        | previd |
|        |        | enza   |        |        | S11.36 |        | enza   |
|        |        | di     |        |        | e      |        | assent |
|        |        | Catego |        |        | S11.37 |        | e      |
|        |        | ria    |        |        |        |        |        |
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
| 41     | PER    | Dati   |        | `DATI_ |        |        |        |
|        | OGNI   | Sogget |        | PERSON |        |        |        |
|        | SOGGET | to     |        | A_FISI |        |        |        |
|        | TO     | incari |        | CA <#d |        |        |        |
|        | INCARI | cato   |        | ati_pe |        |        |        |
|        | CATO   |        |        | rsona_ |        |        |        |
|        |        |        |        | fisica |        |        |        |
|        |        |        |        | >`__   |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 42     |        | Ruolo  | O      | `RUOLI | Lista  | B      | Selezi |
|        |        |        |        | _RESPO | di     |        | onare  |
|        |        |        |        | NSABIL | valori |        | un     |
|        |        |        |        | E <#ru | da     |        | valore |
|        |        |        |        | oli_re | elenco |        | tra    |
|        |        |        |        | sponsa |        |        | quelli |
|        |        |        |        | bile>` |        |        | previs |
|        |        |        |        | __     |        |        | ti     |
+--------+--------+--------+--------+--------+--------+--------+--------+

.. [1]
   Per i CIG associati a gare create anteriormente al 12/05/2014, i CUP
   sono acquisiti in questa scheda e le relative attività di controllo e
   validazione del CUP devono essere effettuate sui dati inseriti nella
   scheda stessa. In tal caso i dati dovranno essere resi disponibili,
   visibili e non editabili anche nella scheda lotto (S02)

   Per i CIG associati a gare create a partire dal 12/05/2014 le
   informazioni devono essere acquisite nella scheda lotto (S02) e rese
   visibili e non modificabili nella scheda di aggiudicazione (S08 o
   S10).

.. [2]
   Per i CIG associati a gare create anteriormente al 12/05/2014, i CUP
   sono acquisiti in questa scheda e le relative attività di controllo e
   validazione del CUP devono essere effettuate sui dati inseriti nella
   scheda stessa. In tal caso i dati dovranno essere resi disponibili,
   visibili e non editabili anche nella scheda lotto (S02)

   Per i CIG associati a gare create a partire dal 12/05/2014 le
   informazioni devono essere acquisite nella scheda lotto (S02) e rese
   visibili e non modificabili nella scheda di aggiudicazione (S08 o
   S10).

.. [3]
    questa sezione viene visualizzata solo in presenza di contratti
   multilotto ed è utilizzata come riferimento per i controlli
   successivi

.. [4]
    questa sezione viene visualizzata solo in presenza di contratti
   multilotto ed è utilizzata come riferimento per i controlli
   successivi
