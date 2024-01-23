# stock-market-
 It helps in understanding the underlying patterns and relationships in the stock market data. we will perform EDA on the S&amp;P dataset using Python
1. Load the Dataset
The first step is to load the dataset. We will be using the  dataset, which contains stock prices of the largest publicly traded companies . The dataset can be downloaded from Kaggle.

import pandas as pd

# Load the dataset
df = pd.read_csv('SP500.csv')
![stock market2](https://github.com/Rajendradegala/stock-market-/assets/140039152/f84b1878-1954-4c7a-8c6e-82ab178a0b23)

2. Explore the Dataset
The next step is to explore the dataset. We can use the head() method to view the first few rows of the dataset.

# View the first few rows of the dataset
df.head()
![view data](https://github.com/Rajendradegala/stock-market-/assets/140039152/61cf7f8d-1062-44c2-ae7f-77b33c16ebc8)

# View the data types and non-null values in the dataset
df.info()
