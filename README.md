

### Kaspi.kz Smartphone Analysis

This project is dedicated to scraping and analyzing smartphone data from Kaspi.kz, and comparing it with a dataset from Kaggle. The analysis includes comparing prices, features, and other aspects of smartphones to identify trends and differences between the platforms.

The project is divided into four main parts:

## 1. Web Scraping (web_scrap/)
Goal: Collect smartphone data from Kaspi.kz.
# 1.1 Used BeautifulSoup and Selenium to extract smartphone details (name, price, features, etc.) from product pages.
# 1.2 Saved the scraped data in structured CSV files for further analysis.
# 1.3 The scraping script is adaptable for other e-commerce websites by modifying the URL and scraping logic.
## 2. Data Cleaning (data_cleaning/)
Goal: Clean and preprocess the scraped data.
# 2.1 Handled missing or inconsistent values.
# 2.2 Replaced missing values with the mean or mode where appropriate.
# 2.3 Dropped irrelevant columns and rows.
# 2.4 Ensured the dataset was in the right format for analysis and modeling.
## 3. Data Visualization (data_visualization/)
Goal: Visualize key insights from the dataset.
# 3.1 Used Matplotlib to create graphs and charts that compare prices, features, and trends of smartphones on Kaspi.kz and the Kaggle dataset.
# 3.2 Analyzed price distributions, feature correlations, and visualized key patterns in the data.
## 4. Machine Learning and Prediction (ml_predict/)
Goal: Build machine learning models to predict smartphone prices and analyze features.
# 4.1 Preprocessed the data by converting categorical variables into numerical ones.
# 4.2 Created new features to improve model performance and understanding.
# 4.3 Built and evaluated various machine learning models, such as regression models, to predict smartphone prices based on their features.
