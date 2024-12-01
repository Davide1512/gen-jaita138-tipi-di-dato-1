
==Database 1==

| Libri |                               | Java   | SQL      |
| ----- | ----------------------------- | ------ | -------- |
|       | ID libro                      | INT    | Int      |
|       | autore                        | String | VARCHAR  |
|       | titolo                        | String | VARCHAR  |
|       | genere                        | String | VARCHAR  |
|       | copie disponibili             | short  | smallint |
|       | copie totali della biblioteca | short  | smallint |
|       | codice del libro              | String | VARCHAR  |


| Membri |                    | JAVA   | SQL     |
| ------ | ------------------ | ------ | ------- |
|        | ID membro          | INT    | Int     |
|        | nome e cognome     | String | VARCHAR |
|        | numero di telefono | byte   | tinyint |
|        | email              | String | VARCHAR |
|        |                    |        |         |



| Prestiti |                                        | Java | SQL  |
| -------- | -------------------------------------- | ---- | ---- |
|          | ID prestito                            | INT  | Int  |
|          | data inizio                            |      | Date |
|          | data finale                            |      | Date |
|          | informazioni sul richiedente del libro |      | text |
|          | data effettiva della riconsegna        |      | Date |


==Database 2==


| Piatti |               | JAVA    | SQL     |
| ------ | ------------- | ------- | ------- |
|        | ID piatto     | INT     | Int     |
|        | nome piatto   | String  | VARCHAR |
|        | prezzo        | float   | decimal |
|        | disponibilità | boolean | boolean |



| Ingredienti |                              | JAVA   | SQL     |
| ----------- | ---------------------------- | ------ | ------- |
|             | ID ingrediente               | INT    | Int     |
|             | nomi                         | String | VARCHAR |
|             | quantità presente nel piatto | float  | decimal |



| Clienti |                                           | JAVA   | SQL     |
| ------- | ----------------------------------------- | ------ | ------- |
|         | ID cliente                                | INT    | Int     |
|         | nome e cognome                            | String | VARCHAR |
|         | telefono                                  | byte   | tinyint |
|         | email                                     | String | VARCHAR |
|         | indirizzo in caso di consegne a domicilio | String | VARCHAR |


==Database 3==



| Fiori |                      | JAVA   | SQL      |
| ----- | -------------------- | ------ | -------- |
|       | ID fiore             | INT    | Int      |
|       | nome fiore           | String | VARCHAR  |
|       | specie               | String | VARCHAR  |
|       | prezzo               | float  | decimal  |
|       | colori principali    | String | VARCHAR  |
|       | quantità disponibile | short  | smallint |



| Fornitori |                | JAVA   | SQL     |
| --------- | -------------- | ------ | ------- |
|           | ID fornitore   | INT    | Int     |
|           | nome e cognome | String | VARCHAR |
|           | telefono       | byte   | tinyint |
|           | email          | String | VARCHAR |



| Clienti |                               | JAVA   | SQL     |
| ------- | ----------------------------- | ------ | ------- |
|         | ID cliente                    | INT    | Int     |
|         | nome e cognome                | String | VARCHAR |
|         | telefono                      | byte   | tinyint |
|         | email                         | String | VARCHAR |
|         | indirizzo in caso di consegne | String | VARCHAR |
