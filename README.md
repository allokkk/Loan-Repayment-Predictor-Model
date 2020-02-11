# Loan-Repayment-Predictor-Model


##
The objective of this project is to accurately predict weather or not a borrower of a loan will pay the loan in full or no
As an investor you would want to invest in people who showed a profile of having a high probability of paying you back. We will try to create a model that will help predict this.
In order to accurately predict this, we create a Decision tree and a Random forest in order to obtain Classification report and Confusion matrix from the testing set. The program should be able to train itself by obtaining a training set from the given data set and then run a test set on the trained model in order to predict the desired outcome. Furthermore, it gives us its accuracy measures which we can obtain from the Classification report.
These results obtained from the DECISION TREE and RANDOM FOREST are then compared in order to find out which method is optimal, as per the requirements.

### Datasets

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




