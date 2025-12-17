# PM1-phage-depolymerase-analysis
Bioinformatics pipeline for depolymerase prediction in Proteus mirabilis phage vB_PmiA_PM1
# PM1 Phage Depolymerase Analysis

## Project Overview
Bioinformatics pipeline for predicting depolymerase candidates in *Proteus mirabilis* phage vB_PmiA_PM1 (GenBank: PQ065999).

## Methods
1. Gene prediction using Prodigal
2. Signal peptide analysis
3. Hydrophobicity profiling (Kyte-Doolittle)
4. Motif screening (acidic/aromatic pairs)
5. Confidence scoring system

## Requirements
- Python 3.9+
- Biopython
- pandas, numpy
- scikit-learn

## Usage
```bash
# Clone repository
git clone https://github.com/yourusername/PM1-phage-depolymerase-analysis.git

# Install dependencies
pip install -r requirements.txt

# Run analysis
python scripts/complete_pipeline.py
