# ClassificationAssignment03_DecisionTree_DreamClubLoanDataSet

# Problem statement:


The given dataset is from Dream Club which connects borrowers with investors. We will use lending data from 2007-2010 and build a classifier model to predict whether or not the borrower has paid back their loan in full.

 

Here are what the columns represent:

 

credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.

purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").

int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.

installment: The monthly installments owed by the borrower if the loan is funded.

log.annual.inc: The natural log of the self-reported annual income of the borrower.

dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).

fico: The FICO credit score of the borrower.

days.with.cr.line: The number of days the borrower has had a credit line.

revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).

revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).

inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.

delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.

pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).

not.fully.paid: whether or not the borrower paid back their loan in full

 

For the dataset (Loan dataset), implement the Decision Tree classifier using Python. [9M]

Dataset: loan data.csv 

 

QUESTIONS:
 

Q-1: Load the dataset and print the metadata in the notebook. 1M

 

Q-2: Print a heatmap to check NULL values. 1M

 

Q-3: Perform stratified splitting of train and test data. 1M

 

Q-4: Build a classifier model using the Decision Tree algorithm. 2M

 

Q-5: Print confusion matrix and classification report before and after pruning the Decision tree. (1+1)M

 

Q-6 Plot the final decision tree model. 1M

 

Q-7: Find out the stratified cross-validation accuracy 1M.


