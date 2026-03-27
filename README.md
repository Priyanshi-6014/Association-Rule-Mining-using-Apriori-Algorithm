# Association Rule Mining using Apriori Algorithm

This project implements **Association Rule Mining**, a popular unsupervised machine learning technique used to discover relationships between items in large datasets.

##  Overview

Association rules help identify patterns like:

> "If a customer buys X, they are likely to buy Y"

These rules are widely used in **market basket analysis**, recommendation systems, and business analytics.

Each rule is represented as:

* **X → Y**

  * X = Antecedent (input items)
  * Y = Consequent (predicted items)

##  Implementation Steps

1. Load and preprocess transaction dataset
2. Convert data into one-hot encoded format
3. Generate frequent itemsets using the Apriori algorithm
4. Extract association rules based on:

   * Support
   * Confidence
   * Lift
5. Visualize results (bar plots, scatter plots, heatmaps)

##  Key Metrics

* **Support**: Frequency of itemset occurrence in dataset
* **Confidence**: Probability that Y occurs given X
* **Lift**: Strength of association between X and Y

These metrics help evaluate how useful and reliable a rule is. ([GeeksforGeeks][1])

##  Libraries Used

* pandas
* mlxtend
* matplotlib
* seaborn
* networkx

##  Applications

* Market Basket Analysis (retail insights)
* Recommendation Systems
* Fraud Detection
* Healthcare pattern analysis ([GeeksforGeeks][1])

##  Dataset

The dataset contains transactional records where each row represents items purchased together.

##  Key Learning

* Understanding unsupervised learning
* Discovering hidden patterns in data
* Applying Apriori algorithm for real-world insights
