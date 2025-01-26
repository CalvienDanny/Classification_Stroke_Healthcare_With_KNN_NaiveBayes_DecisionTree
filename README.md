# Classification Stroke Healthcare With KNN NaiveBayes DecisionTree

This notebook contains data analysis for stroke classification using several machine learning models, including Decision Tree, Naive Bayes, and K-Nearest Neighbors (KNN). Python libraries such as `pandas` are utilized for data manipulation, `matplotlib` and `seaborn` for visualization, and `sklearn` for building and evaluating models. The dataset, loaded from a CSV file named `healthcare-dataset-stroke-data.csv`, consists of 5110 rows and 12 columns. These columns include information about patients' health conditions and lifestyles, such as `age`, `hypertension`, `heart_disease`, `avg_glucose_level`, and the target variable `stroke`.

Evaluation results show that the Naive Bayes model achieved an accuracy of 86.95%, with a precision of 0.97 for class 0 and 0.17 for class 1. The model's recall was 0.89 for class 0 and 0.49 for class 1, resulting in an overall weighted f1-score of 0.90. The KNN model demonstrated excellent performance, with a training accuracy of 95.75% and a test accuracy of 95.04%. Meanwhile, the Decision Tree model achieved an overall accuracy of 95.56%. These results indicate that KNN and Decision Tree outperformed Naive Bayes for stroke classification based on the given dataset.
