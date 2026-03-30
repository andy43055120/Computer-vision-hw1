# NYCU Computer Vision 2026 HW1
- Student ID: 111550148
- Name: 陳冠達

## Introduction
This task aims to perform image classification over 100 categories.
My core idea is to train the model – ResNeXt-101 with the pretrained weights and fine-tune it and perform model ensembling.

## Environment Setup
This project is developed and executed using Google Colab.
Most required libraries are pre-installed in Colab. If additional dependencies are needed, they can be installed using:
```bash
!pip install -r requirements.txt
```
To access the dataset and saved models, Google Drive is mounted:
```python
from google.colab import drive
drive.mount('/content/drive')
```
