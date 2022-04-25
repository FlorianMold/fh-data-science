# Comparison of the two data-sets

## HR

+--------------------+-------------------+------------------------+----------------------+----------------+------------+--------+
| Algorithm          | Mean Train Time   | Mean Prediction Time   | Mean Accuracy Time   | Mean F1 Time   | Accuracy   | F1     |
+====================+===================+========================+======================+================+============+========+
| k-Nearest-Neighbor | 0.00934s          | 0.02229s               | 0.00038s             | 0.00104s       | 53.72%     | 51.97% |
+--------------------+-------------------+------------------------+----------------------+----------------+------------+--------+
| Perceptron         | 0.00507s          | 0.00448s               | 0.00137s             | 0.00149s       | 66.99%     | 56.07% |
+--------------------+-------------------+------------------------+----------------------+----------------+------------+--------+
| DecisionTree       | 0.00259s          | 0.00075s               | 0.00056s             | 0.00267s       | 75.66%     | 67.21% |
+--------------------+-------------------+------------------------+----------------------+----------------+------------+--------+

## Census-Income

+--------------------+-------------------+------------------------+----------------------+----------------+------------+--------+
| Algorithm          | Mean Train Time   | Mean Prediction Time   | Mean Accuracy Time   | Mean F1 Time   | Accuracy   | F1     |
+====================+===================+========================+======================+================+============+========+
| k-Nearest-Neighbor | 1.60001s          | 38.22458s              | 0.00054s             | 0.00150s       | 85.01%     | 84.19% |
+--------------------+-------------------+------------------------+----------------------+----------------+------------+--------+
| Perceptron         | 0.23120s          | 0.01242s               | 0.00066s             | 0.00184s       | 77.83%     | 70.91% |
+--------------------+-------------------+------------------------+----------------------+----------------+------------+--------+
| DecisionTree       | 0.31189s          | 0.00545s               | 0.00061s             | 0.00174s       | 95.76%     | 94.36% |
+--------------------+-------------------+------------------------+----------------------+----------------+------------+--------+

## Comparison

All algorithms have better effectiveness scores on the census-income dataset.

If we compare the knn algorithm of the small and of the big dataset we see that the accuracy and f1-score are very far apart. 
The census-income data has about 30% more in both scores.

If we compare the perceptron algorithm, census-income also performs much better. For accuracy, it has about 10% more and for 
the f1-score it has about 14% more.

If we compare the decision tree algorithm, census-income is also the best. For accuracy, it has about 20% more and for 
the f1-score it has about 27% more. The decision-tree in combination with census-income performs almost 100% accuracy and 
f1-score.

The run is considerably better for the hr-dataset, but this is expected as the hr-dataset is much smaller than the census-income
data-set. The advantage is the runtime of the knn-algorithm, as the runtime is not as bad compared to the others in the 
hr-dataset.

