S02 – Creazione lotto
=====================

+---------+---------+---------+---------+---------+---------+---------+
| S02 –   |         |         |         |         |         |         |
| creazio |         |         |         |         |         |         |
| ne      |         |         |         |         |         |         |
| lotto   |         |         |         |         |         |         |
+=========+=========+=========+=========+=========+=========+=========+
| COD     | ETICHET | TIPO    | FORMATO | CONTROL | MESSAGG |         |
|         | TA      |         |         | LO      | IO      |         |
+---------+---------+---------+---------+---------+---------+---------+
|         |         |         |         | DESCRIZ | TIPO    |         |
|         |         |         |         | IONE    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 01      | Oggetto | O       | STRINGA | testo   | B       | Inserir |
|         | lotto   |         |         | libero  |         | e       |
|         |         |         |         |         |         | l’ogget |
|         |         |         |         |         |         | to      |
|         |         |         |         |         |         | del     |
|         |         |         |         |         |         | lotto   |
+---------+---------+---------+---------+---------+---------+---------+
| 02      | Esecuzi |         | FLAG    | Valore: |         |         |
|         | one     |         |         | SI/NO   |         |         |
|         | di      |         |         |         |         |         |
|         | lavori  |         |         | Default |         |         |
|         | di      |         |         | :       |         |         |
|         | somma   |         |         | NO      |         |         |
|         | urgenza |         |         |         |         |         |
|         | (ex     |         |         |         |         |         |
|         | art.    |         |         |         |         |         |
|         | 147 DPR |         |         |         |         |         |
|         | 554/99) |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 03      | Importo | O       | IMPORTO | Se      | B       | inserir |
|         | a base  |         |         | valoriz |         | e       |
|         | d'asta  |         |         | zato    |         | l’      |
|         | o       |         |         | deve    |         | importo |
|         | presunt |         |         | essere  |         | a base  |
|         | o       |         |         | un      |         | d'asta  |
|         |         |         |         | valore  |         | o       |
|         |         |         |         | importo |         | presunt |
|         |         |         |         | valido  |         | o       |
|         |         |         |         | e > 0   |         | maggior |
|         |         |         |         |         |         | e       |
|         |         |         |         |         |         | di 0    |
+---------+---------+---------+---------+---------+---------+---------+
| 04      | di cui  |         | IMPORTO | Valori  |         | Il      |
|         | per     |         |         | numeric |         | campo   |
|         | attuazi |         |         | i       |         | contien |
|         | one     |         |         | senza   |         | e       |
|         | della   |         |         | segni   |         | caratte |
|         | sicurez |         |         | di      |         | ri      |
|         | za      |         |         | interpu |         | non     |
|         |         |         |         | nzione  |         | validi  |
|         |         |         |         | e tre   |         |         |
|         |         |         |         | decimal |         |         |
|         |         |         |         | i       |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 05      | CPV     | OIF     | `CODICE | codice  | B       | Il      |
|         |         |         | _CPV <# | cpv     |         | codice  |
|         |         |         | codice_ | valido  |         | inserit |
|         |         |         | cpv>`__ | compost |         | o       |
|         |         |         |         | o       |         | non è   |
|         |         |         |         | da      |         | valido  |
|         |         |         |         | almeno  |         |         |
|         |         |         |         | 3 cifre |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 06      | scelta  | O       | `SCELTA | lista   | B       | Selezio |
|         | del     |         | _CONTRA | di      |         | nare    |
|         | contrae |         | ENTE <# | valori  |         | un      |
|         | nte     |         | scelta_ | da      |         | valore  |
|         |         |         | contrae | elenco  |         | tra     |
|         |         |         | nte>`__ |         |         | quelli  |
|         |         |         | \  [3]_ |         |         | previst |
|         |         |         |         |         |         | i       |
+---------+---------+---------+---------+---------+---------+---------+
| 07      | Oggetto | O       | `OGGETT | lista   | B       | Selezio |
|         | princip |         | O_CONTR | di      |         | nare    |
|         | ale     |         | ATTO <# | valori  |         | un      |
|         | del     |         | oggetto | da      |         | valore  |
|         | contrat |         | _contra | elenco  |         | tra     |
|         | to      |         | tto>`__ |         |         | quelli  |
|         |         |         |         |         |         | previst |
|         |         |         |         |         |         | i       |
+---------+---------+---------+---------+---------+---------+---------+
| 08      | Contrat | O       | FLAG    | Valore: | B       | Selezio |
|         | to      |         |         | SI/NO   |         | nare    |
|         | escluso |         |         |         |         | un      |
|         | in      |         |         | Valore  |         | valore  |
|         | tutto o |         |         | di      |         | tra     |
|         | in      |         |         | default |         | quelli  |
|         | parte   |         |         | :       |         | previst |
|         | nell'am |         |         | NO      |         | i       |
|         | bito    |         |         |         |         |         |
|         | di      |         |         |         |         |         |
|         | applica |         |         |         |         |         |
|         | zione   |         |         |         |         |         |
|         | del     |         |         |         |         |         |
|         | codice  |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 09      | Esclusi | OIF     | `ART_ES | obbliga |         | Selezio |
|         | one     |         | CLUSION | torio   |         | nare    |
|         | ai      |         | E <#art | se      |         | un      |
|         | sensi   |         | _esclus | S02.08  |         | valore  |
|         | dell’ar |         | ione>`_ | uguale  |         | tra     |
|         | ticolo  |         | _       | a “si”  |         | quelli  |
|         |         |         |         |         |         | previst |
|         |         |         |         |         |         | i       |
+---------+---------+---------+---------+---------+---------+---------+
| 10      | Codice  | OIF     | `CODICE | Valoriz | B       | Non e'  |
|         | del     |         | _ISTAT  | zare    |         | stato   |
|         | luogo   |         | <#codic | in      |         | indicat |
|         | di      |         | e_istat | alterna |         | o       |
|         | esecuzi |         | >`__    | tiva    |         | codice  |
|         | one     |         |         | al      |         | ISTAT   |
|         | del     |         |         | codice  |         |         |
|         | contrat |         |         | NUTS    |         |         |
|         | to      |         |         |         |         |         |
|         | (ISTAT) |         |         | Se non  |         |         |
|         |         |         |         | valoriz |         |         |
|         |         |         |         | zato    |         |         |
|         |         |         |         | e se    |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S01.10  |         |         |
|         |         |         |         | >= €    |         |         |
|         |         |         |         | 500.000 |         |         |
|         |         |         |         | e se    |         |         |
|         |         |         |         | almeno  |         |         |
|         |         |         |         | un      |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S02.06  |         |         |
|         |         |         |         | dei     |         |         |
|         |         |         |         | lotti   |         |         |
|         |         |         |         | attivi  |         |         |
|         |         |         |         | è       |         |         |
|         |         |         |         | uguale  |         |         |
|         |         |         |         | a :     |         |         |
|         |         |         |         | 1,2,8,9 |         |         |
|         |         |         |         | ,13     |         |         |
|         |         |         |         |         |         |         |
|         |         |         |         | o se    |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S06.17= |         |         |
|         |         |         |         | ’SI’    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 11      | Codice  | OIF     | `CODICE | Valoriz | B       | Non e'  |
|         | del     |         | _NUTS < | zare    |         | stato   |
|         | luogo   |         | #codice | in      |         | indicat |
|         | di      |         | _nuts>` | alterna |         | o       |
|         | esecuzi |         | __      | tiva    |         | codice  |
|         | one     |         |         | al      |         | NUTS    |
|         | del     |         |         | codice  |         |         |
|         | contrat |         |         | ISTAT   |         |         |
|         | to      |         |         |         |         |         |
|         | (NUTS)  |         |         | Se non  |         |         |
|         |         |         |         | valoriz |         |         |
|         |         |         |         | zato    |         |         |
|         |         |         |         | e se    |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S01.10  |         |         |
|         |         |         |         | >= €    |         |         |
|         |         |         |         | 500.000 |         |         |
|         |         |         |         | e se    |         |         |
|         |         |         |         | almeno  |         |         |
|         |         |         |         | un      |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S02.06  |         |         |
|         |         |         |         | dei     |         |         |
|         |         |         |         | lotti   |         |         |
|         |         |         |         | attivi  |         |         |
|         |         |         |         | è       |         |         |
|         |         |         |         | uguale  |         |         |
|         |         |         |         | a :     |         |         |
|         |         |         |         | 1,2,8,9 |         |         |
|         |         |         |         | ,13     |         |         |
|         |         |         |         |         |         |         |
|         |         |         |         | o se    |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S06.17= |         |         |
|         |         |         |         | ’SI’    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 12      | Trienni |         | NUMERIC | Se      | B       | Il      |
|         | o       |         | O       | valoriz |         | trienni |
|         | anno    |         |         | zato    | W       | o       |
|         | inizio  |         |         | deve    |         | inserit |
|         |         |         |         | essere  |         | o       |
|         |         |         |         | S02.12  |         | non è   |
|         |         |         |         | <       |         | valido  |
|         |         |         |         | S02.13  |         |         |
|         |         |         |         | e       |         | Estremi |
|         |         |         |         | S02.13  |         | del     |
|         |         |         |         | -       |         | program |
|         |         |         |         | S02.12  |         | ma      |
|         |         |         |         | = 2     |         | trienna |
|         |         |         |         |         |         | le      |
|         |         |         |         | Se non  |         | incompl |
|         |         |         |         | valoriz |         | eti     |
|         |         |         |         | zato    |         |         |
|         |         |         |         | e campo |         |         |
|         |         |         |         | S02.07= |         |         |
|         |         |         |         | ”Lavori |         |         |
|         |         |         |         | ”       |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 13      | Trienni |         | NUMERIC | Se      | B       | Il      |
|         | o       |         | O       | valoriz |         | trienni |
|         | anno    |         |         | zato    | W       | o       |
|         | fine    |         |         | deve    |         | inserit |
|         |         |         |         | essere  |         | o       |
|         |         |         |         | S02.12  |         | non è   |
|         |         |         |         | <       |         | valido  |
|         |         |         |         | S02.13  |         |         |
|         |         |         |         | e       |         | Estremi |
|         |         |         |         | S02.13  |         | del     |
|         |         |         |         | -       |         | program |
|         |         |         |         | S02.12  |         | ma      |
|         |         |         |         | = 2     |         | trienna |
|         |         |         |         |         |         | le      |
|         |         |         |         | Se non  |         | incompl |
|         |         |         |         | valoriz |         | eti     |
|         |         |         |         | zato    |         |         |
|         |         |         |         | e campo |         |         |
|         |         |         |         | S02.07= |         |         |
|         |         |         |         | ”Lavori |         |         |
|         |         |         |         | ”       |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 14      | Progres |         | NUMERIC | Se      | B       | Progres |
|         | sivo    |         | O       | valoriz |         | sivo    |
|         | nell’am |         |         | zato    | W       | nell’am |
|         | bito    |         |         | deve    |         | bito    |
|         | del     |         |         | essere  |         | del     |
|         | trienni |         |         | un      |         | program |
|         | o       |         |         | valore  |         | ma      |
|         |         |         |         | numeric |         | trienna |
|         |         |         |         | o       |         | le      |
|         |         |         |         |         |         | non     |
|         |         |         |         | Se non  |         | valido  |
|         |         |         |         | valoriz |         |         |
|         |         |         |         | zato    |         | Estremi |
|         |         |         |         | e campo |         | del     |
|         |         |         |         | S02.07= |         | program |
|         |         |         |         | ”Lavori |         | ma      |
|         |         |         |         | ”       |         | trienna |
|         |         |         |         |         |         | le      |
|         |         |         |         |         |         | incompl |
|         |         |         |         |         |         | eti     |
+---------+---------+---------+---------+---------+---------+---------+
| 15      | CUI     |         | NUMERIC | Se      | B       | CUI     |
|         | assegna |         | O       | valoriz |         | assegna |
|         | to      |         |         | zato    | W       | to      |
|         | dal     |         |         | deve    |         | dal     |
|         | sistema |         |         | essere  |         | sistema |
|         |         |         |         | un      |         | del     |
|         |         |         |         | campo   |         | Min.    |
|         |         |         |         | numeric |         | Infrast |
|         |         |         |         | o       |         | rutture |
|         |         |         |         | di      |         | non     |
|         |         |         |         | lunghez |         | valido  |
|         |         |         |         | za      |         |         |
|         |         |         |         | 22      |         | Non     |
|         |         |         |         |         |         | sono    |
|         |         |         |         | Se non  |         | stati   |
|         |         |         |         | valoriz |         | comunic |
|         |         |         |         | zato    |         | ati     |
|         |         |         |         | e campo |         | gli     |
|         |         |         |         | S02.07= |         | estremi |
|         |         |         |         | ”Lavori |         | del     |
|         |         |         |         | ”       |         | program |
|         |         |         |         |         |         | ma      |
|         |         |         |         |         |         | annuale |
+---------+---------+---------+---------+---------+---------+---------+
| 16      | L’appal |         | FLAG    | Valore: | B       | I campi |
|         | to      |         |         | SI/NO   |         | non     |
|         | prevede |         |         |         |         | possono |
|         | ripetiz |         |         | Valore  |         | essere  |
|         | ioni?   |         |         | di      |         | valoriz |
|         |         |         |         | default |         | zati    |
|         |         |         |         | :       |         | entramb |
|         |         |         |         | NO      |         | i       |
|         |         |         |         |         |         | a ‘SI’  |
|         |         |         |         | Se      |         |         |
|         |         |         |         | S12.16  |         |         |
|         |         |         |         | e       |         |         |
|         |         |         |         | S12.17  |         |         |
|         |         |         |         | =”SI”   |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 17      | Ripetiz |         | FLAG    | Valore: | B       | I campi |
|         | ione    |         |         | SI/NO   |         | non     |
|         | di      |         |         |         |         | possono |
|         | precede |         |         | Valore  |         | essere  |
|         | nte     |         |         | di      |         | valoriz |
|         | contrat |         |         | default |         | zati    |
|         | to      |         |         | :       |         | entramb |
|         |         |         |         | NO      |         | i       |
|         |         |         |         |         |         | a ‘SI’  |
|         |         |         |         | Se      |         |         |
|         |         |         |         | S12.16  |         |         |
|         |         |         |         | e       |         |         |
|         |         |         |         | S12.17  |         |         |
|         |         |         |         | =”SI”   |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 18      | CIG     | OIF     | CIG     | Se non  | B       | Obbliga |
|         | contrat |         |         | valoriz |         | torio   |
|         | to      |         |         | zato    | B       | se      |
|         | origina |         |         | e il    |         | ‘L’Appa |
|         | rio     |         |         | campo   |         | lto     |
|         |         |         |         | S02.17  |         | è la    |
|         |         |         |         | = “SI”  |         | ripetiz |
|         |         |         |         |         |         | ione    |
|         |         |         |         | Se      |         | di un   |
|         |         |         |         | valoriz |         | precede |
|         |         |         |         | zato    |         | nte     |
|         |         |         |         | e il    |         | contrat |
|         |         |         |         | campo   |         | to      |
|         |         |         |         | S02.17  |         |         |
|         |         |         |         | = “NO”  |         | Il      |
|         |         |         |         |         |         | campo   |
|         |         |         |         |         |         | CIG     |
|         |         |         |         |         |         | contrat |
|         |         |         |         |         |         | to      |
|         |         |         |         |         |         | origina |
|         |         |         |         |         |         | rio     |
|         |         |         |         |         |         | non     |
|         |         |         |         |         |         | deve    |
|         |         |         |         |         |         | essere  |
|         |         |         |         |         |         | valoriz |
|         |         |         |         |         |         | zato    |
+---------+---------+---------+---------+---------+---------+---------+
| 18.1    | L'appal | O       | FLAG    | Valore: | B       | selezio |
|         | to      | (E [4]_ |         | SI/NO/B |         | nare    |
|         | è       | )       |         | lank    |         | un      |
|         | finaliz |         |         |         |         | valore  |
|         | zato    |         |         | Valore  |         | tra     |
|         | alla    |         |         | di      |         | quelli  |
|         | realizz |         |         | default |         | previst |
|         | azione  |         |         | :       |         | i       |
|         | di      |         |         | NULL    |         |         |
|         | progett |         |         |         |         |         |
|         | i       |         |         | Se      |         |         |
|         | d'inves |         |         | obbliga |         |         |
|         | timento |         |         | torio   |         |         |
|         | pubblic |         |         | e campo |         |         |
|         | o       |         |         | non     |         |         |
|         | per i   |         |         | valoriz |         |         |
|         | quali è |         |         | zato    |         |         |
|         | previst |         |         |         |         |         |
|         | a       |         |         |         |         |         |
|         | l'acqui |         |         |         |         |         |
|         | sizione |         |         |         |         |         |
|         | del     |         |         |         |         |         |
|         | codice  |         |         |         |         |         |
|         | CUP ai  |         |         |         |         |         |
|         | sensi   |         |         |         |         |         |
|         | dell'ar |         |         |         |         |         |
|         | t.      |         |         |         |         |         |
|         | 11 L.   |         |         |         |         |         |
|         | 3/2003  |         |         |         |         |         |
|         | e       |         |         |         |         |         |
|         | ss.mm.? |         |         |         |         |         |
|         |         |         |         |         |         |         |
|         | (E'     |         |         |         |         |         |
|         | necessa |         |         |         |         |         |
|         | rio     |         |         |         |         |         |
|         | acquisi |         |         |         |         |         |
|         | re      |         |         |         |         |         |
|         | e       |         |         |         |         |         |
|         | comunic |         |         |         |         |         |
|         | are     |         |         |         |         |         |
|         | il CUP  |         |         |         |         |         |
|         | per     |         |         |         |         |         |
|         | interve |         |         |         |         |         |
|         | nti     |         |         |         |         |         |
|         | finanzi |         |         |         |         |         |
|         | ati,    |         |         |         |         |         |
|         | anche   |         |         |         |         |         |
|         | in      |         |         |         |         |         |
|         | parte,  |         |         |         |         |         |
|         | con     |         |         |         |         |         |
|         | risorse |         |         |         |         |         |
|         | Comunit |         |         |         |         |         |
|         | arie)   |         |         |         |         |         |
|         | (Si/No) |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 18.2    | Cup     | OIF (E) | STRINGA | Sono    | B       | Il      |
|         | associa |         |         | ammessi |         | codice  |
|         | ti      |         |         | uno o   |         | CUP non |
|         | al      |         |         | più     |         | è       |
|         | lotto   |         |         | codici  |         | valido  |
|         |         |         |         |         |         |         |
|         |         |         |         | Se      |         |         |
|         |         |         |         | inserit |         |         |
|         |         |         |         | o       |         |         |
|         |         |         |         | deve    |         |         |
|         |         |         |         | essere  |         |         |
|         |         |         |         | coerent |         |         |
|         |         |         |         | e       |         |         |
|         |         |         |         | (15     |         |         |
|         |         |         |         | caratte |         |         |
|         |         |         |         | ri      |         |         |
|         |         |         |         | alfanum |         |         |
|         |         |         |         | erici)  |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 18.3    | Tipolog | O (E)   | `TIPOLO | Lista   | B       | Selezio |
|         | ia      |         | GIA_LAV | di      |         | nare    |
|         | lavoro  |         | ORO <#t | valori  |         | almeno  |
|         |         |         | ipologi | da      |         | un      |
|         |         |         | a_lavor | elenco  |         | valore  |
|         |         |         | o>`__   |         |         | tra     |
|         |         |         |         |         |         | quelli  |
|         |         |         |         |         |         | previst |
|         |         |         |         |         |         | i       |
+---------+---------+---------+---------+---------+---------+---------+
| 18.4    | Modalit |         | `MODALI | lista   |         |         |
|         | à       |         | TA_ACQU | di      |         |         |
|         | di      |         | ISIZION | valori  |         |         |
|         | acquisi |         | E <#leg | da      |         |         |
|         | zione   |         | ge-8914 | elenco  |         |         |
|         |         |         | >`__    |         |         |         |
|         | (per    |         |         |         |         |         |
|         | servizi |         |         |         |         |         |
|         | e       |         |         |         |         |         |
|         | fornitu |         |         |         |         |         |
|         | re)     |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 19      | Categor | O       | `CATEGO | Lista   | B       | “Selezi |
|         | ia      |         | RIA <#c | di      |         | onare   |
|         | ‘preval |         | ategori | valori  |         | un      |
|         | ente’   |         | a>`__   | da      |         | valore  |
|         | o       |         |         | elenco  |         | tra     |
|         | ‘scorpo |         |         |         |         | quelli  |
|         | rabile’ |         |         |         |         | previst |
|         | eventua |         |         |         |         | i”      |
|         | le      |         |         |         |         |         |
|         | compone |         |         |         |         |         |
|         | nte     |         |         |         |         |         |
|         | lavori  |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+

