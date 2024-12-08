# Parkinson's Disease Prediction from Multiple Voice Recordings: Code and Data Repository

This repository contains the code and supplementary data for:

**Optimizing Parkinson's Disease Prediction: A Comparative Analysis of Data Aggregation Methods Using Multiple Voice Recordings via an Automated Artificial Intelligence Pipeline**


**Zhengxiao Yang<sup>1,†</sup>, Hao Zhou<sup>1,†</sup>, Sudesh Srivastav<sup>1</sup>, Jeffrey G. Shaffer<sup>1</sup>, Kuukua E. Abraham<sup>2</sup>, Samuel M. Naandam<sup>3</sup>, Samuel Kakraba<sup>1,4</sup>**

1 Department of Biostatistics and Data Science, Tulane Celia Scott Weatherhead School of Public Health and Tropical Medicine, Tulane University, New Orleans, LA 70112, USA  
2 Minnesota State University, Mankato, MN 60001, USA  
3 Department of Mathematics, University of Cape Coast, Ghana  
4 Tulane Center for Aging, School of Medicine, Tulane University, New Orleans, LA 70112, USA  
† These authors contributed equally to this work.  
• Correspondence: [skakraba@tulane.edu](mailto:skakraba@tulane.edu) (S.K) 

Preprint: [DOI:10.20944/preprints202412.0366.v1](https://doi.org/10.20944/preprints202412.0366.v1)

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
1. **Original Dataset**:
   - The dataset used in this study is obtained from the UCI Machine Learning Repository: [Parkinson's Disease Classification Dataset](https://archive.ics.uci.edu/dataset/470/parkinson+s+disease+classification).
   - Stored in the `data/original` directory.

2. **Model Evaluation Tables**:
   - Stored in the `data/evaluation_tables` directory in `.csv` format.
   - Each file corresponds to a specific aggregation strategy and includes evaluation metrics such as Accuracy, Precision, Sensitivity, Specificity, F1 Score, AUC, and MCC.

### Figures
- Performance comparison figures from the paper are included in the `figures` directory for easy reference.
  
