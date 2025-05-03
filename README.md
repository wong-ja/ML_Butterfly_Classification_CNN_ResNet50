# Butterfly Species Classification Using Transfer Learning with ResNet50

## Project & Overview

Human intervention in the decline of butterfly species populations may be necessary in the near future. The automation of butterfly identification and classification can aid in scientific research and biodiversity conservation workflows. 

Read the [Final Report](docs/report.pdf) or view the [Project Presentation](docs/447-present).


## Technologies 

- Python 3.13.1, Jupyter Notebooks
- NumPy
- Pandas
- Pillow (PIL)
- PyTorch and Torchvision
- TQDM
- Scikit-learn
- Matplotlib
- Seaborn 


## Installation & Usage

1. <b>Butterfly Image Classification Dataset (Version 2)</b>: [https://www.kaggle.com/datasets/phucthaiv02/butterfly-image-classification/data](https://www.kaggle.com/datasets/phucthaiv02/butterfly-image-classification/data) 

2. <b>[Final_ML_Butterfly_Classification.ipynb](notebooks/Final_ML_Butterfly_Classification.ipynb)</b>

## 

Expected file structure (after downloading dataset):
```
project
|
|-- butterfly-image-classification.zip
|-- butterfly-image-classification/
|---- test/
|------ Image_1.jpg
|------ ...
|---- train/
|------ Image_1.jpg
|------ ...
|---- Testing_set.csv
|---- Training_set.csv
|-- Final_ML_Butterfly_Classification.ipynb
|
```

Run All: `Final_ML_Butterfly_Classification.ipynb`

Expected file structure (after running code):
```
project
|
|-- butterfly-image-classification.zip
|-- butterfly-image-classification/
|---- test/
|------ Image_1.jpg
|------ ...
|---- train/
|------ ADONIS/
|-------- Image_2.jpg
|-------- ...
|------ ...
|---- val/
|------ ADONIS/
|-------- Image_2.jpg
|-------- ...
|------ ...
|---- Testing_set.csv
|---- Training_set.csv
|-- Final_ML_Butterfly_Classification.ipynb
|-- butterfly_cnn.pth
|
```

# 
