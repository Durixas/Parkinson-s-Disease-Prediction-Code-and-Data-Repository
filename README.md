# Parkinson's Disease Prediction: Code and Data Repository

This repository contains the code and supplementary data for **"Optimizing Parkinson's Disease Prediction: A Comparative Analysis of Data Aggregation Methods Using Multiple Voice Recordings and an Artificial Intelligence Pipeline"**.

## Contents

### Jupyter Notebooks
1. **`post_agg.ipynb`**:
   - Implements the post-aggregation strategy for handling multiple voice recordings per patient.
   - Includes methods for post-mean, post-min, and post-max aggregation.
   - Covers model training and evaluation using 12 machine learning algorithms.

2. **`pre_agg.ipynb`**:
   - Implements the pre-aggregation strategy, aggregating features of multiple recordings before model training.
   - Covers model training and evaluation using 12 machine learning algorithms.

### Data
- **Model Evaluation Tables**:
  - Stored in the `evaluation_tables` directory in `.csv` format.
  - Each file corresponds to a specific aggregation strategy and includes evaluation metrics such as Accuracy, Precision, Sensitivity, Specificity, F1 Score, AUC, and MCC.

### Figures
- Performance comparison figures from the paper are included in the `figures` directory for easy reference.
  
