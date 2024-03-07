Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

# Cars Table Structure

| Filed| Type | Attributes| Index |
|---|---|---| --- |
ID | INT | NOT NULL, UNSIGNED, AUTO INCREMENT | PRIMARY KEY|
Marca | VARCHAR(50)| NOT NULL| |
Modello | VARCHAR(50)| NOT NULL| |
NUMERO_DI_TELAIO | CHAR(17)| NOT NULL , UNIQUE| |
Anno_produzione | INT | NOT NULL | |
Anno_immatricolazione | INT | NOT NULL ||
Tipo_Carburante | VARCHAR(50) | NOT NULL ||
Tpo_Cambio | VARCHAR(50) | NOT NULL ||
Tipo_Trasmissione | VARCHAR(50) | NULL ||
KM_FATTI | INT | NOT NULL ||
Colore | VARCHAR(50) | NOT NULL ||
Nr_porte | INT | NULL ||
Stato_di_usura| TESTO | NULL ||
PREZZO| DECIMAL(10,2)| NOT NULL||

