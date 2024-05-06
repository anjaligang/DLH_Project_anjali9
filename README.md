# Video Presentation

Click [here](https://youtu.be/wvt74wxUmr8?si=DycmLcN6Hq8_aWlS) to watch the project presentation.

## Introduction

This paper introduces several convolutional neural network (CNN) models for accurate prediction of cancer types based on gene expression data from The Cancer Genome Atlas (TCGA).

**Main Contributions:**
- Proposing three novel CNN architectures (1D-CNN, 2D-Vanilla-CNN, and 2D-Hybrid-CNN) tailored for processing unstructured gene expression data.
- Incorporating normal tissue samples during training to account for the influence of tissue-of-origin.
- Developing a unique interpretation scheme based on guided saliency maps to identify important marker genes for each cancer type.
- Identifying a total of 2090 marker genes across 33 cancer types and normal samples.
- Demonstrating applicability by achieving 88.42% accuracy in predicting breast cancer subtypes using the 1D-CNN architecture.

## Discussion

### Implications of Experimental Results

**1D-CNN Model Effectiveness:**
- Demonstrated good performance aligning with the original paper's findings, suggesting promise for developing robust cancer diagnosis tools.
  
**Generalizability and Robustness:**
- Evidence for model's generalizability and robustness across different data splits, crucial for ensuring performance consistency.
  
**Potential for Improvement:**
- Room for further enhancement by exploring different CNN architectures, feature selection methods, and hyperparameter optimization strategies.

### Reproducibility of the Original Paper

**Partial Reproducibility:**
- Achieved good performance aligning with the main findings of the original paper.

**Discrepancies in Accuracy:**
- Attributed to factors like data preprocessing, hyperparameter tuning, and software versions.
  
**Factors Affecting Reproducibility:**
- Insufficient detail on data preprocessing steps and limited data accessibility posed challenges.

### Recommendations for Improvement

- **Detailed Methodology:** Provide comprehensive description of data preprocessing and feature selection.
- **Data Availability:** Share processed data or provide clear instructions on obtaining and preprocessing data.

By following these recommendations, researchers can contribute to greater reproducibility and transparency in scientific research, facilitating further progress and collaboration in cancer classification using deep learning.

