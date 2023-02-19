# sampling
This program is designed to download a credit card fraud detection dataset and apply various sampling techniques to create a balanced dataset. The balanced dataset is then used to create five samples and apply five different sampling techniques to five machine learning models.

 ## Data Source:
The credit card fraud detection dataset is available at the following link: https://github.com/AnjulaMehto/Sampling_Assignment/blob/main/Creditcard_data.csv

## Requirements:
To run this program, the following packages need to be installed:
•pandas
•imblearn
•scikit-learn

The sampling techniques used in this program are:
•Random Oversampling
•Random Undersampling
•SMOTE (Synthetic Minority Oversampling Technique)
•ADASYN (Adaptive Synthetic)
•Easy Ensemble Classifier

The five machine learning models used in this program are:
•ExtraTrees
•AdaBoost
•Random Forest
•Gradient Boosting
•XGBoost

For each sampling technique, the program creates five different samples of the balanced dataset and applies each machine learning model to each sample. The program then generates the classification report of each model and presents the results in a table. Also AUC (Area Under the ROC Curve) is also calculated.

## Contributors:
This program was created by Rohit Banyal. If you have any suggestions or would like to contribute to this project, please contact rohitbanyal2202@gmail.com.
