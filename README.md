# Building a Multivariate Time Series Model

## Introduction
Since 1999, the U.S. Postal Service has been at the forefront of utilizing machine learning and scanning technologies. With the immense task of processing around half a billion pieces of mail daily, they have invested significant effort into researching and creating highly effective algorithms that can accurately read and interpret addresses. This innovation isn't limited to the postal service alone; various other applications have emerged in different sectors.

For instance, ATMs have been designed to recognize handwritten bank checks, making transactions smoother for users. Similarly, Evernote has developed the capability to identify handwritten task lists, helping individuals keep track of their to-dos more efficiently. Expensify also employs this technology to recognize handwritten receipts, streamlining expense reporting for users. These advancements showcase the versatility of machine learning in everyday applications.

So, how do these systems achieve such remarkable feats? This project delves into K-means clustering, the algorithm that powers this impressive technology. By using scikit-learn, there is an opportunity to cluster images of handwritten digits, gaining insight into the underlying processes that enable these applications to function effectively.


This project will scope, analyze, prepare, plot data, and seek to explain the findings from the analysis.

**Data Sources:**

- [Optical Recognition of Handwritten Digits](https://archive.ics.uci.edu/dataset/80/optical+recognition+of+handwritten+digits)
  

## Project Goals
In this initiative, the viewpoint will be that of an economics analyst. The analyst's objective is to analyze how economic indicators such as gross national product (GNP) and inflation/deflation fluctuate over time.  As a result, the primary goals will be to understand economic conditions particularly through the lens of various finacial features and their predicted future use and to uncover emerging trends. Several questions will be asked:

- What economic challenges are anticipated?      
- Is the general trend upward or downward?



#### Why use a multivariate forecasting algorithm to predict future energy output?
K-means clustering is a technique used in unsupervised machine learning that organizes similar data points into clusters, helping to uncover underlying patterns within the dataset, which aligns well with the objectives of this project. 


## Data
A dataset from [UC Irving ML Repository](https://archive.ics.uci.edu/dataset/80/optical+recognition+of+handwritten+digits) that can be used to train the machine-learning model has been found. It is a CSV file containing 5620 financial records. 


## Conclusions
- What economic challenges are anticipated?
    - RGNP is expected to experience fluctuations in the early 1990s before entering a growth phase.
    - PGNP is anticipated to show overall growth, with a minor setback in the late 1980s.      
- Is the general trend upward or downward?
    - Overall, the majority of features are showing an upward trend.
