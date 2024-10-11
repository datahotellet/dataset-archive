# Datasett:     Valglokaler, stortingsvalget 2017
 Sist oppdatert: 2017-08-18 09:32

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
| county_id | County ID |  |
| county_name | County name |  |
| municipality_id | Municipality ID |  |
| municipality_name | Municipality name |  |
| borough_id | Borough ID |  |
| borough_name | Borough name |  |
| polling_place_id | Polling place ID |  |
| polling_place_name | Polling place name |  |
| address_line | Address line |  |
| postal_code | Postal code |  |
| area | Area |  |
| info_text | Info text |  |
| gps_coordinates | GPS coordinates |  |
| election_day_voting | Election day voting | 0 (false) for forhåndsstemmesteder og 1 (true) for valgtingsstemmesteder |
| opening_hours | Opening hours | Forhåndsstemmesteder har ikke åpningstider på strukturert format og angis derfor i kolonnen info_text. |
