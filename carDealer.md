# Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

| id                                 | country_production | brand       | model       | motor       | year_production | location_production | CONDITIONS             |
| ---------------------------------- | ------------------ | ----------- | ----------- | ----------- | --------------- | ------------------- | ---------------------- |
| NOT NULL - AUTO_INCREMENT - UNIQUE | VARCHAR(50)        | VARCHAR(50) | VARCHAR(30) | VARCHAR(20) | YEAR            | VARCHAR(20)         | NOT NULL - VARCHAR(10) |
