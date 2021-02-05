# NGS Gene Differential Expression Analysis

## Original Dataset on Kaggle
https://www.kaggle.com/usharengaraju/indian-women-in-defense

## Data Introduction

Asthma is a chronic inflammatory airway disease. The most common medications used for its treatment are β2-agonists and glucocorticosteroids, and one of the primary tissues that these drugs target in the treatment of asthma is the airway smooth muscle. RNA-Seq is used to characterize the human airway smooth muscle (HASM) transcriptome at baseline and under three asthma treatment conditions.

## Methods
The Illumina TruSeq assay was used to prepare 75bp paired-end libraries for HASM cells from four white male donors under four treatment conditions: 1) no treatment; 2) treatment with a β2-agonist (i.e. Albuterol, 1μM for 18h); 3) treatment with a glucocorticosteroid (i.e. Dexamethasone (Dex), 1μM for 18h); 4) simultaneous treatment with a β2-agonist and glucocorticoid, and the libraries were sequenced with an Illumina Hi-Seq 2000 instrument. The Tuxedo Suite Tools were used to align reads to the hg19 reference genome, assemble transcripts, and perform differential expression analysis

Content Source : https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE52778

## Data Processing
- Data Cleaning
- Identify which columns are numeric
- Check that the dataframes of treated and control are the same size

## Paired sample t-test

merged in data from  http://bioinformatics.sdstate.edu/go/ with p-value 0.1

## Data ViZ
- Barplot for gene ontology enrichment data
- Scatter plot with pandas function
- Barplot for the mean difference differentially expressed genes  (gene control greater than treated)

## Evaluating Which Genes Responded to Treatment

- Data manipulation for smallest (most negative) differential expression differences
- Data manipulation for largest (most positive) differential expression differences

