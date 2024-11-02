# CarValue_AnalysisAndPrediction

## Project Overview
## Exploratory Data Analysis (EDA) Figures:

![1](https://github.com/user-attachments/assets/eabfeedd-8882-44f5-b47b-f464aa26b8e1)
![2](https://github.com/user-attachments/assets/0b6cb018-8d6f-4710-bb55-964eeb5036ab)
## Machine Learning Models:
Regression:
![Unknown-13](https://github.com/user-attachments/assets/98a15142-41f4-4823-8626-81f6db85c2af)
Random Forest:
![Unknown-14](https://github.com/user-attachments/assets/4f22e5bc-f2c5-4e3c-a250-452521b30683)


### Steps Followed

1. **Data Import and Cleaning**: We began by importing the dataset and performing necessary cleaning to ensure the data was ready for analysis.

2. **Exploratory Data Analysis (EDA)**: Conducted EDA to explore relationships between individual features and vehicle prices, helping to identify key correlations and draw insightful conclusions.

3. **Linear Regression Analysis**: Applied linear regression to significant features to understand the impact of individual variables on price.

4. **Model Development**: 
   - Initially used a Multiple Regression Model, but encountered negative price predictions, indicating robustness issues.
   - Transitioned to a **Random Forest Regressor**, which provided improved performance with an R² score of **91%**. This model better captures non-linear relationships and interactions among variables.

5. **Validation Techniques**: Implemented Train-Test Split for cross-validation and utilized K-Folds to enhance model reliability and mitigate inaccuracies in accuracy scores.

### Business Understanding

#### Objective
This analysis aims to identify factors influencing vehicle pricing based on attributes such as Engine capacity, Power, Mileage, and Seating. Insights gained will help stakeholders optimize pricing strategies and enhance decision-making.

#### Context
Understanding how various features impact pricing is crucial for manufacturers, dealers, and consumers in the automotive market, allowing for better product positioning and improved customer satisfaction.

#### Key Focus Areas
- **Price Influencers**: Explore how Engine size, Power output, Mileage, and Seating capacity correlate with prices.
- **Market Segmentation**: Identify segments that suggest different pricing strategies.
- **Outlier Analysis**: Examine the effect of outliers, particularly for premium and high-performance vehicles.
- **Trend Analysis**: Analyze trends by region and over time to understand the impact of external factors like economic conditions.

#### Questions to Explore:
1. How do Engine size and Power output affect vehicle pricing?
2. What role does Mileage play in determining prices?
3. How does the number of Seats influence pricing?
4. Which brands command higher prices, and what features do they share?
5. How do outliers impact pricing analysis?
6. What geographical trends affect vehicle pricing?
7. How have vehicle prices changed over time, and what external factors are influential?
