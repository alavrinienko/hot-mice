# Analysis Notebook
[![DOI](https://zenodo.org/badge/353986938.svg)](https://zenodo.org/badge/latestdoi/353986938)

## Comparable response of wild rodent gut microbiome to anthropogenic habitat contamination

This repository contains the code used to analyse the data in Lavrinienko et al. 2021. The Jupyter Notebook contains commands to process raw read data, reproduce the qiime2 analyses, some stats and main figures.

This repository provides the main data files, i.e. metadata, dada2 feature-tables, representative sequences, phylogenetic tree and taxonomy. It should be possible to generate the rest of the data using these files and commands. The raw sequence data for this study have been deposited in the European Nucleotide Archive (ENA) at EMBL-EBI under accession number [PRJEB44039](https://www.ebi.ac.uk/ena/browser/view/PRJEB44039). To analyse these data we have used computing resources and infrastructure provided by [the Finnish Centre for Scientific Computing (CSC)](https://www.csc.fi/csc).

If you use this resource in your research, please cite the following [article](xxx):



## Requirements

qiime2 is required to run most of the commands described below (the 2019.4 qiime2 version was used).
To install qiime2 follow [these](https://docs.qiime2.org/2019.4/install/) instructions.

### File explanations

 - qiime2 analysis notebook: github-ver-hot-mice.ipynb (the github-ver-hot-mice.html is an easy access copy)
 - metadata: metadata-apo272.txt (metadata associated with *Apodemus* mice)
 - metadata: metadata-vole137-apo272.txt (metadata associated with *Apodemus* mice and bank voles)
 - metadata: dsFDR-apo272-05percent.txt (metadata associated with taxa differential abundance testing for mice)
 - qiime2 feature-table: apo272-table-dada2.qza (the original dada2 feature-table for mice)
 - qiime2 rarefied feature-table: rarefied_table.qza (the 'filtered10', rarefied dada2 feature-table for mice)
 - qiime2 rarefied feature-table: rarefied_table_chernobyl142.qza (the 'filtered10', rarefied dada2 feature-table for mice, Chernobyl samples only)
 - qiime2 rarefied feature-table: rarefied_table_fukushima130.qza (the 'filtered10', rarefied dada2 feature-table for mice, Fukushima samples only)
 - qiime2 rarefied feature-table: rarefied_table_chernobyl115_flavicollis.qza (the 'filtered10', rarefied dada2 feature-table for mice, *Apodemus flavicollis* samples only)
 - qiime2 rarefied feature-table: rarefied_table_chernobyl27_sylvaticus.qza (the 'filtered10', rarefied dada2 feature-table for mice, *Apodemus sylvaticus* samples only)
 - qiime2 rarefied feature-table: rarefied_table_fukushima53_argenteus_small.qza (the 'filtered10', rarefied dada2 feature-table for mice, *Apodemus argenteus* samples only)
 - qiime2 rarefied feature-table: rarefied_table_fukushima77_speciosus_large.qza (the 'filtered10', rarefied dada2 feature-table for mice, *Apodemus speciosus* samples only)
 - qiime2 feature-table: dada2-table-vole137.qza (the original dada2 feature-table for bank voles)
 - qiime2 rarefied feature-table: rarefied_table-vole137.qza (the 'filtered10', rarefied dada2 feature-table for bank voles)
 - qiime2 representative sequences: apo272-rep-seqs-dada2.qza (the dada2 representative sequences for mice)
 - qiime2 representative sequences: dada2-rep-seqs-vole137.qza (the dada2 representative sequences for bank voles)
 - qiime2 phylogenetic tree: rooted-apo272-tree-dada2.qza (the phylogenetic tree for mice)
 - qiime2 taxonomy: apo272-dada2-taxonomy.qza (the taxonomy for mice)
