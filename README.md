# Gender Classification using Machine Learning
### And testing it on various classifiers

The aim of the project is to choose the best gender classification model between -
* Logistic Regression
* Linear SVM
* Gaussian SVM
* Random Forest 
* Adaptive Boost classifiers. 

At the end we will also see how well each chosen model works.

## Steps involved in the process:
1. Data Processing
2. Dimensionality Reduction
3. Fit the default Classifier
4. Tune Hyperparameters using Grid Search
5. Estimating the Best Parameters and the Best Scores
6. Plot Learning Curve

## A. DATA PRE-PROCESSING -
1. Import the Dataset
  * Import and separate data for both the genders.
2. Process the Data
  * Convert to Gray
  * Detect faces using HAAR Cascade
  * Crop the face
  * Resize Image
3. Creating DataFrame 
  * Label data and save as a dataframe


