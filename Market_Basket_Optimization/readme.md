Market Basket Optimization

Download the Market Basket Optimization dataset from the following link:

* **Data Set:** [Kaggle - Market Basket Optimization Dataset](https://www.kaggle.com/hemanthkumar05/market-basket-optimization)

### Overview
This dataset comprises the list of transactions of a retail company over a period of one week. It contains a total of **7,501 transaction records**, where each record consists of the list of items sold in a single transaction. Using this record of transactions, find the association rules between items.

> **Note:** There is no header in the dataset, and the first row contains the first transaction. Make sure to set `header = None` when loading the dataset.

### Tasks
- **a.** Follow the steps outlined below.
- **b.** Data Pre-processing.
- **c.** Generate the list of transactions from the dataset.
- **d.** Train the **Apriori algorithm** on the dataset.
- **e.** Visualize the list of rules.
- **f.** Generated rules depend on the values of hyperparameters. Increase the minimum confidence value and find the rules accordingly.