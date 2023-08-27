# Iris Classification
Experimenting with various algorithms on the famous Iris Dataset ✨

## Dataset
### Columns
* Sepal Length
* Sepal Width
* Petal Length
* Petal Width
* target ( Species )

## EDA through Visualisations

### Distribution of the data (After applying Principal Component Analysis)
![image](https://github.com/abdulhakkeempa/iris-classification/assets/92361680/80c1cf6d-67cf-4458-b221-f5927bc12816)


### Correlation Matrix
![image](https://github.com/abdulhakkeempa/iris-classification/assets/92361680/e9f8f13e-dfc0-4f20-a51a-aba8e03d445a)

### Data Distribution using Histrogram & Outlier Detection using Box Plot
#### The sepal length and sepal width have a negative skew, indicating they have more values towards the left side of the plot and it's mean would be less that its median and mode

* Sepal Length
  ![image](https://github.com/abdulhakkeempa/iris-classification/assets/92361680/b1d3df67-6f2a-4a9e-8646-0fbc7b44da90)
* Sepal Width - This column contains a few outliers
  ![image](https://github.com/abdulhakkeempa/iris-classification/assets/92361680/d0513746-2387-4546-be60-78b44c473cfc)
#### The petal length and petal width have a positive skew, indicating they have more values towards the right side of the plot and it's mean would be greater that its median and mode
* Petal Length
![image](https://github.com/abdulhakkeempa/iris-classification/assets/92361680/f523cc0d-e878-44fa-a692-7c4aad332233)
* Petal Width
  ![image](https://github.com/abdulhakkeempa/iris-classification/assets/92361680/ed7c16de-cfcb-420b-bd3c-f504a5f39a71)
* target ( Species )
  ![image](https://github.com/abdulhakkeempa/iris-classification/assets/92361680/972a8c40-3a90-4cae-889d-154126fe9f87)

## Models
| Algorithm  | Train Score | Test Score |
| ------------- | ------------- | ------------- |
| Logistic Regression  | 0.97  | 0.96 |
| Support Vector Machine (linear)  | 0.983  | 1.00 |
| K-Nearest Neighbours (k=5)  | 0.966  | 1.00 |
