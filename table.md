## Svolgimento

### Tabella auto concessionario:

| FIELD                | TYPE        | ATTRIBUTES                         | INDEXES     |
| -------------------- | ----------- | ---------------------------------- | ----------- |
| id                   | INT         | AUTO INCREMENT, (NOT NULL, UNIQUE) | PRIMARY KEY |
| brand                | VARCHAR(13) | NOT NULL                           |             |
| model                | VARCHAR(20) | NOT NULL                           |             |
| type_fuel            | VARCHAR(13) | NOT NULL                           |             |
| km_by_full_tank      | SMALLINT    | NOT NULL                           |             |
| km_done              | MEDIUMINT   | NOT NULL, DEFAULT("0")             |             |
| engine_horsepower    | SMALLINT    | NOT NULL                           |             |
| year_model           | YEAR        | NOT NULL                           |             |
| year_veicle          | YEAR        | NOT NULL                           |             |
| color                | VARCHAR(20) | NOT NULL, DEFAULT("Customize")     |             |
| brief_description_ad | TEXT        | NOT NULL, UNSIGNED                 |             |
| price                | FLOAT(10,2) | NOT NULL                           |             |
