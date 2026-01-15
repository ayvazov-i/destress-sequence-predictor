# DE-STRESS Sequence-Based Protein Aggregation Prediction

This project predicts **Aggrescan3D total values** (a DE-STRESS feature)
from **protein sequence only**, using:

- **ESM2 protein language model embeddings**
- **XGBoost regression**

## Motivation
3D-structure-based stability metrics are expensive to compute.
This project explores whether **sequence-only embeddings** can recover
aggregation-related properties.

## Methods
- Dataset: DE-STRESS (AF2 structures)
- Input: protein amino acid sequence
- Embeddings: ESM2 (t6_8M_UR50D)
- Model: XGBoost regressor
- Evaluation: R², RMSE

## Results
Best model achieved:
- R² ≈ 0.86
- RMSE ≈ 74

## Running the code
1. Create environment
2. Install requirements
3. Run notebook or Gradio app

## Author
Ibrahim Ayvazov  
University of Edinburgh
