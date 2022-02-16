S06 – Perfezionamento e pubblicazione gara [1]_
===============================================

+---------+---------+---------+---------+---------+---------+---------+
| S06 –   |         |         |         |         |         |         |
| Perfezi |         |         |         |         |         |         |
| onament |         |         |         |         |         |         |
| o       |         |         |         |         |         |         |
| e       |         |         |         |         |         |         |
| pubblic |         |         |         |         |         |         |
| azione  |         |         |         |         |         |         |
| gara    |         |         |         |         |         |         |
+=========+=========+=========+=========+=========+=========+=========+
| COD     | ETICHET | TIPO    | FORMATO | CONTROL | MESSAGG |         |
|         | TA      |         |         | LO      | IO      |         |
+---------+---------+---------+---------+---------+---------+---------+
|         |         |         |         | DESCRIZ | TIPO    |         |
|         |         |         |         | IONE    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 01      | Numero  | E       | NUMERIC |         |         |         |
|         | gara    |         | O       |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **DATI  |         |         |         |         |         |         |
| DI      |         |         |         |         |         |         |
| PERFEZI |         |         |         |         |         |         |
| ONAMENT |         |         |         |         |         |         |
| O       |         |         |         |         |         |         |
| DEI     |         |         |         |         |         |         |
| LOTTI** |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+

