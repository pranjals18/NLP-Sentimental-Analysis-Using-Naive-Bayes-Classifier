# NLP-Sentimental-Analysis-Using-Naive-Bayes-Classifier

This repository houses datasets and algorithms essential for our sentiment analysis project focused on deciphering movie reviews.

Team Members:
1. Chinmay Haval (21BDS014)
2. Milind Murmu (21BDS038)
3. Rahul Singh (21BDS054)
4. Saksham (21BDS058)
5. Pranjal Shinde (21BDS062)



Usage
To effectively utilize the datasets and algorithms contained in this repository, follow the steps outlined below:

1. Clone the Repository using this command:
    **git clone https://github.com/PranjalShinde18/NLP-Sentimental-Analysis-Using-Naive-Bayes-Classifier**

2. Navigate to the downloded Directory:
    **Run the movies.ipynb.**

# About Model:

1. Data preprossing :


The dataset was initially converted into a DataFrame using the Python library 'Pandas.' Subsequently, the NLTK library's PorterStemmer class was employed for word stemming, a process that removes morphological suffixes from words to reveal their base or root form, resulting in a lower unique word count.

Following the stemming process, the text input underwent a transformation into a numerical representation using the TF-IDF method. This transformation was carried out using the TfidfVectorizer class from the scikit-learn library. Only the top 590 most informative features, each representing a feature's TF-IDF score, were embedded in the data. The TF-IDF score provides insights into the significance of a particular feature within the dataset. This approach helps capture the importance of words by considering their frequency in specific documents relative to their occurrence across the entire dataset.

2. Model Training :

The model usages three different types of Naive Bayes to classify the review as a positive or negative.

   1. **Multinomial Naive Bayes.**
   2. **Complement Naive Bayes.**
   3. **Bernoulli Naive Bayes.**


