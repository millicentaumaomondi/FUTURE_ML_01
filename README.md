# Advanced Regression 
* We used the [house prices dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) from kaggle.
* We have three .ipynb files
  - cleaning the training dataset
  - cleaning the test dataset
  - Training the regression models
* We start by uploading the training dataset on the "clean_train_dataset.ipynb" file,
 - Then proceed with EDA and data cleaning,
 - Save the cleaned training dataset in the form of a CSV file.
* On the second file "clean_test_dataset.ipynb" file,
  - we merge the test data with the submission.csv file,
  - then perform EDA and data cleaning,
  - then save the clean test data in the form of a CSV file.
* On the third file,
   - We merge the cleaned test dataset with the clean training dataset, which has a single dataset.
   - We split the merged data set into train and test in the ratio 80:20
   - We run the split train set on various regression models like linear regression, lasso regression, ridge regression,
   decision tree, random forest, gradient boosting, and XGBoost.
