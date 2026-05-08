# rnaseq-xenium-analysis
This repository contains the R scripts and workflows used for RNA-seq differential expression analysis and Xenium spatial transcriptomics analysis in this study. The code includes preprocessing, normalization, clustering, and spatial transcriptomic data analysis.

Cortical Projection Neuron RNA-seq and Xenium Spatial Transcriptomics Analysis

This repository contains analysis pipelines for bulk RNA-seq and Xenium spatial transcriptomics datasets generated from cortical neuron samples.

Repository Contents
Xenium Spatial Transcriptomics Analysis
Xenium_upstream_file_merging.rmd

Preprocessing workflow for Xenium datasets including:

Import of Xenium output files
File merging and object creation
Metadata handling
Initial preprocessing steps
Final Xenium Analysis all samples.Rmd

Complete Xenium spatial transcriptomics analysis pipeline including:

Quality control
Normalization
Clustering
Cell type annotation
Differential expression analysis
Spatial visualization
Comparative analysis across samples
clean_cluster2.Rmd

Subset analysis of Layer 2/3 projection neurons (L2/3 PNs), including:

Cluster extraction
Re-clustering
Marker identification
Visualization and downstream analysis


clean_cluster0.Rmd

Subset analysis of Layer 5/6 projection neurons (L5/6 PNs), including:

Cluster extraction
Re-clustering
Marker identification
Visualization and downstream analysis
Bulk RNA-seq Analysis

The following RMarkdown files contain differential expression analysis workflows using EdgeR for bulk cortical neuron RNA-seq datasets.

Comparisons Included
LgDel vs WT.Rmd
LD vs LD_NAC.Rmd
LD_NAC vs WT.Rmd
WT vs WT_NAC.Rmd
Txn vs WT.Rmd

Bulk RNA-seq Workflow Includes
STAR count table processing
CPM filtering
Library normalization
PCA and clustering analysis
Differential expression analysis using EdgeR
TPM normalization
Gene annotation using BioMart
Export of annotated gene tables
