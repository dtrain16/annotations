


TAIR10 STATS [Nov 17 2010]
The Arabidopsis Information Resource (TAIR) is pleased to announce the release of the latest version of the Arabidopsis genome annotation (TAIR10). 
The latest release builds upon the gene structures of the previous TAIR9 release using RNA-seq and proteomics datasets as well as manual updates informed by cross species alignments, peptides and community input regarding missing and incorrectly annotated genes. 

The TAIR10 release contains 27,416 protein coding genes, 4827 pseudogenes or transposable element genes and 1359 ncRNAs (33,602 genes in all, 41,671 gene models). A total of 126 new loci and 2099 new gene models were added. 

Eighteen percent (5885) of Arabidopsis genes now have annotated splice variants. Updates were made to 1184 gene models of which 707 had CDS updates. 
There were 41 gene splits and 37 gene merges. No changes were made to the Arabidopsis genome assembly for the TAIR10 release. 

Gene annotation utilized available proteomics data (Baerenfaller et al., 2008 and Castellana et al., 2008) and RNA-seq data from the Ecker and Mockler labs
 (Lister et al. 2008, Filichkin et al. 2010). RNA-seq data was mapped to the Arabidopsis genome using TopHat, HashMatch or supersplat. After quality and 
low complexity filtering a total of ~200 million RNA-seq reads were successfully mapped to the genome. Of these, ~9 million represent spliced reads. 
Proteomics data and spliced RNA-seq reads were provided to Augustus and the resulting gene models categorised and manually reviewed. Validated gene 
updates, novel genes and novel splice variants were incorporated into the TAIR10 release. Additional spliced RNA-seq reads not already incorporated into 
gene models by Augustus were supplied to TAU. The resulting TAU models were again reviewed for potential novel splice variants. Transcript assemblies were 
generated via Cufflinks using all spliced reads and unspliced reads from the Ecker sets. Transcript assemblies were filtered and compared to existing gene 
models, resulting in the addition of 56 novel genes. Additional new proteome data provided to us by Katja Baerenfaller was used to directly update 24 gene 
models. 

Gene models created using the Gnomon pipeline were provided to TAIR by NCBI. Reanalysis of these models for TAIR10 resulted in 11 additional novel genes, 
67 additional alternative splice variants and 164 updates to existing genes. 

We would like to thank all those who contributed to the latest release by providing submissions for new and incorrectly annotated genes. 

TAIR wishes to thank Cornell University for use of the computer clusters at the Cornell Center for Advanced Computing (CAC).



ABOUT THE TAIR10 FILES
All files shown in the TAIR10_genome_release directory reflect data as of November 2010, when TAIR10 was releases. If some of the files available
from this location still contain the name 'TAIR9', this is due to the fact that this specific dataset has not changed between TAIR9 and TAIR10
releases.

NCBI files: These are the table files for TAIR10 that we submitted to NCBI
NCBI_Chr1.tbl
NCBI_Chr2.tbl
NCBI_Chr3.tbl
NCBI_Chr4.tbl
NCBI_Chr5.tbl

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Association files: These files indicate which ESTs and cDNAs were associated to which TAIR10 AGIs by TAIR curators. Note that assocations to a Locus merely
required overlap of coordinates while Model associations requited each internal junction of a transcript to match that of the Model.
TAIR10_Locus_EST_associations.gz
TAIR10_Locus_cDNA_associations.gz
TAIR10_Model_EST_associations.gz
TAIR10_Model_cDNA_associations.gz
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


TAIR10_gff3: This file is the main TAIR10 gff file representing each feature of each TAIR10 gene model.


TAIR10_functional_descriptions; This file contains the short description, curator summary and computational description of each TAIR10 gene


TAIR10_locushistory.txt: This file summarizes all locus changes made since tigr5
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Confidence files: These files provide confidence scores to each exon/gene in TAIR10 based on the experimental data/VISTA sequence similarity 
available.To learn more about how TAIR curators have developed these confidence scores, see ftp://ftp.arabidopsis.org/Genes/TAIR9_genome_release/Gene_Confidence.pdf

confidenceranking_exon
confidenceranking_gene
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
TAIR10-Subcellular_Predictions.xlsx

AtSubP analysis of TAIR10 proteome.  Data kindly provided by Dr. Rakesh Kaundal.  Methodology based on http://www.plantphysiol.org/content/154/1/36.short. The first column indicates the Gene name; second is length of protein sequence, and then individual scores generated by AtSubP models for each of the subcellular localization, followed by the final prediction based on sorted score (last column). 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


Errors, omissions or comments should be reported to curator@arabidopsis.org