.. [1]

.. [2]
    Per i CIG associati a gare create a partire dal 12/05/2014 le
   informazioni relative al CUP (campi 18.1, 18.2, 18.3, 18.4) devono
   essere acquisite nella scheda lotto (S02) e rese visibili e non
   modificabili nella successiva scheda di aggiudicazione (S08 o S10)

   Per i CIG associati a gare create anteriormente al 12/05/2014, i CUP
   sono acquisiti nella scheda di aggiudicazione e le relative attività
   di controllo e validazione del CUP devono essere effettuate sui dati
   inseriti nella scheda stessa. In tal caso i dati dovranno essere resi
   disponibili, visibili e non editabili anche nella scheda lotto.

.. [3]

.. [4]
    Per i CIG associati a gare create a partire dal 12/05/2014 le
   informazioni relative al CUP (campi 18.1, 18.2, 18.3, 18.4) devono
   essere acquisite nella scheda lotto (S02) e rese visibili e non
   modificabili nella successiva scheda di aggiudicazione (S08 o S10)

   Per i CIG associati a gare create anteriormente al 12/05/2014, i CUP
   sono acquisiti nella scheda di aggiudicazione e le relative attività
   di controllo e validazione del CUP devono essere effettuate sui dati
   inseriti nella scheda stessa. In tal caso i dati dovranno essere resi
   disponibili, visibili e non editabili anche nella scheda lotto.
