# Datasett: 	Sidevisninger pr. datasett på datahotellet
 Sist oppdatert: 2024-10-14 12:53

 Filer:
 - [sample.csv](sample.csv) — eksempeldata
 - [dataset.csv](dataset.csv) — datasett
 - [dataset.original.csv](dataset.original.csv) — datasett i originalt Datahotell-format
 - [meta.xml](meta.xml) — metadata (tittel og sist-oppdatert)
 - [fields.xml](fields.xml) — feltdefinisjonar (XML)
 - [fields.csv](fields.csv) — feltdefinisjonar (CSV)


## Feltdefinisjonar
Henta frå fields.csv

| shortname | name | content |
| --- | --- | --- |
| year | År | Kva år statistikken gjeld for. |
| month | Månad | "Månad statistikken gjeld (01-12). Stjerne (""*"") tyder at statistikken gjeld heile året." |
| coverage | Dekke | "Stjerne (""*"") tyder at data på denne rada gjeld heile perioden som er nemt i felta for År og Månad. Eksempel på at statistikken ikkje gjeld heile perioden er verdi som ""2017-12-07_0020"", som tyder at tala kun gjeld fram til det tidspunktet." |
| dataset_location | Datasett | "Datasett statistikken gjeld for, oppgjeve ved datasettet sin identifikator (""location"") i datahotellet." |
| total_pageviews | Sidevisningar totalt | "Totalt antal sidevisningar. Talet er sum av sidevisningar på ulike format (JSON, JSONP, XML, YAML og Komplette nedlastingar). API-kall til /meta og /fields er utelatt frå statistikken." |
| json | JSON | Tal på API-kall med JSON som format. |
| jsonp | JSONP | Tal på API-kall med JSONP som format. Vising av datasettet via web-grensesnittet på hotell.difi.no vil gje utslag her. |
| xml | XML | Tal på API-kall med XML som format. |
| yaml | YAML | Tal på API-kall med YAML som format. |
| csv | CSV | "Tal på API-kall med CSV som format. Komplette nedlastingar, også i CSV-format, er telt for seg sjølv." |
| download | Komplette nedlastingar | Antall komplette nedlastingar av datasettet. |
| traffic_bytes | Trafikk i bytes | "Sum av snitt-størrelse på kvar type API-kall (JSON, XML etc.) ganga opp med antall API-kall for den enkelte typen. Snitt-størrelse er frå AWStats. Feltet egner seg for å sortere tabellen etter trafikk." |
| traffic_hr | Trafikk - lesbart | "Menneskelesbar versjon av ""Trafikk i bytes""." |
| hotel_visible | Synleg i datahotellet | "Om eit datasett er synleg i datahotellet. ""No"" betyr at datasettet enten er fjerna frå datahotellet, eller at det er sett til å vere usynleg. Eit datasett kan bli sett til å vere usynleg fordi det er avpublisert, eller skal fasast ut. Verdien er sett i det statistikk-datasettet vart generert, sjå dette datasettets ETag for ca. tidspunkt for når datasettet vart generert." |
| datanorgeLink | Data.norge.no - URL | "Lenke til oppføring på data.norge.no. Lenken er sett inn i det datasettet vart generert, og vil endre seg etter kvart som innhaldet på data.norge.no endrar seg." |
| datanorgeTitle | Data.norge.no - Tittel | "Tittelen på datasett-oppføringa på data.norge.no. Sett inn i det statistikken vart generert, og vil endre seg etter kvar som innhaldet på data.norge.no endrar seg." |
| datanorgePublisherName | Data.norge.no - Utgjevar | "Navn på utgjevar, frå datasett-oppføringa på data.norge.no. Sett inn i det statistikken vart generert, og vil endre seg etter kvar som innhaldet på data.norge.no endrar seg." |
