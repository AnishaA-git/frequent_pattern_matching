# Frequent Itemset Mining and Basket Analysis

Let’s start with an introduction to Frequent Itemset Mining and Basket Analysis.

## Basket Analysis
Basket Analysis is the study of baskets in shopping. This can be online or offline shopping, as long as you can obtain data that tracks the products for each transaction.
A much-studied use case in basket analysis is to study products that are frequently bought together. This type of insight can be used for making recommendations to the customer for online shopping, or for re-arranging the products in a regular store so that it is easier for customers to add them to their basket.

## Frequent Itemset Mining
Frequent Itemset Mining is the technical term for finding product combinations that are often bought together. You generally start from a list of transactions, in which each transaction is represented as a list of products.

The goal of Frequent Itemset Mining is to identify often occurring product combinations with a fast and efficient algorithm. There are different algorithms for this. One of the foundational algorithms is the Apriori algorithm.
The FP Growth algorithm can be seen as Apriori’s modern version, as it is faster and more efficient while obtaining the same goal.
By the way, Frequent Itemset Mining algorithms are not domain-specific: you could use frequent itemset mining for other fields than basket analysis.

An example use case for the FP Growth algorithm
Let’s use an example data set that contains a list of transactions of a night store. For each transaction, we have a list of products that were bought during the transaction. The example is also used in this article on the Apriori algorithm, so that will give us an interesting benchmark to compare the performances of the two algorithms.

Please refer Colab for details: https://github.com/AnishaA-git/frequent_pattern_matching/blob/master/frequent_pattern_matching.ipynb
