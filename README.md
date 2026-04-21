# Turkish Crisis Sentiment and Urgency Dataset

This repository hosts the manually labeled dataset used in the study:

**“Multi-Task Transformer Architectures for Simultaneous Sentiment and Urgency Classification of Turkish Crisis Communications.”**

The repository includes the manually annotated Turkish earthquake-related tweet dataset used for model training and evaluation.

## Repository Contents

### Manually Labeled Dataset
The file included in this repository contains the manually labeled dataset used for supervised learning experiments in the study.

Annotations include:

- **Sentiment**: Negative, Neutral
- **Urgency**: U0, U1, U2, U3, U4

## Additional Dataset Resource

A separate Kaggle resource is also provided for the cleaned dataset on which the trained model was applied after training:

https://www.kaggle.com/datasets/abdo94ma/scoreddataset
This Kaggle resource is intended as a supplementary data resource and is distinct from the manually labeled training dataset hosted in this repository.

## Dataset Purpose

The manually labeled dataset was prepared for research on Turkish crisis communication following the February 6, 2023 Kahramanmaraş earthquakes. It supports:

- binary sentiment classification
- five-level urgency classification
- multi-task learning experiments
- comparative evaluation of classical, deep learning, and transformer-based models

## Label Definitions

### Sentiment Labels
- **Negative**
- **Neutral**

### Urgency Labels
- **U0**: Informational / non-urgent
- **U1**: Low urgency
- **U2**: Moderate urgency
- **U3**: High urgency
- **U4**: Extreme urgency

## Citation

If you use this dataset, please cite the associated article:

**Abdulrahman Alsamaraie and CAN YÜZKOLLAR.**  
*Multi-Task Transformer Architectures for Simultaneous Sentiment and Urgency Classification of Turkish Crisis Communications.*  
Sakarya University Journal of Computer and Information Sciences.

## Contact

**Abdulrahman Alsamaraie**  
abdulrahman.al-samaraie2@ogr.sakarya.edu.tr
