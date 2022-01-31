S09 – Adesione accordo quadro convenzione
=========================================

+--------+--------+--------+--------+--------+--------+--------+--------+
| **S09  |        |        |        |        |        |        |        |
| -      |        |        |        |        |        |        |        |
| Adesio |        |        |        |        |        |        |        |
| ne     |        |        |        |        |        |        |        |
| accord |        |        |        |        |        |        |        |
| o      |        |        |        |        |        |        |        |
| quadro |        |        |        |        |        |        |        |
| conven |        |        |        |        |        |        |        |
| zione* |        |        |        |        |        |        |        |
| *\  [2 |        |        |        |        |        |        |        |
| ]_     |        |        |        |        |        |        |        |
+========+========+========+========+========+========+========+========+
| **COD* | ETICHE | TIPO   | FORMAT | CONTRO | MESSAG |        |        |
| *      | TTA    |        | O      | LLO    | GIO    |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
|        |        |        |        | DESCRI | TIPO   |        |        |
|        |        |        |        | ZIONE  |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **OGGE |        |        |        |        |        |        |        |
| TTO    |        |        |        |        |        |        |        |
| DELL'A |        |        |        |        |        |        |        |
| DESION |        |        |        |        |        |        |        |
| E**    |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 01     | Codice | R      | STRING |        |        |        |        |
|        | di     |        | A      |        |        |        |        |
|        | indivi |        |        |        |        |        |        |
|        | duazio |        |        |        |        |        |        |
|        | ne     |        |        |        |        |        |        |
|        | dell'a |        |        |        |        |        |        |
|        | ppalto |        |        |        |        |        |        |
|        | (CIG)  |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 02     | Oggett | E      | TESTO  |        |        |        |        |
|        | o      |        |        |        |        |        |        |
|        | del    |        |        |        |        |        |        |
|        | Contra |        |        |        |        |        |        |
|        | tto    |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 03     | Luogo  | P      | `CODIC | Valori | B      | Codice |        |
|        | ISTAT  |        | E_ISTA | zzare  |        | ISTAT  |        |
|        |        |        | T <#co | in     |        | obblig |        |
|        |        |        | dice_i | altern |        | atorio |        |
|        |        |        | stat>` | ativa  |        | se     |        |
|        |        |        | __     | al     |        | codice |        |
|        |        |        |        | campo  |        | NUTS   |        |
|        |        |        |        | S09.04 |        | non è  |        |
|        |        |        |        |        |        | valori |        |
|        |        |        |        |        |        | zzato  |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 04     | Luogo  | P      | `CODIC | Valori | B      | Codice |        |
|        | NUTS   |        | E_NUTS | zzare  |        | NUTS   |        |
|        |        |        |  <#cod | in     |        | obblig |        |
|        |        |        | ice_nu | altern |        | atorio |        |
|        |        |        | ts>`__ | ativa  |        | se     |        |
|        |        |        |        | al     |        | codice |        |
|        |        |        |        | campo  |        | ISTAT  |        |
|        |        |        |        | S09.03 |        | non è  |        |
|        |        |        |        |        |        | valori |        |
|        |        |        |        |        |        | zzato  |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **DATI |        |        |        |        |        |        |        |
| ECONOM |        |        |        |        |        |        |        |
| ICI    |        |        |        |        |        |        |        |
| DELL'A |        |        |        |        |        |        |        |
| DESION |        |        |        |        |        |        |        |
| E**    |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 05     | Codice |        | `TIPO_ | Lista  |        |        |        |
|        | Strume |        | STRUME | di     |        |        |        |
|        | nto    |        | NTO <# | valori |        |        |        |
|        | di     |        | tipo_s | da     |        |        |        |
|        | progra |        | trumen | elenco |        |        |        |
|        | mmazio |        | to>`__ |        |        |        |        |
|        | ne     |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **FINA |        |        |        |        |        |        |        |
| NZIAME |        |        |        |        |        |        |        |
| NTI**  |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 06     | RIPETE | Tipo   | O      | `TIPO_ | Lista  | B      | Non è  |
|        | RE     | di     |        | FINANZ | di     |        | stato  |
|        | PER    | finanz |        | IAMENT | valori |        | indica |
|        | OGNI   | iament |        | O <#ti | da     |        | to     |
|        | TIPO   | o      |        | po_fin | elenco |        | un     |
|        | DI     |        |        | anziam |        |        | finanz |
|        | FINANZ |        |        | ento>` |        |        | iament |
|        | IAMENT |        |        | __     |        |        | o      |
|        | O      |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 07     |        | Import | O      | IMPORT | Valori | B      | Non è  |
|        |        | o      |        | O      | numeri |        | stato  |
|        |        | finanz |        |        | ci     | B      | indica |
|        |        | iament |        |        | senza  |        | to     |
|        |        | o      |        |        | segni  |        | l’impo |
|        |        |        |        |        | di     |        | rto    |
|        |        |        |        |        | interp |        | del    |
|        |        |        |        |        | unzion |        | finanz |
|        |        |        |        |        | e      |        | iament |
|        |        |        |        |        | e tre  |        | o      |
|        |        |        |        |        | decima |        |        |
|        |        |        |        |        | li     |        | Il     |
|        |        |        |        |        |        |        | campo  |
|        |        |        |        |        |        |        | contie |
|        |        |        |        |        |        |        | ne     |
|        |        |        |        |        |        |        | caratt |
|        |        |        |        |        |        |        | eri    |
|        |        |        |        |        |        |        | non    |
|        |        |        |        |        |        |        | validi |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 08     | Import | C      | IMPORT | Somma  |        |        |        |
|        | o      |        | O      | import |        |        |        |
|        | totale |        |        | i      |        |        |        |
|        | finanz |        |        | campo  |        |        |        |
|        | iament |        |        | S09.07 |        |        |        |
|        | o      |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 09     | Import |        | IMPORT | Valori | B      | Il     |        |
|        | o      |        | O      | numeri |        | valore |        |
|        | di     |        |        | ci     |        | digita |        |
|        | adesio |        |        | senza  |        | to     |        |
|        | ne     |        |        | segni  |        | contie |        |
|        | compon |        |        | di     |        | ne     |        |
|        | ente   |        |        | interp |        | caratt |        |
|        | lavori |        |        | unzion |        | eri    |        |
|        | in €   |        |        | e      |        | non    |        |
|        | (al    |        |        | e tre  |        | ammess |        |
|        | netto  |        |        | decima |        | i      |        |
|        | dell'I |        |        | li     |        |        |        |
|        | VA     |        |        |        |        |        |        |
|        | e      |        |        | Se non |        |        |        |
|        | degli  |        |        | valori |        |        |        |
|        | oneri  |        |        | zzato  |        |        |        |
|        | di     |        |        | almeno |        |        |        |
|        | sicure |        |        | uno    |        |        |        |
|        | zza)   |        |        | dei    |        |        |        |
|        |        |        |        | campi  |        |        |        |
|        |        |        |        | S09.09 |        |        |        |
|        |        |        |        | ,      |        |        |        |
|        |        |        |        | S09.10 |        |        |        |
|        |        |        |        | ,      |        |        |        |
|        |        |        |        | S09.11 |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 10     | Import |        | IMPORT | Valori |        | Il     |        |
|        | o      |        | O      | numeri |        | valore |        |
|        | di     |        |        | ci     |        | digita |        |
|        | adesio |        |        | senza  |        | to     |        |
|        | ne     |        |        | segni  |        | contie |        |
|        | compon |        |        | di     |        | ne     |        |
|        | ente   |        |        | interp |        | caratt |        |
|        | serviz |        |        | unzion |        | eri    |        |
|        | i      |        |        | e      |        | non    |        |
|        | in €   |        |        | e tre  |        | ammess |        |
|        | (come  |        |        | decima |        | i      |        |
|        | sopra) |        |        | li     |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 11     | Import |        | IMPORT | Valori |        | Il     |        |
|        | o      |        | O      | numeri |        | valore |        |
|        | di     |        |        | ci     |        | digita |        |
|        | adesio |        |        | senza  |        | to     |        |
|        | ne     |        |        | segni  |        | contie |        |
|        | compon |        |        | di     |        | ne     |        |
|        | ente   |        |        | interp |        | caratt |        |
|        | fornit |        |        | unzion |        | eri    |        |
|        | ure    |        |        | e      |        | non    |        |
|        | in €   |        |        | e tre  |        | ammess |        |
|        | (come  |        |        | decima |        | i      |        |
|        | sopra) |        |        | li     |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 12     | Sub    | C      | IMPORT | Somma  |        |        |        |
|        | Totale |        | O      | dei    |        |        |        |
|        |        |        |        | valori |        |        |        |
|        |        |        |        | dei    |        |        |        |
|        |        |        |        | campi  |        |        |        |
|        |        |        |        | S09.09 |        |        |        |
|        |        |        |        | ,      |        |        |        |
|        |        |        |        | S09.10 |        |        |        |
|        |        |        |        | ,      |        |        |        |
|        |        |        |        | S09.11 |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **AGGI |        |        |        |        |        |        |        |
| UDICAZ |        |        |        |        |        |        |        |
| IONE   |        |        |        |        |        |        |        |
| /      |        |        |        |        |        |        |        |
| AFFIDA |        |        |        |        |        |        |        |
| MENTO* |        |        |        |        |        |        |        |
| *      |        |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 13     | Ribass | E      | PERCEN | Vale 0 |        |        |        |
|        | o      |        | TUALE  | solo   |        |        |        |
|        | di     |        |        | se     |        |        |        |
|        | aggiud |        |        | S08.05 |        |        |        |
|        | icazio |        |        | = 11   |        |        |        |
|        | ne     |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 14     | Offert | E      | PERCEN | Vale 0 |        |        |        |
|        | a      |        | TUALE  | solo   |        |        |        |
|        | in     |        |        | se     |        |        |        |
|        | aument |        |        | S08.05 |        |        |        |
|        | o      |        |        | = 11   |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 15     | Import | E      | IMPORT | Vale   |        |        |        |
|        | o      |        | O      | S09.12 |        |        |        |
|        | di     |        |        | solo   |        |        |        |
|        | aggiud |        |        | se     |        |        |        |
|        | icazio |        |        | S08.05 |        |        |        |
|        | ne/aff |        |        | = 11   |        |        |        |
|        | idamen |        |        |        |        |        |        |
|        | to     |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 16     | Data   | E      | DATA   |        |        |        |        |
|        | di     |        |        |        |        |        |        |
|        | aggiud |        |        |        |        |        |        |
|        | icazio |        |        |        |        |        |        |
|        | ne     |        |        |        |        |        |        |
|        | defini |        |        |        |        |        |        |
|        | tiva   |        |        |        |        |        |        |
|        | o      |        |        |        |        |        |        |
|        | defini |        |        |        |        |        |        |
|        | zione  |        |        |        |        |        |        |
|        | proced |        |        |        |        |        |        |
|        | ura    |        |        |        |        |        |        |
|        | negozi |        |        |        |        |        |        |
|        | ata    |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 17     | L'affi | E      | FLAG   | Vale:  |        |        |        |
|        | datari |        |        | SI o   |        |        |        |
|        | o      |        |        | NO     |        |        |        |
|        | ha     |        |        |        |        |        |        |
|        | richie |        |        | Defaul |        |        |        |
|        | sto    |        |        | t:NULL |        |        |        |
|        | in     |        |        |        |        |        |        |
|        | sede   |        |        |        |        |        |        |
|        | di     |        |        |        |        |        |        |
|        | offert |        |        |        |        |        |        |
|        | a      |        |        |        |        |        |        |
|        | la     |        |        |        |        |        |        |
|        | possib |        |        |        |        |        |        |
|        | ilità  |        |        |        |        |        |        |
|        | di     |        |        |        |        |        |        |
|        | subapp |        |        |        |        |        |        |
|        | altare |        |        |        |        |        |        |
|        | parte  |        |        |        |        |        |        |
|        | delle  |        |        |        |        |        |        |
|        | presta |        |        |        |        |        |        |
|        | zioni? |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| 18     | PER    | Dati   | E      | `DATI_ | Se non | B      | Il     |
|        | OGNI   | Aggiud |        | AGGIUD | inseri |        | campo  |
|        | AGGIUD | icatar |        | ICATAR | to     |        | è      |
|        | ICATAR | io     |        | IO <#d | almeno |        | obblig |
|        | IO     |        |        | ati_ag | un     |        | atorio |
|        |        |        |        | giudic | aggiud |        |        |
|        |        |        |        | atario | icatar |        |        |
|        |        |        |        | >`__   | io     |        |        |
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
| **19** | | PER  | Dati   |        | `DATI_ |        | W      | Non    |
|        |   OGNI | Sogget |        | PERSON |        |        | sono   |
|        |   SOGG | to     |        | A_FISI |        |        | stati  |
|        | ETTO   | incari |        | CA <#d |        |        | inseri |
|        |   INCA | cato   |        | ati_pe |        |        | ti     |
|        | RICATO |        |        | rsona_ |        |        | incari |
|        | | SE   |        |        | fisica |        |        | cati   |
|        |   PRES |        |        | >`__   |        |        |        |
|        | ENTE   |        |        |        |        |        |        |
|        |   (dov |        |        |        |        |        |        |
|        | rebbe  |        |        |        |        |        |        |
|        |   esse |        |        |        |        |        |        |
|        | rci    |        |        |        |        |        |        |
|        |   alme |        |        |        |        |        |        |
|        | no     |        |        |        |        |        |        |
|        |   un   |        |        |        |        |        |        |
|        |   inca |        |        |        |        |        |        |
|        | ricato |        |        |        |        |        |        |
|        |   )    |        |        |        |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+
| **20** |        | Ruolo  | O      | `RUOLI | | List | B      | Selezi |
|        |        |        |        | _RESPO | a      |        | onare  |
|        |        |        |        | NSABIL |   di   | W      | un     |
|        |        |        |        | E <#ru |   valo |        | valore |
|        |        |        |        | oli_re | ri     |        | tra    |
|        |        |        |        | sponsa |   da   |        | quelli |
|        |        |        |        | bile>` |   elen |        | previs |
|        |        |        |        | __     | co.    |        | ti     |
|        |        |        |        |        | | Se è |        |        |
|        |        |        |        |        |   stat |        | Non    |
|        |        |        |        |        | o      |        | sono   |
|        |        |        |        |        |   inse |        | stati  |
|        |        |        |        |        | rito   |        | inseri |
|        |        |        |        |        |   un   |        | ti     |
|        |        |        |        |        |   inca |        | incari |
|        |        |        |        |        | ricato |        | cati   |
|        |        |        |        |        |        |        |        |
|        |        |        |        |        | Deve   |        |        |
|        |        |        |        |        | essere |        |        |
|        |        |        |        |        | inseri |        |        |
|        |        |        |        |        | to     |        |        |
|        |        |        |        |        | almeno |        |        |
|        |        |        |        |        | un     |        |        |
|        |        |        |        |        | incari |        |        |
|        |        |        |        |        | cato   |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+

.. [1]
    Scheda da compilare in caso di contratto d’appalto discendente da
   Accordo Quadro senza successivo confronto competitivo.

.. [2]
    Scheda da compilare in caso di contratto d’appalto discendente da
   Accordo Quadro senza successivo confronto competitivo.
