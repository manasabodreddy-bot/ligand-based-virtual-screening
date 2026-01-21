# Ligand-Based Virtual Screening & Compound Prioritization

## Overview
This project demonstrates a ligand-based virtual screening workflow designed to support early-stage drug discovery teams. The focus is on transparent, rule-based compound prioritization using molecular properties rather than predictive modeling.

## Workflow
- Input compound dataset (SMILES format)
- SMILES validation using RDKit
- Calculation of key molecular descriptors (MW, LogP, HBD, HBA, TPSA)
- Rule-based filtering using Lipinski-style criteria
- Simple scoring and ranking for compound prioritization
- Visualization of key physicochemical properties

## Tools
- Python
- RDKit
- pandas
- matplotlib

## Output
- Ranked compound list (CSV)
- Property distribution plots
- Interpretable prioritization logic suitable for screening support

## Use Case
The workflow mirrors typical ligand-based screening support tasks in CRO and pharma discovery environments, emphasizing clarity, reproducibility, and decision support.
