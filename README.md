**README**

# Black Friday Insights: Gender and Demographic Spending Trends at a Retail Giant

## Project Overview

This repository contains a comprehensive analysis of customer purchase behavior during Black Friday at a major retail giant. The primary objective is to understand if spending habits differ between male and female customers and analyze how various demographic factors influence purchase amounts. The insights derived from this analysis will help the business make informed strategic decisions.

## Business Problem

The management team at the retail giant wants to analyze customer purchase behavior, specifically focusing on purchase amounts relative to customers’ gender and other factors. They aim to determine if there is a significant difference in spending between male and female customers and to understand the broader spending patterns across different demographic groups. This information is crucial for making data-driven decisions to enhance business strategies and customer targeting.

## Dataset

The dataset consists of transactional data from customers who made purchases during Black Friday at the retail giant's stores. The features included in the dataset are as follows:

- **User_ID:** Unique identifier for each customer
- **Product_ID:** Unique identifier for each product
- **Gender:** Gender of the customer
- **Age:** Age group of the customer
- **Occupation:** Occupation of the customer (masked for privacy)
- **City_Category:** Category of the city (A, B, C)
- **StayInCurrentCityYears:** Number of years the customer has lived in the current city
- **Marital_Status:** Marital status of the customer
- **ProductCategory:** Product category (masked for privacy)
- **Purchase:** Purchase amount

## Analysis Steps

1. **Data Import and Exploration:**
   - Import the dataset and examine its structure and characteristics.
   - Detect and handle null values and outliers using methods like boxplots and descriptive statistics.

2. **Data Exploration:**
   - Track the amount spent per transaction for all 50 million female customers and 50 million male customers.
   - Calculate the average purchase amount for both genders and draw conclusions from these averages.
   - Use the sample averages to calculate confidence intervals for the population averages, leveraging the Central Limit Theorem.
   - Experiment with different sample sizes and confidence intervals (90%, 95%, 99%) to observe the distribution of spending.

3. **Demographic Analysis:**
   - Perform the same analysis for marital status (married vs. unmarried) and age groups.
   - Create age bins based on life stages: 0-17, 18-25, 26-35, 36-50, 51+ years.

4. **Inference and Recommendations:**
   - Determine if the confidence intervals for average male and female spending overlap.
   - Provide actionable insights and recommendations for the retail giant based on the analysis.

## Key Findings and Recommendations

- **Seasonal Trends:** Analysis revealed increased bike rentals during summer and fall, suggesting the need to bolster bike stocks during these periods to meet higher demand.
- **Holiday Impact:** Higher rentals on holidays indicate strategic inventory management on such days can be beneficial.
- **Working Day Analysis:** A slight increase in rentals on holidays and weekends suggests no significant impact of working days on rentals.
- **Weather Influence:** Reduced rentals during adverse weather conditions prompt inventory adjustments.
- **Humidity & Temperature Effects:** Lower rentals during low humidity and cold temperatures recommend reducing bike availability in such conditions.
- **Wind Speed Consideration:** High wind speeds correlate with lower bike rentals, suggesting limiting bike availability during such conditions.

## Conclusion

This analysis provides valuable insights into customer spending behavior during Black Friday, segmented by gender and various demographic factors. The results will help the retail giant optimize inventory management, target marketing efforts, and improve overall customer satisfaction.

## How to Use This Repository

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/black-friday-insights.git
   ```

2. **Install Required Libraries:**
   Ensure you have Python and the necessary libraries installed. You can use the following command to install required packages:
   ```sh
   pip install -r requirements.txt
   ```

3. **Run the Analysis:**
   Open the Jupyter notebooks provided in the repository to explore the data and perform the analysis step-by-step.

## Contributions

Contributions to this project are welcome. Feel free to fork the repository, make improvements, and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for exploring this project. We hope it provides valuable insights and helps drive better business decisions for the retail giant.
