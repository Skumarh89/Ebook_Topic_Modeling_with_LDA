# Ebook_Topic_Modeling_with_LDA


Overview

This repository contains Python code to perform Latent Dirichlet Allocation (LDA) topic modeling on ebook text. LDA is a popular technique for identifying topics within a collection of text data. The code leverages the NLTK and scikit-learn libraries for text preprocessing and topic modeling, respectively. Additionally, it utilizes matplotlib and seaborn for data visualization and wordcloud for generating word clouds of keywords.

Features

    * Preprocesses ebook text data by tokenization, removal of stopwords, and lemmatization.
    * Saves preprocessed ebook data to a CSV file for further analysis.
    * Trains an LDA model on the preprocessed ebook data to identify topics.
    * Allows users to input their text passages for keyword extraction based on the trained LDA model.
    * Performs exploratory data analysis (EDA) on both user input and generated keywords.
    * Visualizes keyword frequency using a bar plot and creates a word cloud of keywords.
    * Saves the results, including topics, keywords, and probability scores, to a CSV file.

Getting Started

To run the code in this repository, follow these steps:

    Clone the repository to your local machine:

       git clone https://github.com/yourusername/ebook-topic-modeling-with-lda.git
       cd ebook-topic-modeling-with-lda
       
   Install the required Python libraries:

     pip install -r requirements.txt

  Place your ebook file in the same directory as the Python script and rename it to "edata.txt".
  Run the Python script to preprocess the ebook data and train the LDA model:

      python ebook_topic_modeling.py

