# ML_WaferDefect
A machine learning project on wafer defect classification.

### About the Dataset
The dataset used to train the models on wafer defects was sourced from the study: "Deformable Convolutional Networks for Efficient Mixed-Type Wafer Defect Pattern Recognition." It was obtained through [Kaggle](https://www.kaggle.com/datasets/co1d7era/mixedtype-wafer-defect-datasets) in the form of a .npz file. Unfortunately, the dataset is too big for me to upload. To add, more details regarding the dataset including the work of the study can be found [here](https://github.com/Junliangwangdhu/WaferMap). Other info can also be found in the [E.pdf](E.pdf) file.

### About the Models
This project used three models. Two are classical machine learning algorithms, specifically XGBoost and Random Forest, and the other is a Convolutional Neural Network model. Both classical models used Bayesian Search for their hyperparameter optimization. 
- [RandomForest.ipynb](RandomForest.ipynb) - Random Forest Model
- [XGBoost.ipynb](XGBoost.ipynb) - XGBoost Model
- [CNN.ipynb](CNN.ipynb) - Convolutional Neural Network Model
