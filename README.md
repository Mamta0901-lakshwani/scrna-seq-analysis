# Single Cell RNA-seq Analysis using Scanpy

This project performs single-cell RNA sequencing (scRNA-seq) analysis using the Python library Scanpy. The analysis includes quality control, normalization, dimensionality reduction, clustering, and marker gene identification to explore cellular heterogeneity.

Dataset used: GSE84133 pancreatic islet single-cell RNA-seq dataset obtained from the Gene Expression Omnibus (GEO) database. The dataset contains gene expression counts for individual cells along with barcode identifiers and assigned cell type clusters.

Objective: The aim of this project is to analyze single-cell gene expression data to identify cellular populations, visualize cell clusters using UMAP, and detect marker genes that characterize different cell types.

Pipeline steps:
- Data loading and preprocessing
- Quality control filtering
- Normalization and log transformation
- Highly variable gene selection
- PCA dimensionality reduction
- UMAP visualization
- Leiden clustering
- Marker gene identification

Results generated:
- QC violin plots
- PCA variance plot
- UMAP visualization
- Clustered UMAP plot
- Marker gene plots
- Marker gene heatmap

Tools used:
- Python
- Scanpy
- Pandas
- Matplotlib

The results and figures generated from the analysis are stored in the `results` folder.
