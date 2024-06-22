# Mock-community-data
Mock community data collection

## Metagenome

### Data with ground truth abundance

+ E.coli mock community
  
  Description: Mock community with 99% human and 1% E. coli

  Source: [SRR13355226](https://www.ncbi.nlm.nih.gov/sra/SRR13355226)

  Data_type: NGS

  Abundance: 80% H10407, 15% UTI89, 4.9% Sakai, and 0.1% E24337A

  Original_study: [StrainGE](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-022-02630-0#Sec2)

  Reference: [StrainScan](https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-023-01615-w)

  Comment: 4 E.coli strains can be found in NCBI RefSeq, complete genome


+ ATCC MSA-1003(Staggered)
  
  Description: 20 Strain Staggered Mix Genomic

  Source: [SRR9328980](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR9328980&display=metadata), [SRR8359173](https://trace.ncbi.nlm.nih.gov/Traces/?run=SRR8359173)

  Data_type: SRR9328980(PacBio HiFi), SRR8359173(Illumina)

  Abundance: https://www.atcc.org/products/msa-1003

  Original_study:

  Reference: [Evaluation of taxonomic classification and profiling methods for long-read shotgun metagenomic sequencing datasets](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9749362/)

  Comment: One species per strain(20 species). 4 strains can not be found in NCBI RefSeq, complete genome. (ATCC 17029, ATCC 9027, ATCC BAA-816, ATCC 17982)

+ Tourlousse

  Description: 20 species

  Source: SRR17380241–SRR17380246

  Data_type: NGS

  Abundance: https://journals.asm.org/doi/10.1128/spectrum.01915-21 table1

  Original_study: [Characterization and Demonstration of Mock Communities as Control Reagents for Accurate Human Microbiome Community Measurements](https://journals.asm.org/doi/10.1128/spectrum.01915-21)

  Reference: [Mock community taxonomic classification performance of publicly available shotgun metagenomics pipelines](https://www.nature.com/articles/s41597-023-02877-7#Sec18)

  Comment: 1. The authors developed both a DNA mixture and a whole-cell mixture(including Replicates group), usually we choose DNA mixture. 2. The strain Bifidobacterium longum subsp. longum was renamed and combined with Bifidiobacterium longum for a total relative abundance of 10.4% in reference paper.

+ ZymoBIOMICS Microbial Community Standard(Zymo D6330)

  Description: 8 bacteria and 2 yeasts

  Source: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6520541/table/tbl2/?report=objectonly, https://lomanlab.github.io/mockcommunity/, https://github.com/LomanLab/mockcommunity

  Data_type: Illumina, R9.4.1, R10.4(only in https://github.com/LomanLab/mockcommunity)

  Abundance: https://github.com/LomanLab/mockcommunity/blob/master/specs/_d6300_zymobiomics_microbial_community_standard.pdf

  Original_study: [Ultra-deep, long-read nanopore sequencing of mock microbial community standards](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6520541/)

  Reference:

  Comment:

+ ZymoBIOMICS gut microbiome standard(Zymo D6331)

  Description: 14 bacteria, 1 archaea, and 2 yeasts. Five species occur at 14% abundance, four at 6%, four at 1.5%, and one species per 0.1%, 0.01%, 0.001%, and 0.0001% abundance level. 

  Source: SRR13128014

  Data_type: PacBio HiFi

  Abundance: https://files.zymoresearch.com/datasheets/ds1712_zymobiomics_gut_microbiome_standard_data_sheet.pdf

  Original_study:

  Reference: [Evaluation of taxonomic classification and profiling methods for long-read shotgun metagenomic sequencing datasets](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9749362/)

  Comment:

+ Bmock12
  
  Description: 12 bacterial strains from 10 species

  Source: SRA Accessions SRX516198569 (ONT no size selection), SRX490158670 (ONT 10 kb size selection), SRX490158471 & SRX490158572 (PacBio 10 kb size selection; two libraries were combined for analysis), SRX490158373 (Illumina).

  Data_type: Illumina, PacBio, ONT

  Abundance: https://static-content.springer.com/esm/art%3A10.1038%2Fs41597-023-02877-7/MediaObjects/41597_2023_2877_MOESM1_ESM.pdf(compute based on mapped read in each species and genome length in original study), https://static-content.springer.com/esm/art%3A10.1038%2Fs41597-019-0287-z/MediaObjects/41597_2019_287_MOESM2_ESM.docx

  Original_study: [Shotgun metagenome data of a defined mock community using Oxford Nanopore, PacBio and Illumina technologies](https://www.nature.com/articles/s41597-019-0287-z#MOESM1)

  Reference: [Mock community taxonomic classification performance of publicly available shotgun metagenomics pipelines](https://www.nature.com/articles/s41597-023-02877-7#Sec18)

  Comment: many species not in NCBI RefSeq.

+ Gut-Mix-RR(even) and Gut-HiLo-RR(staggered)

  Description: 20 common gut microbiome strains. These reference reagents comprised strains spanning 5 phyla, 13 families, 16 genera, and 19 species, to allow testing of pipelines’ ability at different taxonomic levels.

  Source: PRJNA622674

  Data_type: Illumina

  Abundance: https://static-content.springer.com/esm/art%3A10.1038%2Fs41597-023-02877-7/MediaObjects/41597_2023_2877_MOESM1_ESM.pdf Table S1(e)

  Original_study: [Developing standards for the microbiome field](https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-020-00856-3#availability-of-data-and-materials)

  Reference: [Mock community taxonomic classification performance of publicly available shotgun metagenomics pipelines](https://www.nature.com/articles/s41597-023-02877-7#Sec18)

  Comment: The strain Bifidobacterium longum subsp. longum was renamed and combined with Bifidiobacterium longum for a total RA of 37% in the staggered community and 13% in the even community in reference paper.

### Data without ground truth abundance

+ Human Microbiome Project

  Description: 21 known organisms (including E. coli, C. acnes, and S. epidermidis)

  Source: SRR172902(even), SRR172903(SRR172903)

  Data_type: NGS

  Original_study:

  Reference: [StrainScan](https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-023-01615-w)

  Comment: [mock community composition](https://www.hmpdacc.org/HMMC/)

+ MBARC-26

  Description: 23 bacterial and 3 archaeal strains with finished genomes(can be found in GeneBank)

  Source: [SRR3656745](https://www.ncbi.nlm.nih.gov/sra/?term=SRX1836716), [SRR3656744](https://www.ncbi.nlm.nih.gov/sra/?term=SRX1836715)

  Data_type: SRR3656745(Illumina), SRR3656744(PacBio)

  Original_study: [Next generation sequencing data of a defined microbial mock community](https://www.nature.com/articles/sdata201681)

  Reference:

  Comment:

+ NWCs

  Description: Drawn from Natural whey starter cultures. Three species generally pre-dominate: Streptococcus thermophilus, Lactobacillus helveticus and Lactobacillus delbrueckii.

  Source: SAMN09703751(NWC_1), SAMN09580370(NWC_2)

  Data_type: NWC_1(NGS, PacBio), NWC_2(NGS, PacBio, ONT R9.5)

  Original_study: [Long-read based de novo assembly of low-complexity metagenome samples results in finished genomes and reveals insights into strain diversity and an active phage system](https://bmcmicrobiol.biomedcentral.com/articles/10.1186/s12866-019-1500-0#availability-of-data-and-materials)

  Reference: StrainXpress

  Comment: NGS reads was trimmed



### Useful supplement

+ CAMISIM
+ Mock community taxonomic classification performance

  Description: many mock community dataset
  [Mock community taxonomic classification performance of publicly available shotgun metagenomics pipelines](https://www.nature.com/articles/s41597-023-02877-7#Sec18)
