# Datasett:     Arbeidssøkere yrke år
 Sist oppdatert: 2018-01-23 09:05

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
| aar | År |  |
| yrke_grovgruppe | Grov gruppering av yrke | NAV gruppering av yrker. |
| yrke_fingruppe | Fin gruppering av yrke | NAV gruppering av yrker. |
| yrkeskode | Yrkeskode | Yrkeskode (4-siffer) i STYRK |
| yrke | Yrke | Navn på yrke. Betegnes yrke i STYRK. |
| yrkesbetegnelse | Yrkesbetegnelse | Detaljering av yrke i mer detaljerte yrkesbetegnelser. I datasett er alle observerte yrkebetegnelser per yrkeskode satt sammen på samme rad. |
| isco_versjon | ISCO-versjon | "ISCO=International Standard Classification of Occupations. Utarbeidet av ILO. ISCO-88 benyttes som kode for norsk STYRK, og ISCO-08 for STYRK-08." |
| antall_arbeidssokere | Antall arbeidssøkere | "Gjennomsnittlig månedsbeholdning. Arbeidssøkere er betegnelsen på summen av helt ledige, delvis ledige, arbeidssøkere på tiltak og andre arbeidssøkere." |
