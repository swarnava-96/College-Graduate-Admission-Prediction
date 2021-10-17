# College-Graduate-Admission-Prediction
### Goal: The goal of this project is to predict Graduate Admissions from an Indian perspective.

### About the data set: 
The data set is downloaded from [Kaggle](https://www.kaggle.com/mohansacharya/graduate-admissions).
The dataset contains several parameters which are considered important during the application for Masters Programs.
The parameters included are :

1. GRE Scores ( out of 340 )
2. TOEFL Scores ( out of 120 )
3. University Rating ( out of 5 )
4. Statement of Purpose and Letter of Recommendation Strength ( out of 5 )
5. Undergraduate GPA ( out of 10 )
6. Research Experience ( either 0 or 1 )
7. Chance of Admit ( ranging from 0 to 1 )

### Project Description:
1. After loading the data set, data pre-processing was performed. Data pre-processing steps included, checking for null values, 
removing unwanted features, feature scaling, dividing into independent and dependent features and finally train test split.

2. Then, a two layer neural network ANN model was built from scratch for this regression problem statement and trained for 10 epochs.
I have tried multiple models just to increase the performance of the model. Model was evaluated on the basis of R2 score.
Finally, a plot showing loss vs validation loss was plotted as shown below:
 
![image](https://user-images.githubusercontent.com/75041273/137596356-cc961c30-4e1c-4813-a534-6a25c1ca6e67.png)

Kaggle Kernel: https://www.kaggle.com/swarnavamukherjee/college-graduate-admission-using-ann
