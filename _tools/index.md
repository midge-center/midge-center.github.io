---
layout: index_page
category: tools
title: Computational workflows and tools
---

We develop computational workflows and tools to help us analyze multi-omics data and make sense of amplicon and genomic data. Click on the badges below to learn more about each of the workflows and tools.


### Viruses

#### HMPV IRMA module [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/lauringlab/HMPV_IRMA_module)

A module for human metapneumovirus (HMPV) to be used with [IRMA](https://wonder.cdc.gov/amd/flu/irma/index.html). The consensus sequences are derived from all whole genomes available on GenBank on October 18, 2024.

#### RSV amplicon sequencing [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/lauringlab/RSV_amplicon_sequencing) [![Paper](https://img.shields.io/static/v1?style=flat&logo=google-scholar&label=+&message=Paper&color=white)](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2817146)

A protocol for RSV-A and RSV-B sequencing that consists of two pools of overlapping amplicons. It is designed to work with current Arctic SARS-CoV-2 protocols.

#### COVID-19 Sequence Assembly [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/lauringlab/COVID19SequenceCompile)
An R-based workflow for assembling COVID-19 genome sequences from Nanopore or Illumina sequence data.

#### Sequencing bioinformatic pipelines [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/lauringlab/Sequencing_bioinformatic_pipelines)
Scripts and reference files needed to make consensus sequences for Influenza, SARS-CoV-2, and RSV.



### Bacteria

#### QCD [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/Snitkin-Lab-Umich/QCD)

Snakemake workflow for quality control and contamination detection of microbial Illumina whole-genome sequencing (WGS) data


####  nanoQC [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/Snitkin-Lab-Umich/nanoQC)

Snakemake workflow for quality control and assembly of Nanopore (long-read) sequencing data.


#### Nanosake [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/Snitkin-Lab-Umich/Nanosake)

Snakemake workflow for hybrid assembly using cleaned Illumina short reads and Nanopore long reads


#### SNPkit [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/Snitkin-Lab-Umich/snpkit)

Snakemake workflow for microbial variant calling


#### pubQCD [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/Snitkin-Lab-Umich/pubQCD)

Snakemake workflow for quality control of datasets downloaded from public repositories such as NCBI and SRA


#### Data-Flow-SOP [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/Snitkin-Lab-Umich/Data-Flow-SOP)

Collection of standard operating procedures (SOPs) for processing short-read, long-read, and hybrid bacterial sequencing data


#### Phylokit [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/Snitkin-Lab-Umich/phylokit)

Snakemake workflow for recombination detection and phylogenetic tree reconstruction from a sequence alignment



### Fungi

#### funQCD [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/Snitkin-Lab-Umich/funQCD)
Snakemake pipeline for de novo assembly and annotation of C. auris short-read sequencing data.

#### nanofunQC [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/Snitkin-Lab-Umich/nanofunQC)
Snakemake pipeline for de novo assembly and annotation of C. auris long-read sequencing data.

#### nanofunsake [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/Snitkin-Lab-Umich/nanofunsake)
Snakemake pipeline for de novo hybrid assembly and annotation, using a combination of C. auris long-read and short-read data.

#### cauris-data-flow [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/Snitkin-Lab-Umich/cauris-data-flow)
Set of scripts to standardize the output of multiple different runs of the above C. auris assembly pipelines.

#### cauris_dotplot [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/Snitkin-Lab-Umich/cauris_dotplot)
Tool to generate large numbers of synteny dotplots, to aid in visualizing structural variation across assemblies.


### Technology & Data Core

#### phyloAMR [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/kylegontjes/phyloAMR/tree/master)
An R package that leverages ancestral state reconstruction and other phylogenetically-informed algorithms to characterize the evolutionary history of genome-influenced traits and investigate phenotype-genotype associations.

#### corHMM [![GitHub](https://img.shields.io/static/v1?style=flat&logo=GitHub&label=+&message=GitHub&color=black)](https://github.com/thej022214/corHMM)
New functionality included in this phylogenetics package as part of MIDGE to incorporate uncertainty into joint ancestral reconstruction analysis.

