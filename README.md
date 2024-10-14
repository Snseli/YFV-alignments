# YFV-alignments
These alignments use the data available on genbank for all yellow fever virus (YFV) sequences. It is updated monthly a priori (in progress).

last update : october 2th, 2024 

This alignment is cleaned and filtered to keep only yellow fever virus sequences around 11,000 bp in length. Our alignment therefore does not include :
* laboratory strains (adapted, passaged, recombinant, antiviral & vaccine experiments)
* duplicates (when more than one sequence is available for a single strain)
* related strain to YFV, such as the French neurotropic virus or the French viscerotropic virus.
* Sequences that have been poorly sequenced

Only the codon region is shown here. The fasta file was aligned using mafft and inspected manually. We have one alignment file:
* YFV wild-type (WT) (982 sequences) and vaccinal strain (VACC) (30 seqeunces)

Then, phylogeny by likelihood maximization (ML) is reconstructed with IQ-TREE. In this github, the obtained tree will be presented. 

## All sequenced YFV per years 
The number of sequences varies from country to country. In this dataset, Brazil has the highest number of sequences. To analyse the number of sequences by year group (by decade after the 2000s), a bar chart has been produced. To make the chart easier to understand, Brazil was removed from the chart and a pie chart was created specifically for that country.
[]
[]

## YFV wild-type strain
 Total number of WT sequences : 982

Fasta header format : 

`Genotype | Genbank accession | Country | date`

Key :

Genotype :
|code|genotype|count|
|---|---|---|
|AGO|Angola|19|
|EA|East Africa|1|
|ECA|East Central Africa|5|
|WA|West Africa|58|
|WCA|West Central Africa|3|
|SA1|South America 1|889|
|SA2|South America 2|7|

Country :
|code|country|count|
|---|---|---|
|AGO|Angola|2|
|BOL|Bolivia|2|
|BRA|Brazil|868|
|CAF|Central African Republic|1|
|CHN|China|16|
|CIV|Ivory Coast|2|
|COL|Colombie|2|
|ETH|Ethiopia|1|
|GHA|Ghana|3|
|GMB|Gambia|1|
|GIN|Guinea|1|
|GMB/SEN|Gambia or Senegal|1|
|NGA|Nigeria|15|
|PAN|Panama|1|
|PER|Peru|3|
|SDN|Sudan|1|
|SEN|Senegal|29|
|SUR|Surinam|1|
|TTO|Trinidad and Tobago|8|
|UGA|Uganda|3|
|UNK|Unknown|10|
|VEN|Venezuela|11|

## YFV vaccinal strain
Total number of VACC sequences : 30

Fasta header format : 

`VAC|Genbank accession | Country | date | vaccine | adverse event (AE)`

Key :

Vaccine :
|code|vaccine|count|
|---|---|---|
|17D-204|17D-204|10|
|17D-213|17D-213|1|
|17D-Tiantan|17D-Tiantan|1|
|17DD|17DD|3|
|STAMARIL|Stamaril, 17D-204|4|
|UNK|Unknown|11|
|YF-VAX|Sanofi Pasteur 17D-204|0|

## Tree representation and alignment file
Alignement file :[Yellow_fever_virus_aln.fasta](https://github.com/Snseli/YFV-alignments/blob/main/Yellow%20fever%20alignements/YFV_aln_14092023.fasta)

ML Tree file:[YFV_Treefile](https://github.com/Snseli/YFV-alignments/blob/main/yellow%20fever%20treefile/YFV_aln_14092023_treefile.treefile)

![image](https://github.com/Snseli/YFV-alignments/blob/main/PNG/TREE_and_SUBTREE_MAJoct_YFV.PNG)

