# Traffic_Signs_Recognition_machine_learning_project

design machine learning models for a real-world traffic sign recognition application using popular neural network (multi-layer perceptron) and support vector machine models

## Download miniconda

https://docs.conda.io/en/latest/miniconda.html

## Create conda enviroment (2 methods)

1st: `conda create --prefix ./env numpy matplotlib pandas scikit-learn jupyter scikit-image tensorflow`

2nd: `conda env create -f environment.yml`

## Check env

`conda env list`

## Activate conda env (2 methods)

1st: `conda activate ./env`

2nd: `conda activate myenv`

## Go to jupyter

`jupyter notebook`

## Download Data:

https://www.kaggle.com/datasets/flo2607/traffic-signs-classification?resource=download

## Preprocess data | Split the data | Save each dataset to .joblib format

Use `Save_data_to_joblib.ipynb` to step by step achieve this

## Train the models using different algorithms

**Traffic_recognition_MLP.ipynb -> train MLP models using scikit leatn MLPClassifier and Tensorflow

**linear_svc.ipynb/ ploy_svc.ipynb/rbf_svc.ipynb -> train SVC models using different kernels

