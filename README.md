# Heartland Virus Phylodynamics in NewYork
The aim of this project was to understand the evolution and spread of Heartland virus in the United States by sequencing virus strains isolated from Amblyomma americanum collected in New York State. 

## Sample Collection
Ticks were collected across Suffolk County, New York through routine New York State Department of Health (NYSDOH) passive tick surveillance. These efforts were conducted by the Bureau of Communicable Disease at NYSDOH directed by Melissa Prusinski and her team. Viral testing was conducted at the Wadsworth Center, NYSDOH Arbovirus Unit directed by Alexander Ciota. Tick homogonates, viral isolates, and viral sequencing libraries are all maintained in long-term storage at the Arbovirus Unit.

### Sequencing
Whole genome sequencing was conducted at the Wadsworth Center, NYSDOH Advanced Genomic Technologies Core (AGTC) directed by Matthew Shudt. 
Library construction was performed using an amplicon-based sequencing approach using primers found in the "sequencing" folder. Sequencing was performed on an Illumina MiSeq, paired-end 150. 

#### Consensus Genomes 
Consensus genomes and initial phylogenetic analyese were conducted using Geneious Prime v2021.1 with a minimum threshold of 65%. Consensus genomes (nucleotide and amino acid) can be found in the "sequencing" folder. 

##### Phylogenetic Analyses
Phylogenetic analyses were conducted based on the NYS HRTV sequences available in this repository and publicly available HRTV strains in GenBank. The following programs were used for each respective analysis:
* Maximum likelihood phylogenies: Geneious Prime v2021.1
* Time-scaled phylogeneis: TempEST v1.5.3, BEAUti v1.10.4, BEAST v1.10.4, Tracer v1.6, LogCombiner v1.10.4, FigTree v1.4.4
* Phylogeographic reconstruction: BEAUti v1.10.4, BEAST v1.10.4, Tracer v1.6, LogCombiner v1.10.4, RStudio v.4.5.1, Kepler.gl [accessible at http://kepler.gl]

**Disclaimer** Please note that these data are based on unpublished work and should be considered preliminary until peer-review is conducted. 

