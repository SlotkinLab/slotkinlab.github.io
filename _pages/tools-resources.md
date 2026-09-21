---
layout: single
classes: wide
title: Tools & Resources
description:
permalink: /tools-resources/
---
Below are some of the tools and resources developed by the Slotkin Lab:

#### All-in-One (AIO) RNA sequencing Data Pipeline and Machine Learning 

From: (2025)  M.C. Kramer, T.S. Ratnayake, S.A. Edwards, H.L. Lowrey, G. Klaas, L. Sidorenko, B.A. Rowan, R. Michelmore, B.C. Meyers and R.K. Slotkin. [Identification of a cleaved aberrant RNA associated with the initiation of transgene silencing](https://academic.oup.com/plcell/article/37/10/koaf219/8258484 ). The Plant Cell 37: koaf219. Github repository available [here](https://github.com/sandaruwanrat/AIO_paper).
This repo contains the scripts for all data analysis steps for "All-in-One" RNA-seq, Random Forest machine learning, small RNA sequencing, and RMarkdown files for each figure in the manuscript.


#### Image Resources for plant growth under high CO2 conditions

From: (2023) K. Panda, B. Mohanasundaram, J. Gutierrez, L. McLain, S.E. Castillo, H. Sheng, A. Casto, G. Gratacós, A. Chakrabarti, N. Fahlgren,  S. Pandey,  M.A. Gehan and R.K. Slotkin. [The plant response to high CO2 levels is heritable and orchestrated by DNA methylation](https://nph.onlinelibrary.wiley.com/doi/abs/10.1111/nph.18876). New Phytologist. Images available [here](https://github.com/danforthcenter/heritable-highCO2-response).

#### Resources for *in vivo* Protein-RNA tethering 

Plasmids and seeds available from the ABRC: [Link](https://abrc.osu.edu/stocks?search%5Btaxon%5D=Arabidopsis+thaliana&search%5Bsearch_text%5D=Slotkin&search%5Bsearch_fields%5D=Donor+last+name)
From: [A plant tethering system for the functional study of protein-RNA interactions in vivo](https://plantmethods.biomedcentral.com/articles/10.1186/s13007-022-00907-w) (2022). D. Cuerda-Gil, Y.-H. Hung, K. Panda and R.K. Slotkin. Plant Methods 18: 75.

#### Improved annotation of Arabidopsis Transposable Elements

[Long-read cDNA Sequencing Enables a ‘Gene-Like’ Transcript Annotation of Arabidopsis Transposable Elements.](http://www.plantcell.org/content/32/9/2687) K. Panda and R.K. Slotkin.  *Annotations are available on [GitHub](https://github.com/KaushikPanda1/AthalianaTETranscripts).*

---
#### Software Tools

[Analyze CRISPR knock-in insertion junctions with amplicon sequencing](https://github.com/sandaruwanrat/CRISPR_Amplicon_Seq_Analysis/tree/main) - Analyze the CRISPR junction intactness using GATK on amplicon reads and visualize basepair insertions and deletions.

Analyze CRISPR on and off target insertion rate using Insertion-seq [analysis pipeline](https://github.com/sandaruwanrat/CRISPR-insertion-seq/tree/main/Scripts)
Whole-genome CRISPR off-target insertion screening, and visualization of unintended insertion events.

[CHIP-seq data processing snakemake pipeline](https://github.com/sandaruwanrat/CHIP-Seq_snakemake_pipeline). Snakemake based CHIP-seq processing pipeline for HPCs. Generates bam files  and normalized bigwig tracks

[Small RNA-seq data processing snakemake pipeline](https://github.com/sandaruwanrat/sRNA_processing_pipeline_snakemake). Snakemake based sRNA-seq processing pipeline for HPCs. Generate Genome mapped bam files and count files.

DNA Methylation Analysis - Bisulfite Amplicon sequencing (BSAS-seq) [processing wrapper](https://github.com/sandaruwanrat/BSA_seq_wrapper)
Analyze Bisulfite Amplicon sequencing reads, map reads using methylpy, generate allC files, count methylation percentage, coverage and stats.

Tool to determine the stength of RNA-directed DNA Methylation (RdDM). From: [An siRNA-guided Argonaute protein directs RNA Polymerase V for the first round of RNA-directed DNA methylation](https://www.nature.com/articles/s41477-021-01008-7) (2021). M. Sigman, K. Panda, R. Kirchner, L.L. McLain, H. Payne, J.R. Peasari, A.Y. Husbands, R.K. Slotkin, A.D. McCue.Nature Plants 7: 1461-1474. 
2026 - [Improved pipeline](https://github.com/sandaruwanrat/BSA_seq_wrapper) to calculate RNA-directed DNA Methylation (RdDM) strength from bisulfite amplicon sequencing data using Bismark.

[EpiTEome: Simultaneous detection of transposable element insertion sites and their DNA methylation levels.](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-017-1232-0) J. Daron and R.K. Slotkin. Genome Biology v18:7704.  *Available on [GitHub](https://github.com/jdaron/epiTEome).*

![image-right]({{ site.url }}{{ site.baseurl }}/assets/images/kismeth-1.jpg){: .align-right}
[Kismeth: Analyzer of Plant Methylation States Through Bisulfite Sequencing.](http://www.biomedcentral.com/1471-2105/9/371) E. Gruntman<sup>\*</sup>, Y. Qi<sup>\*</sup>, R.K. Slotkin<sup>\*</sup>, T. Roeder, R.A. Martienssen and R. Sachidanandam. BMC Bioinformatics v9: e371.<sup> \*</sup>*These authors contributed equally to this manuscript. Available as an [web-based tool.](http://katahdin.mssm.edu/kismeth/revpage.pl)*

---
#### Teaching Resources

R.K. Slotkin. [Designing a Better Laboratory Course.](http://gsi.berkeley.edu/slotkinrk-2005/) **Teaching Guide for Graduate Student Instructors** 2005-2006, University of California Press.
