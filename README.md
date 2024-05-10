# Corporation Favorita Sales Forecasting Project

## 1. Business Understanding

Predicting sales is critical for effective business planning. In this project, we leverage machine learning to develop a model that forecasts store sales using data from Corporation Favorita, a prominent grocery retailer in Ecuador.

## Project Objective

Our primary aim is to construct a Machine Learning Model capable of predicting unit sales for various items sold across Favorita stores. By analyzing sales trends, identifying seasonal patterns, and considering factors like oil prices, holidays, and promotions, we seek to provide actionable insights to grocery retailers. These insights can inform marketing strategies, optimize inventory management, reduce costs, and enhance profitability, particularly for perishable items.

## Approach and Methodology

This project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) Framework, a widely adopted methodology for data science projects. We explore a range of machine learning techniques, including:

1. **Time Series Forecasting**: Utilizing methods such as ARIMA, LSTM, or Prophet to uncover sales trends and seasonal variations.
  
2. **Regression Models**: Employing techniques like linear regression, decision trees, random forests, or gradient boosting to evaluate the impact of promotions, product attributes, and store specifics on sales.

## Hypothesis

**Null Hypothesis (H0)**: Promotion activities have no significant effect on sales.

**Alternative Hypothesis (Ha)**: Promotion activities have a significant effect on sales.

This hypothesis forms the basis for investigating the impact of promotions on sales, a crucial aspect of our analysis.

| Feature          | Description                                                                                                         |
|------------------|---------------------------------------------------------------------------------------------------------------------|
| store_nbr        | Identifier for the store where the products are sold.                                                                |
| family           | Type of product sold.                                                                                               |
| onpromotion      | Indicator of whether the item was being promoted at the store on a given date.                                       |
| sales            | Total sales for a product family at a particular store on a given date.                                               |
| date             | Date of the sales record.                                                                                           |
| transaction      | Number of transactions made at a specific store on a given date.                                                     |
| city             | City where the store is located.                                                                                    |
| state            | State where the store is located.                                                                                   |
| type             | Type of store.                                                                                                      |
| cluster          | Grouping of similar stores.                                                                                         |
| oil_price        | Daily oil price.                                                                                                    |
| type             | Type of holiday or event.                                                                                           |
| transferred      | Indicator of whether a holiday was transferred to another date by the government.                                    |
| additional_holidays | Indicator of additional holidays added to a regular calendar holiday.                                                 |

This table provides a concise summary of the features present in the datasets, including identifiers, product information, store metadata, oil prices, and holiday events.

**Author**
**Denis**   
@murithidenisgitobu