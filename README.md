# NLP_Resume_Screening

This project is a simple NLP-based resume classifier that uses TF-IDF for vectorization and Logistic Regression for classification. It takes resumes as input, performs a series of natural language preprocessing steps, and predicts the corresponding job category.

## Problem Statement 

The goal of this project is to automatically classify resumes into appropriate job categories. This can be used to streamline the hiring process by routing resumes to the correct departments or job roles.

## Task Objectives

1. Preprocess the resume text using either NLTK or spaCy:

2. Tokenization

3. Lowercasing

4. Stopword removal

5. Lemmatization

6. TF-IDF vectorization for text representation.

7. Simple classifier (e.g., Logistic Regression) to predict the job category.

8. Evaluate the model using an accuracy score.

## Preprocessing Steps Explained

1. Tokenization
Tokenization is the process of breaking down a text into individual units called tokens (e.g., words or phrases).
Example:
Text: "Resumes are classified." → Tokens: ['Resumes', 'are', 'classified', '.']

2. Lowercasing
Converts all characters in the text to lowercase to ensure uniformity.
Example: "Engineer" → "engineer"

3. Stopword Removal
Removes common words like "is", "the", "and" that do not add much meaning.
Example: "She is a data scientist" → "data scientist"

4. Lemmatization
Reduces words to their base or dictionary form.
Example: "running" → "run"

## TF-IDF Vectorization

TF-IDF (Term Frequency-Inverse Document Frequency) is a statistical measure used to evaluate how important a word is to a document in a collection or corpus


TF (Term Frequency): How frequently a term appears in a document.


IDF (Inverse Document Frequency): How rare the term is across all documents.


The result is a numerical vector that represents the importance of words in resumes.

## Classification Model

We use Logistic Regression, a linear classifier suitable for multiclass classification tasks, to predict the job category from the TF-IDF vectorized resume.

## Model Evaluation
We evaluate our model using:

--> Accuracy Score: Measures the number of correct predictions divided by the total predictions.

--> Accuracy = (Correct Predictions) / (Total Predictions)

## Dataset

The resumes and their categories are preprocessed and split into training and testing sets.

Each resume is vectorized using TF-IDF before being passed to the classifier.

## Requirements

1. Python

2. NLTK / spaCy

3. Scikit-learn

4. Pandas

5. NumPy

## Visualizations

<img width="1019" height="662" alt="image" src="https://github.com/user-attachments/assets/65fa16ff-96a9-468b-ae70-f8d1299f2247" />


<img width="867" height="526" alt="image" src="https://github.com/user-attachments/assets/8afe85a0-3cf2-43e2-9480-05fa03ab576d" />


<img width="713" height="414" alt="image" src="https://github.com/user-attachments/assets/a2881588-4dda-457f-a29f-2685093c1d81" />

## Accuracy Score by using Logistic Regression

<img width="410" height="36" alt="image" src="https://github.com/user-attachments/assets/b7149780-dae5-42cd-a439-37d9c3b54aa9" />


<img width="615" height="90" alt="image" src="https://github.com/user-attachments/assets/11a59ef6-d938-4e37-a58c-a8d5aa7c3a96" />


<img width="555" height="457" alt="image" src="https://github.com/user-attachments/assets/05a2bd8e-454f-4c53-927f-e907db5d2f8a" />


<img width="545" height="58" alt="image" src="https://github.com/user-attachments/assets/c397e708-3ee1-48b8-a3d8-4c9ca71c132e" />


<img width="1135" height="638" alt="image" src="https://github.com/user-attachments/assets/1066f79a-0199-4051-b4c5-3be555f59e09" />


## Result 

Successfully completed a resume classification project using NLP techniques. Used TF-IDF and Logistic Regression to predict job categories with evaluated accuracy.




