# Credit Risk Prediction
### Overview and Business Understanding

Credit risk prediction is a cricial process for financial institutions, aiming to asses the likehood of a borrower defaulting on a loan. That way the non-defaulter people can access easily to credist with better
conditions, while the institutions reduce the risk of finantial loss.
There are many techniques to predict credit risk, but Machine Learning can be used to automate the prediction process, since it learns the patterns asociated with a defaulter profile and its use reduces time and resources consumption.
Detecting people with a high risk profile can be a complex task, but still it implies better profit margin for the institution, and ML using improves a lot the efficiency, and the institution resources can be now used in other areas that require human supervision.

Our team at Deloitte seeks to use different machine learning models to predict the credit risk for different profiles, test them and implement a metric to compare them, once evaluated, we´ll select the model with the best results, as well as understand what are the features with the greatest impact in the final result, that will give added value to the client. 

### Description of Data


**Data Source**: Credit Risk Dataset: (https://www.kaggle.com/datasets/laotse/credit-risk-dataset)

**Exploratory analysis** 
We first reviewed all the variables to understand their meaning.
Plots, etc.

Correlation matrix


### Data Understanding and Analysis


When training our machine learning model for detecting bank account fraud, we employed a set of robust success metrics essential for evaluating its performance. Initially we utlized the ROC/AUC curve, which offered an understanding of the model's ability to distinguish between fraudulent and legitimate transactions. This success metric allows us to see the trade-off between sensitivity and specificity of fruaduluent and non-fraudulent accounts. A high AUC score indicates a strong capability to classify between the two classes, serving as a reliable gauge of overall model performance.

Moreover, precision and recall were important success metrics in our evaluation strategy. Precision quantifies the accuracy of positive predictions made by the model, emphasizing the proportion of correctly identified fraudulent cases among all predicted positives. Recall, on the other hand, measures the model's capability to identify all actual positive cases, indicating the completeness of fraud detection. Therefore, recall proved more useful in our model evaluation. In our model we were looking for a high recall through changing the decision thresholds and different weights to the target classes. Through this and additional techiniques we were able to acheive a recall **0.63*. This coupled with our high AUC of 0.76 helped prove the effectiveness of our model. Additionally, balancing these two metrics ensures a comprehensive understanding of the model's effectiveness, guarding against false positives and false negatives, both critical in the context of bank account fraud detection. 

Finally, we created and analyzed confusion matrixes in order to see the models effectivness on a more granualar level. In turn this helped us improve out model throughout the process and identify areas of improvement for future tuning of our model. 
