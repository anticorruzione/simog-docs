S03 – Cancellazione gara
========================

+---------+---------+---------+---------+---------+---------+---------+
| S03 –   |         |         |         |         |         |         |
| cancell |         |         |         |         |         |         |
| azione  |         |         |         |         |         |         |
| gara [2 |         |         |         |         |         |         |
| ]_      |         |         |         |         |         |         |
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
| 02      | Motivaz | O       | `MOTIVO | Lista   | B       | “Selezi |
|         | ione    |         | _CANCEL | di      |         | onare   |
|         |         |         | LAZIONE | valori  |         | un      |
|         |         |         | _GARA < | da      |         | valore  |
|         |         |         | #motiva | elenco  |         | tra     |
|         |         |         | zione_c |         |         | quelli  |
|         |         |         | ig_sogg |         |         | previst |
|         |         |         | etti_ag |         |         | i”      |
|         |         |         | gregato |         |         |         |
|         |         |         | ri>`__  |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 03      | Note    | OIF     | TESTO   | se      | B       | Aggiung |
|         |         |         |         | S03.02= |         | ere     |
|         |         |         |         | 8       |         | una     |
|         |         |         |         |         |         | nota    |
|         |         |         |         |         |         | per la  |
|         |         |         |         |         |         | cancell |
|         |         |         |         |         |         | azione  |
+---------+---------+---------+---------+---------+---------+---------+

.. [1]
    Una gara può essere cancellata solo se sono stati preventivamente
   cancellati tutti i lotti associati

.. [2]
    Una gara può essere cancellata solo se sono stati preventivamente
   cancellati tutti i lotti associati
