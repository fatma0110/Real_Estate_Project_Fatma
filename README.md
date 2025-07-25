# Real_Estate_Project_Fatma

## Objectives
The primary objective of this project is to collect, clean, and analyze rental property data from various websites. The goal is to create a comprehensive dataset suitable for exploratory analysis and predictive modeling related to property rentals in Oman.

## Websites Used
- **Bayut**: [https://www.bayut.com](https://www.bayut.com)
- **Osooq**: [https://www.osooq.com](https://www.osooq.com)

## Data Collection
- Used web scraping techniques to extract property listings from Bayut and Osooq.
- Employed requests and BeautifulSoup libraries to fetch and parse HTML content.

## Data Cleaning
- Loaded the scraped data into Pandas DataFrames.
- Merged datasets from both sources into a unified DataFrame.
- Handled missing values using appropriate strategies.

## Size Cleaning
- Converted size descriptions into numerical format to enable quantitative analysis.

## Governorate Extraction
- Parsed location strings to extract governorate.

## Price Normalization
- Cleaned and standardized price data to ensure consistent numerical formatting.

## Additional Features
- Created a new column for **price per square meter**.
- Encoded categorical features using LabelEncoder for compatibility with modeling algorithms.

## Modeling Approach

- Implemented a **Decision Tree Regressor** to predict rental prices based on engineered features.
- Split the dataset into **training and testing sets** to evaluate model performance.
- Assessed accuracy using:
  - **Mean Squared Error (MSE)**
  - **R-squared (R²)**
