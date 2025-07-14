# MACHINE-LEARNING-MODEL-IMPLEMENTATION

COMPANY: CODTECH IT SOLUTIONS

NAME: MANDAR JOG

INTERN ID: CT04DF1656

DOMAIN: Python Programming

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

**TASK SUMMARY:**
This Python script builds a highly accurate, end-to-end predictive model to classify SMS messages as either "spam" or "ham." Using the Scikit-learn library, the program implements a complete machine learning workflow, starting from data loading and preparation to model training, evaluation, and real-world prediction.
The core of the program is a Pipeline that streamlines the entire process. First, it uses a TfidfVectorizer to convert raw text messages into a numerical format that captures the importance of each word. These numerical vectors are then passed to a powerful LinearSVC (Support Vector Classifier), an algorithm well-suited for text classification.
To maximize performance, the script employs GridSearchCV to automatically tune the model's hyperparameters. This crucial step systematically tests different combinations of settings for both the vectorizer and the classifier, ensuring the final model is optimized for the highest possible accuracy.
After training, the model is rigorously evaluated on a separate, unseen test dataset. The evaluation is comprehensive, including not just an overall accuracy score but also a confusion matrix to visualize specific error types, a detailed classification report (with precision and recall), and an ROC curve with its corresponding AUC score. The ROC/AUC analysis provides a robust measure of the model's ability to distinguish between classes. Finally, the script demonstrates the model's practical utility with a function that can classify any new, custom message in real-time.
