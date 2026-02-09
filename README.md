# Exploratory Analysis of Sales Volumes

This project presents an exploratory data analysis (EDA) of an e-commerce transaction dataset.

The main objective is to analyze sales volumes by identifying the most relevant products and customers and by studying the temporal evolution of transactions.
The analysis was carried out for educational purposes using **Python**, **pandas**, and **matplotlib**.

The dataset does not include pricing information; therefore, the analysis focuses exclusively on quantities sold rather than revenue.

---

## Dataset

The dataset contains the following main variables:
- **customer_id**: unique identifier of the customer  
- **product_id**: unique identifier of the product  
- **basket_date**: transaction date  
- **basket_count**: quantity purchased  

Each row represents a product-level transaction.

---

## Analyses Performed

The following analyses were conducted:
- Data quality checks (missing values and duplicates)
- Conversion and handling of temporal variables
- Analysis of overall sales volumes
- Identification of the top-selling products
- Identification of the most active customers
- Analysis of sales volume trends over time
- Data visualization through charts and plots

---

## Key Results

The analysis highlights:
- A strong concentration of sales volumes among a limited number of products
- Significant variations in sales volumes over time
- A very high average number of items per transaction, suggesting that the dataset represents aggregated or bulk transactions rather than individual retail purchases

---

## Future Improvements

Possible extensions of this project include:

- Integrating price information to analyze revenue in addition to sales volumes
- Performing a deeper analysis of customer behavior (purchase frequency and recurrence)
- Developing predictive models to forecast future sales volumes
