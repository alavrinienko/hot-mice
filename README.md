# Analysis: Jupyter Notebook and R Markdown

## Comparable response of wild rodent gut microbiome to anthropogenic habitat contamination

This repository contains the code used to analyse the data in Lavrinienko et al. 2021. The Jupyter Notebook and the R Markdown contain commands to process raw read data, reproduce the qiime2 analyses, stats and main figures.

This repository provides the main data files, i.e. metadata, dada2 feature-tables, representative sequences, phylogenetic tree and taxonomy. It should be possible to generate the rest of the data using these files and commands. The raw sequence data for this study have been deposited in the European Nucleotide Archive (ENA) at EMBL-EBI under accession number [PRJEB44039](https://www.ebi.ac.uk/ena/browser/view/PRJEB44039).

If you use this resource in your research, please cite the following [article](xxx):



## Requirements

qiime2 is required to run most of the commands described below (the 2019.4 qiime2 version was used).
To install qiime2 follow [these](https://docs.qiime2.org/2019.4/install/) instructions.

### File explanations

 - qiime2 analysis notebook: chern-cmr-voles-v200419.ipynb
 - Metadata: metadata-malesrt.txt (metadata for wild bank voles from the Chernobyl Exclusion Zone, Ukraine)
 - qiime2 feature-table: malesrt2_table-dada2.qza (the original dada2 feature-table)
 - qiime2 rarefied feature-table: rarefied_table.qza (the 'filtered10', rarefied dada2 feature-table)
 - qiime2 representative sequences: malesrt2_rep-seqs-dada2.qza (the dada2 representative sequences)
