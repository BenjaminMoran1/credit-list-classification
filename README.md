The purpose of this analysis was to train and evaluate this machine learning model based on loan risk and determine whether or not a person is eligible for a healthy or high-risk loan. All the financial information in this dataset was taken from a single bank, and contained various variables needed to assess loan risk such as a borrower’s income, their total debt and so on. First, we created the initial dataframe and secluded the “loan_status” column. From there, we checked out the balance of our target values using the “value_counts” functions and then split the data into training and testing datasets. We then fitted our LogisticRegression model with the training data and created predictions by using the “.predict” function on the testing data. Finally, we evaluated the model’s performance by calculating its accuracy score, generating a confusion matrix and printing the classification score.

Model Results:

·   The accuracy of the model was 0.9520479254722232 which means that roughly 95% of the total predicted outcomes were correct.

·   Precision is a measure of how many of the predicted positive instances were actually positive. For Class 0 (healthy loan), the precision is 1.00, indicating that all instances predicted as Class 0 were actually Class 0. For Class 1 (high-risk loan), the precision is 0.85, indicating that about 85% of instances predicted as Class 1 were actually Class 1.

·   Recall measures how many of the actual positive instances were correctly predicted. For Class 0 (healthy loan), the recall is .99, indicating that 99% of the actual Class 0 instances were correctly predicted. For Class 1 (high-risk loan), the recall is 0.91, meaning that 91% of the actual Class 1 instances were correctly predicted.
 
The stand-out results from this machine learning model were the balanced accuracy score of 0.952 and the weighted average for both precision and recall of 0.99. Due to our lack of knowledge and expertise in the loan lending business, we cannot say for certain whether or not this model will be useful for the bank/company in question. However, with an accuracy score of 0.952 and a weighted average for both precision and recall of 0.99, we think it is safe to say that this model is more than capable of making correct decisions in regards to assessing loan risk, and thus earns our recommendation.

worked with John Xuereb on this assignment: https://github.com/johnxuereb17/Credit_Risk_Classification
