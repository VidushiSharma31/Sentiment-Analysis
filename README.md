### **Sentiment Analysis using Classical Machine Learning**

### 

##### **Overview**



This project implements a sentiment analysis system on the IMDB movie reviews dataset sourced from Hugging Face, using classical machine learning algorithms. Multiple models and text representation techniques are compared to evaluate their effectiveness in sentiment classification.



The project focuses on understanding the impact of text preprocessing, feature extraction, and model selection, without using transformer-based architectures.



##### **Models Implemented**



* Logistic Regression
* Decision Tree
* Random Forest
* Naive Bayes



##### **Text Representation Techniques**



* Bag of Words (BoW)
* TF-IDF
* Word2Vec



##### **Text Preprocessing**



Text preprocessing was performed using spaCy, including:



* Tokenization
* Lemmatization
* HTML tags removal
* Stopword removal



##### **Evaluation**



* Models were trained and evaluated using accuracy as the primary metric.
* Comparative analysis was conducted across different combinations of classifiers and feature representations.
* The best-performing configuration achieved ~87% accuracy using TF-IDF with Logistic Regression on the IMDB dataset.



##### **Tech Stack**



Language: Python

Libraries: Scikit-learn, spaCy, NumPy, Pandas, Matplotlib, NLTK / Gensim

Dataset: IMDB Reviews (Hugging Face)

Environment: Jupyter Notebook



##### 📁**Repository Structure**

├── sentiment\_analysis.ipynb

├── README.md



##### **How to Run**



Step-1: Clone the repository

Step-2: Install required dependencies

Step-3: Download the IMDB dataset from Hugging Face (or use the provided dataset folder)

Step-4: Open sentiment\_analysis.ipynb in Jupyter Notebook

Step-5: Run all cells sequentially



##### **Key Takeaways**



* Classical machine learning models can achieve strong baseline performance for sentiment analysis.
* Text preprocessing using spaCy significantly improves model effectiveness.
* TF-IDF with Logistic Regression provides a strong, interpretable baseline for sentiment classification.
