# McDonald's Menu Nutritional Analysis

## Introduction
This project analyzes the nutritional content of McDonald's menu items to identify healthier and less healthy options, understand calorie distribution, and provide actionable insights for balanced eating. The goal is to present findings through data cleaning, exploratory analysis, and visualizations.

## Data Overview
- **Source:** McDonald's official menu dataset (nutritional facts per item)
- **Rows:** 260+ menu items
- **Columns:** Nutritional metrics including Calories, Total Fat, Saturated Fat, Cholesterol, Sodium, Carbohydrates, Dietary Fiber, Sugars, and Protein.
- **Categories:** Breakfast, Burgers, Chicken & Fish, Sides, Beverages, Desserts, Salads.

## Data Cleaning
- Removed duplicate entries.
- Standardized category names (e.g., “Burgers” vs “Burger”).
- Converted serving sizes to a consistent unit.
- Handled missing values (replaced with category averages or removed where necessary).
- Ensured all numeric fields were correctly typed for analysis.

## Exploratory Analysis
- **Calorie Range:** From under 100 calories (black coffee) to over 1,200 calories (large meal items).
- **Macronutrient Trends:** Burgers and chicken items tend to have the highest protein but also high fat and sodium.
- **Category Comparisons:** Salads generally lower in calories but may have high sodium in dressings.
- **Sugar Content:** Beverages and desserts have the highest sugar concentration.

## Visualizations
- Bar charts comparing average calories per category.
- Scatter plots showing calorie vs. protein trade-offs.
- Heatmap of correlation between nutritional factors.
- Pie chart of macronutrient composition for selected items.
- Box plots to compare calorie distribution across categories.

## Insights & Conclusion
- **High Calorie + Low Nutrient Density:** Many large combo meals offer excessive calories with limited micronutrient benefits.
- **Hidden Sodium Risk:** Even low-calorie options like salads can have high sodium from dressings and toppings.
- **Best Protein Sources:** Grilled chicken items offer better protein-to-calorie ratios compared to fried options.
- **Sugar Watch:** Specialty beverages can contribute more sugar than desserts.
- **Recommendation:** Consumers aiming for healthier choices should focus on grilled proteins, avoid large-sized portions, and be mindful of sauces and drinks.

---
