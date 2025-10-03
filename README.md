# YFV-alignments
These alignments use the data available on genbank for all yellow fever virus (YFV) sequences. It is updated monthly a priori (in progress).

last update : october 3rd, 2025 

This alignment is cleaned and filtered to keep only yellow fever virus sequences around 11,000 bp in length. Our alignment therefore does not include :
* laboratory strains (adapted, passaged, recombinant, antiviral & vaccine experiments)
* duplicates (when more than one sequence is available for a single strain)
* related strain to YFV, such as the French neurotropic virus or the French viscerotropic virus.
* Sequences that have been poorly sequenced

Only the codon region is shown here. The fasta file was aligned using mafft and inspected manually. We have one alignment file:
* YFV wild-type (WT) (1210 sequences) and vaccinal strain (VACC) (25 seqeunces)

Then, phylogeny by likelihood maximization (ML) is reconstructed with IQ-TREE. In this github, the obtained tree will be presented. 

## All sequenced YFV 
The number of sequences varies from country to country. In this dataset, Brazil has the highest number of sequences. To analyse the number of sequences by year group (by decade after the 2000s), a bar chart has been produced. To make the chart easier to understand, Brazil was removed from the chart and a pie chart was created specifically for that country.

![image]()
![image]()

## YFV wild-type strain
 Total number of WT sequences : 1210

Fasta header format : 

`Genotype | Genbank accession | Country | date`

Key :

Genotype :
|code|genotype|count|
|---|---|---|
|AGO|Angola|20|
|EA|East Africa|3|
|ECA|East Central Africa|6|
|WA|West Africa|65|
|WCA|West Central Africa|9|
|SA1|South America 1|1096|
|SA2|South America 2|10|

## YFV vaccinal strain
Total number of VACC sequences : 25

Fasta header format : 

`VAC|adverse event (AE)|Genbank accession | Country | date | vaccine `

Key :

Vaccine :
|code|vaccine|count|
|---|---|---|
|17D-204|17D-204|9|
|17D-213|17D-213|0|
|17D-Tiantan|17D-Tiantan|1|
|17DD|17DD|1|
|STAMARIL|Stamaril, 17D-204|1|
|UNK|Unknown|13|
|YF-VAX|Sanofi Pasteur 17D-204|0|

Number of adverse event : 3

## Infection country for YFV wild-type and vaccinal strains
Country :
|code|country|count|
|---|---|---|
|AGO|Angola|3|
|AUS|Australia|1|
|BOL|Bolivia|3|
|BRA|Brazil|1062|
|BFA|Burkina Faso|3|
|CAF|Central African Republic|1|
|CHN|China|13|
|CIV|Ivory Coast|2|
|COL|Colombie|3|
|ECU|Ecuador|1|
|ESP|Spain|1|
|ETH|Ethiopia|2|
|GHA|Ghana|3|
|GMB|Gambia|1|
|GNB|Guinea|1|
|GMB/SEN|Gambia or Senegal|1|
|NGA|Nigeria|20|
|PAN|Panama|1|
|PER|Peru|7|
|SDN|Sudan|4|
|SEN|Senegal|34|
|SUR|Surinam|1|
|SGP|Singapor|1|
|TTO|Trinidad and Tobago|9|
|UGA|Uganda|3|
|UNK|Unknown|26|
|USA|United-State of America|1|
|VEN|Venezuela|15|

## Tree representation and alignment file
Alignement file :[Yellow_fever_virus_aln.fasta]()

ML Tree file:[YFV_Treefile]()

![image]()

