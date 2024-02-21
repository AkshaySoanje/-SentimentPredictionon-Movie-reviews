Sentiment Prediction on Movie Reviews



This project focuses on predicting sentiment (positive or negative) from movie reviews. The dataset includes various features like review text, audience score, runtime minutes, genre, etc. Several models are trained and evaluated for this task.

Data Preparation
The dataset is loaded and merged with additional movie information. Missing values are handled, and text data is preprocessed using TF-IDF vectorization.

Exploratory Data Analysis
Sentiment distribution is visualized.
Missing values are shown using a heatmap.
The relationship between isFrequentReviewer and sentiment is analyzed.

Data Preprocessing
Numerical features are imputed and scaled.
Categorical features are imputed with empty strings.

Model Building
Several classification models are trained and evaluated, including Logistic Regression, LinearSVC, RidgeClassifier, and SGDClassifier. Hyperparameter tuning is performed using GridSearchCV or RandomizedSearchCV.

Model Evaluation
Models are evaluated based on precision, recall, F1-score, and confusion matrix.
The best-performing model is selected based on F1-score.

Conclusion
The best-performing model achieves an F1-score of around 0.87.
LinearSVC and Logistic Regression are the top-performing models.
TfidfVectorizer is found to be more effective than CountVectorizer for text processing.

Submission
The final predictions are made on the test set, and a submission file is generated for evaluation.



 ● Technologies Used : Python, numpy, pandas, matplotlib, seaborn, scikit-learn, scipy.
 ● Created a model for reviews classification on the bases of sentiments.
 ● Best performed found to be LinearSVC.
 ● Achieved 0.83102 F1 score on test data.
 ● Ranked 83 out of 977 participants in kaggle competition organised by IITMadras
