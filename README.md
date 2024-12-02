## nome tabella
cars

## struttura della tabella cars
-id | BIGINT - AUTOINCREMENT - PRIMARY_KEY (UNIQUE - NOTNULL)
-marca | VARCHAR(15) - NOTNULL
-modello | VARCHAR(50) - NOTNULL
-carburante | VARCHAR(10) - NOTNULL
-colore | VARCHAR(20) - NULL
-carrozzeria (berlina, SUV, station wagon, coupé, cabriolet) | VARCHAR(20) - NOTNULL
-targa | CHAR(7) - NOTNULL
-cilindrata | SMALLINT - NOTNULL
-potenza CV | SMALLINT - NOTNULL
-potenza Kw | TINYINT - NULL
-porte | TINYINT - NOTNULL
-posti | TINYINT - NOTNULL
-anno di immatricolazione | YEAR - NOTNULL
-prezzo | MEDIUMINT - NOTNULL
-neopatentati |
-nuova |
-usata |
-km percorsi |
-descrizione | TEXT(300) - NULL