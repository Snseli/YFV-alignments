# YFV-alignments
These alignments use the data available on genbank for all yellow fever virus (YFV) sequences. It is updated monthly a priori (in progress).

last update : april 26th, 2023

This alignment is cleaned and filtered to keep only yellow fever virus sequences around 11,000 bp in length. Our alignment therefore does not include :
* laboratory strains (adapted, passaged, recombinant, antiviral & vaccine experiments)
* duplicates (when more than one sequence is available for a single strain)
* related strain to YFV, such as the French neurotropic virus or the French viscerotropic virus.
* Sequences that have been poorly sequenced

Only the codon region is shown here. The fasta file was aligned using mafft and inspected manually. At this stage, we have 3 alignment files:
* YFV wild-type strain
* YFV vaccinal strain
* YFV wild-type and vaccinal strain

Then, for each alignment files, phylogeny by likelihood maximization (ML) is reconstructed with IQ-TREE. In this github, only the first two alignments will be presented. For the third one, you can send me a message if you need it.

## YFV wild-type strain
Alignement file : [Yellow fever virus alignment, wild-type](https://github.com/Snseli/YFV-alignments/blob/main/Yellow%20fever%20alignements/YFV-WildType-alignements.fasta)

Total number of sequences : 906

Fasta header format : 

`Genotype | Genbank accession | Country | date`

ML Tree file: [Wild-Type treefile](https://github.com/Snseli/YFV-alignments/blob/main/yellow%20fever%20WT%20treefile/YFV-WildType-alignements.fasta.treefile)

![image](https://github.com/Snseli/YFV-alignments/blob/main/PNG/YFV-WildType-treefile.png)


Key :

Genotype :
|code|genotype|count|
|---|---|---|
|AGO|Angola|22|
|EA|East Africa|1|
|ECA|East Central Africa|5|
|WA|West Africa|60|
|WCA|West Central Africa|3|
|SA1|South America 1|810|
|SA2|South America 2|5|

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
|PER|Peru|2|
|SDN|Sudan|1|
|SEN|Senegal|31|
|SUR|Surinam|1|
|TTO|Trinidad and Tobago|9|
|UGA|Uganda|3|
|UNK|Unknown|9|
|VEN|Venezuela|14|

![image](https://github.com/Snseli/YFV-alignments/blob/main/PNG/YFV-WildType-country_years.png)


## YFV vaccinal strain
Alignement file : [Yellow fever virus alignment, vaccinal](https://github.com/Snseli/YFV-alignments/blob/main/Yellow%20fever%20alignements/YFV-Vaccine-alignments.fasta)

Total number of sequences : 38

Fasta header format : 

`Genbank accession | Country | date | vaccine | adverse event (AE)`

ML Tree file: [Vaccinal treefile](https://github.com/Snseli/YFV-alignments/blob/main/yellow%20fever%20vaccine%20treefile/YFV-Vaccine-alignments.fasta.treefile)

![image](https://github.com/Snseli/YFV-alignments/blob/main/PNG/YFV-vaccine-treefile.PNG)


Key :

Vaccine :
|code|vaccine|count|
|---|---|---|
|17D-204-SA|17D-204 South Affrica|3|
|17D-Tiantan|17D-Tiantan|1|
|17DD|17DD|8|
|STAMARIL|Stamaril, 17D-204|14|
|UNK|Unknown|5|
|YF-VAX|Sanofi Pasteur 17D-204|7|


