# credit-risk-classification
  
Use knowledge of Python and supervised learning techniques to train and evaluate a model based on loan risk. Use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
  
[Solution](Credit_Risk/credit_risk_classification.ipynb)  
  
## Report  
Purpose of this analysis is to understand the benefits of oversampling. The data we have shows an imbalance in the data for the two classes. Random Oversampling involves supplementing the training data with multiple copies of some of the minority classes.  
  
When we ran value_counts() on the dataset we got the below numbers.  
0    75036  
1     2500  
  
After oversampling, the numbers will be same for both the classes.  
0    75036  
1    75036  
  
To measure the performance of the Machine Learning model, we use precision, recall and accuracy (f-score).

The precision of a model describes how many detected items are truly relevant. It is calculated by dividing the true positives by overall positives.  
  
Recall is a measure of how many relevant elements were detected. Therefore it divides true positives by the number of relevant elements.  
  
The F-score is a measure of a test's accuracy. It is calculated from recall and precision values.  
  
### Results  
Without over-sampling
* Precision: 0.99  
* Precision: 0.99  
* Precision: 0.99  
  
With over-sampling  
* Precision: 1.00  
* Precision: 1.00  
* Precision: 1.00  

### Summary  
The model did a good job in predicting healthy loans with 100% accuracy again. Model showed a higher accuracy of about 93% when predicting high-risk loans with oversampled data. That shows an improvement of 5% in accuracy. Noteably, with oversampled data, model achieved 100% recall.  
  