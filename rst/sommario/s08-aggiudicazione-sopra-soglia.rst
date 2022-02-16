S08 – Aggiudicazione sopra soglia 
==================================

+--------+--------+--------+--------+--------+--------+--------+--------+
| S08    |        |        |        |        |        |        |        |
| –Aggiu |        |        |        |        |        |        |        |
| dicazi |        |        |        |        |        |        |        |
| one    |        |        |        |        |        |        |        |
| sopra  |        |        |        |        |        |        |        |
| soglia |        |        |        |        |        |        |        |
+========+========+========+========+========+========+========+========+
| COD    | ETICHE | TIPO   | FORMAT | CONTRO | MESSAG |        |        |
|        | TTA    |        | O      | LLO    | GIO    |        |        |
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
| OGGETT |        |        |        |        |        |        |        |
| O      |        |        |        |        |        |        |        |
| DELL’A |        |        |        |        |        |        |        |
| PPALTO |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 02     | Codice | P      | `CODIC | Valori | B      | Codice |        |
|        | del    |        | E_ISTA | zzare  |        | ISTAT  |        |
|        | luogo  |        | T <#co | in     |        | obblig |        |
|        | di     |        | dice_i | altern |        | atorio |        |
|        | esecuz |        | stat>` | ativa  |        | se     |        |
|        | ione   |        | __     | al     |        | codice |        |
|        | del    |        |        | campo  |        | NUTS   |        |
|        | contra |        |        | S08.03 |        | non è  |        |
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
|        | contra |        |        | S08.02 |        | non è  |        |
|        | tto    |        |        |        |        | valori |        |
|        | (NUTS) |        |        |        |        | zzato  |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 04     | Codice | P      | STRING | Se     | B      | Il     |        |
|        | CUP    |        | A      | inseri |        | codice |        |
|        | (event | E      |        | to     |        | CUP    |        |
|        | uale)  |        |        | deve   |        | non è  |        |
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
|        | proget |        |        | Obblig |        |        |        |
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
| 05.L   | Modali | O (E)  | `MODAL | lista  |        |        |        |
|        | tà     |        | ITA_AC | di     |        |        |        |
|        | di     |        | QUISIZ | valori |        |        |        |
|        | acquis |        | IONE < | da     |        |        |        |
|        | izione |        | #legge | elenco |        |        |        |
|        |        |        | -8914> |        |        |        |        |
|        |        |        | `__    |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 05.SF  | Modali | OIF    | `MODAL | lista  | B      | Selezi |        |
|        | tà     | (E)    | ITA_AC | di     |        | onare  |        |
|        | di     |        | QUISIZ | valori |        | almeno |        |
|        | acquis |        | IONE < | da     |        | un     |        |
|        | izione |        | #legge | elenco |        | valore |        |
|        | (per   |        | -8914> | richie |        | tra    |        |
|        | serviz |        | `__    | sto    |        | quelli |        |
|        | i      |        |        | se     |        | previs |        |
|        | e      |        |        | S02.07 |        | ti     |        |
|        | fornit |        |        | = SF   |        |        |        |
|        | ure)   |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 06.L   | Tipolo | O      | `TIPOL | Lista  | B      | Selezi |        |
|        | gia    |        | OGIA_L | di     |        | onare  |        |
|        | lavoro |        | AVORO  | valori |        | almeno |        |
|        |        |        | <#tipo | da     |        | un     |        |
|        |        |        | logia_ | elenco |        | valore |        |
|        |        |        | lavoro |        |        | tra    |        |
|        |        |        | >`__   |        |        | quelli |        |
|        |        |        |        |        |        | previs |        |
|        |        |        |        |        |        | ti     |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 06.SF  | Tipolo | OIF    | `TIPOL | Lista  | B      | Selezi |        |
|        | gia    |        | OGIA_L | di     |        | onare  |        |
|        | lavoro |        | AVORO  | valori |        | almeno |        |
|        | (se    |        | <#tipo | da     |        | un     |        |
|        | presen |        | logia_ | elenco |        | valore |        |
|        | te     |        | lavoro |        |        | tra    |        |
|        | la     |        | >`__   | Obblig |        | quelli |        |
|        | compon |        |        | atorio |        | previs |        |
|        | ente   |        |        | se     |        | ti     |        |
|        | lavori |        |        | campo  |        |        |        |
|        | )      |        |        | S08.18 |        |        |        |
|        |        |        |        | .SF    |        |        |        |
|        |        |        |        | > 0    |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 07     | Opere  | O      | FLAG   | | List | B      | Selezi |        |
|        | di     |        |        | a      |        | onare  |        |
|        | urbani |        |        |   di   |        | almeno |        |
|        | zzazio |        |        |   valo |        | un     |        |
|        | ne     |        |        | ri     |        | opzion |        |
|        | a      |        |        |   da   |        | e      |        |
|        | scompu |        |        |   elen |        | per    |        |
|        | to     |        |        | co     |        | tutti  |        |
|        |        |        |        | | Vale |        | i      |        |
|        |        |        |        | :      |        | campi  |        |
|        |        |        |        |   SI o |        | Si/No  |        |
|        |        |        |        |   NO   |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Valore |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | defaul |        |        |        |
|        |        |        |        | t:     |        |        |        |
|        |        |        |        | NULL   |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 08     | Presta | O      | `TIPO_ | Lista  | B      | Selezi |        |
|        | zioni  |        | PRESTA | di     |        | onare  |        |
|        | compre |        | ZIONI  | valori |        | un     |        |
|        | se     |        | <#tipo | da     |        | valore |        |
|        | nell'a |        | _prest | elenco |        | tra    |        |
|        | ppalto |        | azioni |        |        | quelli |        |
|        |        |        | >`__   |        |        | previs |        |
|        |        |        |        |        |        | ti     |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **PRES |        |        |        |        |        |        |        |
| TAZION |        |        |        |        |        |        |        |
| I      |        |        |        |        |        |        |        |
| PROGET |        |        |        |        |        |        |        |
| TUALI* |        |        |        |        |        |        |        |
| *      |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 09     | RIPETE | Tipolo | O      | `TIPO_ | Lista  | B      | Selezi |
|        | RE     | gia    |        | SOGGET | valori |        | onare  |
|        | PER    | del    |        | TO <#t | da     |        | un     |
|        | OGNI   | sogget |        | ipo_so | elenco |        | valore |
|        | SOGGET | to     |        | ggetto |        |        | tra    |
|        | TO     | incari |        | >`__   |        |        | quelli |
|        | INCARI | cato   |        |        |        |        | previs |
|        | CATO   | della  |        |        |        |        | ti     |
|        |        | presta |        |        |        |        |        |
|        |        | zione  |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 10     |        | Dati   | O      | `DATI_ | Il     | B      | E’     |
|        |        | anagra |        | PERSON | sogget |        | necess |
|        |        | fici   |        | A_FISI | to     |        | ario   |
|        |        | del    |        | CA <#d | può    |        | scegli |
|        |        | sogget |        | ati_pe | essere |        | ere    |
|        |        | to     |        | rsona_ | un     |        | un     |
|        |        |        |        | fisica | incari |        | sogget |
|        |        |        |        | >`__   | cato   |        | to     |
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
| 11     |        | CIG    |        | STRING | Valori | W      | Assenz |
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
| 12     |        | Data   | OIF    | DATA   | Valori | B      | Indica |
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
| 13     |        | Data   | OIF    | DATA   | Valori | B      | Indica |
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
| **FINA |        |        |        |        |        |        |        |
| NZIAME |        |        |        |        |        |        |        |
| NTI**  |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 14     | RIPETE | Tipo   | OIF    | `TIPO_ | Obblig | B      | Non è  |
|        | RE     | di     |        | FINANZ | atorio |        | stato  |
|        | PER    | finanz |        | IAMENT | solo   |        | indica |
|        | OGNI   | iament |        | O <#ti | se     |        | to     |
|        | TIPO   | o      |        | po_fin | S02.07 |        | un     |
|        | DI     |        |        | anziam | = L e  |        | finanz |
|        | FINANZ |        |        | ento>` | S01.11 |        | iament |
|        | IAMENT |        |        | __     | =      |        | o      |
|        | O      |        |        |        | ‘ORDIN |        |        |
|        |        |        |        |        | ARIO’  |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        |        | Lista  |        |        |
|        |        |        |        |        | di     |        |        |
|        |        |        |        |        | valori |        |        |
|        |        |        |        |        | da     |        |        |
|        |        |        |        |        | elenco |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 15     |        | Import | OIF    | IMPORT | Obblig | B      | Non è  |
|        |        | o      |        | O      | atorio |        | stato  |
|        |        | finanz |        |        | se     | B      | indica |
|        |        | iament |        |        | S02.07 |        | to     |
|        |        | o      |        |        | = L e  |        | l’impo |
|        |        |        |        |        | S01.11 |        | rto    |
|        |        |        |        |        | =      |        | del    |
|        |        |        |        |        | ‘ORDIN |        | finanz |
|        |        |        |        |        | ARIO’  |        | iament |
|        |        |        |        |        |        |        | o      |
|        |        |        |        |        | Valori |        |        |
|        |        |        |        |        | numeri |        | Il     |
|        |        |        |        |        | ci     |        | campo  |
|        |        |        |        |        | senza  |        | contie |
|        |        |        |        |        | segni  |        | ne     |
|        |        |        |        |        | di     |        | caratt |
|        |        |        |        |        | interp |        | eri    |
|        |        |        |        |        | unzion |        | non    |
|        |        |        |        |        | e      |        | validi |
|        |        |        |        |        | e tre  |        |        |
|        |        |        |        |        | decima |        |        |
|        |        |        |        |        | li     |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 16     | Import | C      | IMPORT | Somma  |        |        |        |
|        | o      |        | O      | import |        |        |        |
|        | totale |        |        | i      |        |        |        |
|        | finanz |        |        | campo  |        |        |        |
|        | iament |        |        | S08.15 |        |        |        |
|        | o      |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **DATI |        |        |        |        |        |        |        |
| ECONOM |        |        |        |        |        |        |        |
| ICI    |        |        |        |        |        |        |        |
| DELL'A |        |        |        |        |        |        |        |
| PPALTO |        |        |        |        |        |        |        |
| **     |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 17     | Codice | OIF    | `TIPO_ | Lista  | B      | selezi |        |
|        | Strume |        | STRUME | di     |        | onare  |        |
|        | nto    |        | NTO <# | valori | W      | un     |        |
|        | di     |        | tipo_s | da     |        | valore |        |
|        | progra |        | trumen | elenco |        | tra    |        |
|        | mmazio |        | to>`__ |        |        | quelli |        |
|        | ne     |        |        | Obblig |        | previs |        |
|        |        |        |        | atorio |        | ti     |        |
|        |        |        |        | se     |        |        |        |
|        |        |        |        | S02.07 |        | Non è  |        |
|        |        |        |        | = L e  |        | stato  |        |
|        |        |        |        | S01.11 |        | selezi |        |
|        |        |        |        | =      |        | onato  |        |
|        |        |        |        | ‘ORDIN |        | lo     |        |
|        |        |        |        | ARIO’  |        | strume |        |
|        |        |        |        |        |        | nto    |        |
|        |        |        |        | se non |        | di     |        |
|        |        |        |        | valori |        | progra |        |
|        |        |        |        | zzato  |        | mmazio |        |
|        |        |        |        | e      |        | ne     |        |
|        |        |        |        | S02.07 |        |        |        |
|        |        |        |        | = SF   |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 18.L   | Import | OIF    | IMPORT | Obblig | B      | Non è  |        |
|        | o      |        | O      | atorio | B      | stato  |        |
|        | compon |        |        | se     | B      | indica |        |
|        | ente   |        |        | S02.07 |        | to     |        |
|        | lavori |        |        | = L    |        | il     |        |
|        | in €   |        |        |        |        | valore |        |
|        | (al    |        |        | Deve   |        | dell’i |        |
|        | netto  |        |        | essere |        | mporto |        |
|        | dell'I |        |        | > 0    |        | compon |        |
|        | VA     |        |        |        |        | ente   |        |
|        | e      |        |        | Valori |        | lavori |        |
|        | degli  |        |        | numeri |        |        |        |
|        | oneri  |        |        | ci     |        | Il     |        |
|        | di     |        |        | senza  |        | valore |        |
|        | sicure |        |        | segni  |        | non    |        |
|        | zza)   |        |        | di     |        | può    |        |
|        |        |        |        | interp |        | essere |        |
|        |        |        |        | unzion |        | negati |        |
|        |        |        |        | e      |        | vo     |        |
|        |        |        |        | e tre  |        |        |        |
|        |        |        |        | decima |        | Il     |        |
|        |        |        |        | li     |        | campo  |        |
|        |        |        |        |        |        | contie |        |
|        |        |        |        |        |        | ne     |        |
|        |        |        |        |        |        | caratt |        |
|        |        |        |        |        |        | eri    |        |
|        |        |        |        |        |        | non    |        |
|        |        |        |        |        |        | validi |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 18.SF  | Import |        | IMPORT | Se     | B      | Il     |        |
|        | o      |        | O      | valori |        | valore |        |
|        | compon |        |        | zzato  |        | digita |        |
|        | ente   |        |        | deve   |        | to     |        |
|        | lavori |        |        | conten |        | contie |        |
|        | in €   |        |        | ere    |        | ne     |        |
|        | (al    |        |        | valori |        | caratt |        |
|        | netto  |        |        | numeri |        | eri    |        |
|        | dell'I |        |        | ci     |        | non    |        |
|        | VA     |        |        | senza  |        | ammess |        |
|        | e      |        |        | segni  |        | i      |        |
|        | degli  |        |        | di     |        |        |        |
|        | oneri  |        |        | interp |        |        |        |
|        | di     |        |        | unzion |        |        |        |
|        | sicure |        |        | e      |        |        |        |
|        | zza)   |        |        | e tre  |        |        |        |
|        |        |        |        | decima |        |        |        |
|        |        |        |        | li     |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 19.L   | Import |        | IMPORT | Valori | B      | Il     |        |
|        | o      |        | O      | numeri |        | valore |        |
|        | compon |        |        | ci     |        | digita |        |
|        | ente   |        |        | senza  |        | to     |        |
|        | serviz |        |        | segni  |        | contie |        |
|        | i      |        |        | di     |        | ne     |        |
|        | in €   |        |        | interp |        | caratt |        |
|        | (come  |        |        | unzion |        | eri    |        |
|        | sopra) |        |        | e      |        | non    |        |
|        |        |        |        | e tre  |        | ammess |        |
|        |        |        |        | decima |        | i.     |        |
|        |        |        |        | li     |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 19.SF  | Import | OIF    | IMPORT | Obblig | B      | Non e' |        |
|        | o      |        | O      | atorio |        | stato  |        |
|        | compon |        |        | se     | B      | indica |        |
|        | ente   |        |        | S02.07 |        | to     |        |
|        | serviz |        |        | = S    |        | il     |        |
|        | i      |        |        |        |        | valore |        |
|        | in €   |        |        | Se     |        | dell'i |        |
|        | (come  |        |        | valori |        | mporto |        |
|        | sopra) |        |        | zzato  |        | compon |        |
|        |        |        |        | valori |        | ente   |        |
|        |        |        |        | numeri |        | serviz |        |
|        |        |        |        | ci     |        | i      |        |
|        |        |        |        | senza  |        |        |        |
|        |        |        |        | segni  |        | Il     |        |
|        |        |        |        | di     |        | valore |        |
|        |        |        |        | interp |        | digita |        |
|        |        |        |        | unzion |        | to     |        |
|        |        |        |        | e      |        | contie |        |
|        |        |        |        | e tre  |        | ne     |        |
|        |        |        |        | decima |        | caratt |        |
|        |        |        |        | li     |        | eri    |        |
|        |        |        |        |        |        | non    |        |
|        |        |        |        |        |        | ammess |        |
|        |        |        |        |        |        | i.     |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 20.L   | Import |        | IMPORT | Valori | B      | Il     |        |
|        | o      |        | O      | numeri |        | valore |        |
|        | compon |        |        | ci     |        | digita |        |
|        | ente   |        |        | senza  |        | to     |        |
|        | fornit |        |        | segni  |        | contie |        |
|        | ure    |        |        | di     |        | ne     |        |
|        | in €   |        |        | interp |        | caratt |        |
|        | (come  |        |        | unzion |        | eri    |        |
|        | sopra) |        |        | e      |        | non    |        |
|        |        |        |        | e tre  |        | ammess |        |
|        |        |        |        | decima |        | i.     |        |
|        |        |        |        | li     |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 20.SF  | Import | OIF    | IMPORT | Obblig | B      | Non e' |        |
|        | o      |        | O      | atorio |        | stato  |        |
|        | compon |        |        | se     | B      | indica |        |
|        | ente   |        |        | S02.07 |        | to     |        |
|        | fornit |        |        | = F    |        | il     |        |
|        | ure    |        |        |        |        | valore |        |
|        | in €   |        |        | Se     |        | dell'i |        |
|        | (come  |        |        | valori |        | mporto |        |
|        | sopra) |        |        | zzato  |        | compon |        |
|        |        |        |        | valori |        | ente   |        |
|        |        |        |        | numeri |        | fornit |        |
|        |        |        |        | ci     |        | ure    |        |
|        |        |        |        | senza  |        |        |        |
|        |        |        |        | segni  |        | Il     |        |
|        |        |        |        | di     |        | valore |        |
|        |        |        |        | interp |        | digita |        |
|        |        |        |        | unzion |        | to     |        |
|        |        |        |        | e      |        | contie |        |
|        |        |        |        | e tre  |        | ne     |        |
|        |        |        |        | decima |        | caratt |        |
|        |        |        |        | li     |        | eri    |        |
|        |        |        |        |        |        | non    |        |
|        |        |        |        |        |        | ammess |        |
|        |        |        |        |        |        | i.     |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 21     | Sub    | C      | IMPORT |        |        |        |        |
|        | Totale |        | O      |        |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        | (Somma |        |        |        |        |
|        |        |        | dei    |        |        |        |        |
|        |        |        | valori |        |        |        |        |
|        |        |        | dei    |        |        |        |        |
|        |        |        | campi  |        |        |        |        |
|        |        |        | S08.18 |        |        |        |        |
|        |        |        | ,      |        |        |        |        |
|        |        |        | S08.19 |        |        |        |        |
|        |        |        | ,      |        |        |        |        |
|        |        |        | S08.20 |        |        |        |        |
|        |        |        | )      |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 22     | Import |        | IMPORT | Valori |        | Il     |        |
|        | o      |        | O      | numeri |        | valore |        |
|        | totale |        |        | ci     |        | digita |        |
|        | per    |        |        | senza  |        | to     |        |
|        | l'attu |        |        | segni  |        | contie |        |
|        | azione |        |        | di     |        | ne     |        |
|        | della  |        |        | interp |        | caratt |        |
|        | sicure |        |        | unzion |        | eri    |        |
|        | zza    |        |        | e      |        | non    |        |
|        |        |        |        | e tre  |        | ammess |        |
|        |        |        |        | decima |        | i.     |        |
|        |        |        |        | li     |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 23     | Eventu |        | IMPORT | Se     |        | Il     |        |
|        | ali    |        | O      | valori |        | valore |        |
|        | ulteri |        |        | zzato  |        | digita |        |
|        | ori    |        |        | valori |        | to     |        |
|        | somme  |        |        | numeri |        | contie |        |
|        | non    |        |        | ci     |        | ne     |        |
|        | assogg |        |        | senza  |        | caratt |        |
|        | ettate |        |        | segni  |        | eri    |        |
|        | al     |        |        | di     |        | non    |        |
|        | ribass |        |        | interp |        | ammess |        |
|        | o      |        |        | unzion |        | i.     |        |
|        | d'asta |        |        | e      |        |        |        |
|        |        |        |        | e tre  |        |        |        |
|        |        |        |        | decima |        |        |        |
|        |        |        |        | li     |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 24     | Import |        | IMPORT | Valori |        | Il     |        |
|        | o      |        | O      | numeri |        | campo  |        |
|        | proget |        |        | ci     |        | contie |        |
|        | tazion |        |        | senza  |        | ne     |        |
|        | e      |        |        | segni  |        | caratt |        |
|        | (art.  |        |        | di     |        | eri    |        |
|        | 53     |        |        | interp |        | non    |        |
|        | comma  |        |        | unzion |        | validi |        |
|        | 2 lett |        |        | e      |        |        |        |
|        | b, c   |        |        | e tre  |        |        |        |
|        | DIgs   |        |        | decima |        |        |        |
|        | 163/20 |        |        | li     |        |        |        |
|        | 06)    |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 25     | Import | E      | IMPORT |        | .. rub |        |        |
|        | o      |        | O      |        | ric::  |        |        |
|        | a base |        |        |        |    :na |        |        |
|        | d'asta |        |        |        | me: se |        |        |
|        | indica |        |        |        | ction  |        |        |
|        | to     |        |        |        |        |        |        |
|        | in     |        |        |        |        |        |        |
|        | acquis |        |        |        |        |        |        |
|        | izione |        |        |        |        |        |        |
|        | CIG    |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 26     | Import | C      | IMPORT | Se il  | W      | L’impo |        |
|        | o      |        | O      | valore |        | rto    |        |
|        | comple |        |        | è <>   | W      | comple |        |
|        | ssivo  |        | (Somma | da     |        | ssivo  |        |
|        | appalt |        | dei    | S02.03 | W      | dell’a |        |
|        | o      |        | valori |        |        | ppalto |        |
|        |        |        | dei    | Se il  |        | è      |        |
|        |        |        | campi  | valore |        | diffor |        |
|        |        |        | S08.21 | è <    |        | me     |        |
|        |        |        | ,      | del    |        | da     |        |
|        |        |        | S08.22 | valore |        | quello |        |
|        |        |        | ,      | sopra  |        | dichia |        |
|        |        |        | S08.23 | soglia |        | rato   |        |
|        |        |        | ,      |        |        | in     |        |
|        |        |        | S08.24 | Se >   |        | sede   |        |
|        |        |        | )      | dell’i |        | di     |        |
|        |        |        |        | ndice  |        | richie |        |
|        |        |        |        | di     |        | sta    |        |
|        |        |        |        | disper |        | CIG    |        |
|        |        |        |        | sione  |        |        |        |
|        |        |        |        | “devia |        | L’impo |        |
|        |        |        |        | zione  |        | rto    |        |
|        |        |        |        | standa |        | comple |        |
|        |        |        |        | rd”    |        | ssivo  |        |
|        |        |        |        |        |        | dell’a |        |
|        |        |        |        |        |        | ppalto |        |
|        |        |        |        |        |        | è      |        |
|        |        |        |        |        |        | inferi |        |
|        |        |        |        |        |        | ore    |        |
|        |        |        |        |        |        | al     |        |
|        |        |        |        |        |        | valore |        |
|        |        |        |        |        |        | sopra  |        |
|        |        |        |        |        |        | soglia |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        |        |        | Verifi |        |
|        |        |        |        |        |        | care   |        |
|        |        |        |        |        |        | la     |        |
|        |        |        |        |        |        | corret |        |
|        |        |        |        |        |        | tezza  |        |
|        |        |        |        |        |        | dell’i |        |
|        |        |        |        |        |        | mporto |        |
|        |        |        |        |        |        | comple |        |
|        |        |        |        |        |        | ssivo  |        |
|        |        |        |        |        |        | appalt |        |
|        |        |        |        |        |        | o      |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 27     | Import | O      | IMPORT | Valori | B      | Non è  |        |
|        | o      |        | O      | zzazio |        | stato  |        |
|        | totale |        |        | ne     | W      | indica |        |
|        | somme  |        |        | (deve  |        | to     |        |
|        | a      |        |        | essere | **     | l’impo |        |
|        | dispos |        |        | >\ **= | **     | rto    |        |
|        | izione |        |        | **     |        | totale |        |
|        |        |        |        | 0 )    | B      | delle  |        |
|        |        |        |        |        |        | somme  |        |
|        |        |        |        | Se     |        | a      |        |
|        |        |        |        | vale 0 |        | dispos |        |
|        |        |        |        |        |        | izione |        |
|        |        |        |        | Valori |        |        |        |
|        |        |        |        | numeri |        | Non    |        |
|        |        |        |        | ci     |        | sono   |        |
|        |        |        |        | senza  |        | state  |        |
|        |        |        |        | segni  |        | indica |        |
|        |        |        |        | di     |        | te     |        |
|        |        |        |        | interp |        | le     |        |
|        |        |        |        | unzion |        | somme  |        |
|        |        |        |        | e      |        | a      |        |
|        |        |        |        | e tre  |        | dispos |        |
|        |        |        |        | decima |        | izione |        |
|        |        |        |        | li     |        |        |        |
|        |        |        |        |        |        | Il     |        |
|        |        |        |        |        |        | valore |        |
|        |        |        |        |        |        | digita |        |
|        |        |        |        |        |        | to     |        |
|        |        |        |        |        |        | contie |        |
|        |        |        |        |        |        | ne     |        |
|        |        |        |        |        |        | caratt |        |
|        |        |        |        |        |        | eri    |        |
|        |        |        |        |        |        | non    |        |
|        |        |        |        |        |        | ammess |        |
|        |        |        |        |        |        | i.     |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 28     | Import | C      | NUMERI | Se     | W      | L’impo |        |
|        | o      |        | CO     | campo  |        | rto    |        |
|        | comple |        |        | S08.16 |        | comple |        |
|        | ssivo  |        | (Somma | > 0 e  |        | ssivo  |        |
|        | dell'i |        | dei    | S08.28 |        | degli  |        |
|        | nterve |        | valori | >      |        | interv |        |
|        | nto    |        | dei    | S08.16 |        | enti   |        |
|        |        |        | campi  |        |        | non è  |        |
|        |        |        | S08.26 |        |        | intera |        |
|        |        |        | e      |        |        | mente  |        |
|        |        |        | S08.27 |        |        | copert |        |
|        |        |        | )      |        |        | o      |        |
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
| 29     | Proced | O      | `SCELT | Lista  | B      | Selezi |        |
|        | ura    |        | A_CONT | di     |        | onare  |        |
|        | di     |        | RAENTE | valori |        | un     |        |
|        | scelta |        |  <#sce | da     |        | valore |        |
|        | contra |        | lta_co | elenco |        | tra    |        |
|        | ente   |        | ntraen |        |        | quelli |        |
|        |        |        | te>`__ |        |        | previs |        |
|        |        |        |        |        |        | ti     |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 30     | Modali | OIF    | `MODAL | Da     | B      | Selezi |        |
|        | tà     |        | ITA_RI | valori |        | onare  |        |
|        | di     |        | AGGIUD | zzare  |        | un     |        |
|        | riaggi |        | ICAZIO | in     |        | valore |        |
|        | udicaz |        | NE <#m | caso   |        | tra    |        |
|        | ione/a |        | odalit | di     |        | quelli |        |
|        | ffidam |        | a_riag | riaggi |        | previs |        |
|        | ento   |        | giudic | udicaz |        | ti     |        |
|        | dell'a |        | azione | ione   |        |        |        |
|        | ppalto |        | >`__   | o      |        |        |        |
|        |        |        |        | affida |        |        |        |
|        |        |        |        | mento  |        |        |        |
|        |        |        |        | a      |        |        |        |
|        |        |        |        | seguit |        |        |        |
|        |        |        |        | o      |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | interr |        |        |        |
|        |        |        |        | uzione |        |        |        |
|        |        |        |        | antici |        |        |        |
|        |        |        |        | pata   |        |        |        |
|        |        |        |        | del    |        |        |        |
|        |        |        |        | contra |        |        |        |
|        |        |        |        | tto    |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Lista  |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | valori |        |        |        |
|        |        |        |        | da     |        |        |        |
|        |        |        |        | elenco |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 31     | Ricors | O      | FLAG   | Lista  | B      | Selezi |        |
|        | o      |        |        | di     |        | onare  |        |
|        | all'as |        |        | valori |        | almeno |        |
|        | ta     |        |        | da     |        | un     |        |
|        | elettr |        |        | elenco |        | opzion |        |
|        | onica  |        |        |        |        | e      |        |
|        |        |        |        | Vale:  |        | per    |        |
|        |        |        |        | SI o   |        | tutti  |        |
|        |        |        |        | NO     |        | i      |        |
|        |        |        |        |        |        | campi  |        |
|        |        |        |        | Defaul |        | Si/No  |        |
|        |        |        |        | t:     |        |        |        |
|        |        |        |        | Blank  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 32     | Condiz | OIF    | `CONDI | Lista  | B      | Selezi |        |
|        | ioni   |        | ZIONI_ | valori |        | onare  |        |
|        | che    |        | NEGOZI | da     |        | almeno |        |
|        | giusti |        | ATA <# | elenco |        | un     |        |
|        | ficano |        | condiz |        |        | valore |        |
|        | il     |        | ioni_n | Valori |        | tra    |        |
|        | ricors |        | egozia | zzazio |        | quelli |        |
|        | o      |        | ta>`__ | ne     |        | previs |        |
|        | alla   |        |        | se il  |        | ti     |        |
|        | proced |        |        | campo  |        |        |        |
|        | ura    |        |        | S08.29 |        |        |        |
|        | negozi |        |        | = 10 o |        |        |        |
|        | ata    |        |        | S08.29 |        |        |        |
|        | senza  |        |        | = 4    |        |        |        |
|        | previa |        |        |        |        |        |        |
|        | pubbli |        |        |        |        |        |        |
|        | cazion |        |        |        |        |        |        |
|        | e      |        |        |        |        |        |        |
|        | di un  |        |        |        |        |        |        |
|        | bando  |        |        |        |        |        |        |
|        | oppure |        |        |        |        |        |        |
|        | senza  |        |        |        |        |        |        |
|        | previa |        |        |        |        |        |        |
|        | indizi |        |        |        |        |        |        |
|        | one    |        |        |        |        |        |        |
|        | di una |        |        |        |        |        |        |
|        | gara   |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 33     | Criter | OIF    | `CRITE | Lista  | B      | “Selez |        |
|        | i      |        | RI_AGG | di     |        | ionare |        |
|        | di     |        | IUDICA | valori |        | un     |        |
|        | aggiud |        | ZIONE  | da     |        | valore |        |
|        | icazio |        | <#crit | elenco |        | tra    |        |
|        | ne     |        | eri_ag |        |        | quelli |        |
|        |        |        | giudic | Obblig |        | previs |        |
|        |        |        | azione | atorio |        | ti”    |        |
|        |        |        | >`__   | se     |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S08.32 |        |        |        |
|        |        |        |        | <> 2,  |        |        |        |
|        |        |        |        | 5, 7,  |        |        |        |
|        |        |        |        | 9, 10, |        |        |        |
|        |        |        |        | 11,    |        |        |        |
|        |        |        |        | 14,    |        |        |        |
|        |        |        |        | 16,    |        |        |        |
|        |        |        |        | 17,    |        |        |        |
|        |        |        |        | 18,    |        |        |        |
|        |        |        |        | 23,    |        |        |        |
|        |        |        |        | 24, 28 |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 34     | E'     | O      | FLAG   | Lista  | B      | Selezi |        |
|        | stata  |        |        | di     |        | onare  |        |
|        | utiliz |        |        | valori |        | un     |        |
|        | zata   |        |        | da     |        | valore |        |
|        | la     |        |        | elenco |        | tra    |        |
|        | proced |        |        |        |        | quelli |        |
|        | ura    |        |        | Vale:  |        | previs |        |
|        | accele |        |        | SI o   |        | ti     |        |
|        | rata   |        |        | NO     |        |        |        |
|        | per    |        |        |        |        |        |        |
|        | ragion |        |        | Defaul |        |        |        |
|        | i      |        |        | t:     |        |        |        |
|        | di     |        |        | NO     |        |        |        |
|        | urgenz |        |        |        |        |        |        |
|        | a?     |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 35     | E'     | O      | FLAG   | Lista  | B      | Selezi |        |
|        | stata  |        |        | di     |        | onare  |        |
|        | effett |        |        | valori |        | un     |        |
|        | uata   |        |        | da     |        | valore |        |
|        | la     |        |        | elenco |        | tra    |        |
|        | preinf |        |        |        |        | quelli |        |
|        | ormazi |        |        | Vale:  |        | previs |        |
|        | one?   |        |        | SI o   |        | ti     |        |
|        |        |        |        | NO     |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Defaul |        |        |        |
|        |        |        |        | t:     |        |        |        |
|        |        |        |        | NO     |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 36     | E'     | O      | FLAG   | Lista  | B      | Selezi |        |
|        | stato  |        |        | di     |        | onare  |        |
|        | utiliz |        |        | valori |        | un     |        |
|        | zato   |        |        | da     |        | valore |        |
|        | un     |        |        | elenco |        | tra    |        |
|        | termin |        |        |        |        | quelli |        |
|        | e      |        |        | Vale:  |        | previs |        |
|        | ridott |        |        | SI o   |        | ti     |        |
|        | o      |        |        | NO     |        |        |        |
|        | con    |        |        |        |        |        |        |
|        | avviso |        |        | Defaul |        |        |        |
|        | di     |        |        | t:     |        |        |        |
|        | preinf |        |        | NO     |        |        |        |
|        | ormazi |        |        |        |        |        |        |
|        | one?   |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 37     | Modali | OIF    | `MODAL | Se non | B      | Non è  |        |
|        | tà     |        | ITA_IN | valori |        | stata  |        |
|        | di     |        | DIZION | zzato  |        | selezi |        |
|        | indizi |        | E <#mo | e il   |        | onata  |        |
|        | one    |        | dalita | CIG    |        | la     |        |
|        | della  |        | _indiz | appart |        | Modali |        |
|        | gara   |        | ione>` | iene   |        | tà     |        |
|        | (art.  |        | __     | ai     |        | di     |        |
|        | 224 c. |        |        | settor |        | indizi |        |
|        | 1)     |        |        | i      |        | one    |        |
|        | Settor |        |        | specia |        | della  |        |
|        | i      |        |        | li     |        | gara   |        |
|        | Specia |        |        | e      |        | (art.  |        |
|        | li     |        |        | campo  |        | 224 c. |        |
|        |        |        |        | S08.29 |        | 1)     |        |
|        |        |        |        | <> 10  |        | Settor |        |
|        |        |        |        | e      |        | i      |        |
|        |        |        |        | S08.29 |        | Specia |        |
|        |        |        |        | <> 11  |        | li     |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Lista  |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | valori |        |        |        |
|        |        |        |        | da     |        |        |        |
|        |        |        |        | elenco |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **REQU |        |        |        |        |        |        |        |
| ISITI  |        |        |        |        |        |        |        |
| DI     |        |        |        |        |        |        |        |
| PARTEC |        |        |        |        |        |        |        |
| IPAZIO |        |        |        |        |        |        |        |
| NE     |        |        |        |        |        |        |        |
| /      |        |        |        |        |        |        |        |
| QUALIF |        |        |        |        |        |        |        |
| ICAZIO |        |        |        |        |        |        |        |
| NE**   |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 38     | Requis | Criter |        | FLAG   | | Vali | B      | Selezi |
|        | iti    | i      |        |        | do     |        | onare  |
|        | Settor | di     |        |        |   se   |        | un     |
|        | i      | selezi |        |        |   S01. |        | valore |
|        | Specia | one    |        |        | 11     |        | tra    |
|        | li     | stabil |        |        |   =    |        | quelli |
|        |        | iti    |        |        |   ‘SPE |        | previs |
|        |        | dalla  |        |        | CIALE’ |        | ti     |
|        |        | stazio |        |        | | Vale |        |        |
|        |        | ne     |        |        | :      |        |        |
|        |        | appalt |        |        |   SI o |        |        |
|        |        | ante   |        |        |   NO   |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        |        | Defaul |        |        |
|        |        |        |        |        | t:     |        |        |
|        |        |        |        |        | NULL   |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 39     |        | Sistem |        | FLAG   | | Vali | B      | Selezi |
|        |        | a      |        |        | do     |        | onare  |
|        |        | di     |        |        |   se   |        | un     |
|        |        | qualif |        |        |   S01. |        | valore |
|        |        | icazio |        |        | 11     |        | tra    |
|        |        | ne     |        |        |   =    |        | quelli |
|        |        | intern |        |        |   ‘SPE |        | previs |
|        |        | o      |        |        | CIALE’ |        | ti     |
|        |        |        |        |        | | Vale |        |        |
|        |        |        |        |        | :      |        |        |
|        |        |        |        |        |   SI o |        |        |
|        |        |        |        |        |   NO   |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        |        | Defaul |        |        |
|        |        |        |        |        | t:     |        |        |
|        |        |        |        |        | NULL   |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 40     | RIPETE | Catego | OIF    | `CATEG | Lista  | B      | Selezi |
|        | RE     | ria    |        | ORIA < | di     |        | onare  |
|        | PER    |        |        | #categ | valori | B      | un     |
|        | OGNI   |        |        | oria>` | da     |        | valore |
|        | REQUIS |        |        | __     | elenco | W      | tra    |
|        | ITO    |        |        |        | catego |        | quelli |
|        |        |        |        |        | rie    |        | previs |
|        |        |        |        |        | lavori |        | ti     |
|        |        |        |        |        |        |        |        |
|        |        |        |        |        | Se non |        | Defini |
|        |        |        |        |        | valori |        | re     |
|        |        |        |        |        | zzato  |        | un     |
|        |        |        |        |        | e se   |        | codice |
|        |        |        |        |        | S01.11 |        | catego |
|        |        |        |        |        | =      |        | ria    |
|        |        |        |        |        | ‘ORDIN |        |        |
|        |        |        |        |        | ARIO’  |        | Non è  |
|        |        |        |        |        |        |        | stata  |
|        |        |        |        |        | Se non |        | selezi |
|        |        |        |        |        | valori |        | onata  |
|        |        |        |        |        | zzato  |        | la     |
|        |        |        |        |        | e se   |        | Catego |
|        |        |        |        |        | S01.11 |        | ria    |
|        |        |        |        |        | =      |        | scorpo |
|        |        |        |        |        | ‘ORDIN |        | rabile |
|        |        |        |        |        | ARIO’  |        | /      |
|        |        |        |        |        | e      |        | subapp |
|        |        |        |        |        | S08.43 |        | altabi |
|        |        |        |        |        | = NO   |        | le     |
|        |        |        |        |        |        |        |        |
|        |        |        |        |        | e      |        |        |
|        |        |        |        |        | S08.44 |        |        |
|        |        |        |        |        | = NO   |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 41     |        | Classe | OIF    | `CLASS | Lista  | B      | Selezi |
|        |        | d’Impo |        | I_IMPO | di     |        | onare  |
|        |        | rto    |        | RTO <# | valori |        | un     |
|        |        |        |        | catego | da     |        | valore |
|        |        |        |        | rie-me | elenco |        | tra    |
|        |        |        |        | rceolo |        |        | quelli |
|        |        |        |        | giche> | solo   |        | previs |
|        |        |        |        | `__    | se     |        | ti     |
|        |        |        |        |        | S01.11 |        |        |
|        |        |        |        |        | =      |        |        |
|        |        |        |        |        | ‘ORDIN |        |        |
|        |        |        |        |        | ARIO’  |        |        |
|        |        |        |        |        | e      |        |        |
|        |        |        |        |        | S08.40 |        |        |
|        |        |        |        |        | è      |        |        |
|        |        |        |        |        | valori |        |        |
|        |        |        |        |        | zzato  |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 42     |        | La     |        | FLAG   | | List | B      | Defini |
|        |        | catego |        |        | a      |        | re     |
|        |        | ria    |        |        |   di   |        | una    |
|        |        | è      |        |        |   valo |        | catego |
|        |        | Preval |        |        | ri     |        | ria    |
|        |        | ente   |        |        |   da   |        | preval |
|        |        |        |        |        |   elen |        | ente   |
|        |        |        |        |        | co     |        |        |
|        |        |        |        |        | | Vale |        |        |
|        |        |        |        |        | :      |        |        |
|        |        |        |        |        |   SI o |        |        |
|        |        |        |        |        |   NO   |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        |        | Valore |        |        |
|        |        |        |        |        | di     |        |        |
|        |        |        |        |        | defaul |        |        |
|        |        |        |        |        | t:     |        |        |
|        |        |        |        |        | Blank  |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        |        | Se non |        |        |
|        |        |        |        |        | valori |        |        |
|        |        |        |        |        | zzato  |        |        |
|        |        |        |        |        | se     |        |        |
|        |        |        |        |        | S01.11 |        |        |
|        |        |        |        |        | =      |        |        |
|        |        |        |        |        | ‘ORDIN |        |        |
|        |        |        |        |        | ARIO’  |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 43     |        | La     |        | FLAG   | | List | W      | Non e' |
|        |        | catego |        |        | a      |        | stata  |
|        |        | ria    |        |        |   di   |        | selezi |
|        |        | è      |        |        |   valo |        | onata  |
|        |        | Scorpo |        |        | ri     |        | la     |
|        |        | rabile |        |        |   da   |        | Catego |
|        |        |        |        |        |   elen |        | ria    |
|        |        |        |        |        | co     |        | Scorpo |
|        |        |        |        |        | | Vale |        | rabile |
|        |        |        |        |        | :      |        | /      |
|        |        |        |        |        |   SI o |        | Sub-Ap |
|        |        |        |        |        |   NO   |        | paltab |
|        |        |        |        |        |        |        | ile    |
|        |        |        |        |        | Valore |        |        |
|        |        |        |        |        | di     |        |        |
|        |        |        |        |        | defaul |        |        |
|        |        |        |        |        | t:     |        |        |
|        |        |        |        |        | Blank  |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        |        | Se non |        |        |
|        |        |        |        |        | valori |        |        |
|        |        |        |        |        | zzato  |        |        |
|        |        |        |        |        | se     |        |        |
|        |        |        |        |        | S01.11 |        |        |
|        |        |        |        |        | =      |        |        |
|        |        |        |        |        | ‘ORDIN |        |        |
|        |        |        |        |        | ARIO’  |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 44     |        | La     |        | FLAG   | | List | W      | Non e' |
|        |        | catego |        |        | a      |        | stata  |
|        |        | ria    |        |        |   di   |        | selezi |
|        |        | è      |        |        |   valo |        | onata  |
|        |        | Sub-Ap |        |        | ri     |        | la     |
|        |        | paltab |        |        |   da   |        | Catego |
|        |        | ile    |        |        |   elen |        | ria    |
|        |        |        |        |        | co     |        | Scorpo |
|        |        |        |        |        | | Vale |        | rabile |
|        |        |        |        |        | :      |        | /      |
|        |        |        |        |        |   SI o |        | Sub-Ap |
|        |        |        |        |        |   NO   |        | paltab |
|        |        |        |        |        |        |        | ile    |
|        |        |        |        |        | Valore |        |        |
|        |        |        |        |        | di     |        |        |
|        |        |        |        |        | defaul |        |        |
|        |        |        |        |        | t:     |        |        |
|        |        |        |        |        | NO     |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        |        | Se non |        |        |
|        |        |        |        |        | valori |        |        |
|        |        |        |        |        | zzato  |        |        |
|        |        |        |        |        | se     |        |        |
|        |        |        |        |        | S01.11 |        |        |
|        |        |        |        |        | =      |        |        |
|        |        |        |        |        | ‘ORDIN |        |        |
|        |        |        |        |        | ARIO’  |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **INVI |        |        |        |        |        |        |        |
| TI     |        |        |        |        |        |        |        |
| E      |        |        |        |        |        |        |        |
| OFFERT |        |        |        |        |        |        |        |
| E      |        |        |        |        |        |        |        |
| /      |        |        |        |        |        |        |        |
| SOGLIA |        |        |        |        |        |        |        |
| DI     |        |        |        |        |        |        |        |
| ANOMAL |        |        |        |        |        |        |        |
| IA**   |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 45     | Data   | OIF    | DATA   | Se     | B      | Data   |        |
|        | di     |        |        | valori |        | formal |        |
|        | scaden |        |        | zzato  | W      | mente  |        |
|        | za     |        |        | deve   |        | non    |        |
|        | per la |        |        | essere |        | corret |        |
|        | presen |        |        | un     |        | ta     |        |
|        | tazion |        |        | campo  |        |        |        |
|        | e      |        |        | data   |        | Non è  |        |
|        | delle  |        |        | formal |        | stata  |        |
|        | manife |        |        | mente  |        | indica |        |
|        | stazio |        |        | valido |        | ta     |        |
|        | ni     |        |        |        |        | la     |        |
|        | di     |        |        | Deve   |        | data   |        |
|        | intere |        |        | essere |        | di     |        |
|        | sse    |        |        | valori |        | scaden |        |
|        |        |        |        | zzato  |        | za     |        |
|        |        |        |        | se il  |        | per la |        |
|        |        |        |        | campo  |        | presen |        |
|        |        |        |        | S08.37 |        | tazion |        |
|        |        |        |        | = 1    |        | e      |        |
|        |        |        |        |        |        | delle  |        |
|        |        |        |        |        |        | manife |        |
|        |        |        |        |        |        | stazio |        |
|        |        |        |        |        |        | ni     |        |
|        |        |        |        |        |        | di     |        |
|        |        |        |        |        |        | intere |        |
|        |        |        |        |        |        | sse    |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 46     | Data   | OIF    | DATA   | Se     | B      | Data   |        |
|        | di     |        |        | valori |        | formal |        |
|        | scaden |        |        | zzato  | W      | mente  |        |
|        | za     |        |        | deve   |        | non    |        |
|        | per la |        |        | essere | B      | corret |        |
|        | presen |        |        | un     |        | ta     |        |
|        | tazion |        |        | campo  |        |        |        |
|        | e      |        |        | data   |        | Non è  |        |
|        | della  |        |        | formal |        | stata  |        |
|        | richie |        |        | mente  |        | indica |        |
|        | sta    |        |        | valido |        | ta     |        |
|        | di     |        |        |        |        | la     |        |
|        | invito |        |        | Deve   |        | data   |        |
|        |        |        |        | essere |        | di     |        |
|        |        |        |        | valori |        | scaden |        |
|        |        |        |        | zzato  |        | za     |        |
|        |        |        |        | se il  |        | per la |        |
|        |        |        |        | campo  |        | presen |        |
|        |        |        |        | S08.29 |        | tazion |        |
|        |        |        |        | = 2 o  |        | e      |        |
|        |        |        |        | S08.29 |        | della  |        |
|        |        |        |        | = 9    |        | richie |        |
|        |        |        |        |        |        | sta    |        |
|        |        |        |        | Non    |        | di     |        |
|        |        |        |        | deve   |        | invito |        |
|        |        |        |        | essere |        | (NON è |        |
|        |        |        |        | valori |        | MOSTRA |        |
|        |        |        |        | zzato  |        | TO)    |        |
|        |        |        |        | se     |        |        |        |
|        |        |        |        | campo  |        | Il     |        |
|        |        |        |        | S08.29 |        | campo  |        |
|        |        |        |        | <> 2 o |        | data   |        |
|        |        |        |        | S08.29 |        | di     |        |
|        |        |        |        | <> 9   |        | scaden |        |
|        |        |        |        |        |        | za     |        |
|        |        |        |        |        |        | per la |        |
|        |        |        |        |        |        | presen |        |
|        |        |        |        |        |        | tazion |        |
|        |        |        |        |        |        | e      |        |
|        |        |        |        |        |        | della  |        |
|        |        |        |        |        |        | richie |        |
|        |        |        |        |        |        | sta    |        |
|        |        |        |        |        |        | di     |        |
|        |        |        |        |        |        | invito |        |
|        |        |        |        |        |        | non    |        |
|        |        |        |        |        |        | deve   |        |
|        |        |        |        |        |        | essere |        |
|        |        |        |        |        |        | valori |        |
|        |        |        |        |        |        | zzato  |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 47     | Data   |        | DATA   | se     | B      | Data   |        |
|        | Invito |        |        | valori |        | formal |        |
|        |        |        |        | zzato  |        | mente  |        |
|        |        |        |        | deve   |        | non    |        |
|        |        |        |        | essere |        | corret |        |
|        |        |        |        | un     |        | ta     |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | data   |        |        |        |
|        |        |        |        | formal |        |        |        |
|        |        |        |        | mente  |        |        |        |
|        |        |        |        | valido |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 48     | Data   | O      | DATA   | se     | B      | Data   |        |
|        | di     |        |        | valori |        | formal |        |
|        | scaden |        |        | zzato  | B      | mente  |        |
|        | za     |        |        | deve   |        | non    |        |
|        | per la |        |        | essere |        | corret |        |
|        | presen |        |        | un     |        | ta     |        |
|        | tazion |        |        | campo  |        |        |        |
|        | e      |        |        | data   |        | Non è  |        |
|        | delle  |        |        | formal |        | stata  |        |
|        | offert |        |        | mente  |        | indica |        |
|        | e      |        |        | valido |        | ta     |        |
|        |        |        |        |        |        | la     |        |
|        |        |        |        | Se non |        | data   |        |
|        |        |        |        | valori |        | di     |        |
|        |        |        |        | zzato  |        | scaden |        |
|        |        |        |        |        |        | za     |        |
|        |        |        |        |        |        | per la |        |
|        |        |        |        |        |        | presen |        |
|        |        |        |        |        |        | tazion |        |
|        |        |        |        |        |        | e      |        |
|        |        |        |        |        |        | delle  |        |
|        |        |        |        |        |        | offert |        |
|        |        |        |        |        |        | e      |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 49     | n°     | OIF    | NUMERI | se     | B      | Dato   |        |
|        | Sogget |        | CO     | valori |        | formal |        |
|        | ti     |        |        | zzato  | B      | mente  |        |
|        | che    |        |        | deve   |        | non    |        |
|        | hanno  |        |        | essere |        | corret |        |
|        | presen |        |        | un     |        | to     |        |
|        | tato   |        |        | valore |        |        |        |
|        | manife |        |        | numeri |        | Non è  |        |
|        | stazio |        |        | co     |        | stato  |        |
|        | ne     |        |        | > 0    |        | indica |        |
|        | di     |        |        | (numer |        | to     |        |
|        | intere |        |        | o      |        | il n.  |        |
|        | sse    |        |        | intero |        | sogget |        |
|        |        |        |        | )      |        | ti     |        |
|        |        |        |        |        |        | che    |        |
|        |        |        |        | deve   |        | hanno  |        |
|        |        |        |        | essere |        | presen |        |
|        |        |        |        | valori |        | tato   |        |
|        |        |        |        | zzato  |        | manife |        |
|        |        |        |        | se     |        | stazio |        |
|        |        |        |        | valori |        | ne     |        |
|        |        |        |        | zzato  |        | di     |        |
|        |        |        |        | il     |        | intere |        |
|        |        |        |        | campo  |        | sse    |        |
|        |        |        |        | S08.45 |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 50     | n°     | OIF    | NUMERI | valore | B      | Dato   |        |
|        | Sogget |        | CO     | di     |        | formal |        |
|        | ti     |        |        | defaul | W      | mente  |        |
|        | che    |        |        | t=NULL |        | non    |        |
|        | hanno  |        |        |        |        | corret |        |
|        | presen |        |        | Se     |        | to     |        |
|        | tato   |        |        | valori |        |        |        |
|        | richie |        |        | zzato  |        | Non è  |        |
|        | sta    |        |        | deve   |        | stato  |        |
|        | di     |        |        | essere |        | indica |        |
|        | invito |        |        | un     |        | to     |        |
|        |        |        |        | valore |        | il n.  |        |
|        |        |        |        | numeri |        | sogget |        |
|        |        |        |        | co     |        | ti     |        |
|        |        |        |        | >= 0   |        | che    |        |
|        |        |        |        | (numer |        | hanno  |        |
|        |        |        |        | o      |        | presen |        |
|        |        |        |        | intero |        | tato   |        |
|        |        |        |        | )      |        | richie |        |
|        |        |        |        |        |        | sta    |        |
|        |        |        |        | deve   |        | di     |        |
|        |        |        |        | essere |        | invito |        |
|        |        |        |        | valori |        |        |        |
|        |        |        |        | zzato  |        |        |        |
|        |        |        |        | se     |        |        |        |
|        |        |        |        | valori |        |        |        |
|        |        |        |        | zzato  |        |        |        |
|        |        |        |        | il     |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S08.46 |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 51     | n°     | OIF    | NUMERI | valore | B      | Dato   |        |
|        | Sogget |        | CO     | di     | W      | formal |        |
|        | ti     |        |        | defaul |        | mente  |        |
|        | invita |        |        | t=NULL |        | non    |        |
|        | ti     |        |        |        |        | corret |        |
|        | a      |        |        | Se     |        | to     |        |
|        | presen |        |        | valori |        |        |        |
|        | tare   |        |        | zzato  |        | Non è  |        |
|        | offert |        |        | deve   |        | stato  |        |
|        | a      |        |        | essere |        | indica |        |
|        |        |        |        | un     |        | to     |        |
|        |        |        |        | valore |        | il n.  |        |
|        |        |        |        | numeri |        | di     |        |
|        |        |        |        | co     |        | sogget |        |
|        |        |        |        | > 0    |        | ti     |        |
|        |        |        |        | (numer |        | ammess |        |
|        |        |        |        | o      |        | i      |        |
|        |        |        |        | intero |        | a      |        |
|        |        |        |        | )      |        | presen |        |
|        |        |        |        |        |        | tare   |        |
|        |        |        |        | deve   |        | offert |        |
|        |        |        |        | essere |        | a      |        |
|        |        |        |        | valori |        |        |        |
|        |        |        |        | zzato  |        |        |        |
|        |        |        |        | se     |        |        |        |
|        |        |        |        | valori |        |        |        |
|        |        |        |        | zzato  |        |        |        |
|        |        |        |        | il     |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S08.47 |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 52     | n°     | OIF    | NUMERI | valore | B      | Dato   |        |
|        | Sogget |        | CO     | di     |        | formal |        |
|        | ti     |        | (numer | defaul | W      | mente  |        |
|        | che    |        | o      | t=NULL |        | non    |        |
|        | hanno  |        | intero |        |        | corret |        |
|        | presen |        | )      | | Se   |        | to     |        |
|        | tato   |        |        |   valo |        |        |        |
|        | offert |        |        | rizzat |        | Non è  |        |
|        | a      |        |        | o      |        | stato  |        |
|        |        |        |        |   deve |        | indica |        |
|        |        |        |        |   esse |        | to     |        |
|        |        |        |        | re     |        | il n.  |        |
|        |        |        |        |   un   |        | sogget |        |
|        |        |        |        |   valo |        | ti     |        |
|        |        |        |        | re     |        | che    |        |
|        |        |        |        |   nume |        | hanno  |        |
|        |        |        |        | rico   |        | presen |        |
|        |        |        |        |   >\ [ |        | tato   |        |
|        |        |        |        | STRIKE |        | offert |        |
|        |        |        |        | OUT:=] |        | a      |        |
|        |        |        |        |   0    |        |        |        |
|        |        |        |        |   inol |        |        |        |
|        |        |        |        | tre    |        |        |        |
|        |        |        |        | | se   |        |        |        |
|        |        |        |        |   camp |        |        |        |
|        |        |        |        | o      |        |        |        |
|        |        |        |        |   S08. |        |        |        |
|        |        |        |        | 51     |        |        |        |
|        |        |        |        |   > 0  |        |        |        |
|        |        |        |        |   allo |        |        |        |
|        |        |        |        | ra     |        |        |        |
|        |        |        |        |   S08. |        |        |        |
|        |        |        |        | 52     |        |        |        |
|        |        |        |        |   deve |        |        |        |
|        |        |        |        |   esse |        |        |        |
|        |        |        |        | re     |        |        |        |
|        |        |        |        |   <=   |        |        |        |
|        |        |        |        |   S08. |        |        |        |
|        |        |        |        | 51     |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Se non |        |        |        |
|        |        |        |        | valori |        |        |        |
|        |        |        |        | zzato  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 53     | n°     | O      | NUMERI | valore | B      | Dato   |        |
|        | offert |        | CO     | di     |        | formal |        |
|        | e      |        | (numer | defaul | W      | mente  |        |
|        | ammess |        | o      | t=NULL |        | non    |        |
|        | e      |        | intero |        |        | corret |        |
|        |        |        | )      | se     |        | to     |        |
|        |        |        |        | valori |        |        |        |
|        |        |        |        | zzato  |        | Non è  |        |
|        |        |        |        | deve   |        | stato  |        |
|        |        |        |        | essere |        | indica |        |
|        |        |        |        | un     |        | to     |        |
|        |        |        |        | valore |        | il n.  |        |
|        |        |        |        | numeri |        | di     |        |
|        |        |        |        | co     |        | offert |        |
|        |        |        |        | >= 0   |        | e      |        |
|        |        |        |        | inoltr |        | ammess |        |
|        |        |        |        | e      |        | e      |        |
|        |        |        |        | deve   |        |        |        |
|        |        |        |        | essere |        |        |        |
|        |        |        |        | <=     |        |        |        |
|        |        |        |        | S08.51 |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Se non |        |        |        |
|        |        |        |        | valori |        |        |        |
|        |        |        |        | zzato  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 54     | Offert | OIF    | PERCEN | obblig | B      | Non è  |        |
|        | a      |        | TUALE  | atorio |        | stato  |        |
|        | di     |        |        | solo   | B      | indica |        |
|        | massim |        |        | solo   |        | to     |        |
|        | o      |        |        | se     | B      | il     |        |
|        | ribass |        |        | S01.11 |        | valore |        |
|        | o      |        |        | =      |        | dell’o |        |
|        |        |        |        | ‘ORDIN |        | fferta |        |
|        |        |        |        | ARIO’, |        | di     |        |
|        |        |        |        | il     |        | massim |        |
|        |        |        |        | valore |        | o      |        |
|        |        |        |        | del    |        | ribass |        |
|        |        |        |        | campo  |        | o      |        |
|        |        |        |        | S08.33 |        |        |        |
|        |        |        |        | =      |        | Il     |        |
|        |        |        |        | “prezz |        | valore |        |
|        |        |        |        | o      |        | del    |        |
|        |        |        |        | più    |        | campo  |        |
|        |        |        |        | basso” |        | “Offer |        |
|        |        |        |        | e il   |        | ta     |        |
|        |        |        |        | campo  |        | di     |        |
|        |        |        |        | S08.53 |        | massim |        |
|        |        |        |        | > 1    |        | o      |        |
|        |        |        |        |        |        | ribass |        |
|        |        |        |        | Il     |        | o”     |        |
|        |        |        |        | valore |        | non è  |        |
|        |        |        |        | deve   |        | coeren |        |
|        |        |        |        | essere |        | te     |        |
|        |        |        |        | percen |        |        |        |
|        |        |        |        | tuale  |        | Valore |        |
|        |        |        |        | con la |        | percen |        |
|        |        |        |        | possib |        | tuale  |        |
|        |        |        |        | ilità  |        | non    |        |
|        |        |        |        | di     |        | corret |        |
|        |        |        |        | arriva |        | to     |        |
|        |        |        |        | re     |        |        |        |
|        |        |        |        | alla   |        |        |        |
|        |        |        |        | quinta |        |        |        |
|        |        |        |        | cifra  |        |        |        |
|        |        |        |        | decima |        |        |        |
|        |        |        |        | le     |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Deve   |        |        |        |
|        |        |        |        | essere |        |        |        |
|        |        |        |        | >=0 e  |        |        |        |
|        |        |        |        | <100   |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 55     | Offert | OIF    | PERCEN | obblig | B      | Non è  |        |
|        | a      |        | TUALE  | atorio |        | stato  |        |
|        | di     |        |        | solo   | B      | indica |        |
|        | minimo |        |        | se     |        | to     |        |
|        | ribass |        |        | S01.11 | B      | il     |        |
|        | o      |        |        | =      |        | valore |        |
|        |        |        |        | ‘ORDIN |        | dell’o |        |
|        |        |        |        | ARIO’, |        | fferta |        |
|        |        |        |        | il     |        | di     |        |
|        |        |        |        | valore |        | minimo |        |
|        |        |        |        | del    |        | ribass |        |
|        |        |        |        | campo  |        | o      |        |
|        |        |        |        | S08.33 |        |        |        |
|        |        |        |        | =      |        | Il     |        |
|        |        |        |        | “prezz |        | valore |        |
|        |        |        |        | o      |        | del    |        |
|        |        |        |        | più    |        | campo  |        |
|        |        |        |        | basso” |        | “Offer |        |
|        |        |        |        | e il   |        | ta     |        |
|        |        |        |        | campo  |        | di     |        |
|        |        |        |        | S08.53 |        | minimo |        |
|        |        |        |        | > 1    |        | ribass |        |
|        |        |        |        |        |        | o”     |        |
|        |        |        |        | Il     |        | non è  |        |
|        |        |        |        | valore |        | coeren |        |
|        |        |        |        | deve   |        | te     |        |
|        |        |        |        | essere |        |        |        |
|        |        |        |        | percen |        | Valore |        |
|        |        |        |        | tuale  |        | percen |        |
|        |        |        |        | con la |        | tuale  |        |
|        |        |        |        | possib |        | non    |        |
|        |        |        |        | ilità  |        | corret |        |
|        |        |        |        | di     |        | to     |        |
|        |        |        |        | arriva |        |        |        |
|        |        |        |        | re     |        |        |        |
|        |        |        |        | alla   |        |        |        |
|        |        |        |        | quinta |        |        |        |
|        |        |        |        | cifra  |        |        |        |
|        |        |        |        | decima |        |        |        |
|        |        |        |        | le     |        |        |        |
|        |        |        |        | e deve |        |        |        |
|        |        |        |        | essere |        |        |        |
|        |        |        |        | <=     |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S08.53 |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Deve   |        |        |        |
|        |        |        |        | essere |        |        |        |
|        |        |        |        | >=0 e  |        |        |        |
|        |        |        |        | <100   |        |        |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | Deve   |        |        |        |
|        |        |        |        | essere |        |        |        |
|        |        |        |        | <=     |        |        |        |
|        |        |        |        | S08.54 |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 56     | Valore | OIF    | PERCEN | Se     | B      | Dato   |        |
|        | soglia |        | TUALE  | valori |        | NON    |        |
|        | anomal |        |        | zzato  | B      | richie |        |
|        | ia     |        |        | e      |        | sto    |        |
|        |        |        |        | campo  |        | in     |        |
|        |        |        |        | S01.11 |        | relazi |        |
|        |        |        |        | =      |        | one    |        |
|        |        |        |        | “offer |        | al     |        |
|        |        |        |        | ta     |        | criter |        |
|        |        |        |        | econom |        | io     |        |
|        |        |        |        | icamen |        | di     |        |
|        |        |        |        | te     |        | aggiud |        |
|        |        |        |        | più    |        | icazio |        |
|        |        |        |        | vantag |        | ne     |        |
|        |        |        |        | giosa” |        | adotta |        |
|        |        |        |        |        |        | to     |        |
|        |        |        |        | Se     |        |        |        |
|        |        |        |        | valori |        | Il     |        |
|        |        |        |        | zzato  |        | valore |        |
|        |        |        |        | e      |        | del    |        |
|        |        |        |        | campo  |        | campo  |        |
|        |        |        |        | S08.53 |        | “Val.  |        |
|        |        |        |        | >= 5   |        | soglia |        |
|        |        |        |        | il     |        | di     |        |
|        |        |        |        | valore |        | anomal |        |
|        |        |        |        | deve   |        | ia”    |        |
|        |        |        |        | essere |        | non è  |        |
|        |        |        |        | percen |        | coeren |        |
|        |        |        |        | tuale  |        | te     |        |
|        |        |        |        | con la |        |        |        |
|        |        |        |        | possib |        |        |        |
|        |        |        |        | ilità  |        |        |        |
|        |        |        |        | di     |        |        |        |
|        |        |        |        | arriva |        |        |        |
|        |        |        |        | re     |        |        |        |
|        |        |        |        | alla   |        |        |        |
|        |        |        |        | quinta |        |        |        |
|        |        |        |        | cifra  |        |        |        |
|        |        |        |        | decima |        |        |        |
|        |        |        |        | le     |        |        |        |
|        |        |        |        | e deve |        |        |        |
|        |        |        |        | essere |        |        |        |
|        |        |        |        | <=     |        |        |        |
|        |        |        |        | S08.54 |        |        |        |
|        |        |        |        | e >=   |        |        |        |
|        |        |        |        | S08.55 |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 57     | N.offe | OIF    | NUMERI | valore | B      | Dato   |        |
|        | rte    |        | CO     | di     |        | formal |        |
|        | >=     |        |        | defaul | B      | mente  |        |
|        | soglia |        | (numer | t=NULL |        | non    |        |
|        | anomal |        | o      |        |        | corret |        |
|        | ia     |        | intero | se     |        | to     |        |
|        |        |        | )      | valori |        |        |        |
|        |        |        |        | zzato  |        | Il     |        |
|        |        |        |        | deve   |        | valore |        |
|        |        |        |        | essere |        | del    |        |
|        |        |        |        | un     |        | campo  |        |
|        |        |        |        | valore |        | “numer |        |
|        |        |        |        | numeri |        | o      |        |
|        |        |        |        | co     |        | offert |        |
|        |        |        |        | >= 0   |        | e      |        |
|        |        |        |        |        |        | soglia |        |
|        |        |        |        | Se     |        | anomal |        |
|        |        |        |        | valori |        | ia”    |        |
|        |        |        |        | zzato  |        | non è  |        |
|        |        |        |        | deve   |        | coeren |        |
|        |        |        |        | essere |        | te     |        |
|        |        |        |        | un     |        |        |        |
|        |        |        |        | valore |        |        |        |
|        |        |        |        | numeri |        |        |        |
|        |        |        |        | co     |        |        |        |
|        |        |        |        | >= 0   |        |        |        |
|        |        |        |        | inoltr |        |        |        |
|        |        |        |        | e      |        |        |        |
|        |        |        |        | deve   |        |        |        |
|        |        |        |        | essere |        |        |        |
|        |        |        |        | <=     |        |        |        |
|        |        |        |        | campo  |        |        |        |
|        |        |        |        | S08.53 |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 58     | Numero | OIF    | NUMERI | valore | B      | Dato   |        |
|        | impres |        | CO     | di     |        | formal |        |
|        | e      |        | (numer | defaul |        | mente  |        |
|        | esclus |        | o      | t=NULL |        | non    |        |
|        | e      |        | intero |        |        | corret |        |
|        | automa |        | )      | se     |        | to     |        |
|        | ticame |        |        | valori |        |        |        |
|        | nte    |        |        | zzato  |        | Il     |        |
|        |        |        |        | deve   |        | valore |        |
|        |        |        |        | essere |        | del    |        |
|        |        |        |        | un     |        | campo  |        |
|        |        |        |        | valore |        | “Numer |        |
|        |        |        |        | numeri |        | o      |        |
|        |        |        |        | co     |        | impres |        |
|        |        |        |        | >= 0   |        | e      |        |
|        |        |        |        | inoltr |        | esclus |        |
|        |        |        |        | e      |        | e      |        |
|        |        |        |        | deve   |        | automa |        |
|        |        |        |        | essere |        | ticame |        |
|        |        |        |        | <=     |        | nte”   |        |
|        |        |        |        | campo  |        | non è  |        |
|        |        |        |        | S08.53 |        | coeren |        |
|        |        |        |        |        |        | te     |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 59     | Numero | OIF    | NUMERI | valore | B      | Dato   |        |
|        | impres |        | CO     | di     |        | formal |        |
|        | e      |        | (numer | defaul |        | mente  |        |
|        | esclus |        | o      | t=NULL |        | non    |        |
|        | e      |        | intero |        |        | corret |        |
|        | per    |        | )      | se     |        | to     |        |
|        | insuff |        |        | valori |        |        |        |
|        | icient |        |        | zzato  |        | Il     |        |
|        | i      |        |        | deve   |        | valore |        |
|        | giusti |        |        | essere |        | del    |        |
|        | ficazi |        |        | un     |        | campo  |        |
|        | oni    |        |        | valore |        | “Numer |        |
|        |        |        |        | numeri |        | o      |        |
|        |        |        |        | co     |        | impres |        |
|        |        |        |        | >= 0   |        | e      |        |
|        |        |        |        | inoltr |        | esclus |        |
|        |        |        |        | e      |        | e      |        |
|        |        |        |        | deve   |        | per    |        |
|        |        |        |        | essere |        | ins.   |        |
|        |        |        |        | <=     |        | giusti |        |
|        |        |        |        | campo  |        | ficazi |        |
|        |        |        |        | S08.53 |        | oni”   |        |
|        |        |        |        |        |        | non è  |        |
|        |        |        |        |        |        | coeren |        |
|        |        |        |        |        |        | te     |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **AGGI |        |        |        |        |        |        |        |
| UDICAZ |        |        |        |        |        |        |        |
| IONE   |        |        |        |        |        |        |        |
| /      |        |        |        |        |        |        |        |
| AFFIDA |        |        |        |        |        |        |        |
| MENTO* |        |        |        |        |        |        |        |
| *      |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 60     | Ribass |        | PERCEN | Il     | W      | Il     |        |
|        | o      |        | TUALE  | valore |        | valore |        |
|        | di     |        |        | deve   | B      | del    |        |
|        | aggiud |        |        | essere |        | campo  |        |
|        | icazio |        |        | percen | B      | “Ribas |        |
|        | ne     |        |        | tuale  |        | so     |        |
|        |        |        |        | con la | **     | aggiud |        |
|        |        |        |        | possib | **     | icazio |        |
|        |        |        |        | ilità  |        | ne”    |        |
|        |        |        |        | di     | W      | non è  |        |
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
|        |        |        |        | >=0 e  |        | coeren |        |
|        |        |        |        | <100   |        | te     |        |
|        |        |        |        |        |        |        |        |
|        |        |        |        | in     |        | | Sono |        |
|        |        |        |        | altern |        |   stat |        |
|        |        |        |        | ativa  |        | i      |        |
|        |        |        |        | al     |        |   indi |        |
|        |        |        |        | campo  |        | cati   |        |
|        |        |        |        | S08.61 |        |   sia  |        |
|        |        |        |        |        |        |   il   |        |
|        |        |        |        | Se non |        |   riba |        |
|        |        |        |        | valori |        | sso    |        |
|        |        |        |        | zzato  |        |   di   |        |
|        |        |        |        | e      |        |   aggi |        |
|        |        |        |        | campo  |        | udicaz |        |
|        |        |        |        | S08.33 |        | ione   |        |
|        |        |        |        | vale   |        |   sia  |        |
|        |        |        |        | “prezz |        |   l’of |        |
|        |        |        |        | o      |        | ferta  |        |
|        |        |        |        | più    |        |   in   |        |
|        |        |        |        | basso” |        |   aume |        |
|        |        |        |        | e      |        | nto    |        |
|        |        |        |        |        |        | | Valo |        |
|        |        |        |        | -  S01 |        | rizzar |        |
|        |        |        |        | .11    |        | e      |        |
|        |        |        |        |    =   |        |   il   |        |
|        |        |        |        |    ‘OR |        |   Riba |        |
|        |        |        |        | DINARI |        | sso    |        |
|        |        |        |        | O’     |        |   di   |        |
|        |        |        |        |        |        |   aggi |        |
|        |        |        |        | -  S01 |        | udicaz |        |
|        |        |        |        | .11    |        | ione   |        |
|        |        |        |        |    =   |        |   nel  |        |
|        |        |        |        |    ‘se |        |   caso |        |
|        |        |        |        | ttore  |        |   di   |        |
|        |        |        |        |    spe |        |   offe |        |
|        |        |        |        | ciale’ |        | rta    |        |
|        |        |        |        |    **e |        |   a    |        |
|        |        |        |        | **     |        |   prez |        |
|        |        |        |        |    cam |        | zi     |        |
|        |        |        |        | po     |        |   unit |        |
|        |        |        |        |    S08 |        | ari,   |        |
|        |        |        |        | .26    |        |   ovve |        |
|        |        |        |        |    >   |        | ro     |        |
|        |        |        |        |    del |        |   in   |        |
|        |        |        |        | le     |        |   caso |        |
|        |        |        |        |    sog |        |   di   |        |
|        |        |        |        | lie    |        |   form |        |
|        |        |        |        |    com |        | ulazio |        |
|        |        |        |        | unitar |        | ne     |        |
|        |        |        |        | ie     |        |   di   |        |
|        |        |        |        |        |        |   riba |        |
|        |        |        |        |        |        | sso    |        |
|        |        |        |        |        |        |   sull |        |
|        |        |        |        |        |        | ’impor |        |
|        |        |        |        |        |        | to     |        |
|        |        |        |        |        |        |   dell |        |
|        |        |        |        |        |        | e      |        |
|        |        |        |        |        |        |   pres |        |
|        |        |        |        |        |        | tazion |        |
|        |        |        |        |        |        | i      |        |
|        |        |        |        |        |        |   post |        |
|        |        |        |        |        |        | e      |        |
|        |        |        |        |        |        |   a    |        |
|        |        |        |        |        |        |   base |        |
|        |        |        |        |        |        |   di   |        |
|        |        |        |        |        |        |   gara |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 61     | Offert |        | PERCEN | Il     | W      | Il     |        |
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
|        |        |        |        | S08.60 |        | sia il |        |
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
| 62     | Import | O      | IMPORT | valore | B      | Inseri |        |
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
| 63     | Data   | O      | DATA   | deve   | B      | Non è  |        |
|        | di     |        |        | essere |        | stata  |        |
|        | aggiud |        |        | un     | W      | indica |        |
|        | icazio |        |        | campo  |        | ta     |        |
|        | ne     |        |        | data   | W      | la     |        |
|        | defini |        |        |        |        | data   |        |
|        | tiva   |        |        | | Deve |        | di     |        |
|        | o      |        |        |   esse |        | aggiud |        |
|        | defini |        |        | re     |        | icazio |        |
|        | zione  |        |        |   una  |        | ne     |        |
|        | proced |        |        |   data |        | defini |        |
|        | ura    |        |        |   vali |        | tiva   |        |
|        | negozi |        |        | da:    |        |        |        |
|        | ata    |        |        | | <=   |        | Data   |        |
|        |        |        |        |   data |        | di     |        |
|        |        |        |        |   odie |        | aggiud |        |
|        |        |        |        | rna    |        | icazio |        |
|        |        |        |        |   e    |        | ne     |        |
|        |        |        |        |   >=30 |        | non    |        |
|        |        |        |        | /04/20 |        | valida |        |
|        |        |        |        | 08     |        |        |        |
|        |        |        |        |        |        | **     |        |
|        |        |        |        | Se     |        | **     |        |
|        |        |        |        | valore |        |        |        |
|        |        |        |        | <      |        | Data   |        |
|        |        |        |        | campo  |        | di     |        |
|        |        |        |        | S08.48 |        | aggiud |        |
|        |        |        |        |        |        | icazio |        |
|        |        |        |        |        |        | ne     |        |
|        |        |        |        |        |        | antece |        |
|        |        |        |        |        |        | dente  |        |
|        |        |        |        |        |        | la     |        |
|        |        |        |        |        |        | data   |        |
|        |        |        |        |        |        | di     |        |
|        |        |        |        |        |        | scaden |        |
|        |        |        |        |        |        | za     |        |
|        |        |        |        |        |        | della  |        |
|        |        |        |        |        |        | presen |        |
|        |        |        |        |        |        | tazion |        |
|        |        |        |        |        |        | e      |        |
|        |        |        |        |        |        | delle  |        |
|        |        |        |        |        |        | offert |        |
|        |        |        |        |        |        | e      |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 64     | L'affi | O      | FLAG   | | List | B      | Selezi |        |
|        | datari |        |        | a      |        | onare  |        |
|        | o      |        |        |   di   |        | un     |        |
|        | ha     |        |        |   valo |        | valore |        |
|        | richie |        |        | ri     |        | tra    |        |
|        | sto    |        |        |   da   |        | quelli |        |
|        | in     |        |        |   elen |        | previs |        |
|        | sede   |        |        | co     |        | ti     |        |
|        | di     |        |        | | Vale |        |        |        |
|        | offert |        |        | :      |        |        |        |
|        | a      |        |        |   SI o |        |        |        |
|        | la     |        |        |   NO   |        |        |        |
|        | possib |        |        |        |        |        |        |
|        | ilità  |        |        | Defaul |        |        |        |
|        | di     |        |        | t:NULL |        |        |        |
|        | subapp |        |        |        |        |        |        |
|        | altare |        |        |        |        |        |        |
|        | parte  |        |        |        |        |        |        |
|        | delle  |        |        |        |        |        |        |
|        | presta |        |        |        |        |        |        |
|        | zioni? |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 65     | PER    | Dati   | O      | `DATI_ | Se non | B      | Il     |
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
| 66     | PER    | Dati   | O      | `DATI_ | Se non | B      | Il     |
|        | OGNI   | Sogget |        | PERSON | inseri |        | campo  |
|        | SOGGET | to     |        | A_FISI | to     |        | è      |
|        | TO     | incari |        | CA <#d | almeno |        | obblig |
|        | INCARI | cato   |        | ati_pe | un     |        | atorio |
|        | CATO   |        |        | rsona_ | aggiud |        |        |
|        |        |        |        | fisica | icatar |        |        |
|        |        |        |        | >`__   | io     |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 67     |        | Ruolo  | O      | `RUOLI | Lista  | B      | Selezi |
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

.. [1]
    Per i CIG associati a gare create anteriormente al 12/05/2014, i CUP
   sono acquisiti in questa scheda e le relative attività di controllo e
   validazione del CUP devono essere effettuate sui dati inseriti nella
   scheda stessa. In tal caso i dati dovranno essere resi disponibili,
   visibili e non editabili anche nella scheda lotto (S02)

   Per i CIG associati a gare create a partire dal 12/05/2014 le
   informazioni devono essere acquisite nella scheda lotto (S02) e rese
   visibili e non modificabili nella scheda di aggiudicazione (S08 o
   S10)

.. [2]
    Per i CIG associati a gare create anteriormente al 12/05/2014, i CUP
   sono acquisiti in questa scheda e le relative attività di controllo e
   validazione del CUP devono essere effettuate sui dati inseriti nella
   scheda stessa. In tal caso i dati dovranno essere resi disponibili,
   visibili e non editabili anche nella scheda lotto (S02)

   Per i CIG associati a gare create a partire dal 12/05/2014 le
   informazioni devono essere acquisite nella scheda lotto (S02) e rese
   visibili e non modificabili nella scheda di aggiudicazione (S08 o
   S10)
