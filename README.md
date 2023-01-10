#Tutorial Modeling Data Titanic

Tutorial ini akan mengolah data titanic menjadi data yang siap untuk dilakukan pemodelan

## Prerequisite

1. Download data [here](https://www.kaggle.com/datasets/azeembootwala/titanic)
2. Instalasi dengan `pip install requirement.txt`

## Getting Started
- Dataset Splitting
- Training
- Model Validation

### Dataset Splitting

split data into training , validation and test sets
``` Code
X_train,y_train,X_test, y_test = dataset_splitting()
X_train.shape, y_train.shape

## References
1. Di scikit-learn documentain