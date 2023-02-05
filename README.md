# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:

### The purpose of this analysis is well defined (4 pt)
The purpose of this analysis  is to evaluate different techniques to train and evaluate models with unblanaced classes. Also, after the evaluation of the models are complete we will decided whether they should be used to predict credit risk. 
## Results:

### There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)
![image](https://user-images.githubusercontent.com/110268006/216801157-61fe5386-3443-4cd9-9b14-1ce31fb1665c.png)
* Native Randome Oversampling: The balanced accuracy score is 67.42% and the precision score was 99% and the recall is 61%.

![image](https://user-images.githubusercontent.com/110268006/216801174-79432fd9-aadf-4697-b9e2-297647b30758.png)
* SMOTE Oversampling: The balanced accuracy score is 66.23% and the precision score was 99% and the recall is 69%.

![image](https://user-images.githubusercontent.com/110268006/216801232-b38984b8-b19d-44a4-b7f6-b1e4dac5d86d.png)
* Undersampling: The balanced accuracy score is 54.47% and the precision score was 99% and the recall is 40%.

![image](https://user-images.githubusercontent.com/110268006/216801275-18f4bd24-a43d-4c2a-b268-a2adf3764d05.png)
* Combination (Over and Under) Sampling: The balanced accuracy score is 63.11% aand the precision score was 99% and the recall is 60%.

![image](https://user-images.githubusercontent.com/110268006/216801310-6b3265d3-ed6a-4164-b001-e009dfab6650.png)
* Balanced Random Forest Classifier: The balanced accuracy score is 78.43% and the precision score was 99% and the recall is 94%.

![image](https://user-images.githubusercontent.com/110268006/216801346-a64422d9-74e1-4ef4-90f8-b3c1aa1c50cd.png)
* Easy Ensemble AdaBoost Classifier: The balanced accuracy score is 93.16% and the precision score was 99% and the recall is 94%.

## Summary:

### There is a summary of the results (2 pt)
There were six models evaluated and they all had similar precsions scores but the easy ensemble had a higher recall and accuracy compared ot the other models

### There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
I recommend using the easy ensemble model because it has the highest accuracy score and the better precision and recall then the other models. 
