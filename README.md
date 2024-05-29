# Credit Risk Crystal Ball: Predicting Risk with Machine Learning
### Overview and Business Understanding

Credit risk prediction is a crucial process for financial institutions, aiming to asses the likehood of a borrower defaulting on a loan. That way the people not likely to default can more easily access loans with better
conditions, while the institutions reduce the risk of finantial loss.
There are many techniques to predict credit risk, but Machine Learning (ML) can be used to automate the prediction process, since it learns the patterns associated with a defaulter profile and its use reduces time and resource consumption.
Detecting people with a high risk profile can be a complex task, but still results in a better profit margin for the institution. Also, ML improves the efficiency of the process, and the institution resources can be now used in other areas that require human supervision.

Our team at Deloitte seeks to use different machine learning models to predict the credit risk for different profiles, test them and implement a metric to compare them. Once evaluated, we´ll select the model with the best results, and identify the factors with the highest influence on credit risk for a higher value-add to the client.

### Description of Data


**Data Source**: Credit Risk Dataset: (https://www.kaggle.com/datasets/laotse/credit-risk-dataset)

The variables examined in relation to credit risk are as follows:

![image](https://github.com/NJAimesD/AIAcademyCapstone/assets/119623980/187e807f-e252-4b1b-8f5e-62aaebdeeb10)



**Exploratory analysis**   
We first reviewed all the variables to understand their meaning.
Then we checked if the data was balanced, according to the result it wasn´t so, a data balancing technique was needed.
![image](https://github.com/NJAimesD/AIAcademyCapstone/assets/159951082/0d3f2174-0525-43d2-af43-126b4d85363d)

A comparative visual analysis was performed, where we built a correlation matrix for all the variables, 
![image](https://github.com/NJAimesD/AIAcademyCapstone/assets/159951082/5355d94d-3a12-4858-8514-f387efed3549)

Checking the variables correlations to the Loan Status, we found that the most correlated variables are  Loan Percent Income, Loan Interest Rate as well as the Loan Grade D, so we would expect this variables to have the greatest impact on the final result.

![image](https://github.com/NJAimesD/AIAcademyCapstone/assets/159951082/209974dc-5a84-42a7-9adb-3165658c9af1)





Correlation matrix


### Data Understanding and Analysis
