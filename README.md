# YFV-alignments
This alignments use available data on genbank about all yellow fever virus (YFV) sequences. It is monthly updated a priori (in progress). 

last update : april 26th, 2023

This alignment is cleaned and filtered to keep only YFV sequences which lenght is around 11 000 pb. So our alingment do not include : 
* laboratory strains (adapted, passaged, recombinant, antiviral & vaccine experiments)
* duplicates (when more than one sequence is available for a single strain)
* related strain to YFV as like French neurotropic virus or French viscerotropic virus
* Sequences has been mis-sequenced

Only codon region is observe here.the fasta file was aligned using mafft and inspected manually. At this step we have 3 alignments files :
* YFV wild-type strain
* YFV vaccinal strain
* YFV wild-type and vaccinal strain

Then for each alignment files, maximun-likelihood (ML) phylogeny is reconstructed with IQ-TREE. In this github only the first two alignement will be show. For the third one you can send me a message if you needed. 

## YFV wild-type strain
Alignement file : {%%}

Total number of sequences : 906

Fasta header format : 

`Genotype | Genbank accession | Country | date`

ML Tree file: {%%}

*Put image of phylogenic tree here*

Key :

Genotype :
|code|genotype|count|
|---|---|---|
|AGO|Angola|00|
|EA|East Africa|00|
|ECA|East Central Africa|00|
|WA|West Africa|00|
|WCA|West Central Africa|00|
|SA1|South America 1|00|
|SA2|South America 2|00|

Country :
|code|country|count|
|---|---|---|
|AGO|Angola|2|
|BOL|Bolivia|2|
|BRA|Brazil|780|
|CAF|Central African Republic|1|
|CHN|China|19|
|CIV|Ivory Coast|2|
|ETH|Ethiopia|1|
|GHA|Ghana|3|
|GMB|Gambia|1|
|GNB|Guinea-Bissau|1|
|NGA|Nigeria|16|
|NLD|Netherlands|8|
|Per|Peru|2|
|SDN|Sudan|1|
|SEN|Senegal|31|
|SUR|Surinam|1|
|TTO|Trinidad and Tobago|9|
|UGA|Uganda|3|
|UNK|Unknown|9|
|VEN|Venezuela|14|

*Put here a graphic on country*

## YFV wvaccinal strain
Alignement file : {%%}

Total number of sequences : 42

Fasta header format : 

`Genbank accession | Country | date | vaccine | adverse event (AE)`

ML Tree file: {%%}

*Put image of phylogenic tree here*

Key :

Vaccine :
|code|vaccine|count|
|---|---|---|
||||
||||
||||
||||
||||
||||
||||

Country :
|code|country|count|
|---|---|---|
|AGO|Angola|2|
|BOL|Bolivia|2|
|BRA|Brazil|780|
|CAF|Central African Republic|1|
|CHN|China|19|
|CIV|Ivory Coast|2|
|ETH|Ethiopia|1|
|GHA|Ghana|3|
|GMB|Gambia|1|
|GNB|Guinea-Bissau|1|
|NGA|Nigeria|16|
|NLD|Netherlands|8|
|Per|Peru|2|
|SDN|Sudan|1|
|SEN|Senegal|31|
|SUR|Surinam|1|
|TTO|Trinidad and Tobago|9|
|UGA|Uganda|3|
|UNK|Unknown|9|
|VEN|Venezuela|14|

*Put here a graphic on country*
