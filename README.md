# credit-risk-classification
Module 19 Challenge

# Credit Risk Analysis Report
The purpose of this model is to generate reports of the relative risk that an individual poses for taking out a loan. The model uses the loan size, interest rates, borrowers income, relative debt, number of accounts, derogatory marks, and total debt as the independent variables, while the loan status is the dependent variable being measured. The goal of the ML program is to identify whether an individual is a healthy or unhealthy candidate for a loan based on these independent variables.

After running a classification report, the model had the following attributes:
- Accuracy: with a macro score of 0.94 and a weighted average of 0.99, this is an effective tool in determining whether a loan is healthy or unhealthy. Anything greater than 0.8 is typically considered accurate.
- Precision: Similar to accuracy, the model was strong at identifying healthy loans (1.00), while it was adequate at identifying unhealthy loans (0.84). This means that it skews more towards stating that a loan is healthy, despite occassionally accepting loans as healthy when they're not.
- Recall Scores: This represents the ratio of true positives to total incorrect statements (true positives and false negatives). With a Recall score of 0.88 for Unhealthy loans, this is still a strong model.

Basd on the classification report, I believe this is a strong model that should be recommended to a company seeking faster means of approving or rejecting loans. While the model does shift slightly towards accepting unhealthy loans, the numbers are negligable in comparison to the total loans analyzed. A 0.88 recall score for unhealthy loans is still a strong score that would streamline analysis of loans applications.