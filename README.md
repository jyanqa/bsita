# BSITA - Hotels' Reviews Analysis
```
Please run the code again to see entire visualizations and comments of each tasks!
```

## Data
Dataset is a subset of [ABSITA](http://sag.art.uniroma2.it/absita/data/) dataset.

- The data includes reviews and opinion (negative/positive) about hotels listed on *Booking.com* website in 3 cities: **Napoli, Bologna and Milan**. 
- The reviews are in multi-languages but we're going to analyze exclusively **Italian reviews**.
- We consider text reviews of customers and labeled sentiments encoded to the **'target' column**.

## Library

## BSITA project tackle the following tasks:
- Preprocessing the data by **splitting sentences**, **splitting unigram** or **n-grams**, **removing stop words and punctuations**, and **forming a term-document matrix** using **tf-idf indexes**.
- Build a **pipeline** for preprocessing steps.
- Classification: Applied **Logistic Regression** and **Random Forest**  classification methods and executed a GridSearchCV cross Validation in order to find the best parameters and the best score. The labels are negative or positive. 
- Clustering: Using K-means and Hierarchical Agglomerative Cluster methods.
- Topic Modeling: Extracing top 3 and 8 topics of the reviews, listin representiative of each topics and visualizing them using pyLDAvis library.
- Summarization: summary reviews to a consise and meaningful paragrahp of 50 words. 
## Author
[Quynh-Anh Ng](https://github.com/jyanqa)
