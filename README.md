# ML-Project
ML Project code submission       

## Final Model
To run the model and reproduce the accuracy obtained by us on the test file the following command is to be run: `python3 finalModel.py`.

## Dataset
All data can be found in `/data` folder.
Original data is in `data/alldata.csv`     
Preprocessed training data: `data/data_train.csv`     
Preprocessed testing data: `data/data_test.csv`    

## Results
**Results from numerical data**
For reproducing any results regarding models that were run on numerical data please run `rating_from_numerical_data.ipynb`. This file runs the following models on the numerical data:
* Linear regression and its variants (polynomial, regularisation, etc.)
* Naive Bayes
* Decision Trees
* SVM
* K Nearest Neighbours
* Ensemble models (bagging, adaboost, random forest, etc)
* Classification models

**Results from book cover**
For reproducing any results regarding models that were run on book cover please run `rating_from_book_cover.ipynb`. This file runs the following models on book covers:
* ANN
* CNN

**Results from book summary**
For reproducing any results regarding models that were run on book summary please run `rating_from_summary.ipynb`. This file runs the following models on book covers:
* ANN
* ANN + Regularisation
* Doc2Vec + Random forest
