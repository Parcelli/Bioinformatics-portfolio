# Automation of RNASeq Analysis pipeline using Galaxy
The workflow uses data subsets from a Nature Cell Biology paper by Fu et al. 2015. Both the raw data (sequence reads) and processed data (counts) can be downloaded from Gene Expression Omnibus database (GEO) under accession number GSE60450.

This study examined the expression profiles of basal and luminal cells in the mammary gland of virgin, pregnant and lactating mice. 
## Data
Input dataset for the workflow can be a collection of either single end or paired end sequence data.

## Analysis steps
![image](https://github.com/Parcelli/Bioinformatics-portfolio/assets/85280870/a99afcad-c46e-4d17-8f14-b1d77a622d8b)

## Outputs
## Fastqc and Multiqc html reports
* Multiqc for quality of raw reads
![fastqc_per_base_sequence_quality_plot (1)](https://github.com/Parcelli/Bioinformatics-portfolio/assets/85280870/48ee652c-892b-40ef-a872-cbdd82263792)

* Volcano plot

![volcano](https://github.com/Parcelli/Bioinformatics-portfolio/assets/85280870/4cd265b9-a45a-4b57-b7bd-c66d20b662b1)

* Heatmap of differentially expressed genes

![mouse](https://github.com/Parcelli/Bioinformatics-portfolio/assets/85280870/157a333c-20d0-45ee-9b93-e085ee7a83b6)

* List of differentially expressed genes

## Workflow snip
![rnaseq-quickcounter](https://github.com/Parcelli/Bioinformatics-portfolio/assets/85280870/eb5147a8-b9c1-4b65-812f-d70c7211a644)

