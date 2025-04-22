# Wildfire Detection with ResNet-50

This project focuses on training the ResNet-50 model to classify images as either "fire" or "no fire" across multiple datasets. The goal is to analyze the generalization capabilities of ResNet-50 when trained on one dataset and tested on the rest, ultimately identifying the dataset that provides the best generalization results.

## Project Objectives

1. Train the ResNet-50 model on each individual dataset.
2. Test the trained model against the remaining datasets.
3. Record and analyze key metrics such as:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
4. Determine the dataset that yields the best generalization performance across all metrics.

## Methodology

- **Model**: ResNet-50 is used as the core architecture for image classification.
- **Datasets**: Multiple datasets are used, each evaluated individually for its generalization capabilities.
- **Training Process**:
  - The model is trained on one dataset at a time using identical hyperparameters (e.g., optimizer, loss function, learning rate).
  - The trained model is then tested on the remaining datasets.
- **Evaluation**:
  - Metrics such as accuracy, precision, recall, and F1 score are calculated for each test scenario.
  - The results are averaged to determine the generalization ability of the dataset.

## Results

Based on the analysis, the dataset that provided the best generalization results was the **FLAME dataset**. Key findings include:
- **Average Testing Accuracy**: 73.23%
- **F1 Score**: 0.82

This indicates that the FLAME dataset is the most suitable for training a ResNet-50 model that generalizes well across other datasets.

## Dataset Access

The datasets used in this project can be accessed via the following link:
[Datasets](https://drive.google.com/drive/u/2/folders/11EFyD1yJwMsaDtoavPTov4q4kkJJFsB1)

## Visual Results

Below are some visual representations of the results:

![Result Graph 1](https://github.com/user-attachments/assets/86a6fead-bb74-46a7-9a0c-0be222ec9920)

![Result Graph 2](https://github.com/user-attachments/assets/e06895f4-51f8-457d-8142-106a8a1ca574)

## Conclusion

The project demonstrates the importance of selecting an appropriate dataset for training deep learning models in image classification tasks. The FLAME dataset emerged as the best option for achieving high generalization performance across multiple datasets.
