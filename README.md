# YFV-alignments
These alignments use the data available on genbank for all yellow fever virus (YFV) sequences. It is updated monthly a priori (in progress).

last update : october 2th, 2024 

This alignment is cleaned and filtered to keep only yellow fever virus sequences around 11,000 bp in length. Our alignment therefore does not include :
* laboratory strains (adapted, passaged, recombinant, antiviral & vaccine experiments)
* duplicates (when more than one sequence is available for a single strain)
* related strain to YFV, such as the French neurotropic virus or the French viscerotropic virus.
* Sequences that have been poorly sequenced

Only the codon region is shown here. The fasta file was aligned using mafft and inspected manually. We have one alignment file:
* YFV wild-type (WT) and vaccinal strain (VACC)

Then, phylogeny by likelihood maximization (ML) is reconstructed with IQ-TREE. In this github, the obtained tree will be presented. 

## All sequenced YFV per years (?)

... plot bar ? 

## YFV wild-type strain
 Total number of WT sequences : 

Fasta header format : 

`Genotype | Genbank accession | Country | date`

Key :

Genotype :
|code|genotype|count|
|---|---|---|
|AGO|Angola||
|EA|East Africa||
|ECA|East Central Africa||
|WA|West Africa||
|WCA|West Central Africa||
|SA1|South America 1||
|SA2|South America 2||

Country :
|code|country|count|
|---|---|---|
|AGO|Angola||
|BOL|Bolivia||
|BRA|Brazil||
|CAF|Central African Republic||
|CHN|China||
|CIV|Ivory Coast||
|ETH|Ethiopia||
|GHA|Ghana||
|GMB|Gambia||
|GNB|Guinea-Bissau||
|GMB/SEN|Gambia or Senegal||
|NGA|Nigeria||
|PER|Peru||
|SDN|Sudan||
|SEN|Senegal||
|SUR|Surinam||
|TTO|Trinidad and Tobago||
|UGA|Uganda||
|UNK|Unknown||
|VEN|Venezuela||



## YFV vaccinal strain
Total number of VACC sequences : 

Fasta header format : 

`VAC|Genbank accession | Country | date | vaccine | adverse event (AE)`

Key :

Vaccine :
|code|vaccine|count|
|---|---|---|
|17D-204|17D-204||
|17D-Tiantan|17D-Tiantan||
|17DD|17DD||
|STAMARIL|Stamaril, 17D-204||
|UNK|Unknown||
|YF-VAX|Sanofi Pasteur 17D-204||

## Tree representation and alignment file
Alignement file :[Yellow_fever_virus_aln.fasta](https://github.com/Snseli/YFV-alignments/blob/main/Yellow%20fever%20alignements/YFV_aln_14092023.fasta)

ML Tree file:[YFV_Treefile](https://github.com/Snseli/YFV-alignments/blob/main/yellow%20fever%20treefile/YFV_aln_14092023_treefile.treefile)

![image](https://github.com/Snseli/YFV-alignments/blob/main/PNG/)

