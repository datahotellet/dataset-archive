# Datasett:     KMD - Partistøtte 2011
 Sist oppdatert: 2015-02-24 13:43

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
| partinamn | Partinamn | SSB sitt namn på det aktuelle partilag |
| fylkesnr | Fylkesnr | "01 for Østfold, 02 Akershus, 03 Oslo m.m." |
| kommunenr | Kommunenr | fylkesnr og eit tosifra tal. |
| partitype | Partitype | "Det finst fleire typar parti, i dette datasettet skil vi bare mellom fylkesparti, ungdomsparti og kommuneparti. (det finst samlingslister og koalisjonslister med meir)." |
| valar | Valår | "er årstal for siste registrerte val i kolonnane (Stemmer, relativdel og mandat)." |
| stemmer | stemmer | : er stemmetal i det aktuelle valet |
| relativdel | relativdel | er prosentvis oppslutning i høve andre relevante parti i eit val |
| mandat | Mandat | er tal på politiske mandat som dette partiet vann i det aktuelle valet |
| utbetalingsar | Utbetalingsår | "siste årstal for utbetalingar (i kolonne grunnstønad, stemmestøtte og totalt)" |
| grunnstonad | Grunnstønad | ": for å ha rett på grunnstøtte må lista anten ha oppnådd eit valresultat på 4 % av stemmene, eller minst 1 representant i kommunestyre /fylkesting" |
| stemmestotte | Stemmestøtte | ": er summen av tal stemmer, multiplisert med ein årleg sats som vert gjeven av fornyings- administrasjons og kyrkjedepartementet ut frå løyving i statsbudsjettet. " |
| totalt | Totalt | : summen av grunnstøtte og stemmestøtte er beløpet som årleg vert utbetalt frå staten til ulike politiske parti. Partia kan og få bl.a. fylkeskommunal og kommunal støtte. |
