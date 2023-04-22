# Welcome to spam-email-detection repository
## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on analysing a dataset containing Spam vs Non-spam (Ham) Emails found [here](https://www.kaggle.com/datasets/nitishabharathi/email-spam-dataset). For a detailed walkthrough, please view the source code in order from:

   1. [Data Cleaning](https://github.com/ItsEyan/spam-email-detection/blob/main/Data%20Preparation%20%26%20Cleaning.ipynb)
   2. [Exploratory Data Analysis & Visualisation](https://github.com/ItsEyan/spam-email-detection/blob/main/Exploratory%20Data%20Analysis%20%26%20Visualization.ipynb)
   3. [Model Training & Testing](https://github.com/ItsEyan/spam-email-detection/blob/main/Model%20Training.ipynb)
## Contributors
- @ItsEyan - Data Preparation & Cleaning, EDA & Visualisation, Model Training
- @Cyyy03 - Data Preparation & Cleaning, Model Training, Presentation
- @yiping1708 - Problem Formulation, Presentation & Editing
## Problem Definition
- Can we successfully identify Spam vs Ham emails solely based on the text in the email?
- Which model is the best in identifying Spam emails?
## Models Used
- Support Vector Classification (SVC)
- K-Neighbours Classification (KNC)
- Multinomial Naive Bayes (MNB)
- Gradient Boosting Decision Tree (GBDT)
## Conclusion
- Upon further testing, GBDT was found to be able to predict Spam emails from even a small dataset
- Natural Language Processing is one of the best ways to categorise different text
- A few thousand emails is not sufficient to predict every user's Spam emails. We need a larger dataset with a mix of different types of Spam emails in order to create a spam filter for general use
- However, everyone's Spam mail is different. Therefore to get more accurate results, one should train the model based on their own emails
- Yes, it is possible to create a model to successfully identify Spam vs Ham emails with acceptable accuracy and precision
## What did we learn from this project?
- Dataset cleaning for natural language processing (Stop word filtering, lemmatization, etc.)
- Wordcloud visualisation
- Natural language processing & analysis
- General concepts of SVC, KNC, MNB, and GBDT
- Saving the generated models as .pckl files to save time from retraining
- Collaborating using Github and Google Colab
## References
- https://www.kaggle.com/datasets/nitishabharathi/email-spam-dataset
- https://www.kaggle.com/code/eldarsarajlic/spam-filter-practice-w-comments-for-beginners
- https://www.analyticsvidhya.com/blog/2021/06/part-5-step-by-step-guide-to-master-nlp-text-vectorization-approaches/#:~:text=To%20convert%20the%20text%20data,text%20data%20to%20numerical%20vectors
- https://jakevdp.github.io/PythonDataScienceHandbook/05.05-naive-bayes.html#:~:text=Naive%20Bayes%20models%20are%20a,baseline%20for%20a%20classification%20problem
- https://www.kaggle.com/code/rohitshirudkar/email-classification-spam-or-ham
- https://developers.google.com/machine-learning/decision-forests/intro-to-gbdt
