# DNA-Breathing-Publication-Code
Accompanying code repository for the DNA Breathing Publication out of the lab of Dr. Xinhe at the University of Chicago's Human Genetics Department.
Data Repository: DOI 10.17605/OSF.IO/2UHP7 (link: doi.org/10.17605/OSF.IO/2UHP7)

## ChIP-seq Analysis Files

### `chipseq_dataset_flipping_correlations_paper.ipynb`
- Analyzes correlations between DNA flipping dynamics and ChIP-seq binding data

### `chipseq_analysis_paper.ipynb`
- Generates summary statistics and tables for the ChIP-seq dataset

### `chipseq_dataset_analysis_paper.ipynb`
- Main analysis notebook for ChIP-seq data
- Contains correlation analysis between DNA breathing features and transcription factor binding
- Includes statistical tests and visualization of results

### `chipseq_to_fasta_with_jaspar_paper.ipynb`
- Converts ChIP-seq data to FASTA format
- Integrates JASPAR motif information for transcription factor binding site analysis
- Downloads and processes motif files from the JASPAR database
- Runs motif scanning using FIMO from the MEME suite


## gcPBM Analysis Files

### `gcPBM_exploration_paper.ipynb`
- Exploratory analysis of the gcPBM dataset
- Used to study the correlation of bubble presence with binding affinity

### `gcPBM_dataset_analysis_paper.ipynb`
- Analysis of gcPBM data
- Examines DNA breathing features in relation to protein binding patterns
- Examines correlations between motif and bubble presence

## Data Processing Files

### `bubble_data_exploration_paper.ipynb`
- Explores the DNA breathing dataset
- Used to generate tensormaps, heatmaps and plots used to explain the premise of the paper
