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

## Usage
### Training

The model is trained using a Jupyter Notebook in Google Colab.
To train the model, open the notebook and run all cells sequentially until the cell shown below.
<img width="831" height="720" alt="image" src="https://github.com/user-attachments/assets/3c15732d-5ee4-4d71-84cf-cb251fb9cb0f" />


### Inference

To generate predictions, run the last 2 cells to get the predictions.

## Performance Snapshot
<img width="1436" height="55" alt="image" src="https://github.com/user-attachments/assets/409ab539-e976-4ef7-a901-f34e36754862" />





