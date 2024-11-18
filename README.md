# DistilBERT-transformer-model

The goal of this notebook is to **show the possibilities of predicting financial outcomes from textual data via DistilBERT transformer model**.

This notebook builds uses Business Decriptions from Google Finance

(Example: See textual **Description** of AAPL (in this case from Yahoo Finance))"

[link text](https://finance.yahoo.com/quote/AAPL/profile?p=AAPL)

This Colab notebook uses the following files that are posted on the class webite:
*   `company_des.csv` with Company descriptions of a large number of companues from Yahoo Finance

*   `ta.csv` and `rev.csv` with total assets and revenue data. This financial data was downloaded from Yahoo Finance

The steps this ipynb goes through are below:

1.   Upload `stock_des.csv` , ta.csv` and `rev.csv' from your local machine to the Colab working directory.
2.   Install and load the necessary libraries.
3.   Load, merge, clean the data.
4.   Create the label variable.
5.   Prepare the predictor.  
6.   Run the DistilBERT model.
7.   Train logistic regression and evaluate its accuracy.
