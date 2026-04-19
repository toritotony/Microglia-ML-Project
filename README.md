# Microglia-ML-Project

This repository contains code and analysis for modeling microglial phenotype transitions using single-cell RNA sequencing (scRNA-seq) time series data. The project explores how gene expression dynamics reflect shifts in microglial states under neurodegenerative conditions.

## Overview

Microglia exhibit diverse functional phenotypes that evolve over time in response to environmental and pathological signals. Understanding these transitions is key to studying diseases such as Alzheimer’s.

In this project, we:
- Analyze time-resolved scRNA-seq data from hippocampal microglia
- Apply dimensionality reduction (PCA, UMAP) to uncover structure in gene expression
- Use clustering methods (Leiden) to identify distinct transcriptional states
- Evaluate relationships between data-driven clusters and canonical M1/M2 phenotypes
- Investigate the presence of intermediate or previously uncharacterized microglial states

## Goals

- Characterize temporal changes in microglial transcriptional states  
- Assess alignment between clustering results and known biological phenotypes  
- Identify potential novel or mixed phenotype states  
- Provide a computational framework for studying phenotype transitions in single-cell data  

## Tech Stack

- Python (Scanpy, AnnData, NumPy, Pandas, Matplotlib)
- Jupyter Notebook (NRP JupyterLab environment)

## Usage

This repository is intended to be cloned and run within the NRP JupyterLab environment:

```bash
git clone https://github.com/your-username/Microglia-ML-Project.git
