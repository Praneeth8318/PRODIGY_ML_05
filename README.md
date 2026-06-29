# PRODIGY_ML_05 - Food Recognition and Calorie Estimation

## Objective
Develop a machine learning model that recognizes food items from images and estimates calorie content.

## Dataset
Food-101 dataset from Kaggle:
https://www.kaggle.com/datasets/dansbecker/food-101

## Technologies Used
- Python
- TensorFlow / Keras
- MobileNetV2
- Jupyter Notebook

## Workflow
1. Downloaded and extracted Food-101 dataset
2. Preprocessed images using ImageDataGenerator
3. Used MobileNetV2 (Transfer Learning)
4. Trained model for food classification
5. Added calorie estimation mapping

## Model
- Base Model: MobileNetV2
- Input Size: 224x224
- Number of Classes: 101
- Optimizer: Adam
- Loss: Categorical Crossentropy

## Sample Output
Food: Pizza  
Calories: 285 kcal

## Note
Full training on CPU takes several hours due to dataset size (101,000 images). Model pipeline and training setup were successfully implemented.
