# NLP
 Text Classification with SVM Pipeline

Text Classification with SVM Pipeline
In this project, I developed a text classification model using a Support Vector Machine (SVM) within a Scikit-learn pipeline. The model is designed to categorize text data into predefined categories, demonstrating the use of machine learning for natural language processing (NLP) tasks.

Key Components:
Pipeline Construction:

The pipeline includes three main steps:
CountVectorizer: Converts the raw text data into a matrix of token counts.
TfidfTransformer: Transforms the token counts into Term Frequency-Inverse Document Frequency (TF-IDF) features, which reflect the importance of terms in the text.
SGDClassifier: Uses Stochastic Gradient Descent to train an SVM with a hinge loss function, providing robust performance for text classification.
Model Training:

The pipeline is trained on the twenty_train dataset, which includes text samples and their corresponding target categories.
Prediction and Evaluation:

The trained model is used to predict the categories of the twenty_test dataset.
The performance of the model is evaluated by calculating the mean accuracy, which is the proportion of correctly classified samples.
