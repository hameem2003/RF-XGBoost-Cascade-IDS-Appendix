# RF-XGBoost-Cascade-IDS-Appendix
The supplementary materials used in this research are available in an online repository to support transparency and reproducibility. The repository contains the implementation code, trained models, SHAP feature ranking, performance evaluation results, and visualization outputs used in this study.


Contents:
- Final notebook
- Trained models
- SHAP feature ranking
- Confusion matrices
- Final evaluation results

Dataset:
CICIoT2023 (Official Dataset)

                  Start
                    │
                    ▼
        Incoming Network Flow
                    │
                    ▼
         Feature Extraction (39)
                    │
                    ▼
         Data Preprocessing
     • Missing value handling
     • Label encoding
                    │
                    ▼
     SHAP Feature Selection
      Select Top-25 Features
                    │
                    ▼
      Random Forest Classifier
       (Binary Classification)
                    │
          ┌─────────┴─────────┐
          │                   │
          ▼                   ▼
      Benign             Attack
          │                   │
          │            XGBoost Classifier
          │          (33 Attack Classes)
          │                   │
          ▼                   ▼
    Benign_Final      Predicted Attack Type
          └───────────┬───────────┘
                      ▼
         Final Detection Result
                      │
                      ▼
      Performance Evaluation
 (Accuracy, Precision, Recall,
   F1-score, Confusion Matrix,
      ROC-AUC, SHAP Analysis)
                      │
                      ▼
                     End
This repository contains the supplementary materials for the undergraduate thesis.


