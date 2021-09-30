# Arvato Capstone Project

## Installation
This repository only contains a notebook without any of the data required to run it, so you won't need to install anything. However, I have used a library in it called `imblearn` which is similar to scikit-learn, however it is designed to deal with imbalanced classification problems. And while installing imblearn I found out that you need the following packages:
1. joblib >= 0.11
2. numpy >= 1.13.3
3. scipy >= 0.19.1
4. scikit-learn >= 0.24
5. threadpoolctl >= 2.0.0

## Project Motivation
In this project, I role-played that I was a Data Scientist at Bertelsmann Arvato Analytics, where I was handed over a project where the stakeholder was a mail-order sales company in Germany.

According to britannica, a mail order business is a

“method of merchandising in which the seller’s offer is made through mass mailing of a circular or catalog or through an advertisement placed in a newspaper or magazine and in which the buyer places an order by mail.”

And this stakeholder wanted two things from us:

1. First it wanted to understand which parts of the general population described the core customer base of the company.
2. Second it wanted a model which predicts which individuals are most likely to convert new campaigns.

The datasets that were provided with this project were:

 1. A dataset which holds demographic information about the general population in Germany.
 2. A dataset which holds demographic information about the customer base of the stakeholder.
 3. A dataset which has the demographic information about the individuals involved in their campaigning, and whether they converted or not.


## File Descriptions
The repository only contains the notebook where the project was made, and unfortunately the data couldn't due to the Bertelsmann Arvato's request.


## Project Summary

### To summarize what was done in the project:
1. I explored the general population dataset to understand how it should be cleaned for our analysis
2. I made a pipeline for cleaning the general population dataset and any dataset that has a similar structure
3. I performed dimensionality reduction on the general population dataset followed by a clustering analysis of the population
4. I cleaned the customers’ dataset using the pipeline we previously made and analyzed the clusters’ representation of the business’s customer base
5. I analyzed the characteristics of our customer base and how they differ from non-customers
6. I analyzed the differences between different clusters in the customer base
7. I explored the mailout dataset and made a pipeline to prepare the dataset for the supervised learning task
8. I analyzed different algorithms and metrics then selected the best ones that suited the situation of the dataset we have which was Balanced Random Forests for the algorithm and Macro Recall for metric which deals with the target class imbalance
9. I tested using feature selection in the pipeline to improve the results and found that it had indeed improved it
10. I made a final pipeline and tuned it’s hyperparameters to predict individuals with high probability responding the mail-out campaign


For more information about the notebook above, or you can check [this blog post](https://ahmedsamirio.github.io/Arvato_Capstone_Project/).
