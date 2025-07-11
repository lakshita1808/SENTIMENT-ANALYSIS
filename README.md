# SENTIMENT-ANALYSIS
"COMPANY": CODTECH IT SOLUTIONS 
"NAME": LAKSHITA SEHGAL 
"INTERN ID": CT04DG2051
"DOMAIN": DATA ANALYTICS 
"DURATION": 4 WEEKS
 "MENTOR": NEELA SANTOSH
# PROJECT OVERVIEW:

 For Task 4 of my internship project, I worked on performing sentiment analysis using a large dataset of YouTube comments. The primary objective was to classify each comment into one of three sentiment
 categories: Positive, Neutral, or Negative. This task is part of the broader domain of Natural Language Processing (NLP), which involves analyzing human language and extracting meaningful insights from textual
 data.

 The dataset I used contained over 18,000 real YouTube comments, along with their corresponding sentiment labels. To complete this task, I used Google Colab, a free cloud-based Python environment that supports
 machine learning, data analysis, and visualization. I performed all steps using Python and essential libraries such as Pandas, NumPy, Seaborn, Matplotlib, and Scikit-learn.

 The first step was to import and explore the dataset. I checked the number of rows, columns, and looked for any missing values. I found that some comments were missing, so I cleaned the data by removing all rows
 where the comment was empty. I also visualized the sentiment distribution using a bar chart, which gave a clear picture of how many comments were positive, neutral, or negative.

 After cleaning, I performed text preprocessing on the comments. This included converting text to lowercase, removing links, hashtags, mentions, punctuation, and extra whitespace. Then I created a new column
 Cleaned_Comment to store this cleaned text.

 To train a machine learning model, I had to convert the text into numbers. For this, I used the TF-IDF Vectorizer (Term Frequency – Inverse Document Frequency), which transforms each comment into a numerical 
 vector while keeping the most important 5000 words. I also used Label Encoding to convert the target labels (positive, neutral, negative) into numeric form.

 Then, I split the dataset into training (80%) and testing (20%) sets. I used the Logistic Regression model from Scikit-learn for training, which is commonly used for classification problems. After training the
 model on the cleaned and vectorized data, I tested it on unseen data.

 The model achieved an accuracy of 75.82%, which is a strong result for multi-class text classification. The classification report showed high precision and recall for the positive sentiment class, with slightly
 lower performance on neutral and negative sentiments, which is common due to imbalanced data.

 Finally, I visualized the results using a confusion matrix heatmap, which clearly showed the number of correct and incorrect predictions for each class. The entire analysis was done step-by-step in Colab, with 
 each step well-documented for clarity.

 This project helped me understand the complete workflow of sentiment analysis — from raw text to final predictions and evaluation. It improved my skills in Python, machine learning, and data visualization, and
 gave me hands-on experience with real-world data and challenges in NLP.

 # OUTPUT:

 <img width="569" height="402" alt="Image" src="https://github.com/user-attachments/assets/9faa6287-42ee-4543-9da7-d065fe3e6fa0" />


 
<img width="534" height="402" alt="Image" src="https://github.com/user-attachments/assets/50cf4ca7-7ce3-44dc-800c-bd5acfc3c237" />
