S04 – Cancellazione lotto [1]_
==============================

+---------+---------+---------+---------+---------+---------+---------+
| S03 –   |         |         |         |         |         |         |
| cancell |         |         |         |         |         |         |
| azione  |         |         |         |         |         |         |
| lotto   |         |         |         |         |         |         |
+=========+=========+=========+=========+=========+=========+=========+
| COD     | ETICHET | TIPO    | FORMATO | CONTROL | MESSAGG |         |
|         | TA      |         |         | LO      | IO      |         |
+---------+---------+---------+---------+---------+---------+---------+
|         |         |         |         | DESCRIZ | TIPO    |         |
|         |         |         |         | IONE    |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 01      | Numero  | E       | NUMERIC |         |         |         |
|         | lotto   |         | O       |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 02      | Motivaz | O       | `MOTIVO | Lista   | B       | “Selezi |
|         | ione    |         | _CANCEL | di      |         | onare   |
|         |         |         | LAZIONE | valori  |         | un      |
|         |         |         | _LOTTO  | da      |         | valore  |
|         |         |         | <#motiv | elenco  |         | tra     |
|         |         |         | o_cance |         |         | quelli  |
|         |         |         | llazion |         |         | previst |
|         |         |         | e_lotto |         |         | i”      |
|         |         |         | >`__    |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| 03      | Note    | OIF     | TESTO   | se      | B       | Aggiung |
|         |         |         |         | S04.02= |         | ere     |
|         |         |         |         | 4       |         | una     |
|         |         |         |         |         |         | nota    |
|         |         |         |         |         |         | per la  |
|         |         |         |         |         |         | cancell |
|         |         |         |         |         |         | azione  |
+---------+---------+---------+---------+---------+---------+---------+

.. [1]
    La cancellazione del lotto può essere eseguita solo se il lotto non
   è stato perfezionato
