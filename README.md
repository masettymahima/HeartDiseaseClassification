# Heart Disease Classification 🫀
## Classifying if a Patient Has Heart Disease

1 out of every 4 deaths in the United States is caused by a form of preventable heart disease. With the ability of using machine learning to zoom into medical issues making deaths like these avoidable, my team and I undertook the challenge of building machine learning models to deduce whether a patient is at risk of developing heart disease based on their medical statistics. 

### ⭐️ Key highlights of this project:
- Pre-processing the data to turn it into a usable form for model training
- Dropping outliers using interquartile range 
- Imputing missing values of important predictors by testing univariate imputation by mean, median and frequency, multivariate imputation by chained equations, and KNN imputation methods, ultimately picking KNN imputation
- Feature engineering by testing interaction terms using OLS regression
- Exploring relationships between variables by visualizating the data via heat maps, bar graphs etc.
- Building a baseline model with the new set of predictors to compare performance of tuned machine learning models to
- Training logistic regression, ridge classifier regression, decision tree, random forest, reborn tree, boosting and KNN models
- Tuning hyperparameters of all the optimization models to see if it improves performance
- Ultimately picked random forest as the best classifier based on the F1 score which is a harmonic mean of the accuracy and precision scores

### 🔎 Here is a link to the project presentation
[Project Presentation](https://drive.google.com/file/d/1iScEsqkYanDBBxlSoBuAynwmjPnW7gAW/view?usp=share_link)
