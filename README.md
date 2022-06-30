# Customer Lending Risk Classification

<br>
<br>

### Introduction

>This is a personal study made on credit dataset.
>The problem is binary classification, to classify bank customers as their lending ratings.

<br>

### Data Preprocessing
>First I've analysed the dataset by reading through the CSV.
>Checked for any unknown values, the data had no empty cells.
>Used label encoding

<br>

### Dataset Observations
>Examined the correlation matrix, this helped tweaking the bayesian network nodes.
>
>The target class is imbalanced, while there is 700 'good' credit samples,
>there is only 300 'bad' credit samples included.
>
>The data didn't have any null/NaN/? values.
>
>All data were categorical, while evaluation, I took that into account.
>
>The dataset was lack of any single females. This particular data must be gathered
>in case of any single female prediction need.

<br>

### Tested algorithms:
<ul>
<li> Categorical Naive Bayes </li> 
<li> DecisionTreeClassifier </li>
<li> GaussianNB </li>
<li> KNeighborsClassifier </li>
<li> LGBMClassifier </li>
<li> LinearDiscriminantAnalysis </li>
<li> LogisticRegression </li>
<li> RandomForestClassifier </li>
<li> Support Vector Classifier
<li> XGBClassifier </li>
<li> Bayesian  Network </li>
</ul>
