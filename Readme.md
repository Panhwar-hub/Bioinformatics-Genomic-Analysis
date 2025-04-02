# Bioinformatics Genomic Analysis of Species

This project investigates the genomic features of three species: **Cyprinus Carpio**, **Rattus Norvegicus**, and **Parus Major**, using bioinformatics tools and machine learning techniques. The goal is to analyze the GC content and other genomic features, as well as train a Random Forest classifier to find the most important features in distinguishing between the species.

## Project Overview

### Data
- The dataset includes genomic features such as:
  - `Species`: The species of the organism
  - `cds length (bp)`: Length of the coding sequence in base pairs
  - `GC%`: The percentage of GC content in the genome
  - `ENC`: Effective number of codons
  - `CAI`: Codon Adaptation Index
  - `GC1`, `GC2`, `GC3`: GC content at different codon positions
  
### Key Analysis
- Analyzed the relationship between genomic features, including GC content, using statistical methods.
- Generated neutrality plots to visualize patterns.
- Trained a Random Forest classifier to determine the most important features for classifying species.

## Getting Started

To run the code, clone the repository:

## Install the necessary libraries 
pip install -r requirements.txt


### Project Structure

- `data/`: Contains the dataset (and optionally raw data).
- `notebooks/`: Jupyter notebooks with detailed analysis.
- `src/`: Python scripts for data preprocessing, analysis, and machine learning.
- `README.md`: Project description and instructions.

### Usage

1. Preprocess the data using the `data_preprocessing.py` script.
2. Run the analysis (e.g., GC content and neutrality plots) with `analysis.py`.
3. Train the Random Forest classifier using `feature_importance.py`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
