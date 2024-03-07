## Consegna:

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## Svolgimento:

| FIELD                            | TYPE        | ATTRIBUTES                      | INDEXS      |
| -------------------------------- | ----------- | ------------------------------- | ----------- |
| id (identificativo progressivo)  | INT         | NOTNULL, UNIQUE, AUTO_INCREMENT | PRIMARY KEY |
| brand (marca)                    | VARCHAR(20) | NOTNULL                         |             |
| model (modello)                  | VARCHAR(20) | NOTNULL                         |             |
| year (anno)                      | YEAR        | NOTNULL                         |             |
| engine type (tipo di motore)     | VARCHAR(10) | NOTNULL                         |             |
| CV/KW (cavalli/kilowatt)         | VARCHAR(4)  | NOTNULL                         |             |
| doors (porte)                    | CHAR(1)     | NOTNULL                         |             |
| kilometers (km percorsi)         | VARCHAR(6)  | NOTNULL                         |             |
| color (colore)                   |             | NOTNULL                         |             |
| conditions (condizioni generali) | CHAR(1)     | NOTNULL                         |             |
| ...                              | ...         | ...                             | ...         |
|                                  |             |                                 |             |
