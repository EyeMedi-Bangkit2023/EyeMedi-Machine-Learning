# The machine learning part required by the EyeMedi application

<p align="center" ><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ab/TensorFlow_logo.svg/512px-TensorFlow_logo.svg.png?20211220215155" width="325"/> </p>

## Reference dataset:

-   https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification
-   https://www.kaggle.com/code/texasdave/classifying-eye-disease-in-ocular-images/input

## Object label to be detected and classified

1. Cataract
2. Diabetic Retinopathy
3. Glaucoma
4. Normal

## Library

```text
sklearn 
pandas
tensorflow
numpy
matplotlib
```

## Steps to Create a Model

1. Looking for references dataset
2. labeling each data
3. converts each image to RGB
4. Divide the data in a ratio of 80% (train), 10% (validation) and 10% (test)
5. Augmenting image data and Tuning hyperparameter
6. Conduct machine learning model training experiments with 10,000 to 20,000 train steps
7. Evaluate the machine learning model 
8. Testing real data using another image
11. Save the model with format h5
12. Deploy the model 

## Model Evaluation

<p align="center" ><img src="https://github.com/EyeMedi-Bangkit2023/EyeMedi-Machine-Learning/blob/main/accuracy.png" width="500"/> </p>
<p align="center" ><img src="https://github.com/EyeMedi-Bangkit2023/EyeMedi-Machine-Learning/blob/main/loss.png" width="500"/> </p>
<p align="center" ><img src="https://github.com/EyeMedi-Bangkit2023/EyeMedi-Machine-Learning/blob/main/confussion-matrix.png" width="500"/> </p>



