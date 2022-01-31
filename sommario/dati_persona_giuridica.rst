DATI_PERSONA_GIURIDICA
======================

+---------+---------+---------+---------+---------+---------+---------+
| DATI_PE |         |         |         |         |         |         |
| RSONA_G |         |         |         |         |         |         |
| IURIDIC |         |         |         |         |         |         |
| A       |         |         |         |         |         |         |
+=========+=========+=========+=========+=========+=========+=========+
| COD     | ETICHET | TIPO    | FORMATO | CONTROL | MESSAGG |         |
|         | TA      |         |         | LO      | IO      |         |
+---------+---------+---------+---------+---------+---------+---------+
|         |         |         |         | DESCRIZ | TIPO    |         |
|         |         |         |         | IONE    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 01      | Codice  | O       | STRINGA | Deve    | B       | codice  |
|         | fiscale |         |         | essere  |         | fiscale |
|         | /       |         |         | formalm |         | /Partit |
|         | Partita |         |         | ente    |         | a       |
|         | IVA     |         |         | corrett |         | IVA     |
|         |         |         |         | o       |         | formalm |
|         |         |         |         |         |         | ente    |
|         |         |         |         | Se non  |         | non     |
|         |         |         |         | valoriz |         | corrett |
|         |         |         |         | zato    |         | o       |
|         |         |         |         |         |         |         |
|         |         |         |         | Deve    |         | Non è   |
|         |         |         |         | essere  |         | stato   |
|         |         |         |         | un      |         | indicat |
|         |         |         |         | codice  |         | o       |
|         |         |         |         | fiscale |         | il      |
|         |         |         |         | di      |         | codice  |
|         |         |         |         | persona |         | fiscale |
|         |         |         |         | fisica/ |         | /       |
|         |         |         |         | giuridi |         | Partita |
|         |         |         |         | ca      |         | IVA     |
|         |         |         |         | formalm |         | dell’op |
|         |         |         |         | ente    |         | eratore |
|         |         |         |         | corrett |         | economi |
|         |         |         |         | o       |         | co      |
|         |         |         |         | solo se |         | o       |
|         |         |         |         | campo   |         | affidat |
|         |         |         |         | 05 =    |         | ario    |
|         |         |         |         | ‘NO’    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 02      | Denomin | O       | STRINGA | Valoriz | B       | Non è   |
|         | azione  |         |         | zazione |         | stata   |
|         |         |         |         |         |         | indicat |
|         |         |         |         |         |         | a       |
|         |         |         |         |         |         | la      |
|         |         |         |         |         |         | denomin |
|         |         |         |         |         |         | azione  |
|         |         |         |         |         |         | dell’ap |
|         |         |         |         |         |         | palto   |
+---------+---------+---------+---------+---------+---------+---------+
| 03      | Camera  |         | STRINGA | Valoriz |         |         |
|         | Commerc |         |         | zazione |         |         |
|         | io      |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 04      | Tipo    | O       | `TIPO_A | Lista   | B       | Non è   |
|         | Aggiudi |         | GGIUDIC | di      |         | stata   |
|         | catario |         | ATARIO  | valori  |         | selezio |
|         |         |         | <#tipo_ | da      |         | nata    |
|         |         |         | aggiudi | elenco  |         | la      |
|         |         |         | catario |         |         | tipolog |
|         |         |         | >`__    |         |         | ia      |
|         |         |         |         |         |         | di      |
|         |         |         |         |         |         | soggett |
|         |         |         |         |         |         | o       |
+---------+---------+---------+---------+---------+---------+---------+
| 05      | Operato | O       | FLAG    | Valore  | B       | Indicar |
|         | re      |         | (SI/NO) | di      |         | e       |
|         | Economi |         |         | default |         | se      |
|         | co      |         |         | :       |         | l’aggiu |
|         | Estero  |         |         | NO      |         | dicatar |
|         |         |         |         |         |         | io      |
|         |         |         |         |         |         | è       |
|         |         |         |         |         |         | estero  |
+---------+---------+---------+---------+---------+---------+---------+
| 06      | Paese   | OIF     | STRINGA | Se      | B       | Il      |
|         | Operato |         |         | campo   |         | campo   |
|         | re      |         |         | S08.04  |         | Stato   |
|         | Economi |         |         | = ‘SI’  |         | Estero  |
|         | co      |         |         |         |         | non è   |
|         |         |         |         |         |         | valido  |
+---------+---------+---------+---------+---------+---------+---------+
| 07      | Progres | C       | NUMERIC | progres |         |         |
|         | sivo    |         | O       | sivo    |         |         |
|         | raggrup |         |         | generat |         |         |
|         | pamento |         |         | o       |         |         |
|         |         |         |         | dal     |         |         |
|         |         |         |         | sistema |         |         |
|         |         |         |         | in caso |         |         |
|         |         |         |         | di      |         |         |
|         |         |         |         | raggrup |         |         |
|         |         |         |         | pamento |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 08      | Indiriz |         | STRINGA | Valoriz |         |         |
|         | zo      |         |         | zazione |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 09      | Civico  |         | NUMERIC | Se      |         |         |
|         |         |         | O       | valoriz |         |         |
|         |         |         |         | zato    |         |         |
|         |         |         |         | deve    |         |         |
|         |         |         |         | essere  |         |         |
|         |         |         |         | interam |         |         |
|         |         |         |         | ente    |         |         |
|         |         |         |         | numeric |         |         |
|         |         |         |         | o       |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 10      | CAP     |         | NUMERIC | Se      |         |         |
|         |         |         | O       | valoriz |         |         |
|         |         |         |         | zato    |         |         |
|         |         |         |         | deve    |         |         |
|         |         |         |         | essere  |         |         |
|         |         |         |         | interam |         |         |
|         |         |         |         | ente    |         |         |
|         |         |         |         | numeric |         |         |
|         |         |         |         | o       |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 11      | Provinc |         | STRINGA | Valoriz |         |         |
|         | ia      |         |         | zazione |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 12      | Cognome | O       | STRINGA | Valoriz | B       | Non è   |
|         |         |         |         | zazione |         | stato   |
|         |         |         |         |         |         | indicat |
|         |         |         |         |         |         | o       |
|         |         |         |         |         |         | il      |
|         |         |         |         |         |         | Cognome |
|         |         |         |         |         |         | del     |
|         |         |         |         |         |         | rappres |
|         |         |         |         |         |         | entante |
|         |         |         |         |         |         | legale  |
+---------+---------+---------+---------+---------+---------+---------+
| 13      | Nome    |         | STRINGA | Valoriz | W       | Non è   |
|         |         |         |         | zazione |         | stato   |
|         |         |         |         |         |         | indicat |
|         |         |         |         |         |         | o       |
|         |         |         |         |         |         | il Nome |
|         |         |         |         |         |         | del     |
|         |         |         |         |         |         | rappres |
|         |         |         |         |         |         | entante |
|         |         |         |         |         |         | legale  |
+---------+---------+---------+---------+---------+---------+---------+
| 14      | Codice  | OIF     | STRINGA | Deve    | B       | codice  |
|         | Fiscale |         |         | essere  |         | fiscale |
|         | del     |         |         | formalm | B       | formalm |
|         | legale  |         |         | ente    |         | ente    |
|         | Rappres |         |         | corrett |         | non     |
|         | entante |         |         | o       |         | corrett |
|         |         |         |         | solo se |         | o       |
|         |         |         |         | campo   |         |         |
|         |         |         |         | S08.04  |         | Non è   |
|         |         |         |         | = ‘NO’  |         | stato   |
|         |         |         |         |         |         | indicat |
|         |         |         |         | Obbliga |         | o       |
|         |         |         |         | torio   |         | il      |
|         |         |         |         | solo se |         | Codice  |
|         |         |         |         | campo   |         | Fiscale |
|         |         |         |         | S08.04  |         | del     |
|         |         |         |         | = ‘NO’  |         | legale  |
|         |         |         |         | altrime |         | rappres |
|         |         |         |         | nti     |         | entante |
|         |         |         |         | è       |         | dell’im |
|         |         |         |         | facolta |         | presa   |
|         |         |         |         | tivo    |         | aggiudi |
|         |         |         |         |         |         | cataria |
+---------+---------+---------+---------+---------+---------+---------+
| 15      | Ribasso |         | PERCENT | Il      | W       | Il      |
|         | di      |         | UALE    | valore  |         | valore  |
|         | Aggiudi |         |         | deve    | B       | del     |
|         | cazione |         |         | essere  |         | campo   |
|         |         |         |         | percent | B       | “Ribass |
|         |         |         |         | uale    |         | o       |
|         |         |         |         | con la  | **      | aggiudi |
|         |         |         |         | possibi | **      | cazione |
|         |         |         |         | lità    |         | ”       |
|         |         |         |         | di      | W       | non è   |
|         |         |         |         | arrivar |         | coerent |
|         |         |         |         | e       |         | e       |
|         |         |         |         | alla    |         |         |
|         |         |         |         | quinta  |         | Il      |
|         |         |         |         | cifra   |         | valore  |
|         |         |         |         | decimal |         | del     |
|         |         |         |         | e       |         | campo   |
|         |         |         |         |         |         | “Ribass |
|         |         |         |         | Se      |         | o       |
|         |         |         |         | valoriz |         | aggiudi |
|         |         |         |         | zato    |         | cazione |
|         |         |         |         | deve    |         | ”       |
|         |         |         |         | essere  |         | non è   |
|         |         |         |         | >=0 e   |         | coerent |
|         |         |         |         | <100    |         | e       |
|         |         |         |         |         |         |         |
|         |         |         |         | in      |         | | Sono  |
|         |         |         |         | alterna |         |   stati |
|         |         |         |         | tiva    |         |   indic |
|         |         |         |         | al      |         | ati     |
|         |         |         |         | campo   |         |   sia   |
|         |         |         |         | S08.61  |         |   il    |
|         |         |         |         |         |         |   ribas |
|         |         |         |         | Se non  |         | so      |
|         |         |         |         | valoriz |         |   di    |
|         |         |         |         | zato    |         |   aggiu |
|         |         |         |         | e campo |         | dicazio |
|         |         |         |         | S08.33  |         | ne      |
|         |         |         |         | vale    |         |   sia   |
|         |         |         |         | “prezzo |         |   l’off |
|         |         |         |         | più     |         | erta    |
|         |         |         |         | basso”  |         |   in    |
|         |         |         |         | e       |         |   aumen |
|         |         |         |         |         |         | to      |
|         |         |         |         | -  S01. |         | | Valor |
|         |         |         |         | 11      |         | izzare  |
|         |         |         |         |    =    |         |   il    |
|         |         |         |         |    ‘ORD |         |   Ribas |
|         |         |         |         | INARIO’ |         | so      |
|         |         |         |         |         |         |   di    |
|         |         |         |         | -  S01. |         |   aggiu |
|         |         |         |         | 11      |         | dicazio |
|         |         |         |         |    =    |         | ne      |
|         |         |         |         |    ‘set |         |   nel   |
|         |         |         |         | tore    |         |   caso  |
|         |         |         |         |    spec |         |   di    |
|         |         |         |         | iale’   |         |   offer |
|         |         |         |         |    **e* |         | ta      |
|         |         |         |         | *       |         |   a     |
|         |         |         |         |    camp |         |   prezz |
|         |         |         |         | o       |         | i       |
|         |         |         |         |    S08. |         |   unita |
|         |         |         |         | 26      |         | ri,     |
|         |         |         |         |    >    |         |   ovver |
|         |         |         |         |    dell |         | o       |
|         |         |         |         | e       |         |   in    |
|         |         |         |         |    sogl |         |   caso  |
|         |         |         |         | ie      |         |   di    |
|         |         |         |         |    comu |         |   formu |
|         |         |         |         | nitarie |         | lazione |
|         |         |         |         |         |         |   di    |
|         |         |         |         |         |         |   ribas |
|         |         |         |         |         |         | so      |
|         |         |         |         |         |         |   sull’ |
|         |         |         |         |         |         | importo |
|         |         |         |         |         |         |   delle |
|         |         |         |         |         |         |   prest |
|         |         |         |         |         |         | azioni  |
|         |         |         |         |         |         |   poste |
|         |         |         |         |         |         |   a     |
|         |         |         |         |         |         |   base  |
|         |         |         |         |         |         |   di    |
|         |         |         |         |         |         |   gara  |
+---------+---------+---------+---------+---------+---------+---------+
| 16      | Offerta |         | PERCENT | Il      | W       | Il      |
|         | in      |         | UALE    | valore  |         | valore  |
|         | Aumento |         |         | deve    | B       | del     |
|         |         |         |         | essere  |         | campo   |
|         |         |         |         | percent | | **    | “Offert |
|         |         |         |         | uale    |   **    | a       |
|         |         |         |         | con la  | | B     | in      |
|         |         |         |         | possibi |         | aumento |
|         |         |         |         | lità    |         | ”       |
|         |         |         |         | di      |         | non è   |
|         |         |         |         | arrivar |         | coerent |
|         |         |         |         | e       |         | e       |
|         |         |         |         | alla    |         |         |
|         |         |         |         | quinta  |         | Il      |
|         |         |         |         | cifra   |         | valore  |
|         |         |         |         | decimal |         | del     |
|         |         |         |         | e       |         | campo   |
|         |         |         |         |         |         | “Ribass |
|         |         |         |         | Se      |         | o       |
|         |         |         |         | valoriz |         | aggiudi |
|         |         |         |         | zato    |         | cazione |
|         |         |         |         | deve    |         | ”       |
|         |         |         |         | essere  |         | non è   |
|         |         |         |         | >=0     |         | coerent |
|         |         |         |         |         |         | e       |
|         |         |         |         | In      |         |         |
|         |         |         |         | alterna |         | Sono    |
|         |         |         |         | tiva    |         | stati   |
|         |         |         |         | al      |         | indicat |
|         |         |         |         | campo   |         | i       |
|         |         |         |         | S08.60  |         | sia il  |
|         |         |         |         |         |         | ribasso |
|         |         |         |         |         |         | di      |
|         |         |         |         |         |         | aggiudi |
|         |         |         |         |         |         | cazione |
|         |         |         |         |         |         | sia     |
|         |         |         |         |         |         | l’offer |
|         |         |         |         |         |         | ta      |
|         |         |         |         |         |         | in      |
|         |         |         |         |         |         | aumento |
+---------+---------+---------+---------+---------+---------+---------+
| 17      | Importo |         | IMPORTO | valore  | B       | Inserir |
|         | di      |         |         | numeric |         | e       |
|         | Aggiudi |         |         | o       | W       | l’impor |
|         | cazione |         |         | >\ **=* |         | to      |
|         |         |         |         | *       | W       | di      |
|         |         |         |         | 0       |         | aggiudi |
|         |         |         |         |         |         | cazione |
|         |         |         |         | Se >    |         |         |
|         |         |         |         | S08.26  |         | Verific |
|         |         |         |         | e       |         | are     |
|         |         |         |         | S01.11  |         | il      |
|         |         |         |         | =       |         | valore  |
|         |         |         |         | ‘ORDINA |         | dell’im |
|         |         |         |         | RIO’    |         | porto   |
|         |         |         |         |         |         | di      |
|         |         |         |         | Se >    |         | aggiudi |
|         |         |         |         | dell’in |         | cazione |
|         |         |         |         | dice    |         |         |
|         |         |         |         | di      |         | Verific |
|         |         |         |         | dispers |         | are     |
|         |         |         |         | ione    |         | la      |
|         |         |         |         | “deviaz |         | corrett |
|         |         |         |         | ione    |         | ezza    |
|         |         |         |         | standar |         | dell’im |
|         |         |         |         | d”      |         | porto   |
|         |         |         |         |         |         | di      |
|         |         |         |         |         |         | aggiudi |
|         |         |         |         |         |         | cazione |
|         |         |         |         |         |         | /affida |
|         |         |         |         |         |         | mento   |
+---------+---------+---------+---------+---------+---------+---------+

