# Identification of Fungi species in bee pollen 

## Summary
Fungi and Bees have shown a symbiotic relationship.Fungi protect the bees from microbial attacks.However some fungal species cause fatal diseases in bees leading to decline in bee population.
The study aimed to identify fungi species present in beehives in Zanzibar and to compare the performance of two databases in taxonomic classification.
## Research Questions
1.What kind of fungi is in the bee pollen? 

2.Are there any harmful fungi species?

3.How does classification with UNITE and SILVA database differ?

## Data
The data used is paired-end illumina sequenced amplicon data from ITS 2-4 region. The data is distributed across 26 samples from Zanzibar.

## Analysis steps and tools
* Quality control - FASTQC & Trimmomatic
* Denoising - DADA2
* Taxonomic classification - QIIME2
* Diversity analysis - R 

## Results
### Fungi species
55 species of fungi and 43  genus were identified with the dominant genus being Zygosaccharomyces.

The harmful fungal species identified were Fusarium spp & Aspergillus spp.

Their is a huge difference in taxonomic representation between the two database. I attributed this to the type of inadequacy of fungi data present in SILVA database as compared to UNITE.

**SILVA** is a database for aligned ribosomal RNA sequences from; bacteria,archaea and eukaryota

**UNITE** is a database for molecular identification of Fungi.

### Taxonomic classification plots
![UNITE](https://github.com/Parcelli/Bioinformatics-portfolio/assets/85280870/f001e30f-3b26-4184-97ee-a85c53996ad2)
![SILVA](https://github.com/Parcelli/Bioinformatics-portfolio/assets/85280870/6f06e2df-50d7-4bff-9069-5f109dc5ee10)
![tax](https://github.com/Parcelli/Bioinformatics-portfolio/assets/85280870/32c9add1-391a-425b-9c56-e1706a6a0268)

### Alpha diversity plot
Alpha diversity measures the diversity of species in a sample.

![alpha-bee](https://github.com/Parcelli/Bioinformatics-portfolio/assets/85280870/cf7eed9d-0a9f-4a2d-a6df-68dad27a589a)

### Beta diversity plot
Beta diversity measures difference in species between samples.

![beta-bee](https://github.com/Parcelli/Bioinformatics-portfolio/assets/85280870/9c926015-3cf3-4e31-a211-7e0dc033e9df)

**Projects report**

The bioinformatics analysis codes and pipelines are hosted on this [github](https://github.com/mbbu/Fungi_Identification/blob/zanzibar_subset/scratchpad/report.md) page.
