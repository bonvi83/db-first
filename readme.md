## Consegna:

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## Svolgimento:

| FIELD                            | TYPE            | ATTRIBUTES                      | INDEXS      |
| -------------------------------- | --------------- | ------------------------------- | ----------- |
| id (identificativo progressivo)  | INT             | NOTNULL, UNIQUE, AUTO_INCREMENT | PRIMARY KEY |
| brand (marca)                    | VARCHAR(20)     | NOTNULL                         |             |
| model (modello)                  | VARCHAR(20)     | NOTNULL                         |             |
| year (anno)                      | YEAR, INT       | NOTNULL, NUMBER                 |             |
| engine type (tipo di motore)     | VARCHAR(10)     | NOTNULL                         |             |
| CV/KW (cavalli/kilowatt)         | VARCHAR(4)      | NOTNULL, NUMBER                 |             |
| doors (porte)                    | CHAR(1)         | NOTNULL, NUMBER                 |             |
| kilometers (km percorsi)         | VARCHAR(6), INT | NOTNULL, NUMBER                 |             |
| color (colore)                   | VARCHAR(10)     | NOTNULL                         |             |
| conditions (condizioni generali) | CHAR(1)         | NOTNULL                         |             |
| ...                              | ...             | ...                             | ...         |
|                                  |                 |                                 |             |
