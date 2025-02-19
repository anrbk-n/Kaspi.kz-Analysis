      Kaspi.kz Smartphone Price and Feature Analysis
This project is dedicated to scraping and analyzing smartphone data from Kaspi.kz, and comparing it with a dataset from Kaggle. The analysis includes comparing prices, features, and other aspects of smartphones to identify trends and differences between the platforms.

The project is divided into four main parts:

1. Web Scraping (web_scrap/)
Goal: Collect smartphone data from Kaspi.kz.
Used BeautifulSoup and Selenium to extract smartphone details (name, price, features, etc.) from product pages.
Saved the scraped data in structured CSV files for further analysis.
The scraping script is adaptable for other e-commerce websites by modifying the URL and scraping logic.
2. Data Cleaning (data_cleaning/)
Goal: Clean and preprocess the scraped data.
Handled missing or inconsistent values.
Replaced missing values with the mean or mode where appropriate.
Dropped irrelevant columns and rows.
Ensured the dataset was in the right format for analysis and modeling.
3. Data Visualization (data_visualization/)
Goal: Visualize key insights from the dataset.
Used Matplotlib to create graphs and charts that compare prices, features, and trends of smartphones on Kaspi.kz and the Kaggle dataset.
Analyzed price distributions, feature correlations, and visualized key patterns in the data.
4. Machine Learning and Prediction (ml_predict/)
Goal: Build machine learning models to predict smartphone prices and analyze features.
Preprocessed the data by converting categorical variables into numerical ones.
Created new features to improve model performance and understanding.
Built and evaluated various machine learning models, such as regression models, to predict smartphone prices based on their features.
