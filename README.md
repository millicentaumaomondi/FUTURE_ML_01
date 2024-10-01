# Advanced Regression 
* We have three .ipynb files
  - cleaning the train dataset
  - cleaning the test dataset
  - Training the regression models
* We start by uploading the train dataset on the "clean_train_dataset.ipynb" file,
 - Then proceed with EDA and data cleaning,
 - Save the cleaned training dataset inform of a csv file.
* On the second file "clean_test_dataset.ipynb" file,
  - we merge the test data with the submission.csv file,
  - then perform EDA and data cleaning,
  - then save the clean test data inform of a csv file.
* On the third file,
   - we merge the cleaned test dataset with the clean training dataset having a single dataset.
   - We split the merged data set into train and test in the ratio 80:20
   - We run the split train set on various regression models like linear regression, lasso regression, ridge regression,
   decision tree, random forest, gradient boosting and XGBoost.
