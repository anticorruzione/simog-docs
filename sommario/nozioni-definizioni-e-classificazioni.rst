Nozioni, definizioni e classificazioni
======================================

Nella definizione delle schede di comunicazione sono state utilizzate le
seguenti convenzioni:

+-----------------------+-----------------------+-----------------------+
| **Oggetto**           | **Codice tipo**       | **Descrizione**       |
+=======================+=======================+=======================+
| Campo                 | **O (obbligatorio)**  | L’inserimento del     |
|                       |                       | valore è obbligatorio |
+-----------------------+-----------------------+-----------------------+
| Campo                 | **OIF (obbligatorio   | L’inserimento del     |
|                       | condizionato)**       | valore è obbligatorio |
|                       |                       | a condizione che…..   |
+-----------------------+-----------------------+-----------------------+
| Campo                 | **E (Ereditato)**     | Il valore è ereditato |
|                       |                       | da un sistema terzo e |
|                       |                       | non è possibile       |
|                       |                       | modificarlo quindi i  |
|                       |                       | controlli sono        |
|                       |                       | impliciti             |
+-----------------------+-----------------------+-----------------------+
| Campo                 | **P (Pre-compilato)** | Il valore è ereditato |
|                       |                       | da un sistema terzo o |
|                       |                       | da un campo compilato |
|                       |                       | in una precedente     |
|                       |                       | scheda ed è           |
|                       |                       | modificabile          |
+-----------------------+-----------------------+-----------------------+
| Campo                 | **C (Calcolato)**     | Il valore del campo è |
|                       |                       | determinato dai       |
|                       |                       | valori di altri campi |
|                       |                       | imputati e non è      |
|                       |                       | modificabile da parte |
|                       |                       | dell’utente           |
+-----------------------+-----------------------+-----------------------+
| Campo                 | **R (Ricerca)**       | Il valore è oggetto   |
|                       |                       | di ricerca            |
+-----------------------+-----------------------+-----------------------+
| Controllo             | **B**                 | il controllo è        |
|                       |                       | bloccante ed          |
|                       |                       | impedisce l’inoltro   |
|                       |                       | dei dati              |
+-----------------------+-----------------------+-----------------------+
| Controllo             | **W**                 | il controllo è non    |
|                       |                       | bloccante e determina |
|                       |                       | una semplice          |
|                       |                       | segnalazione          |
|                       |                       | all’utente (Warning). |
|                       |                       | L’utente è libero di  |
|                       |                       | ignorare la           |
|                       |                       | segnalazione ed       |
|                       |                       | inviare comunque i    |
|                       |                       | dati.                 |
+-----------------------+-----------------------+-----------------------+

Tabella - Notazione utilizzata nella specifiche dei controlli
