## AutoAnnotate: Scalable Review Sentiment Tagging using Supervised Machine Learning (NLP + Scikit-learn)

A scalable prototype system that performs sentiment annotation on customer review data using Natural Language Processing (NLP) and supervised learning techniques. 

Designed to solve real-world business problems such as customer satisfaction analysis and feedback classification, this project empowers Business Analysts and ML Engineers to automate sentiment tagging with high accuracy using Python and Scikit-learn

---

## OBJECTIVES

- Built a supervised ML model to classify sentiment in customer reviews
- Train the model using a balanced dataset of 1000 labeled samples
- Accept unlabeled review datasets and auto-annotate them with predicted sentiment and confidence.
- Achieve 99%+ model accuracy for production-ready sentiment classification.
- Enable seamless integration into business pipelines for feedback intelligence.

---

## PROJECT STRUCTURE

|              File                       |                   Description                |
|-----------------------------------------|----------------------------------------------|
| `AutoAnnotate.ipynb`                    | Jupyter Notebook with full implementation    |
| `large_labeled_reviews.csv`             | Dataset used for training and testing        |
| `unlabeled_reviews.csv`                 | Sample unlabeled reviews for auto-annotation |
| `README.md`                             | Project documentation                        |


---

## FEATURES

-  Preprocessing using TF-IDF vectorization
-  Supervised ML classification using Logistic Regression
-  High-accuracy performance (98%+)
-  Automatic annotation of uploaded review data
-  Confidence scores for each prediction
-  Easily extendable to real-time business feedback systems

---

## MODEL PERFORMANCE

|     Model     | Positive Class | Negative Class | Overall  |
|---------------|----------------|----------------|----------|
| Precision     |      0.99      |      0.99      |   0.99   |
| Recall        |      0.99      |      0.99      |   0.99   |
| F1-Score      |      0.99      |      0.99      |   0.99   |
| Accuracy      |        -       |        -       |   0.99   |
|-------------------------------------------------------------
| Dataset       |      500       |       500      |   1000   |

---

## HOW TO RUN

1. Open AutoAnnotate.ipynb in Jupyter Notebook.
2. Update the file path of your labeled dataset for model training.
3. Update the file path of your unlabeled dataset or the dataset you are going to use to annotate
4. Specify the output path where the annotated results should be saved.
5. Run all cells to:
   - Train the sentiment classification model on the labeled dataset.
   - Display detailed model accuracy and classification report.
   - Predict sentiment labels and confidence scores for the unlabeled reviews.
   - Save the annotated output as a CSV file in the specified location.

---
