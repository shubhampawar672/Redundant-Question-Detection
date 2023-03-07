# Redundant-Question-Detection
Quora Duplicate Question Detection
This project aims to solve the problem of duplicate questions being posted on the question answering site, Quora, by using data science and machine learning techniques. The goal is to identify duplicate question pairs in order to reduce redundancy in the database.

Data:
The data used for this project is provided by Quora on Kaggle.Dataset contanins 6 features namely id,q_id1, q_id2, question1, question2, isduplicate and over 400000 rows of data.

Exploratory Data Analysis:

Initial exploratory data analysis was done using Python and popular libraries such as NumPy, Pandas, Matplotlib, and Seaborn.

Natural Language Processing:

Natural Language Processing techniques were used to preprocess the data. Tokenization, stop word removal, lemmatization, and vectorization of words using the bag of words model were performed to transform the data into a machine-readable format.

Machine Learning Models:

Four Machine Learning models such as Decision Tree, Random Forest, XGBoost, and AdaBoost were built and compared for their performance. The best model was chosen based on its accuracy and precision,Recall and F1 score.

Conclusion:

The project successfully solved the problem of duplicate questions in the Quora database by using data science and machine learning techniques. Random Forest outperformed other 3 models by achiving accuracy of 81.69%

