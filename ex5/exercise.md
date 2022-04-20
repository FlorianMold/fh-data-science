In this exercise, you shall experiment with a number of (simple) algorithms on several datasets. The aim is to get a feeling how well each of these algorithms works, and whether there are differences depending on the dataset.

- The classifiers you shall use are
  - k-NN (with 3 different values for k)
  - Perceptron, and
  - Decision Trees with 3 different parameter settings (e.g. some pre-pruning setting, different split criterion, ...)


For each dataset, you shall train and evaluate each classifier (with parameter variations), and then compute several evaluation metrics

- Effectiveness: Accuracy, and 1 more of your choice (precision, recall, F1, ...
- Efficiency: runtime for training & testing


As evaluation set splitting technique, you shall use the holdout method with 2/3 training and the rest for testing

You shall present these results in a tabular form, with one table for each dataset & splitting combination approach. 

| Iris/5-folds  | Accuracy | Precision | Training time | Testing time |
|---------------|----------|-----------|---------------|--------------|
| k-NN (3-NN)   | .85      | .82       | 0.1 sec       | 27 sec       |
| Naive Bayes   | .72      | .82       | 1 sec         | 2 sec        |
| Decision Tree | .92      | .76       | 5 sec         | 2 sec        |

Then describe the **results**, and **analyse** e.g.:

- Which classifiers work best?
- Are there differences between the datasets?
- Are the differences in the efficiency measurements?

- How is the runtime changing with the different data sets?
- ...

Your submission shall contain

- The textual report
- All code samples and
- All data sets (if not already included in your software package, e.g. Python)
