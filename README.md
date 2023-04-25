# Credit_Risk_Analysis
## 1. Overview of the analysis: 
•	Explain how a machine learning algorithm is used in data analytics.<br>
•	Create training and test groups from a given data set.<br>
•	Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.<br>
•	Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.<br>
•	Compare the advantages and disadvantages of each supervised learning algorithm.<br>
•	Determine which supervised learning algorithm is best used for a given data set or scenario.<br>
•	Use ensemble and resampling techniques to improve model performance.<br>


## 2. Results: 
- Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. 
#### Naive Random Oversampling
![image](https://user-images.githubusercontent.com/120526544/233904735-13021e7b-979f-4476-bffc-7a215538e342.png)
![image](https://user-images.githubusercontent.com/120526544/233904749-2fe859c5-4bed-46be-aa67-bde28df5c22a.png)

#### SMOTE Oversampling:
 ![image](https://user-images.githubusercontent.com/120526544/233904766-663a42bd-fd0f-40d1-9ec6-fc939b27064f.png)

![image](https://user-images.githubusercontent.com/120526544/233904774-6add733d-c00a-4639-9569-4e274af42308.png)
 
#### Undersampling:
 ![image](https://user-images.githubusercontent.com/120526544/233904795-86c309f9-91c0-4512-aca3-b662cce49544.png)

 ![image](https://user-images.githubusercontent.com/120526544/233904806-1606673e-c0b2-4284-a56e-6c79d5d2bc3d.png)


#### Combination (Over and Under) Sampling
 ![image](https://user-images.githubusercontent.com/120526544/233904830-6ce96d96-54d5-4f92-a10c-7ce98b8d2df0.png)
![image](https://user-images.githubusercontent.com/120526544/233904861-94cf806b-2068-44e6-9a5e-6707a6e7f819.png)

 
#### Balanced Random Forest Classifier
 ![image](https://user-images.githubusercontent.com/120526544/233904887-80ad8624-c353-4ea7-9f69-df98c6b646c3.png)

 ![image](https://user-images.githubusercontent.com/120526544/233904903-930a9b31-6330-441a-a805-6332961b9919.png)

#### Easy Ensemble AdaBoost Classifier 
 ![image](https://user-images.githubusercontent.com/120526544/233904917-2732cbb2-d85c-4b0f-87a2-da6338b49625.png)
![image](https://user-images.githubusercontent.com/120526544/233904926-5ebeae26-bceb-4c7c-950b-31e6b3aaccfa.png)





## 3.Summary: 
- In this analysis, there were six different machine learning models were used to predict credit risk for loan applicants. The models used were Naïve Random, SMOTE, Undersampling, Easy Ensemble AdaBoost Classifier, Combination over and under sampling and Balanced Random Forest Classifier model. The Easy Ensemble AdaBoost Classifier model had the highest balances accuracy score of around .93. The precision scores for high risk were low among all the models ranging from 0.01 and 0.08, whereas the recall scores for low risk were low ranging from 0.40 and 0.94 <br>
By looking at the models, the Easy Ensemble AdaBoost Classifier models is good to use because, it had the highest balanced accuracy score and highest recall score for the low risk. This indicates that the risk is identified accurately with high risk loan applicants which give more confidence with their predictions. 
