# Video_Game_Sales_Analysis_S5

## Overview
This project analyzes historical video game sales data to identify trends and patterns that impact game success. The insights gained will help forecast sales and guide advertising strategies for 2017. 

The dataset includes regional sales, platform information, user and critic reviews, genres, and ESRB ratings. Hypothesis testing is conducted to validate key assumptions.

---

## Project Steps

### 1. **Data Preparation**
- Standardize column names to lowercase.
- Convert data to appropriate types and document changes.
- Handle missing values and special cases like "TBD."
- Add a new column for total sales across all regions.

### 2. **Exploratory Data Analysis**
- Analyze game release trends over the years.
- Explore sales distributions by platform and genre.
- Identify leading platforms and genres.
- Assess the impact of user and critic reviews on sales.
- Examine sales distributions across regions.

### 3. **Regional User Profiles**
- Identify the top 5 platforms and genres for each region (NA, EU, JP).
- Analyze regional variations in platform and genre preferences.
- Examine the effect of ESRB ratings on sales in each region.

### 4. **Hypothesis Testing**
- Test the following hypotheses:
  1. H₀: Average user ratings for Xbox One and PC are the same.
  2. H₀: Average user ratings for Action and Sports genres are the same.
- Use statistical tests with an appropriate significance level.
- Document results and conclusions.

### 5. **Conclusion**
- Summarize findings and provide actionable insights.
- Offer recommendations for future campaigns and strategy.

---

## Dataset Description

| **Column Name**    | **Description**                                   |
|---------------------|---------------------------------------------------|
| `name`             | Name of the video game                           |
| `platform`         | Platform on which the game was released          |
| `year_of_release`  | Year the game was released                       |
| `genre`            | Genre of the game                                |
| `na_sales`         | North American sales (in USD million)            |
| `eu_sales`         | European sales (in USD million)                  |
| `jp_sales`         | Japanese sales (in USD million)                  |
| `other_sales`      | Sales in other regions (in USD million)          |
| `critic_score`     | Critic reviews score (max 100)                   |
| `user_score`       | User reviews score (max 10)                      |
| `rating`           | ESRB rating                                      |

---

## How to Run the Project
1. Open the Jupyter Notebook.
2. Follow the outlined steps in the notebook.
3. Run the code cells and review markdown explanations.
4. Submit your work for review and iterate based on feedback.
