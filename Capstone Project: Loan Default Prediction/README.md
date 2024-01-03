# Loan Default Prediction

<div align='center'>
    <img src="Images/loan.jpeg" width=500/>
    <br/><br/>
</div>

## Problem Definition

The consumer credit department of a bank strives to streamline the approval process for home equity lines of credit. In pursuit of this goal, they intend to adhere to the guidelines set forth by the Equal Credit Opportunity Act. The objective is to construct a credit scoring model that is both empirically derived and statistically robust. The model will leverage data collected through the current loan underwriting process, focusing on recent applicants who have successfully obtained credit. While the model will employ predictive modeling techniques, it is imperative that the resulting model remains interpretable, allowing for clear justifications in cases of adverse outcomes such as rejections.

### The Context:

A significant portion of retail bank profits is derived from interest on home loans, typically acquired by customers with regular or high incomes. The potential for defaulters poses a substantial threat to banks, as non-performing loans can significantly erode their profits. Consequently, exercising prudence in loan approval for their customer base is crucial for banks.

The loan approval process is intricate, involving a manual assessment of various aspects of the application to gauge the applicant's creditworthiness. This process is not only labor-intensive but also susceptible to human errors and biases, potentially leading to incorrect judgments and approvals.

While many banks have sought to automate this process using heuristics, the emergence of data science and machine learning has shifted the focus towards developing machines capable of learning the approval process. The goal is to eliminate biases and enhance efficiency. However, a critical consideration is ensuring that these machines do not perpetuate biases inherent in the human approval process.

## The objective:

The objective of this study is to build a classification model to predict clients who are likely to default on their loan and give recommendations to the bank on the important features to consider while approving a loan.

## The key questions:

Durnig this study we'll try to find answers for:
- How we should prepare the data?
- Which performance metrics should we use?
- What is the acceptable value for the performance metric?
- Which ML algorith does provide the best performance?

## ML Algorithms to be tested:
We'll compare the performance of different algorithms during this study and choose the best one based on the decided performance metric.

- Linear Algorithms

  1. Logistic Regression (LR)
  2. Linear Discriminant Analysis (LDA)

- Non-linear Algorithms

  3. Decision Tree Classifier (DT)
  4. $k$-Neighbors Classifier (KNN)
  5. Support Vector Classifier (SVC)
  6. Gaussian Naive Bayes (GNB)

- Ensemble Algorithms 

  7. Random Forest Classifier (RFC)
  8. AdaBoost Classifier (ABC)
  9. Gradient Boosting Classifier (GBC)