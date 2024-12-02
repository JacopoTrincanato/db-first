## nome tabella
cars

## struttura della tabella cars
-id | BIGINT - AUTOINCREMENT - PRIMARY_KEY (UNIQUE - NOT NULL)
-marca | VARCHAR(15) - NOT NULL
-modello | VARCHAR(50) - NOT NULL
-carburante | VARCHAR(10) - NOT NULL
-colore | VARCHAR(20) - NULL
-carrozzeria (berlina, SUV, station wagon, coupé, cabriolet) | VARCHAR(20) - NOT NULL
-targa | CHAR(7) - UNIQUE - NOT NULL
-cilindrata | SMALLINT - NOT NULL
-potenza CV | SMALLINT - NOT NULL
-potenza Kw | TINYINT - NULL
-porte | TINYINT - NOT NULL
-posti | TINYINT - NOT NULL
-anno di immatricolazione | YEAR - NOT NULL
-prezzo | MEDIUMINT - NOT NULL
-neopatentati | TINYINT - NOT NULL
-nuova | TINYINT - NOT NULL
-usata | TINYINT - NOT NULL
-km percorsi | MEDIUMINT - NOT NULL - DEFAULT(0)
-descrizione | VARCHAR(255) - NULL