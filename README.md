# Taxgpt
This repository contains the complete work for the TaxGPT Data Analysis and Insights project, an experiential learning initiative sponsored by TaxGPT.ca. 
TaxGPT Data Analysis and Insights Project
Overview:

This repository contains the complete work for the TaxGPT Data Analysis and Insights project, an experiential learning initiative sponsored by TaxGPT.ca. The goal of the project was to analyze over 11,500 tax-related questions submitted by users of the platform, using advanced Natural Language Processing (NLP) and machine learning techniques to extract key insights, categorize queries, and provide actionable data for the stakeholders.

Key Objectives:

Data Analysis and Preprocessing: Cleaned, transformed, and preprocessed the dataset containing user-submitted tax-related questions.
Topic Modeling: Applied Latent Dirichlet Allocation (LDA) and other NLP techniques to segment the data into 7 key topics, achieving a coherence score of 0.512.
Demographic Profiling: Performed analysis on user demographics based on location, income, and age to generate insightful profiles of TaxGPT users.
Machine Learning Categorization: Implemented machine learning algorithms to classify and assess the complexity of tax-related questions.
Data Visualization: Created a series of interactive visualizations using Matplotlib and Seaborn to represent data trends, topic distributions, and query complexity.
Webpage Development: Developed a webpage to present the project's results, including an executive summary and visualizations, to TaxGPT.ca stakeholders and over 1 million platform users.
Project Features:

Data Cleaning & Preprocessing: Handling NaN values, tokenization, stopword removal, lemmatization, and vectorization of textual data.
Topic Modeling with LDA: Topic extraction using Gensim’s LDA model, bigrams, and trigrams for improved coherence scores.
Clustering Analysis: K-means clustering of document-topic distributions to further segment and understand user queries.
Machine Learning Frameworks: Implemented models using scikit-learn for classification and complexity estimation of user questions.
Data Visualization: Multiple visualizations including topic distributions, cluster representations, and query patterns.
Technologies Used:

NLP Libraries: NLTK, Gensim, spaCy
Machine Learning: scikit-learn, TensorFlow, PyTorch
Data Analysis: pandas, NumPy
Data Visualization: Matplotlib, Seaborn
Web Development: HTML, CSS, JavaScript
Results:

Analyzed and categorized tax-related questions into 7 key topics with a coherence score of 0.512.
Developed 10+ insightful visualizations that provided clear understanding of user queries and tax-related trends.
Created a fully functional webpage to display results to stakeholders.
How to Use:

Clone the repository.
Install the required dependencies listed in requirements.txt.
Follow the provided Jupyter notebooks to explore the dataset, preprocessing steps, and topic modeling processes.
Review the data visualizations and executive summary in the results/ directory.
Future Improvements:

Explore additional NLP models like BERT or GPT for better question understanding.
Optimize the number of topics further and fine-tune hyperparameters for increased model accuracy.
