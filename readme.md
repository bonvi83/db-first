## Consegna:

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## Svolgimento:

| FIELD                            | TYPE        | ATTRIBUTES                      | INDEXS      |
| -------------------------------- | ----------- | ------------------------------- | ----------- |
| id (identificativo progressivo)  | INT         | NOTNULL, UNIQUE, AUTO_INCREMENT | PRIMARY KEY |
| brand (marca)                    | VARCHAR(20) | NOTNULL                         |             |
| model (modello)                  | VARCHAR(20) | NOTNULL                         |             |
| year (anno)                      | YEAR, INT   | NOTNULL                         |             |
| engine_type (tipo di motore)     | VARCHAR(10) | NOTNULL                         |             |
| power (CV/KW cavalli/kilowatt)   | VARCHAR(4)  | NOTNULL                         |             |
| doors (porte)                    | INT         | NOTNULL                         |             |
| kilometers (km percorsi)         | INT         | NOTNULL                         |             |
| color (colore)                   | VARCHAR(10) | NOTNULL                         |             |
| conditions (condizioni generali) | TEXT        |                                 |             |
| price (prezzo)                   | FLOAT (8,2) | NOTNULL                         |             |
| ...                              | ...         | ...                             | ...         |
|                                  |             |                                 |             |
