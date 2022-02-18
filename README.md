# Classification-of-peptides

Classify functional and non-functional peptides. These peptides have different number of amino acids i.e., peptides have variable length. Amino acids in peptide are represented by a single letter code.

## Usage
**To install packages (imbalanced-learn, pandas, scipy, numpy, scikit-learn, sklearn )**

pip3 install -r requirements.txt

**To run python code**

python code.py

## Data Preprocessing
* Null values detection: No null values in the dataset
* Checked data imbalance: Data is balanced
* Analysis of length of each sequence (to find max_length)

## Feature Extraction
* Integer Encoding
* Binary Profiling
* Frequency count
* Molecular_weight

## The following models were built
* Random Forest Regressor
* Support Vector Machine (SVM)
* K Nearest Neighbors (KNN)
* Random Forest Classifier
* Logistic Regression

## Result
**Random Forest Regressor** comes out to be the best among all the above models.

**Accuracy score:** 0.80174 (on 70% dataset), 0.78183 (on 30% dataset)

(It was a competition on Kaggle under the course Machine Learning for Biomedical Applications @IIITD , 70% data is used for public leaderboard and 30% data for private leaderboard.) 

**Team Members : Vidhi Sharma, Ajay Prakash**
