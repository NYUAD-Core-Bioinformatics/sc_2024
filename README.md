# sc_2024
This repo contains the data and code for CGSB workshop Applied RNA, and single cell RNAseq data analysis organized in Nov 2024.

## Aim:
Apply data analysis to gene expression data, and understand the related concepts.

In this 2 day workshop, participants will learn best practices for data analysis of both bulk, and single cell RNA sequences.
We will cover an array of topics including :
- Bulk vs single cell technology
- RNA seq in silico data generation process
- QC
- Normalization
- Batch correction
- Dimensionality reduction
- Differential gene expression analysis
- Clustering
- Dataset Integration
- Cluster Annotation
- Plotting
- GO Term enrichment


## Requirements:
Participants are expected to have a solid grasp on the biology of gene transcription.
A laptop with min 8GB of ram, and conda ( https://anaconda.org/anaconda/conda ) installed , or an HPC account

### Environment 
We use conda ( https://www.anaconda.com/download/success ) to build the environment, so make sure it's installed on your machine. You can use the command: 

```bash
git clone https://github.com/NYUAD-Core-Bioinformatics/sc_2024.git
cd sc_2024
conda env create -f env/environment.yml
conda activate sc_2024
jupyter-lab --ip=0.0.0.0
```
if you are on an M1-4 processor use this instead :

```bash
git clone https://github.com/NYUAD-Core-Bioinformatics/sc_2024.git
cd sc_2024
CONDA_SUBDIR=osx-64 conda env create -f env/environment.yml
conda activate sc_2024
jupyter-lab --ip=0.0.0.0
```
