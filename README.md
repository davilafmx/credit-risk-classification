# credit-risk-classification
Module 20 challenge

Report

The purpose of credit risk classification is to assess the likelihood of a borrower defaulting on their financial obligations. By categorizing borrowers into different risk classes, financial institutions can determine appropriate interest rates, lending terms, and credit limits. This classification helps mitigate potential losses by identifying high-risk borrowers early on and implementing risk management strategies accordingly.


Initial data preprocessing involved systematic organization and refinement of the raw data set. This dataset comprised diverse financial parameters including but not limited to:

-Loan size
--Interest rates
Borrower income
-Debt-to-income ratio
-Number of accounts
-Derogatory marks
-Total debt
Employment of Logistic Regression, a supervised learning classification algorithm, was undertaken to prognosticate the likelihood of loan creditworthiness. The model was meticulously trained to discern between loans deemed as low-risk (coded as 0) and those categorized as high-risk (coded as 1).

Validation and evaluation of two distinct machine learning models ensued:

The first model exhibited an accuracy that unveiled 18679 true positive and 558 true negative outcomes. Precision values indicated a disparity in performance between predicting healthy loans (precision of 1) versus high-risk loans (precision of 0.87), with recall figures similarly reflecting a discrepancy.
Conversely, the second model showcased a balanced distribution in the training data, resulting in more uniform performance metrics across both loan categories.
Conclusively, the preference is inclined towards the adoption of 'Machine Learning Model 2' owing to its equitable performance across accuracy, precision, and recall metrics, substantiating its suitability for effectively predicting loan risks and stratifying them into either low-risk or high-risk categories. Further augmentation through post-resampling techniques augmented the efficacy of 'Machine Learning Model 2', rendering it a superior choice for risk prediction in the context of loan classification.
