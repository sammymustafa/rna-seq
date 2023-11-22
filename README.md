# RNA-Sequencing Projects

This repository contains summaries and findings from various RNA-seq projects, predominantly leveraging UNIX on the high-performance computing cluster Quest. Each project investigates distinct aspects of the RNA-seq process, employing a variety of techniques and datasets:

### 1. FastQC/MultiQC Reporting for Yeast Replicates (Project 1):
* Objective: Analyze and summarize FastQC and MultiQC reports for 84 files (six biological replicates of wild type & SNF2 mutants yeast)​​.
* Techniques: Quality assessment of sequencing data, summarization using FastQC and MultiQC.

### 2. Optimizing Sequencing Data Download (Project 2):
* Objective: Compare download times for sequencing data from ENA and NCBI using various methods like wget, fastq-dump, fasterq-dump, ascp, and globus​​.
* Techniques: Data retrieval optimization, performance analysis.

### 3. Alignment of Yeast Replicates Using STAR (Project 3):
* Objective: Align yeast wildtype biological replicate using STAR with different alignment settings and examine the aligned reads​​.
* Techniques: Data alignment, analysis of alignment quality and effects of various settings.

### 4. Aligning Human Whole Blood Samples (Project 4):
* Objective: Align two human whole blood samples from GEO accession GSE113883, and analyze the alignment using tools like RSeQC and IGV​​.
* Techniques: Data alignment, differential expression analysis.

### 5. Generating Correlation and Variance Plots (Project 5):
* Objective: Build count tables for yeast wildtype and mutant replicates and create correlation and variance scatterplots​​.
* Techniques: Data processing, visualization in R.

### 6. Differential Expression Analysis (Project 6):
* Objective: Perform differential expression analyses using DESeq2 on previously constructed count tables, and visualize results​​.
* Techniques: Differential expression analysis, heatmap and PCA plot visualization.

### 7. Single Cell Sequencing Data Analysis (Project 7):
* Objective: Align and analyze single cell sequencing data from a mouse brain sample using Seurat​​.
* Techniques: Single-cell RNA-seq data alignment, clustering analysis, and visualization.

### 8. Gene Expression Analysis in Shock Patients (Project 8):
* Objective: Analyze RNA sequencing data from 21 septic shock and 11 cardiogenic shock patients to identify significant gene expression changes and compare time courses of gene expression across conditions​​.
* Techniques: Differential expression analysis, time course analysis.

Feel free to reach out for more information on data sources or detailed methodologies used in these projects.
