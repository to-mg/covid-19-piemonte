Nella cartella data del repository github

https://github.com/to-mg/covid-19-piemonte

è presente per ogni giorno a partire dal 10 maggio 2020 un file in formato CSV con nome

dati_per_tutto_il_periodo_aaaa_mm_gg.csv

con tutti i dati disponibili dal 25 marzo 2020 fino alla data indicata nel nome del file.

Sono inoltre presenti i dati aggregati per provincia, intera regione e ASL.

Mancano i dati del 10 e 11 aprile 2020.

La tabella seguente elenca le colonne del file con la loro descrizione
&nbsp;

&nbsp;


| Nome colonna             | Descrizione |
|--------------------------|-------------|
| Ente | Nome comune, ASL, provincia, regione |
| Tipo	 | Tipo ente, ASL o COM o PRO o REG |
| Provincia	 | Provincia, non significativo per ASL |
| ASL	 | ASL, non significativo per provinca e regione |
| Codice ISTAT	 | codice ISTAT o codice azienda ASL (*) |
| Abitanti	 | numero abitanti |
| Positivi	 | numero positivi al Covid-19 |
| Positivi 1000 abitanti	 | numero positivi al Covid-19 per 1000 abitanti |
| Delta positivi	 | differenza positivi rispetto al giorno precedente |
| Delta positivi 1000 abitanti	 | differenza positivi per 1000 abitanti rispetto al giorno precedente |
| Data | data in formato aaaa/mm/gg |

(\*) Per evitare possibili collisioni tra i codici ISTAT di comuni, province e regione e i codici azienda della ASL, 
a questi ultimi è stato aggiunto il prefisso 'A'
