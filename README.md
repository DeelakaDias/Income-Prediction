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

<h2>Data Exploration</h2>

<p><ul>
    <li>Box plots were generated to visualize the distribution of each feature with respect to the income level.</li>
    <li>A correlation heatmap was created to identify relationships between numerical features and the target variable.</li>
</ul>
</p>

<h2>Model Building</h2>
<p>
    <ul>
        <li>Two machine learning models were trained and evaluated: Naive Bayes Classifier and Random Forest Classifier.</li>
    <li>Randomized Search CV was used to perform hyperparameter tuning for the Random Forest Classifier to improve its performance.</li>
    <li>The accuracy, precision, recall, and F1 score were calculated to evaluate the models' performance on the test dataset.</li>
    </ul>
</p>

<h2>Results</h2>
<p>
    <ul>
        <li>Both models achieved high accuracy on the test dataset, with the Random Forest Classifier slightly outperforming the Naive Bayes Classifier.</li>
        <li>The best Random Forest model achieved an accuracy of 89.38608588140188%, precision of 86.2549625055139%, recall of 93.55085637738015%, and F1 score of 89.75488846047921%.</li>
    </ul>
</p>

<h2>Requirements</h2>
<p>
    <ul>
    <li>pandas</li>
    <li>seabor</li>
    <li>matplotli</li>
    <li>imbalanced-learn</li>
    </ul>
</p>
