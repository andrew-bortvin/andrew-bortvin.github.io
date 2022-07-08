---
layout: post
title: Publications and Posters
---

## McCoy Lab 

### rhapsodi 

Modern sequencing methods allow for DNA sequencing of thousands of individual sperm cells from a donor. This gives scientists a powerful toolkit to study how genetic information is passed down across generations. However, individual cells are sequenced at low coverages (~0.01x), meaning that most of the DNA sequence of each cell is missing. Before sperm data can be analyzed, this missing data needs to be inferred. Our lab has developed [rhapsodi](https://github.com/mccoy-lab/rhapsodi), an R package that uses sperm genotypes to infer the phased genome of the donor and from this reconstructs the full genomes of each individual sperm cell and identifies all recombination sites in each cell.

If an individual has two different alleles of a gene, we expect that both alleles are equally likely to passed down to offspring. Deviation from this expected inheritance pattern where one allele is more commonly inherited than the other is referred to as transmission distortion (TD). TD is well-documented in a variety of plant and animal species but remains controversial in humans. To conduct a genome-wide search for TD in human sperm, we applied rhapsodi to previously published human sperm data. We found no evidence of TD in any of the analyzed donors. 

As a part of the rhapsodi project, I conducted studies benchmarking rhapsodi against Hapi, a previous tool used for analysis of single-sperm DNA sequenced data. My work demonstrates that rhapsodi is able to generate much more complete reconstructions of parental and sperm genomes with no cost to accuracy, and that rhapsodi is able to work with much larger input sizes than other tools. To determine the extent to which rhapsodi is able to detect TD, I developed a simulation that generates sperm data with known amounts of TD. This simulation was used to benchmark rhapsodi's power in detecting TD. 

The manuscript describing rhapsodi and its application to TD is available as a [preprint](https://www.biorxiv.org/content/10.1101/2021.11.19.469261v2) and is currently under review. I have also presented a poster describing this work at the 2022 Johns Hopkins Workshop on Chromatin, Chromosomes, and Epigenomes. This poster can be viewed [here](https://github.com/andrew-bortvin/andrew-bortvin.github.io/blob/main/poster_final_resize.pdf).

## Gimelbrant Lab 

In the Gimelbrant lab, I studied the mechanisms of random autosomal monoallelic expression (RMAE), a phenomenon in which the maternal or the paternal allele of a gene is randomly silenced. While a substantial number of genes have been shown to consistently have these random inactivation patterns, researchers have not been able to identify the molecular mechanisms regulating RMAE. Our lab developed a protocol that allows for rapid and cost-effective screening for drugs that reactivate silenced alleles. 

Our screen identified a candidate drug that can reactivate a genes with monoallelic silencing. I worked to validate this candidate drug and to investigate the biological pathways that it acts upon. I conducted drug treatments in cultured cells and used RNA quantification methods to identify reactivation of silenced target genes. To characterize molecular targets, I used shRNA infection knockdowns to perturb putative drug targets and demonstrate that their perturbation is sufficient to reactivate silenced alleles. 

Our work has been [published in G3](https://academic.oup.com/g3journal/article/12/2/jkab428/6472352?login=true).
