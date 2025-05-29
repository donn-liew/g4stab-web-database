# G4STAB Web Database

A web-based database providing melting temperature predictions for experimentally validated G-quadruplex (G4) sequences using the G4STAB deep learning model.

## About

This database contains G4 stability predictions across four physiologically relevant ionic conditions. The database contains 1,566,008 G4 sequences with genomic annotations including:

- Chromosome location and strand information
- Gene association and gene type classification  
- Conservation scores (phastCons and phyloP)
- Predicted melting temperatures (Tm) with standard error measurements
- Stability predictions under normal and cancer-like ionic environments

## Features

- **Motif Search**: Search for specific DNA motifs within G4 sequences
- **Multi-condition Analysis**: Compare stability across four ionic conditions (high K$^+$, moderate K+, Na+-only, cancer-like)
- **Interactive Results**: Customizable table view with column visibility controls
- **Genomic Context**: Full genomic annotations for biological relevance
- **Confidence Intervals**: Standard error measurements for all predictions

## Ionic Conditions

1. High potassium (100 mM K+, 0 mM Na+)
2. Moderate potassium (50 mM K+, 0 mM Na+) 
3. Sodium-only (0 mM K+, 100 mM Na+)
4. Cancer-like (70 mM K+, 30 mM Na+)

## Citation
