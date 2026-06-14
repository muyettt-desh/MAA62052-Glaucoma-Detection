# MAA62052 — Glaucoma Detection using CNN
Group Assignment | Session 2025/2026-2

## Dataset
Hillel Yaffe Glaucoma Dataset (HYGD) — PhysioNet
https://physionet.org/content/hillel-yaffe-glaucoma-dataset/1.0.0/

## Requirements
pip install torch torchvision scikit-learn matplotlib seaborn pandas numpy pillow

## How to Run
1. Open `MAA62052_GroupID_CNN_HYGD.ipynb` in Google Colab or Kaggle Notebook
2. Run Cell 1 to prepare the dataset
3. Run All cells sequentially from top to bottom
4. Final results appear after `run_full_pipeline()` completes in the last cell

## Models
- **GlaucomaBaseCNN** — Custom CNN baseline (ignores quality scores)
- **GlaucomaQualityCNN** — Quality-Aware CNN using Strategy C (auxiliary quality input)

## Output Files
- `confusion_matrices.png`
- `roc_curves.png`
- `training_curves.png`
- `comparison_table.csv`
- `error_analysis_Baseline_CNN.png`
- `error_analysis_Quality-Aware_CNN.png`

## Reference
Abramovich, O., Pizem, H., Fhima, J., Berkowitz, E., Gofrit, B., Van Eijgen, J., 
Blumenthal, E., & Behar, J. (2025). Hillel Yaffe Glaucoma Dataset (HYGD): 
A Gold-Standard Annotated Fundus Dataset for Glaucoma Detection (Version 1.0.0). 
PhysioNet. https://doi.org/10.13026/z0ak-km33
