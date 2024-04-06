<h1>Adult Income Prediction using Machine Learning</h1>

<p>This repository contains code for predicting the income level of individuals based on various demographic and socioeconomic factors. The dataset used for this task is the Adult dataset obtained from the UCI Machine Learning Repository.
</p>

<h2>Dataset</h2>

<p>The Adult dataset contains information about individuals, including age, education, occupation, marital status, and more. The target variable is 'income', which indicates whether an individual earns more than $50K per year.
</p>

<h2>Data Preprocessing</h2>

<p>
<ul>
    <li>Missing values marked as '?' were handled by imputing the mode value for categorical features such as 'workclass', 'occupation', and 'native-country'.</li>
    <li>Duplicate rows were removed from the dataset</li>
    <li>Categorical features were encoded using Label Encoding to convert them into numerical values.</li>
</ul>
</p>

Data Exploration
Box plots were generated to visualize the distribution of each feature with respect to the income level.
A correlation heatmap was created to identify relationships between numerical features and the target variable.
Model Building
Two machine learning models were trained and evaluated: Naive Bayes Classifier and Random Forest Classifier.
Randomized Search CV was used to perform hyperparameter tuning for the Random Forest Classifier to improve its performance.
The accuracy, precision, recall, and F1 score were calculated to evaluate the models' performance on the test dataset.
Results
Both models achieved high accuracy on the test dataset, with the Random Forest Classifier slightly outperforming the Naive Bayes Classifier.
The best Random Forest model achieved an accuracy of XX%, precision of XX%, recall of XX%, and F1 score of XX%.
Requirements
pandas
seaborn
matplotlib
scikit-learn
imbalanced-learn
