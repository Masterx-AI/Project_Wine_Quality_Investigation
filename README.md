# AI/ML Project - Wine Quality Investigation

<p align="center"><img src="https://user-images.githubusercontent.com/54996245/143786908-603d045d-62ba-475a-b3ae-8e629dc8bedc.jpg" style="width: 1000px;"/></p>

### Description:

This datasets is related to red variants of the Portuguese "Vinho Verde" wine.The dataset describes the amount of various chemicals present in wine and their effect on it's quality. The datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones).Your task is to predict the quality of wine using the given data.

A simple yet challenging project, to anticipate the quality of wine.
The complexity arises due to the fact that the dataset has fewer samples, & is highly imbalanced.
Can you overcome these obstacles & build a good predictive model to classify them?

**This data frame contains the following columns:**

Input variables (based on physicochemical tests):\
1 - fixed acidity\
2 - volatile acidity\
3 - citric acid\
4 - residual sugar\
5 - chlorides\
6 - free sulfur dioxide\
7 - total sulfur dioxide\
8 - density\
9 - pH\
10 - sulphates\
11 - alcohol\
Output variable (based on sensory data):\
12 - quality (score between 0 and 10)

### Acknowledgements:
This dataset is also available from the UCI machine learning repository, https://archive.ics.uci.edu/ml/datasets/wine+quality.

### Objective:
- Understand the Dataset & cleanup (if required).
- Build classification model to predict the quality of red wine.
- Also fine-tune the hyperparameters & compare the evaluation metrics of vaious classification algorithms.

### <center> Stractegic Plan of Action:
**We aim to solve the problem statement by creating a plan of action, Here are some of the necessary steps:**
1. Data Exploration
2. Exploratory Data Analysis (EDA)
3. Data Pre-processing
4. Data Manipulation
5. Feature Selection/Extraction
6. Predictive Modelling
7. Project Outcomes & Conclusion

### Some Visuals of the Project:

**1. Target Variable Distribution**
  
<p align="left"><img src="https://user-images.githubusercontent.com/54996245/143787073-c60c2af7-4667-4d1a-bb0d-3cd2f9733ab7.png" /></p>

**2. Categorical Feature-set Distribution**

**3. Numerical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/143787108-15bc28d1-2e9e-4f4b-91b2-ba4ba3e22613.png)
![image](https://user-images.githubusercontent.com/54996245/143787117-e9481078-dab3-4901-a3a8-cfc7679cfec0.png)

**4. Relationship between the Feature-set**

![image](https://user-images.githubusercontent.com/54996245/143787139-e95e0052-3594-47ae-92fe-8dba58fd6973.png)

**5. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/143787224-6c860e28-5a0d-49fa-9a3c-087984a540aa.png)

**6. Correlation plot for features**

![image](https://user-images.githubusercontent.com/54996245/143787226-8c85b7aa-8270-423c-8d49-210d3df7112a.png)

**7. VIF & RFE Scores**
  
![image](https://user-images.githubusercontent.com/54996245/142758428-43ac9454-da02-4299-9983-8e21fb2d705e.png)
![image](https://user-images.githubusercontent.com/54996245/143787249-48058f75-5fc2-4ea8-b072-3cda27f99d9c.png)

  
**8. ROC Plots**

![image](https://user-images.githubusercontent.com/54996245/143787267-cb444f17-bfbc-4604-b12f-236758ec80f9.png)

**9. Tree Plot & Feature Importance in Random Forest
![image](https://user-images.githubusercontent.com/54996245/143787304-f79f29fe-48a3-4fc1-b2f2-115de421e484.png)
![image](https://user-images.githubusercontent.com/54996245/143787311-3445e102-55df-45e1-8139-52964dd5f683.png)
  
**10. ML Algorithm's Scores for the Dataset**
  
![image](https://user-images.githubusercontent.com/54996245/142758050-7ac78f20-47f5-4c1c-b1e4-25df8b572da3.png)
![image](https://user-images.githubusercontent.com/54996245/142758046-3a9d358a-7dc3-4595-b64e-0c95ba4eaf56.png)

  
### Here are some of the key outcomes of the project:
- The Dataset was small totally around 1338 samples & after preprocessing 1.3% of the datasamples were dropped. 
- The samples were highly imbalanced, hence SMOTE Technique was applied on the data to  balance the classes, adding 59% more samples to the dataset.
- Visualising the distribution of data & their relationships, helped us to get some insights on the relationship between the featureset.
- Feature Selection/Eliminination was carried out and appropriate features were shortlisted.
- Testing multiple algorithms with fine-tuning hyperparamters gave us some understanding on the model performance for various algorithms on this specific dataset.
- The boosting & ensemble algorithms perform the best on the current dataset, followed by Nearest Neighbours Algorithm.
- Yet it wise to also consider simpler model like Logistic Regression as it is more generalisable & is computationally less expensive.

