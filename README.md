# YFV-alignments
These alignments use the data available on genbank for all yellow fever virus (YFV) sequences. It is updated monthly a priori (in progress).

last update : september 14th, 2023

This alignment is cleaned and filtered to keep only yellow fever virus sequences around 11,000 bp in length. Our alignment therefore does not include :
* laboratory strains (adapted, passaged, recombinant, antiviral & vaccine experiments)
* duplicates (when more than one sequence is available for a single strain)
* related strain to YFV, such as the French neurotropic virus or the French viscerotropic virus.
* Sequences that have been poorly sequenced

Only the codon region is shown here. The fasta file was aligned using mafft and inspected manually. We have one alignment file:
* YFV wild-type (WT) and vaccinal strain (VACC)

Then, phylogeny by likelihood maximization (ML) is reconstructed with IQ-TREE. In this github, the obtained tree will be presented. 

## YFV wild-type strain
 Total number of WT sequences : 956

Fasta header format : 

`Genotype | Genbank accession | Country | date`

Key :

Genotype :
|code|genotype|count|
|---|---|---|
|AGO|Angola|19|
|EA|East Africa|1|
|ECA|East Central Africa|5|
|WA|West Africa|68|
|WCA|West Central Africa|3|
|SA1|South America 1|850|
|SA2|South America 2|5|

Country :
|code|country|count|
|---|---|---|
|AGO|Angola|2|
|BOL|Bolivia|2|
|BRA|Brazil|832|
|CAF|Central African Republic|1|
|CHN|China|16|
|CIV|Ivory Coast|2|
|ETH|Ethiopia|1|
|GHA|Ghana|3|
|GMB|Gambia|1|
|GNB|Guinea-Bissau|1|
|GMB/SEN|Gambia or Senegal|1|
|NGA|Nigeria|21|
|PER|Peru|2|
|SDN|Sudan|2|
|SEN|Senegal|32|
|SUR|Surinam|1|
|TTO|Trinidad and Tobago|9|
|UGA|Uganda|3|
|UNK|Unknown|10|
|VEN|Venezuela|9|



## YFV vaccinal strain
Alignement file : 
Total number of VACC sequences : 26

Fasta header format : 

`Genbank accession | Country | date | vaccine | adverse event (AE)`

Key :

Vaccine :
|code|vaccine|count|
|---|---|---|
|17D-204|17D-204|1|
|17D-Tiantan|17D-Tiantan|1|
|17DD|17DD|4|
|STAMARIL|Stamaril, 17D-204|5|
|UNK|Unknown|6|
|YF-VAX|Sanofi Pasteur 17D-204|5|

## Tree representation and alignment file
Alignement file :
ML Tree file:

![image]

