# Ames_Housing_Analysis

## Overview
This project focuses on analyzing historical housing market data from Ames, Iowa, to develop a predictive model for home sale prices. By leveraging statistical methods and regression analysis, we provide actionable insights for homeowners and realtors. The project includes data cleaning, feature engineering, and the implementation of multiple regression models to identify key factors influencing home value.

---

## Key Objectives
- Predict home sale prices based on significant features.
- Identify key variables that influence the market value of a home.
- Provide actionable recommendations to homeowners for optimizing property value.

---

## Dataset Overview
- **Source:** Ames Housing Dataset
- **Size:** 2,931 rows and 82 columns
- **Features:** Includes house attributes (e.g., quality, condition, living area), property details (e.g., garage area, lot frontage), geographic data, and sale information.

### Assumptions and Conditions
- Data accurately represents the Ames housing market.
- Blank values (excluding `Lot_Frontage`) are assumed to represent `0` or N/A.
- Subjective variables like `Overall_Qual` and `Overall_Cond` rely on ordinal scales, which are inherently subjective.
- Analysis focuses exclusively on single-family households.

---

## Tools and Skills Used
- **Tools:** Excel, PowerPoint
- **Techniques:** Data cleaning, regression analysis, feature engineering

---

## Key Findings
### Regression Analysis (Final Model)
- **Overall Quality**: Homes in the "Excellent" category have a $158,950 higher sale price than those in the "Good" category.
- **Living Area**: Every additional square foot adds approximately $54.19 to the sale price.
- **Garage Area**: Each additional square foot increases the price by $79.18.
- Cost-effective improvements to raise home quality (e.g., from "Somewhat Decent" to "Good") can significantly boost home value.

---

## Visuals and Insights
### Correlation Heatmap
- Identified a strong correlation (0.7993) between `Overall_Qual` and `SalePrice`.

### Multiple Regression Models
- Improved interpretability by categorizing ordinal variables like `Overall_Qual` into dummy variables (e.g., "Bad," "Good," "Excellent").
- Insights derived from regression tables guide actionable recommendations for homeowners.

![Improved Regression Table Screenshot](https://github.com/user-attachments/assets/7e98adb1-8e89-4cf3-b1f8-0fff0b3e2d51)

---

## Recommendations
1. **Home Quality Improvements**
   - Focus on cost-effective renovations, especially for homes in the "Bad" or "Somewhat Decent" categories.
   - Invest in areas like kitchens, bathrooms, and structural improvements to improve overall quality.

2. **Living and Garage Area**
   - Expanding above-ground living area or garage space offers a desirable ROI.

3. **Marketing Strategies**
   - Emphasize quality features in property listings to attract higher offers.

---

## Future Work
- Explore the use of Python, SQL, and Machine Learning for optimized exploration and improved prediction accuracy.
- Incorporate additional economic and market trend data to enhance the model.
- Put more of a focus on data cleaning and outlier handling processes for key variables.

---
## Relevant Files
### Full Report
- The detailed report is available [here](https://github.com/user-attachments/files/18234311/Ames.Final.Essay.Complete.docx)
### Excel File
- The reference material for the data exploration, cleaning, and analysis is available [here](https://github.com/user-attachments/files/18234340/Ames.Housing.Analysis.Reference.Material.xlsx)

---

## Contact
Feel free to connect with me or reach out with any questions:
- **Email**: [ethnmcmanus@gmail.com](mailto:ethnmcmanus@gmail.com)
- **LinkedIn**: [linkedin.com/in/ethan-mcmanus](https://www.linkedin.com/in/ethan-mcmanus)