.. _section-1:

24. .. rubric::  Tabelle tipologiche
       :name: tabelle-tipologiche

    15. .. rubric:: ART_ESCLUSIONE
           :name: art_esclusione

+--------------------+-------------------------+------------------------+
| **ART_ESCLUSIONE** |                         |                        |
+====================+=========================+========================+
| **codice**         | **Descrizione**         | **data fine validità** |
+--------------------+-------------------------+------------------------+
| 1                  | Art. 19 D.Lgs. 163/2006 |                        |
+--------------------+-------------------------+------------------------+
| 2                  | Art. 20 D.Lgs. 163/2006 |                        |
+--------------------+-------------------------+------------------------+
| 3                  | Art. 21 D.Lgs. 163/2006 |                        |
+--------------------+-------------------------+------------------------+
| 4                  | Art. 22 D.Lgs. 163/2006 |                        |
+--------------------+-------------------------+------------------------+
| 5                  | Art. 23 D.Lgs. 163/2006 |                        |
+--------------------+-------------------------+------------------------+
| 6                  | Art. 24 D.Lgs. 163/2006 |                        |
+--------------------+-------------------------+------------------------+
| 7                  | Art. 25 D.Lgs. 163/2006 |                        |
+--------------------+-------------------------+------------------------+
| 8                  | Art. 16 D.Lgs. 163/2006 |                        |
+--------------------+-------------------------+------------------------+
| 9                  | Art. 17 D.Lgs. 163/2006 |                        |
+--------------------+-------------------------+------------------------+
| 10                 | Art. 18 D.Lgs. 163/2006 |                        |
+--------------------+-------------------------+------------------------+
| 11                 | Art. 26 D.Lgs. 163/2006 |                        |
+--------------------+-------------------------+------------------------+
| 12                 | Esclusione per OO.CC.   |                        |
+--------------------+-------------------------+------------------------+
