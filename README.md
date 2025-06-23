This repository contains the code and supplementary materials for the research paper:

"**Improving Bean Disease Classification with Stepwise Fine-tuning of CNN-based Transfer Learning Model**"

**Affiliation(s):** [Batangas State University]

## Overview

The study presents a structured transfer learning approach combining model comparison and progressive fine-tuning to classify bean leaf diseases with high accuracy. We evaluated five pre-trained CNN architectures (VGG16, ResNet50, DenseNet121, EfficientNetB0, MobileNetV2) and implemented a stepwise fine-tuning strategy on ResNet50, which achieved a test accuracy of 98.86% on a combined bean disease dataset.

## Repository Contents

*   `revised-bean-disease-classification-finetuning.ipynb`: The main Jupyter notebook containing all the Python code for data loading, preprocessing, model benchmarking, stepwise fine-tuning, evaluation, and visualization.

## Running the Code

This notebook is designed to be easily run on Kaggle, providing a convenient cloud-based environment with necessary libraries pre-installed and dataset access configured. **Kaggle also offers free access to GPUs, which are highly recommended for significantly faster training of deep learning models like the ones used in this project.**

[![kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/theinkyawlwin/revised-bean-disease-classification-finetuning)
[![colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tklwin/bean-disease-classification-finetuning/blob/main/revised-bean-disease-classification-finetuning.ipynb)
[![code](https://badges.aleen42.com/src/github.svg)](https://github.com/tklwin/bean-disease-classification-finetuning)

## Dataset

We used [integrated version](https://github.com/tklwin/bean-disease-classification-finetuning/tree/main/new_bean_dataset) of following datasets:
- iBean dataset: https://github.com/AI-Lab-Makerere/ibean/
- Bangladesh Bean Leaf Dataset: https://data.mendeley.com/datasets/ykvcrjffzd/1
