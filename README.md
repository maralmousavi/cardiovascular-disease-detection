# Cardiovascular Disease Detection

Implementing several machine learning approaches to detect the presence of cardiovascular disease.

* Deep Neural Network
* Logistic Regression
* Random Forest Classifier 
* Histogram-based Gradient Boosting Classifier
* Support Vector Machine
* Gaussian Naive Bayes
* XGBoost Classifier

# Results
Results of implemented machine learning methods:   
* Deep Neural Network:  73.01
* Logistic Regression - 71.99
* Random Forest Classifier - 73.69 
* Histogram-based Gradient Boosting Classifier - 73.68
* Support Vector Machine - 72.95
* Gaussian Naive Bayes - 59.44
* XGBoost Classifier - 73.89

# Dataset description
[The cardiovascular disease dataset](https://www.kaggle.com/sulianova/cardiovascular-disease-dataset) is an open-source dataset found on Kaggle. The dataset consists of 70,000 patient records and also contains 11 features.

Data description:
There are 3 types of input features:

Objective: factual information;
Examination: results of medical examination;
Subjective: information given by the patient.
Features:

* Age | Objective Feature | age | int (days)
* Height | Objective Feature | height | int (cm) |
* Weight | Objective Feature | weight | float (kg) |
* Gender | Objective Feature | gender | categorical code |
* Systolic blood pressure | Examination Feature | ap_hi | int |
* Diastolic blood pressure | Examination Feature | ap_lo | int |
* Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |
* Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
* Smoking | Subjective Feature | smoke | binary |
* Alcohol intake | Subjective Feature | alco | binary |
* Physical activity | Subjective Feature | active | binary |
* Presence or absence of cardiovascular disease | Target Variable | cardio | binary |

All of the dataset values were collected at the moment of medical examination.

### Acuracy Machine Learning Methods
![Graph](https://github.com/maralmousavi/cardiovascular-disease-detection/raw/master/images/accuracy-algorithms.png)

### Feature Importance
![Graph](https://github.com/maralmousavi/cardiovascular-disease-detection/raw/master/images/Feature-Importance.png)

#### Model DNN Summary
![Graph](https://github.com/maralmousavi/cardiovascular-disease-detection/raw/master/images/Model-Summary.png)

#### Model DNN Accuracy-Accuracy Plot
![Graph](https://github.com/maralmousavi/cardiovascular-disease-detection/raw/master/images/Model-Accuracy.png)

#### Model DNN Accuracy-Loss Plot
![Graph](https://github.com/maralmousavi/cardiovascular-disease-detection/raw/master/images/Model-Loss.png)

#### Precision-Recall Plot
![Graph](https://github.com/maralmousavi/cardiovascular-disease-detection/raw/master/images/Precision-Recall.png)

#### ROC-Curve Plot
![Graph](https://github.com/maralmousavi/cardiovascular-disease-detection/raw/master/images/ROC-Curve.png)

#### F1-score--Precision
![Graph](https://github.com/maralmousavi/cardiovascular-disease-detection/raw/master/images/F1-score--Precision.png)

#### Recall-Specificity
![Graph](https://github.com/maralmousavi/cardiovascular-disease-detection/raw/master/images/Recall-Specificity.png)

#### Graph of the Deep Neural Network
![Graph](https://github.com/maralmousavi/cardiovascular-disease-detection/raw/master/images/graph-deep-neural-network.png)
 
## Collaborators
- [Taher Fattahi](https://www.github.com/taherfattahi)

## License
[MIT](https://choosealicense.com/licenses/mit/)
