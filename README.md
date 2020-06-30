<h1> Bank Telemarketing Analysis (ML-Classification) </h1>
<h3> Final Project Purwadhika </h3>

<p> Source Dataset: https://archive.ics.uci.edu/ml/datasets/bank+marketing <br><br>[Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014</p>

Proyek ini menggunakan <b>Logistic Regression, Random Forest Classifier, dan XGBoost Classifier</b>, kemudian dilakukan juga resampling menggunakan <b>SMOTE dan Near-miss Algorithm.</b> 

## Overview

Pada repo ini terbagi menjadi lima bagian:

1. Data cleaning and exploratory analysis
2. Modelling
3. Adjusting Threshold
4. Feature Importances
5. Model Deployment

## Summary

Pada <b>bagian pertama</b>: saya membersihkan data, dimana di data ini terdapat missing value yang ditandai dengan data berisikan <i>unknown</i> dan <i>non-existent</i>, kemudian saya juga melakukan eksplorasi data yang berisikan rekomendasi-rekomendasi seperti memberitahu profiling orang-orang yang tepat dikontak dan ditawarkan deposito dan juga dilakukannya analisa statistik (normality test & significance test). Untuk lebih lengkapnya dapat dilihat di [notebook ini](https://github.com/Stev-create/Bank-Telemarketing-Analysis---ML-Classification/blob/master/notebook/1.%20Data%20cleaning%20and%20exploratory%20analysis.ipynb)

Kemudian pada <b>bagian kedua</b>: dilakukannya resampling menggunakan SMOTE dan near-miss. Yang saya juga melakukan eksplorasi model dari model default hingga model yang telah di tuning. Untuk lebih lengkapnya dapat dilihat di [notebook ini untuk default](https://github.com/Stev-create/Bank-Telemarketing-Analysis---ML-Classification/blob/master/notebook/2.%20ML_Classification_Part_1%20(Default%20Model).ipynb) dan [notebook ini untuk model yang telah di tuning](https://github.com/Stev-create/Bank-Telemarketing-Analysis---ML-Classification/blob/master/notebook/3.%20ML_Classifiation_Part_2%20(Hyperparamater%20Tuning).ipynb). Di project ini, model terbaik dilihat dari F1-macro terbaik, dikarenakan dataset ini termasuk kategori <i>highly-imbalanced</i>. 

Selanjutnya pada <b>bagian ketiga</b>: saya melakukan adjusting threshold dengan bantuan precision-recall curve yang dapat dilihat lebih lengkapnya di [notebook ini](https://github.com/Stev-create/Bank-Telemarketing-Analysis---ML-Classification/blob/master/notebook/4.%20Adjusting%20threshold.ipynb)

Dan untuk <b>bagian keempat</b>: saya menunjukkan feature importances, yang dimakusdkan untuk memberitahu fitur apa yang paling membantu model melakukan klasifikasi. Yang juga dapat membantu bank untuk menyusun strategi selanjutnya. Untuk lengkapnya ada di [notebook ini](https://github.com/Stev-create/Bank-Telemarketing-Analysis---ML-Classification/blob/master/notebook/5.%20Feature%20Importances.ipynb)

Sedangkan di <b>bagian kelima</b>: Karena tujuan akhir project ini juga membuat dashboard. Maka saya mencoba untuk melihat gambarannya, yang lengkapnya dapat dilihat di [notebook ini](https://github.com/Stev-create/Bank-Telemarketing-Analysis---ML-Classification/blob/master/notebook/6.%20Model%20Deployment%20(try).ipynb)




