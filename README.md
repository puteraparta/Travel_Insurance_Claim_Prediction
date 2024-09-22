# CAPSTONE PROJECT MODULE 3
## TRAVEL INSURANCE CUSTOMER CLAIM PREDICTION CLASSIFICATION
### Business Understanding
A travel insurance company offers a variety of insurance products to customers traveling to different destinations. These products are distributed through agencies or online channels, with different types of plans such as annual coverage, cancellation, and comprehensive insurance. Manager of Risk and Claims in the Insurance Department is a key stakeholder in this project. They are responsible for assessing risk, managing insurance claims, and designing strategies to minimize claim-related losses
### Problem
This travel insurance company wants to predict how likely it is for policyholders to file a claim, so they can better manage and allocate funds for coverage. By preparing the right amount, the company can keep the claims process smooth and avoid having too much unused money if fewer claims are made
### Analytical Approach and Metrics Evaluation
The data analysis aims to identify differences in patterns between policyholders who make claims and those who don't, and to understand claim opportunities based on insurance product types. Following this, a classification model will be developed to predict the likelihood of a policyholder filing a claim. The model will use several classification algorithms, including Logistic Regression, Decision Tree, KNN, Random Forest, XGBoost, and LightGBM.

To address the risks of misclassifying positive and negative cases, the model will focus on both classes. The primary evaluation metric will be ROC/AUC (Receiver Operating Characteristic), while balanced accuracy will be used instead of overall accuracy due to the imbalanced nature of the data. Several models will be assessed based on these metrics, and the best-performing model will be selected for hyperparameter tuning to further improve its performance.
