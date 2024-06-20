# Skin Sight App Machine Learning


## Dataset

we collect our dataset from Roboflow [Public Dataset 1](https://universe.roboflow.com/parin-kittipongdaja-vwmn3/skin-problem-multilabel) and [Public Dataset 2](https://universe.roboflow.com/test-itme1/redness-7qf1p). Then, we input the dataset into [Kaggle Skin Sight](https://www.kaggle.com/datasets/tessaagitha/skinsightapp) so that it can be processed.


## Requirements and Notebook

- kaggle
- random
- shutil
- cv2
- os
- TensorFlow
- matplotlib
- sklearn
- NumPy

You can access the Notebook [here](https://colab.research.google.com/drive/1IgC8B7l2GGIBd5Btma7JNjMrQgUlVxv7?usp=sharing).


## Model

We use CNN Pre-trained model MobileNetV2 as base model and add custom classification layer on the top of the base model.

![Screenshot 2024-06-21 020825](https://github.com/SkinSightApp/SKinSIght-ML/assets/80873008/39fa4111-6d44-44cc-a8ab-5b6fb15679ee)

![download](https://github.com/SkinSightApp/SKinSIght-ML/assets/80873008/442065fe-b691-4901-8e5e-c46fea6bf175)

Accuracy curve shows gradual improvement, reaching 97% and Loss curve decreases, indicating enhanced predictive capability.
