# SpamFiltering

Steps to Run:
1. Enter the address of Dictionary where spam phrases are seperated by a newline
2. Enter the address of all the documents that are considered

Working:
1. Given Dictionary file, identify all the phrases that are spam keywords
2. From the given documents, count the no. of times a spam phrase has occured and store in 2D array
3. Compute TF-IDF values on the term frequency matrix 
4. Rank the document by summation of tf-idf values of each term
