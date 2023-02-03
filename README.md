# LoanEligibilty_ML
Analysis of Streaming dataset with different attributes of a Customer to find whether they are eligible for a loan.

This analysis is from data presented in Kaggle: <a href="https://www.kaggle.com/code/vijay0707/loan-eligibility-prediction/comments">Loan Eligibility Prediction</a>

This project analyses a streaming dataset of Customers. The Machine Learning algorithm then decides if they are eligible for a loan or not. Classification algorithms applied include:
<ul>
  <li>No-change Classifier</li>
  <li>Majority Class Classifier</li>
  <li>Hoeffding Trees</li>
  <li>SAM-KNN</li>
  <li>Hoeffding Adaptive Trees(HAT)</li>
  <li>Adaptive Random Forest(ARF)</li>
  <li>Leverage bagging</li>
</ul>
The accuracies of the above algorithms on the dataset is shown below
<p align="center"><img src="https://drive.google.com/uc?export=view&id=1KR5ycl-NAC9u3AA_StNpUDwwMIVoyqqW" alt="PerformanceGraphLoanEligibility"></p>
As expected the No-change classifier being very basic one delivers poor performance. The HAT delivers the best performance on this dataset
