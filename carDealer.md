# Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

| name               | type        | attributes                         | key     |
| ------------------ | ----------- | ---------------------------------- | ------- |
| id                 | INT         | NOT NULL - AUTO_INCREMENT - UNIQUE | PRIMARY |
| country_production | VARCHAR(30) | NOT NULL                           |         |
| producer           | VARCHAR(20) | NOT NULL                           |         |
| model              | VARCHAR(10) | NOT NULL                           |         |
| motor              | VARCHAR(20) | NOT NULL                           |         |
| year_production_at | DATE        | NOT NULL - DEFAULT(4)              |         |
| number_series      | INT         | NOT NULL - DEFAULT(17)             |         |
| CONDITION_STATE    | VARCHAR(10) | NOT NULL                           |
