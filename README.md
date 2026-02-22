# LUSC-bulkRNAseq-analysis
Bulk RNA-seq differential expression and pathway analysis of early-stage Lung Squamous Cell Carcinoma in R.

This repository contains R scripts for differential gene expression and pathway enrichment analysis of bulk RNA-seq data from early-stage lung squamous cell carcinoma (GEO GSE268175), including QC, normalization, visualization, and biological interpretation.

## Dataset
- Source: GEO GSE268175  
- Samples: 28 tumor and 28 matched adjacent normal lung tissue samples  
- Data type: bulk RNA-seq raw counts  
- Human subjects: publicly available, de-identified data

## Analysis Workflow
1. Download raw count data and metadata from GEO  
2. Quality control and filtering  
3. Normalization and differential expression analysis using edgeR  
4. Visualization (PCA, volcano plots, heatmaps)  
5. Gene Ontology and pathway enrichment using clusterProfiler and ReactomePA

## Tools
- R  
- Bioconductor  
- edgeR  
- clusterProfiler  
- ReactomePA  
- ggplot2

## Repository Structure
scripts/     R analysis scripts  
figures/     Output plots  
data/        Input data (not included if large)  
README.md

## Outputs
- Differentially expressed gene lists  
- PCA and volcano plots  
- Heatmaps of top DE genes  
- GO and pathway enrichment results

## Ethics
This study uses only publicly available, de-identified data and involves no direct human subject interaction.

## Author
Iris Zheng, 2025
