# Image-Super-Resolution-SRGAN
  A Tensorflow Implementation of Ocular Disease Recognition of Normal, Cataract, Glaucoma and Hypertension.
 
## Requirements
### Python
Python version used Python 3.10.6
### Python Libraries
- Tensorflow
```
pip install tensorflow==2.6.4
```
- opencv
```
pip install opencv-python
```
- tqdm
```
pip install tqdm
```
- Pillow
```
pip install Pillow
```
- imblearn
```
pip install imbalanced-learn
```

## Datasets

### Dataset
The data used to developed the model is taken from https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k.
The dataset consists of 



## Repository Tree Structure
``` 
|   .gitattributes
|   ocular_224x224.py
|   ocular_pseudo.py
|   ocular_512x512.py
|   README.md
```

## Files

- `ocular_224x224.py` :- In this file, different models performance is compared by training on image file shape of 224x224. Later, upsampling and downsampling performance is observed on best model.
- `ocular_pseudo.py` :-  In this file, pseudo labeling was on 193 images using EfficientNetB0 model.
- `ocular_512x512.py` :- In this file, different models performance is compared by training on image file shape of 512x512. Later, downsampling performance is observed on best model.




## Usage
The notebooks are created and run on kaggle website.
Connect the following datasets to the notebook:
https://www.kaggle.com/datasets/ferroxrocks/file-name-and-its-class-idx
https://www.kaggle.com/datasets/ferroxrocks/ml-project-correct-dataset
https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k
https://www.kaggle.com/datasets/ferroxrocks/ocular-final-csv

Accelerator used GPU P100
