# Random-Forest

This project is realised in the "Python for Data Science and Machine Learning Bootcamp".
For this project, I will explore some public available data from www.lendingclub.com.
Lending Club connects people who need money(borrowers) with people who have money(investors).
As an investor, you would want to invest in people who showed a profile of having a high probability of paying you back.
In this project I will try to create a model that will help predict this.
I will use lending data from 2007-2010 and try to classify and predict whther or not the borrower paid back their loan in full.
The data will be read from the csv file loan_data.csv.

The semnifications from the columns in the data set:

-> credit.policy: 1 if the customer meets the credit underwritting criteria of LendingClub.com, or 0 otherwise
-> purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").
-> int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.
-> installment: The monthly installments owed by the borrower if the loan is funded.
-> log.annual.inc: The natural log of the self-reported annual income of the borrower.
-> dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).
-> fico: The FICO credit score of the borrower.
-> days.with.cr.line: The number of days the borrower has had a credit line.
-> revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
-> revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
-> inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.
-> delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
-> pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).

->not.fully.paid: the output column, to predict if the loan was fully paid by the borrower or not.

In this project, we will use DECISION TREE and RANDOM FOREST machine learning alghoritms in order to the predict if a borrower has fully paid his loan or not.
After training the both models,we can see that overall the RANDOM FOREST algorithm had better results than the DECISION TREE.