+---------+---------+---------+---------+---------+---------+---------+
| 02.X    | Data    | O [3]_  | DATA    | Se non  | B       | Inserir |
|         | pubblic |         |         | valoriz |         | e       |
|         | azione  |         |         | zata    | B       | la data |
|         |         |         |         |         |         | di      |
|         |         |         |         | Se non  |         | pubblic |
|         |         |         |         | è una   |         | azione  |
|         |         |         |         | data    |         |         |
|         |         |         |         |         |         | Data    |
|         |         |         |         |         |         | formalm |
|         |         |         |         |         |         | ente    |
|         |         |         |         |         |         | non     |
|         |         |         |         |         |         | corrett |
|         |         |         |         |         |         | a       |
+=========+=========+=========+=========+=========+=========+=========+
| 03.X    | Data    | O\ :sup | DATA    | se non  | B       | Inserir |
|         | scadenz | :`4`    |         | valoriz |         | e       |
|         | a       |         |         | zata    | B       | la data |
|         | per la  |         |         |         |         | di      |
|         | present |         |         | Se non  | B       | scadenz |
|         | azione  |         |         | è una   |         | a       |
|         | delle   |         |         | data    |         | present |
|         | offerte |         |         |         |         | azione  |
|         |         |         |         | Se      |         | delle   |
|         |         |         |         | minore  |         | offerte |
|         |         |         |         | di      |         |         |
|         |         |         |         | S06.02  |         | Data    |
|         |         |         |         |         |         | formalm |
|         |         |         |         |         |         | ente    |
|         |         |         |         |         |         | non     |
|         |         |         |         |         |         | corrett |
|         |         |         |         |         |         | a       |
|         |         |         |         |         |         |         |
|         |         |         |         |         |         | La data |
|         |         |         |         |         |         | di      |
|         |         |         |         |         |         | scadenz |
|         |         |         |         |         |         | a       |
|         |         |         |         |         |         | per la  |
|         |         |         |         |         |         | present |
|         |         |         |         |         |         | azione  |
|         |         |         |         |         |         | delle   |
|         |         |         |         |         |         | offerte |
|         |         |         |         |         |         | deve    |
|         |         |         |         |         |         | essere  |
|         |         |         |         |         |         | success |
|         |         |         |         |         |         | iva     |
|         |         |         |         |         |         | alla    |
|         |         |         |         |         |         | data di |
|         |         |         |         |         |         | pubblic |
|         |         |         |         |         |         | azione  |
+---------+---------+---------+---------+---------+---------+---------+
| 04.X    | Ora     |         | ORA     | Se non  | B       | ora     |
|         | scadenz |         |         | è un    |         | formalm |
|         | a       |         |         | formato |         | ente    |
|         |         |         |         | di tipo |         | non     |
|         | per la  |         |         | ora     |         | corrett |
|         | present |         |         |         |         | a       |
|         | azione  |         |         |         |         |         |
|         | delle   |         |         |         |         |         |
|         | offerte |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 05.PR   | Data di | OIF\ :s | DATA    | Se non  | B       | Data    |
|         | scadenz | up:`4`  |         | è una   |         | formalm |
|         | a       |         |         | data    |         | ente    |
|         | per la  |         |         |         |         | non     |
|         | present |         |         |         |         | corrett |
|         | azione  |         |         |         |         | a       |
|         | della   |         |         |         |         |         |
|         | richies |         |         |         |         |         |
|         | ta      |         |         |         |         |         |
|         | di      |         |         |         |         |         |
|         | invito  |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 06.PR   | Data    | OIF\ :s | DATA    | Se non  | B       | Data    |
|         | della   | up:`4`  |         | è una   |         | formalm |
|         | lettera |         |         | data    |         | ente    |
|         | di      |         |         |         |         | non     |
|         | invito  |         |         |         |         | corrett |
|         |         |         |         |         |         | a       |
+---------+---------+---------+---------+---------+---------+---------+
| 02.AD   | Data di | OIF\ :s | DATA    | Se il   | B       | Data di |
|         | adesion | up:`4`  |         | campo   |         | adesion |
|         | e       |         |         | S01.13  | B       | e       |
|         | all'acc |         |         | (modali |         | all'acc |
|         | ordo    |         |         | tà      |         | ordo    |
|         | quadro/ |         |         | di      |         | quadro/ |
|         | convenz |         |         | realizz |         | convenz |
|         | ione    |         |         | azione  |         | ione    |
|         |         |         |         | ) = 2 o |         | non     |
|         |         |         |         | 11      |         | valida  |
|         |         |         |         |         |         |         |
|         |         |         |         | In      |         | Data    |
|         |         |         |         | alterna |         | formalm |
|         |         |         |         | tiva    |         | ente    |
|         |         |         |         | ai      |         | non     |
|         |         |         |         | campi   |         | corrett |
|         |         |         |         | S06.02, |         | a       |
|         |         |         |         | .03,    |         |         |
|         |         |         |         | .04     |         |         |
|         |         |         |         |         |         |         |
|         |         |         |         | Se non  |         |         |
|         |         |         |         | valoriz |         |         |
|         |         |         |         | zato    |         |         |
|         |         |         |         |         |         |         |
|         |         |         |         | Se non  |         |         |
|         |         |         |         | è una   |         |         |
|         |         |         |         | data    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **PUBBL |         |         |         |         |         |         |
| ICITA’  |         |         |         |         |         |         |
| DELL’AP |         |         |         |         |         |         |
| PALTO** |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 05      | Data    |         | DATA    | Se non  | B       | Data    |
|         | Gazzett |         |         | è una   |         | formalm |
|         | a       |         |         | data    |         | ente    |
|         | Ufficia |         |         |         |         | non     |
|         | le      |         |         |         |         | corrett |
|         | Comunit |         |         |         |         | a       |
|         | à       |         |         |         |         |         |
|         | Europea |         |         |         |         |         |
|         | - GUCE  |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 06      | Numero  | OIF     | STRINGA | Se non  | B       | Obbliga |
|         | Gazzett |         |         | valoriz |         | torio   |
|         | a       |         |         | zato    |         | se Data |
|         | Ufficia |         |         | e       |         | GUCE è  |
|         | le      |         |         | S06.05  |         | valoriz |
|         | Comunit |         |         | è       |         | zato    |
|         | à       |         |         | valoriz |         |         |
|         | Europea |         |         | zato    |         |         |
|         | - GUCE  |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 07      | Data    |         | DATA    | Se non  | B       | Data    |
|         | Gazzett |         |         | è una   |         | formalm |
|         | a       |         |         | data    |         | ente    |
|         | Ufficia |         |         |         |         | non     |
|         | le      |         |         |         |         | corrett |
|         | Regiona |         |         |         |         | a       |
|         | le      |         |         |         |         |         |
|         | o       |         |         |         |         |         |
|         | Bollett |         |         |         |         |         |
|         | ino     |         |         |         |         |         |
|         | Regiona |         |         |         |         |         |
|         | le      |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 08      | Numero  |         | STRINGA | Se non  | B       | Obbliga |
|         | Gazzett |         |         | valoriz |         | torio   |
|         | a       |         |         | zato    |         | se Data |
|         | Ufficia |         |         | e       |         | BORE è  |
|         | le      |         |         | S06.07  |         | valoriz |
|         | Regiona |         |         | è       |         | zato    |
|         | le      |         |         | valoriz |         |         |
|         | o       |         |         | zato    |         |         |
|         | Bollett |         |         |         |         |         |
|         | ino     |         |         |         |         |         |
|         | Regiona |         |         |         |         |         |
|         | le      |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 09      | Data    |         | DATA    | Se non  | B       | Data    |
|         | Gazzett |         |         | è una   |         | formalm |
|         | a       |         |         | data    |         | ente    |
|         | Ufficia |         |         |         |         | non     |
|         | le      |         |         |         |         | corrett |
|         | Repubbl |         |         |         |         | a       |
|         | ica     |         |         |         |         |         |
|         | Italian |         |         |         |         |         |
|         | a       |         |         |         |         |         |
|         | - GURI  |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 10      | Numero  |         | STRINGA | Se non  | B       | Obbliga |
|         | Gazzett |         |         | valoriz |         | torio   |
|         | a       |         |         | zato    |         | se Data |
|         | Ufficia |         |         | e       |         | GURI è  |
|         | le      |         |         | S06.09  |         | valoriz |
|         | Repubbl |         |         | è       |         | zato    |
|         | ica     |         |         | valoriz |         |         |
|         | Italian |         |         | zato    |         |         |
|         | a       |         |         |         |         |         |
|         | - GURI  |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 11      | Data    |         | DATA    | Se non  | B       | Data    |
|         | Albo    |         |         | è una   |         | formalm |
|         | pretori |         |         | data    |         | ente    |
|         | o       |         |         |         |         | non     |
|         | del     |         |         |         |         | corrett |
|         | Comune  |         |         |         |         | a       |
|         | ove si  |         |         |         |         |         |
|         | eseguon |         |         |         |         |         |
|         | o       |         |         |         |         |         |
|         | i       |         |         |         |         |         |
|         | lavori  |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 12      | Quotidi |         | NUMERIC | Se non  | B       | Il      |
|         | ani     |         | O       | è un    |         | campo   |
|         | naziona |         |         | numero  | W       | contien |
|         | li      |         |         |         |         | e       |
|         |         |         |         |         |         | caratte |
|         |         |         |         |         |         | ri      |
|         |         |         |         |         |         | non     |
|         |         |         |         |         |         | validi  |
|         |         |         |         |         |         |         |
|         |         |         |         |         |         | numero  |
|         |         |         |         |         |         | quotidi |
|         |         |         |         |         |         | ani     |
|         |         |         |         |         |         | naziona |
|         |         |         |         |         |         | li      |
|         |         |         |         |         |         | non     |
|         |         |         |         |         |         | valido  |
+---------+---------+---------+---------+---------+---------+---------+
| 13      | Quotidi |         | NUMERIC | Se non  | W       | Il      |
|         | ani     |         | O       | è un    |         | campo   |
|         | locali  |         |         | numero  |         | contien |
|         |         |         |         |         |         | e       |
|         |         |         |         |         |         | caratte |
|         |         |         |         |         |         | ri      |
|         |         |         |         |         |         | non     |
|         |         |         |         |         |         | validi  |
|         |         |         |         |         |         |         |
|         |         |         |         |         |         | numero  |
|         |         |         |         |         |         | quotidi |
|         |         |         |         |         |         | ani     |
|         |         |         |         |         |         | locali  |
|         |         |         |         |         |         | non     |
|         |         |         |         |         |         | valido  |
+---------+---------+---------+---------+---------+---------+---------+
| 14      | Periodi |         | NUMERIC | Se non  |         | Il      |
|         | ci      |         | O       | è un    |         | campo   |
|         |         |         |         | numero  |         | contien |
|         |         |         |         |         |         | e       |
|         |         |         |         |         |         | caratte |
|         |         |         |         |         |         | ri      |
|         |         |         |         |         |         | non     |
|         |         |         |         |         |         | validi  |
+---------+---------+---------+---------+---------+---------+---------+
| 15      | Sito    | OIF     | FLAG    | Valore: | B       | Non è   |
|         | Informa |         |         | SI/NO   |         | stata   |
|         | tico    |         |         |         |         | effettu |
|         | Ministe |         |         | Default |         | ata     |
|         | ro      |         |         | :       |         | la      |
|         | Infrast |         |         | BLANK   |         | pubblic |
|         | rutture |         |         |         |         | azione  |
|         |         |         |         | Se vale |         | sul     |
|         |         |         |         | ‘no’ e  |         | sito    |
|         |         |         |         | campo   |         | informa |
|         |         |         |         | S01.10  |         | tico    |
|         |         |         |         | >=      |         | del     |
|         |         |         |         | 500.000 |         | Ministe |
|         |         |         |         |         |         | ro      |
|         |         |         |         |         |         | delle   |
|         |         |         |         |         |         | Infrast |
|         |         |         |         |         |         | rutture |
+---------+---------+---------+---------+---------+---------+---------+
| 16      | Link    |         | STRINGA |         |         |         |
|         | Sito    |         |         |         |         |         |
|         | Committ |         |         |         |         |         |
|         | ente    |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 17      | Procedu | OIF     | FLAG    | Valore: | B       | selezio |
|         | ra      |         |         | SI/NO   |         | nare    |
|         | negozia |         |         |         | B       | un      |
|         | ta      |         |         | Default |         | valore  |
|         | ex art. |         |         | :       | B       | tra     |
|         | 204     |         |         | NULL    |         | quelli  |
|         | comma 1 |         |         |         |         | previst |
|         | D.Lgs.  |         |         | Se non  |         | i       |
|         | 163/200 |         |         | valoriz |         |         |
|         | 6       |         |         | zato    |         | I dati  |
|         |         |         |         |         |         | relativ |
|         |         |         |         | Se      |         | i       |
|         |         |         |         | valoriz |         | alla    |
|         |         |         |         | zato    |         | pubblic |
|         |         |         |         | e       |         | ità     |
|         |         |         |         | S01.13  |         | dell'ap |
|         |         |         |         | <> 1,   |         | palto   |
|         |         |         |         | 2, 8, 9 |         | non     |
|         |         |         |         |         |         | devono  |
|         |         |         |         | Se      |         | essere  |
|         |         |         |         | valoriz |         | inserit |
|         |         |         |         | zato    |         | i’      |
|         |         |         |         | a ‘SI’  |         |         |
|         |         |         |         | e       |         | il      |
|         |         |         |         | S01.13  |         | valore  |
|         |         |         |         | = 2,    |         | del     |
|         |         |         |         | 25, 13, |         | campo   |
|         |         |         |         | 9       |         | deve    |
|         |         |         |         |         |         | essere  |
|         |         |         |         |         |         | obbliga |
|         |         |         |         |         |         | toriame |
|         |         |         |         |         |         | nte     |
|         |         |         |         |         |         | NO      |
+---------+---------+---------+---------+---------+---------+---------+
| **ALLEG |         |         |         |         |         |         |
| ATI     |         |         |         |         |         |         |
| AL      |         |         |         |         |         |         |
| BANDO   |         |         |         |         |         |         |
| DI      |         |         |         |         |         |         |
| GARA**  |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 18      | Bando   | OIF     | FILE    | Se non  | B       | previst |
|         | di Gara |         |         | valoriz |         | o       |
|         |         |         |         | zato    | W       | l'inser |
|         |         |         |         | e se    |         | imento  |
|         |         |         |         | campo   |         | dell'al |
|         |         |         |         | S01.10  |         | legato  |
|         |         |         |         | >= €    |         |         |
|         |         |         |         | 500.000 |         | previst |
|         |         |         |         | ,       |         | o       |
|         |         |         |         | se      |         | l'inser |
|         |         |         |         | S02.07  |         | imento  |
|         |         |         |         | = ‘L’ e |         | dell'al |
|         |         |         |         | se      |         | legato  |
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
|         |         |         |         | oppure  |         |         |
|         |         |         |         | se      |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S06.17= |         |         |
|         |         |         |         | ’SI’    |         |         |
|         |         |         |         |         |         |         |
|         |         |         |         | Se non  |         |         |
|         |         |         |         | valoriz |         |         |
|         |         |         |         | zato    |         |         |
|         |         |         |         | e se    |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S01.10  |         |         |
|         |         |         |         | < €     |         |         |
|         |         |         |         | 500.000 |         |         |
|         |         |         |         | o se    |         |         |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S02.06  |         |         |
|         |         |         |         | dei     |         |         |
|         |         |         |         | lotti   |         |         |
|         |         |         |         | attivi  |         |         |
|         |         |         |         | è <>    |         |         |
|         |         |         |         | da:     |         |         |
|         |         |         |         | 1,2,8,9 |         |         |
|         |         |         |         | ,13     |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 19      | Discipl | OIF     | FILE    | Se non  | W       | previst |
|         | inare   |         |         | valoriz |         | o       |
|         |         |         |         | zato    |         | l'inser |
|         |         |         |         | e se    |         | imento  |
|         |         |         |         | campo   |         | dell'al |
|         |         |         |         | S01.10  |         | legato  |
|         |         |         |         | >= €    |         |         |
|         |         |         |         | 500.000 |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 20      | Lettera |         | FILE    | Se non  | B       | previst |
|         | di      |         |         | valoriz |         | o       |
|         | Invito  |         |         | zato    |         | l'inser |
|         | (ex     |         |         | e se    |         | imento  |
|         | art.204 |         |         | campo   |         | dell'al |
|         | c.1)    |         |         | S06.17= |         | legato  |
|         |         |         |         | ’SI’    |         |         |
+---------+---------+---------+---------+---------+---------+---------+

.. [1]
    In fase di perfezionamento della gara è possibile cancellare i lotti
   associati secondo la scheda S04

.. [2]
   Vedi tabella, paragrafo 5.3 ‘Tabella di mappatura ‘procedura scelta
   contraente’/ ‘data’’

.. [3]
   Vedi tabella, paragrafo 5.3 ‘Tabella di mappatura ‘procedura scelta
   contraente’/ ‘data’’
