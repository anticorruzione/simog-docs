S02a – Integrazione dati CUP
============================

+---------+---------+---------+---------+---------+---------+---------+
| S02a –  |         |         |         |         |         |         |
| integra |         |         |         |         |         |         |
| zione   |         |         |         |         |         |         |
| dati    |         |         |         |         |         |         |
| CUP     |         |         |         |         |         |         |
+=========+=========+=========+=========+=========+=========+=========+
| COD     | ETICHET | TIPO    | FORMATO | CONTROL | MESSAGG |         |
|         | TA      |         |         | LO      | IO      |         |
+---------+---------+---------+---------+---------+---------+---------+
|         |         |         |         | DESCRIZ | TIPO    |         |
|         |         |         |         | IONE    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 01      | L'appal | O (P)   | FLAG    | Valore: | B       | Selezio |
|         | to      |         |         | SI/NO/B |         | nare    |
|         | è       |         |         | lank    |         | almeno  |
|         | finaliz |         |         |         |         | un      |
|         | zato    |         |         | Valore  |         | opzione |
|         | alla    |         |         | di      |         | per     |
|         | realizz |         |         | default |         | tutti i |
|         | azione  |         |         | :       |         | campi   |
|         | di      |         |         | NULL    |         | Si/No   |
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
| 02      | Cup     | OIF (P) | STRINGA | Sono    | B       | Il      |
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
| 03      | Tipolog | O (P)   | `TIPOLO | Lista   | B       | Selezio |
|         | ia      |         | GIA_LAV | di      |         | nare    |
|         | lavoro  |         | ORO <#t | valori  |         | almeno  |
|         |         |         | ipologi | da      |         | un      |
|         |         |         | a_lavor | elenco  |         | valore  |
|         |         |         | o>`__   |         |         | tra     |
|         |         |         |         |         |         | quelli  |
|         |         |         |         |         |         | previst |
|         |         |         |         |         |         | i       |
+---------+---------+---------+---------+---------+---------+---------+
| 04      | Modalit | (P)     | `MODALI | lista   |         |         |
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
