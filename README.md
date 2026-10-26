# SMS Spam Detection Using Machine Learning

## Project Overview

This project compares four machine learning algorithms for classifying SMS messages as spam or legitimate (ham). Text messages are converted into numerical features using Term Frequency–Inverse Document Frequency (TF-IDF).

The project evaluates the models using accuracy, precision, recall, F1-score, confusion matrices, and execution time.

## Objectives

- Analyse and preprocess an SMS dataset.
- Convert text messages into numerical features using TF-IDF.
- Implement four machine learning classifiers.
- Compare model performance using evaluation metrics.
- Study the effect of changing the K parameter in K-Nearest Neighbours.
- Identify a suitable classifier for SMS spam detection.

## Dataset

**Dataset:** SMS Spam Collection Dataset

**Source:** Kaggle — https://www.kaggle.com/uciml/sms-spam-collection-dataset

The dataset contains SMS messages labelled as:
- `ham`: Legitimate messages.
- `spam`: Unwanted or spam messages.



## Algorithms Implemented

1. Decision Tree
2. K-Nearest Neighbours (KNN)
3. Support Vector Machine (SVM)
4. Multinomial Naive Bayes

## Technologies Used

- Python
- Google Colab
- pandas
- NumPy
- Matplotlib
- scikit-learn

## Methodology

1. Load and inspect the dataset.
2. Clean missing values and duplicate records.
3. Analyse the class distribution.
4. Split the data into training and testing sets.
5. Extract TF-IDF features.
6. Train and evaluate all four classifiers.
7. Compare evaluation metrics and execution times.
8. Generate a confusion matrix.
9. Conduct a KNN parameter experiment.
10. Save the experimental results.

## Evaluation Metrics

- Accuracy
- Spam precision
- Spam recall
- Spam F1-score
- Training time
- Prediction time

## What-If Experiment

The number of neighbours in KNN is varied across K = 3, 5, 7, and 9 to investigate its effect on classification performance.

## Project Files

- `SMS_Spam_Detection_IR_Project.ipynb` — Project notebook and experiments.
- `classifier_comparison.csv` — Comparison of the four classifiers.
- `knn_what_if_results.csv` — Results of the KNN experiment.

## How to Run

1. Download the dataset from Kaggle.
2. Open the notebook in Google Colab.
3. Upload the dataset when prompted.
4. Run the notebook cells in order.
5. Review the generated graphs, metrics, and experimental results.

## Conclusion

The project compares four machine learning classifiers for SMS spam detection. The most suitable classifier will be identified based on the experimental results, particularly spam precision, spam recall, F1-score, and computational efficiency.


